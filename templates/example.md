# Template Examples

This document provides examples of all available templates in this repository.

## C4 Model Diagrams

### C1 Context Diagram

Shows the system's relationship with users and other systems.

```mermaid
%% C4 Model - Level 1: System Context
%% Purpose: Shows the system's relationship with users and other systems.
%% Instructions: Replace placeholders like [User Role] and [External System].

graph TD
    %% Define Users (Actors)
    user1("[User Role]<br>[Person]")
    user2("[Another User Role]<br>[Person]")

    %% Define your system within a boundary
    subgraph Your Company
        yourSystem("<strong>[Your Service Name]</strong><br>[Software System]<br>Briefly describe its core purpose here.")
    end

    %% Define External Systems it interacts with
    extSystem1("[External System]<br>[Software System]<br>e.g., Payment Gateway")
    extSystem2("[Another External System]<br>[Software System]<br>e.g., Email Service")

    %% Define the relationships and data flow
    user1 -- "Interacts via [Action]" --> yourSystem
    user2 -- "Interacts via [Action]" --> yourSystem
    yourSystem -- "Sends/Receives [Data] to/from" --> extSystem1
    yourSystem -- "Sends/Receives [Data] to/from" --> extSystem2
```

### C2 Container Diagram

Decomposes your system into its major building blocks.

### C3 Component Diagram

Decomposes a single container into its key internal code modules.

### C4 Code Diagram

Shows how code is organized within a single component.

## Other Diagram Types

### Sequence Diagram

Shows interaction between different actors/objects over time.

### Flowchart

Shows a process flow or decision tree.

### State Diagram

Shows different states of an object and transitions between them.

## Documentation Templates

### RFC (Request for Comments)

For proposing significant changes or new features.

### ADR (Architecture Decision Record)

For documenting architectural decisions that have been made.

### 1-Pager

For concise project summaries and proposals.

## Tools

### Excalidraw Guide

For creating hand-drawn style diagrams and sketches.
