# Node.js + TypeScript Backend Starter

Opinionated Node.js + TypeScript REST API starter with Hexagonal Architecture, Drizzle ORM, SQL-first migrations, and context-based scaffolding. Built with pnpm, Vitest, ESLint, and Prettier.

---

## Overview

This project is a reusable backend starter designed to provide a solid foundation for building scalable and maintainable APIs.

It focuses on clear architectural boundaries, domain isolation, and developer productivity through consistent structure and tooling. The goal is to balance simplicity with good engineering practices, avoiding unnecessary complexity while still enabling real-world use cases.

---

## Goals

- Provide a reusable backend starter for Node.js + TypeScript
- Enforce modular architecture (Hexagonal-inspired)
- Keep domain layer free of external dependencies
- Use SQL-first migrations for full database control
- Enable fast development through context-based scaffolding

---

## Tech Stack

- Node.js
- TypeScript
- Express
- Drizzle ORM
- PostgreSQL
- Vitest
- ESLint + Prettier
- pnpm

---

## Architecture

This project follows a modular architecture inspired by Hexagonal Architecture:

- **domain**: business logic and entities (framework-agnostic)
- **application**: use cases and orchestration
- **infrastructure**: external services (DB, ORM, etc.)
- **interfaces**: HTTP layer (controllers, routes, validation)

---

## Status

🚧 Work in progress — currently building the base template and core architecture.

---

## Roadmap

- [ ] Project setup (TypeScript, tooling)
- [ ] Base architecture structure
- [ ] Database setup and migrations
- [ ] First context implementation
- [ ] Context scaffolding script
- [ ] Documentation and examples
