# ⚡️ Algo North

**Building scalable automation infrastructure, AI services, and high-performance web products.**

Welcome to the Algo North engineering organization. This is our central hub for all core platforms, automation systems, and client-facing web applications. We treat our infrastructure as a product, prioritizing clean code, modular architecture, and rapid deployment.

---

## 🗺️ System Architecture

Our organization is structured into strict domains. **If you are looking for a specific system, check its designated category:**

### ⚙️ 00. Infrastructure & DevOps
The deployment pipelines and shared services that keep Algo North running.
* `infra-docker-stack` - Core environment setups (DBs, Redis, Nginx)
* `infra-ci-cd` - GitHub Actions templates and deployment workflows

### 🧠 01. Core Platform
The backend engine and centralized APIs.
* `algo-north-core-api` - Main backend routing and logic
* `algo-north-auth-service` - Centralized user management and authentication

### 🤖 02. Automation Systems
Our primary value drivers and internal workflows.
* `automation-workflow-engine` - Internal automation routing system
* `automation-lead-generator` - Scraping and data collection pipelines

### 🌐 03. Web Products
Client-facing interfaces and internal tools.
* `web-algo-north-site` - Official public landing page
* `web-dashboard-ui` - Reusable frontend component library

### 🤖 04. AI Services
The intelligence layer powering our automation, built on multi-model architectures integrating Claude 3.5 Sonnet and GPT-4o for processing and generation tasks.
* `ai-chat-agents` - Context-aware assistants
* `ai-rag-system` - Retrieval augmented generation pipelines

---

## 🚀 Developer Onboarding

If you are a new core developer joining the team, follow these steps to get started:

1. **Request Access:** Ensure you have been added to the `Core Devs` GitHub team.
2. **Clone the Hub:** Start by cloning the repository you are assigned to (e.g., `algo-north-core-api`).
3. **Environment Setup:** Copy the `.env.example` to `.env` and request the active development keys from the team lead.
4. **Branching:** Never push directly to `main`. Create a branch using the format `feature/your-feature-name` or `fix/issue-name`.

---

## 🛠️ Engineering Standards

To maintain a professional, production-ready codebase, we enforce the following rules:

* **One Purpose Per Repo:** Do not mix frontend, backend, and marketing code.
* **Pull Requests Required:** All code must be submitted via PR and reviewed before merging into the `main` branch. 
* **Self-Documenting Code:** If a system is complex, it requires a localized `README.md` in its repository folder.

***

*Property of Algo North. Internal Engineering Use Only.*
