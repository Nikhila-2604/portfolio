# 🚀 Modern Full-Stack Developer Portfolio

Welcome to my personal portfolio repository! This is a high-performance, edge-optimized web application built to showcase my projects, skills, and professional journey. 

🌐 **Live Demo:** [View Live Portfolio](https://tanstack-start-app.poolanikhila2604.workers.dev/)

---

## ✨ Features

* **⚡ Edge-Rendered Performance:** Powered by TanStack Start and deployed globally on Cloudflare Workers for near-zero latency.
* **🔒 Secure Authentication:** Implemented via Supabase Auth for restricted dashboard access.
* **📦 Dynamic Content Management:** Projects, skills, and experience are dynamically fetched from a Supabase PostgreSQL database.
* **🎨 Modern UI/UX:** A fully responsive, accessible design crafted with component-driven architecture.
* **🚀 Blazing Fast Builds:** Utilizes Bun as a runtime and bundler for rapid development workflows.

---

## 🛠️ Tech Stack

### Frontend & Framework
* **[TypeScript](https://www.typescriptlang.org/):** Strong static typing for robust code quality.
* **TanStack Start / Router:** Type-safe routing and state synchronization.
* **[Vite](https://vitejs.dev/):** Ultra-fast frontend tooling and hot module replacement.

### Backend & Infrastructure
* **[Supabase](https://supabase.com/):** PostgreSQL database, Authentication, and Object Storage.
* **[Cloudflare Workers](https://workers.cloudflare.com/):** Serverless edge computing platform via Wrangler.
* **[Bun](https://bun.sh/):** All-in-one JavaScript runtime, package manager, and test runner.

---

## ⚙️ Project Structure

```text
├── .env                # Local environment variables (gitignored)
├── bunfig.toml         # Bun package manager configuration
├── components.json     # UI component system configurations
├── eslint.config.js    # Linting rules for code consistency
├── src/                # Application source code
│   ├── components/     # Reusable UI components
│   ├── routes/         # TanStack file-based routing
│   └── utils/          # Database clients and helper functions
├── supabase/           # Database migrations, schemas, and seeds
├── vite.config.ts      # Vite bundler configuration
└── wrangler.jsonc      # Cloudflare Workers deployment configuration
