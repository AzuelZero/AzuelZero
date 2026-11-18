# Hi, I'm Azuel 👋

**Backend Developer** focused on building reliable, secure services — with a strong **DevOps and infrastructure** mindset.

- 🔭 Currently building the backend for a **mental-health & wellness platform** (iOS · Android · Web, in production)
- 🛠️ Daily stack: **TypeScript · NestJS · PostgreSQL · Redis · Docker · GitHub Actions**
- 🌱 Currently learning **Go** — building [Miyano](https://github.com/AzuelZero/Miyano), an offline-first workout app, from scratch
- 🔐 I care a lot about **applied security**: I've handled real secret-rotation incident response, SAST/SCA pipelines, and GDPR workflows

---

## ⚙️ Tech I work with

**Languages**
`TypeScript` `Go (learning)` `SQL` `Python` `Java` `C#`

**Backend**
`NestJS` `Node.js` `REST` `JWT (access/refresh rotation)` `OAuth2 (Google / Apple)` `Django` `Spring Boot` `Express`

**Data & Caching**
`PostgreSQL` `Redis` `MongoDB` `SQLite` `Drizzle ORM` `sqlc` `Prisma`

**DevOps & Infrastructure**
`Docker` (multi-stage, least-privilege) · `GitHub Actions` (CI/CD) · `VPS / Linux` · `Docker Compose` · `GHCR`

**Security**
`SAST/SCA` · `CodeQL` · `Trivy` · `gitleaks` · `OWASP` · `MFA / TOTP` · `Secret rotation` · `GDPR / RGPD`

**Frontend (full-stack capable)**
`React` `Next.js` `React Native / Expo` `Vue 3` `Tailwind`

---

## 🚀 What I'm working on

### 🧠 Backend @ a mental-health & wellness startup — *current, production*

The backend powering a cross-platform wellness app (iOS, Android, web) — **NestJS + PostgreSQL + Redis + Drizzle**, deployed to a VPS via Docker + CI/CD.

Things I've owned end-to-end:

- 🔐 **Auth & identity** — JWT access/refresh rotation, Google + Apple Sign-In, MFA TOTP, magic links, rate limiting, anti-enumeration
- 💳 **Payments across three gateways** — Stripe, Apple StoreKit 2, and Google Play Billing v2, with server-to-server verification and idempotent webhooks
- 🤖 **AI features** — a conversational wellness companion using RAG + per-user semantic memory, with a safety layer that routes crisis signals to emergency resources *before* the model responds
- 🛡️ **Security & compliance (GDPR)** — led the response to a real production secret-leak (rotation + full history scan), built an append-only consent ledger, soft-delete with legal-hold, and a SAST/SCA pipeline (CodeQL, Trivy, gitleaks)
- ⚙️ **DevOps** — multi-stage Docker images, least-privilege deploys, CI quality gates (test / lint / audit), health checks and graceful shutdown for zero-downtime rolling deploys

### 📚 [Byeolpedia](https://github.com/AzuelZero/Byeolpedia) — K-pop merch collection manager

Full-stack app for managing K-pop merchandise collections. **Django REST Framework** backend with JWT auth + a custom permissions system, **Flutter** frontend, **PostgreSQL** with a complex relational model. Roadmap: on-device image recognition with TensorFlow Lite.

### 🏋️ [Miyano](https://github.com/AzuelZero/Miyano) — Offline-first workout app *(learning Go)*

A personal project I'm building **from scratch to learn Go properly** — no shortcuts. Offline-first (critical for gym/travel without coverage), with an adaptive progression engine. Backend in **Go + Chi + sqlc + pgx**, frontend in **Vue 3 + Capacitor**. Currently in the architecture/design phase, with every decision written up as an ADR.

---
## 👀 Beyond code

- 🦥 Lazy to the bone — which is exactly why I'm building a workout app (someone has to force me off the couch)
- 🎮 Game modding in C# / .NET (BepInEx / Harmony) and EN↔ES game translation packs

---

*Always more interested in understanding things "for real" than in copying the first tutorial I find.*
