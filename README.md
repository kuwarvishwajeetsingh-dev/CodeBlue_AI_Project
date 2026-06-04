
# CodeBlue AI 🚑💡

> An intelligent, scalable, and AI-powered healthcare emergency response ecosystem designed to minimize response delays and maximize patient survival outcomes.**


📁 CodeBlue_AI_Project

 ├── 🌿 main         -> 📄 (Only documents, system layout images, README)
 
 ├── 🌿 frontend     -> 💻 (Only frontend code)
 
 └── 🌿 backend      -> ⚙️ (Only backend code)

## 🌟 The Unified Vision
Every second optimized in emergency transit is a heartbeat reclaimed for a family. Legacy healthcare emergency frameworks suffer from critical communication silos and transit latency. 
CodeBlue AI bridges this gap by engineering a multi-login, real-time ecosystem that harmonizes patients, emergency dispatchers, and clinical hubs into a single intelligent matrix, powered by advanced predictive logic and spatial computing.

---

## 🏗️ System Architecture & Subsystems
CodeBlue AI is engineered as a highly responsive, secure, multi-tier ecosystem:
* **Intelligence Layer:** Deep context parsing and automated routing decisions driven by the **Google Gemini AI API**.
* **Frontend Matrix:** Highly performant, dynamic interface built using a responsive **React / Vite** architecture.
* **Telemetry Core:** Live GIS spatial mapping environments coupled with predictive, low-latency ambulance routing algorithms.
* **Hospital Dashboard Feed:** Real-time data streaming feeds providing clinical hubs with pre-arrival diagnostics and live situational metrics.

---

## 👥 Executive Leadership Board & Core Roles

### 1. Kuwar Vishwajeet Singh — Founder & Chief Execution 
* **Strategic Mandate:** Guides the overall vision, long-term operational scaling boundaries, investor relations, and high-stakes executive decisions along with Core Development.
* **Core Engineering Impact:** Conceptualized the baseline ecosystem workflow; architected the multi-login cloud structure and supervised Gemini API logic implementations.

### 2. Amritansh Singh — Chief Technology Officer (CTO) & Co-Founder
* **Technical Governance:** Owns the baseline technology choices, full-stack software development models, system security protocols, and API microservices.
* **Core Engineering Impact:** Deployed the React/Vite application layer, wired the Gemini API endpoints, and built the live web-socket data streaming matrices for the hospital dashboard feeds.

### 3. Adima Agarwal — Chief Operating Officer (COO) & Co-Founder
* **Operational Governance:** Commands agile sprint scheduling, , cross-functional communication guardrails, and key performance tracking.
* **Core Engineering Impact:** Designed the centralized issue task board matrix, spearheaded end-to-end parallel system validation testing, and managed delivery pipelines.
* Future Backend Integration using Springboot.

---

## 🛠️ Technology Stack
* **Language & Runtime:** JavaScript / TypeScript, Node.js(At Starting),  Springboot(Future Integration)
* **Framework & Build Utility:** React, Vite
* **Artificial Intelligence Engine:** Google Gemini AI APIs MAP, Adhar Authentication API
* **Mapping Environment:** GIS Spatial Mapping & Dynamic Routing Services
* **State Management & Communication:** Web-Sockets for real-time concurrent data pipelines

---

## 🛡️ Security & Secret Management Mandate
This codebase interacts directly with proprietary configurations and API keys. Protection of these variables is non-negotiable.
* **API Constraints:** All primary credentials (such as `VITE_GEMINI_API_KEY`) must live strictly within a localized, disconnected `.env` file.
* **Git Trackers:** Direct commits containing explicit configuration strings are permanently restricted. The root level `.gitignore` is pre-configured to drop local `.env` and `node_modules` from tracking buffers.

---

## 🚀 Branching Protocol & Engineering Workflow
To preserve production environment up-time, our engineering team adheres to strict branch protection mandates:

1. **`main`**: Sacred production node. Direct commits are restricted. Code changes land here exclusively via formal releases.
2. **`develop`**: Central sandbox layer where integration, testing, and sprint tracking tasks compile.
3. **`feature/*` or `fix/*`**: Ephemeral development sandboxes where developers write individual feature milestones before logging a pull request review.

### Standard Git Execution Sequence:
```bash
# Sync local environment with remote develop branch
git checkout develop
git pull origin develop

# Generate isolated feature tracker environment
git checkout -b feature/your-feature-name

# Compile changes with atomic, descriptive messages
git add .
git commit -m "feat: short description of specific adjustment made"

# Safely push milestone updates to origin repository
git push origin feature/your-feature-name
