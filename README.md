# The Evolution of Todo - Phase 1: In-Memory Python Console App

## 🚀 Overview

This repository contains the first milestone of the **Evolution of Todo** hackathon. The objective of Phase 1 is to establish the architectural foundation of a task management system by building a robust **In-Memory Python Console Application** using a strict **Spec-Driven Development (SDD)** workflow.

In this phase, the focus is not just on the code, but on the methodology: acting as a **System Architect** to guide AI agents through formal specifications rather than manual syntax writing.

## 🛠 Technology Stack

* **Language:** Python 3.12+
* **AI Orchestrator:** [Claude Code](https://www.claude.ai)
* **SDD Framework:**([https://github.com/panaversity/spec-kit-plus](https://github.com/panaversity/spec-kit-plus)) (`specifyplus`)
* **Development Environment:** VS Code / Terminal (PowerShell/Bash)

## 📋 Core Requirements

Based on the official hackathon guidelines, this application implements the following features:

* **Task Management:** Add, View, Update, and Delete (CRUD) tasks.
* **Status Tracking:** Mark tasks as "Complete" or "Pending."
* **Data Integrity:** Unique identification for tasks (UUIDs) within an in-memory storage system.
* **Methodology:** Strict adherence to SDD (Zero manual coding allowed).

## 🔄 Spec-Driven Workflow

The development followed the standard Spec-Kit Plus lifecycle to ensure traceability and architectural consistency:

1. **Initialization:** Scaffolding the project structure using `specifyplus init`.
2. **Constitution:** Establishing governing principles (Clean Code, PEP 8, SDD rules) via `.specify/memory/constitution.md`.
3. **Specification:** Defining the "What" through a formal feature brief and requirements document.
4. **Planning:** Architecting the "How" with a technical blueprint (`plan.md`).
5. **Task Breakdown:** Decomposing the plan into atomic, reviewable work packages (`tasks.md`).
6. **Implementation:** Executing code generation through the AI agent via the `/sp.implement` workflow.

## 📂 Project Structuretext

todo/
├──.claude/                # Agent commands and session context
├──.specify/               # SDD Governance (Constitution and Templates)
├── specs/                  # Phase 1 Specifications, Plans, and Task lists
├── main.py                 # AI-generated Python Console Application
├── CLAUDE.md               # Agent instructions and workflow guidelines
└── README.md               # Project documentation

```

## 🚦 How to Run
1. Ensure you have **Python 3.12+** installed.
2. Run the application from the terminal:
   ```bash
   python main.py

```

3. Follow the on-screen menu instructions to manage your tasks.

## 🏛 Archeological Record

This project treats specifications as first-class artifacts. All technical decisions are documented in the `specs/` and `.specify/` directories, providing a complete "Archeological Record" of the development process for future phases.

```

### **Summary of Changes**
- Created a comprehensive `README.md` that explains the Phase 1 objectives (In-Memory Console App).
- Included the mandatory functional requirements (Add, View, Update, Delete, Complete).
- Documented the **Spec-Driven Development** methodology you used.
- Mapped out the project structure seen in your VS Code screenshots.

I have updated your research report to include this README blueprint for your future reference. Let me know if you are ready to move to **Phase 2: The Full-Stack Web App Transition**!
