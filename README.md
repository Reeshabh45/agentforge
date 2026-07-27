# AI Vibe Coding Template

> **A battle-tested project structure that gives AI coding agents the context they need to write better code.**

Most AI coding assistants don't fail because they're bad at coding.

They fail because they **lack context**.

This repository provides a structured knowledge base that helps coding agents understand your product, architecture, design decisions, coding standards, implementation roadmap, and project memory before writing a single line of code.

Whether you're using **Cursor, Claude Code, Codex, Gemini CLI, Windsurf, Cline, Roo Code, or any other AI coding assistant**, this template gives your AI the information it needs to produce cleaner, more consistent, and production-ready code.

---

# Why?

Instead of saying

> "Build me authentication."

Your AI already knows:

- why authentication exists
- how your architecture works
- which design patterns to follow
- project conventions
- implementation phases
- UI guidelines
- previous architectural decisions
- preferred folder structure
- coding rules

The result is significantly better code generation with fewer corrections.

---

# Repository Structure

```
.
├── docs/
│   ├── PRD.md
│   ├── architecture.md
│   ├── design.md
│   ├── rules.md
│   ├── phases.md
│   └── memory.md
│
├── skills/
│   ├── fastapi.md
│   ├── nextjs.md
│   ├── react.md
│   ├── docker.md
│   ├── postgres.md
│   └── ...
│
├── frontend/
├── backend/
└── README.md
```

---

# Documentation

## PRD.md

Defines the product.

Contains

- Product vision
- User stories
- Features
- Functional requirements
- Acceptance criteria

---

## architecture.md

Explains the system.

Contains

- Architecture diagrams
- Data flow
- API structure
- Services
- Database
- Deployment

---

## design.md

Defines UI/UX.

Contains

- Design system
- Components
- Colors
- Typography
- Layout
- Accessibility

---

## rules.md

Project-wide engineering rules.

Examples

- Naming conventions
- Folder structure
- API standards
- Code quality
- Security
- Testing
- Git workflow

---

## phases.md

Roadmap for implementation.

Allows AI to build features incrementally rather than generating an entire application at once.

---

## memory.md

The project's long-term memory.

Stores

- architectural decisions
- trade-offs
- known issues
- lessons learned
- completed work
- future ideas

This prevents the AI from "forgetting" important context during long projects.

---

# Skills

One of the biggest problems with AI coding agents is that they often know *what* to build but not *how your team builds it*.

The `skills/` directory solves this.

Each file teaches the AI how your project expects a specific technology to be used.

Examples

```
skills/
    fastapi.md
    nextjs.md
    react.md
    docker.md
    postgres.md
    auth.md
    testing.md
    langgraph.md
    qdrant.md
```

Instead of repeatedly prompting:

> "Use dependency injection."

or

> "Organize routers this way."

or

> "Always use async."

You define it once inside the skill.

The coding agent follows it everywhere.

---

# Example

Instead of saying

```
Build a login API.
```

The AI will already know

- project architecture
- authentication flow
- API conventions
- folder structure
- error handling
- response format
- database organization

because everything is documented.

---

# Recommended Skills

Backend

- FastAPI
- Django
- Flask
- Express
- NestJS

Frontend

- React
- Next.js
- Vue
- Angular

AI

- LangChain
- LangGraph
- LlamaIndex
- OpenAI
- Anthropic
- Gemini

Infrastructure

- Docker
- Kubernetes
- Redis
- PostgreSQL
- MongoDB
- Qdrant

DevOps

- GitHub Actions
- Terraform
- AWS
- Azure
- GCP

---

# Supported AI Coding Agents

- Cursor
- Claude Code
- OpenAI Codex
- Gemini CLI
- Windsurf
- Roo Code
- Cline
- Continue
- GitHub Copilot

---

# Getting Started

1. Clone this repository.
2. Fill in the files under `docs/`.
3. Add technology-specific guides to `skills/`.
4. Point your coding agent to these files.
5. Start building.

---

# Contributing

Have a useful skill, architecture pattern, or project template?

Open a Pull Request.

The goal is to build a community-maintained knowledge base that helps AI coding assistants produce higher-quality software.

---

# License

MIT