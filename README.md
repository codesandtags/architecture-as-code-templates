# Architecture as Code

This repository contains our collection of version-controlled architecture diagrams. The goal is to create a "living documentation" of our systems that evolves alongside our code.

## 🎯 Purpose

* **Clarity:** Provide a clear, shared understanding of our software architecture.
* **Onboarding:** Accelerate ramp-up time for new engineers.
* **Collaboration:** Enable better technical discussions between teams.

## 🛠️ Tooling & Framework

* **Tool:** We use [Mermaid.js](https://mermaid.js.org/) for its "diagrams as code" approach.
* **Framework:** We follow the [C4 Model](https://c4model.com/) (Context, Containers, Components) to describe systems at different levels of detail.

## 🚀 How to Contribute

1.  Find the service you want to document under the `/services` directory.
2.  If it doesn't exist, create a new directory for it.
3.  Copy the relevant files from the `/templates` directory to your new service directory.
4.  Edit the `.mermaid` files to describe your system.
5.  Create a Pull Request for review.