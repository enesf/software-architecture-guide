# software-architecture-guide

A software architecture guide.

---

# Introduction

This guide aims to provide a concise overview of various aspects of software architecture. It covers key concepts, architectural styles, and essential principles to help developers, architects, and tech enthusiasts understand the foundational elements of building robust software systems.

## What is Software Architecture?

There is no clear and universally accepted definition of software architecture, as it heavily depends on the context and objectives of a system. Generally, software architecture describes the entirety of decisions that shape the design, structure, and behavior of a software system. These decisions can be made consciously or unconsciously.
Regardless of whether these decisions are deliberate or accidental, every software project inevitably develops a software architecture. The quality and clarity of this architecture significantly impact the maintainability, extensibility, and scalability of the system.

---

# Key concepts

## Coupling

Coupling describes the degree of dependency between two components in a system.
In general, we aim for a system with as **loose coupling** between components as possible. 
A component can represent various entities, such as a module, a service, or a database. 

Dependencies can manifest in many forms and affect the flexibility and maintainability of the system.

**Types of coupling**: 
- Temporal Coupling
- Data Coupling
- Content Coupling
- Control Coupling
- Contextual Coupling
- Common Coupling
- Sequential Coupling
- External Coupling

Examples of Coupling:

- Component A imports another component B: This creates a direct dependency where A relies on the functionality or structure of B. If B changes, A might also need to be updated.
- A component depends on receiving data from a REST API: The component must wait for the API's response before it can process or proceed. This introduces a dependency on external communication and response times.

## Cohesion

Cohesion describes how strongly components within a module or system are related. In general, we aim to achieve high cohesion.
High cohesion ensures that components are focused on a single responsibility, making the system easier to understand, maintain, and extend.

---

# Architecture Styles

## Monolithic Architecture

Monolithic Architecture is an architectural style where the entire system is built as a single, unified block. All components, such as the user interface, business logic, and data access layer, are tightly integrated and operate as a single application.

## Microservices

A microservice is an architectural style where a system is composed of multiple independent services. Each service is designed to perform a specific function and operates autonomously, communicating with other services through well-defined APIs.

## Event-Driven Architecture

## Service-Oriented Architecture (SOA)

## Serverless and Cloud Architecture

---

# Design Patterns

## Structural Patterns
## Behavioral Patterns
## Creational Patterns

---

# Contribution 

If you'd like to contribute, feel free to create a pull request. 
If you think a topic is missing, please open an issue.
