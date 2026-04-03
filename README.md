# 🚀 Brev.ly

Brev.ly is a full-stack URL shortening and management platform that allows users to create, track, and manage short links efficiently.

It combines a React front end with a Fastify API, focusing on performance, scalability, and a clean user experience.

---

## 🧩 Overview

The application provides an end-to-end solution for managing shortened URLs, including creation, redirection, analytics, and data export.

Users can:
- generate short links
- track usage through access counters
- manage and delete links
- export data for reporting purposes

---

## 🏗️ Architecture

The project is structured as a monorepo with two main applications:

- **client** — React SPA built with Vite
- **server** — Fastify API handling business logic and persistence

---

## ⚙️ Tech stack

### Front end
- React 19
- TypeScript
- Vite
- React Router
- Tailwind CSS
- shadcn/ui
- Zod

### Back end
- Fastify
- TypeScript
- PostgreSQL
- Drizzle ORM
- Zod
- Swagger

### Tooling
- Docker
- ESLint & Prettier
- Vitest
- dotenv

---

## ✨ Key features

- Short URL generation with validation
- Duplicate prevention
- Redirection to original URLs
- Link management (list and delete)
- Access tracking (click count)
- CSV export for reporting

---

## 📦 Getting started

For setup and development instructions, please refer to:
- [Client README](./client/README.md)
- [Server README](./server/README.md)

---

## 💡 Notes

This project was developed as part of a postgraduate programme, with a focus on building a production-ready full-stack application, emphasising scalability, performance, and clean architecture.

---

## 👩‍💻 Author

Created by **Patricia Segantine** — Frontend Engineer
