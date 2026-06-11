<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=28&pause=1000&color=D32F2F&center=true&vCenter=true&width=700&lines=Vijay+Kumar+G+K;ECE+Engineer+|+Full-Stack+Developer;AI-Augmented+Software+Engineer" alt="Typing SVG" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white" alt="Kotlin" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black" alt="React" />
  <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white" alt="Next.js" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" alt="FastAPI" />
  <img src="https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black" alt="Firebase" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white" alt="Tailwind CSS" />
  <img src="https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white" alt="Android" />
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white" alt="GitHub Actions" />
</p>

---

## Professional Summary

**Electronics & Communication Engineering** student at **Government Srikrishnarajendra Silver Jubilee Technological Institute**, Bangalore (VTU University, 2026).

I architect **end-to-end production systems** spanning Android (Kotlin/Jetpack Compose), modern web (React/Next.js/TypeScript), and AI-powered backends (Python/FastAPI), unified by Firebase and Docker infrastructure. Every project in my portfolio was built using an **agentic AI-augmented workflow** — leveraging agentic IDEs and LLM toolchains to accelerate design, code generation, documentation, and testing while maintaining full engineering rigor.

> **Philosophy:** *AI accelerates the routine. Engineering judgement drives the architecture.*

---

## Agentic Workflow

I employ a structured **human-in-the-loop agentic workflow** where AI handles accelerated generation, and I retain full architectural control. This approach enables me to ship production-grade, multi-service applications that would typically require a team.

### 1. Specification & Architecture Design

Every project begins with a **detailed specification document** — a `plan.md` that captures all requirements, data flow diagrams, route tables, schema designs, security rules, component trees, and deployment strategy. This document serves as the single source of truth for both human and AI agents.

```
plan.md (comprehensive spec)
  ├── Feature breakdown with acceptance criteria
  ├── Technology stack decisions with rationale
  ├── Data flow diagrams & architecture ASCII art
  ├── Route/API endpoint tables with auth requirements
  ├── Database schema & Firestore security rules
  ├── Component tree & file structure
  ├── Testing strategy & CI/CD pipeline design
  └── Deployment topology & environment variables
```

### 2. Skills-Based Decomposition

The specification is decomposed into **discrete, parallelizable skill units** — each mapped to a specialized sub-agent with context-limited scope. This mirrors how a team of engineers would divide work:

| Skill | Responsibility | Agent Scope |
|---|---|---|
| **Scaffolder** | Vite+React+TS setup, Tailwind/shadcn/ui init, Firebase SDK config, React Router wiring, providers | Project skeleton & infrastructure |
| **Feature Builder** | All pages, forms, modals, listing screens, static pages; wires everything to Firebase hooks | UI layer & business logic |
| **Map Specialist** | Leaflet map integration, geolocation API, donor markers, radius circles, location picker | Geo-spatial features |
| **Hook Builder** | Custom Firestore real-time hooks with `onSnapshot`, loading/error states, typed collections | Data layer |

Each sub-agent receives only the relevant slice of the specification, ensuring focused, high-quality output without cross-contamination.

### 3. Iterative Agentic Generation

Agents work in a **structured generation loop** supervised through human review after each phase:

```
Specification
     │
     ▼
[Agent: Scaffolder] → Project skeleton initialized (Vite, Firebase, Router, Tailwind, Theme, Auth)
     │
     ▼
     Human Review → Confirm structure, adjust config
     │
     ▼
[Agent: Hook Builder] → Firestore typed hooks created (useDonors, useHospitals, useEmergencyies, useAuth...)
     │
     ▼
[Agent: Feature Builder] → Pages & components generated (SearchPage, Registration, SOS, Certificates...)
     │
     ▼
[Agent: Map Specialist] → Map components integrated (DonorMap, LocationPicker, RadiusCircle)
     │
     ▼
     Human Review → Code review, integration testing, edge case handling
     │
     ▼
[Agent: Docs + Polish] → README, DOCUMENTATION, LICENSE, screenshots, CI/CD
     │
     ▼
     Human Final Review → Quality gate, security audit, production readiness
```

### 4. Context Management & Toolchain

Each agent operates within a **tightly scoped context** using the following AI toolchain:

| Tool | Role | How It's Used |
|---|---|---|
| **OpenCode CLI** | Primary agentic orchestrator | Context-aware multi-file edits, sub-agent delegation, skill-based task routing, sequential thinking for complex refactors |
| **Claude Code** | Deep reasoning for architecture & planning | Cross-file dependency analysis, migration planning, complex refactoring, security audit |
| **Gemini CLI** | Rapid prototyping & boilerplate | Quick component generation, translation tasks, batch file transformations |
| **Open Router** | LLM routing gateway | Routes to optimal model per task (GPT-4o for planning, Claude for reasoning, DeepSeek for code) |
| **Prompt Engineering** | Structured task definition | Chain-of-thought specs, few-shot examples, exact output formatting for consistent agent results |

### 5. Quality Assurance & Deployment

All agent-generated code passes through the same engineering rigor as hand-written code:

1. **TypeScript strict mode** — no implicit any, full type safety enforced
2. **Lint & typecheck** — automated in CI pipeline before any merge
3. **Firestore security rules** — validated against the auth model from `plan.md`
4. **Cross-platform consistency** — web, Android, and HTML versions share identical Firebase backend
5. **CI/CD automation** — GitHub Actions builds, type-checks, and deploys to GitHub Pages on every push

### 6. Real-World Application

This workflow was used to build every project in this portfolio. For example, the **Rakta-Vahini web app** was generated across 4 agent sessions — each focused on a specific skill — producing 40+ components, 12 pages, 6 custom Firestore hooks, 17 shadcn/ui primitives, Leaflet map integration, smart scoring algorithms, and a GitHub Actions CI/CD pipeline, all within a single unified architecture.

The **Employee Knowledge Assistant** was built using a similar decomposition: a `plan.md` spec covering the RAG pipeline, vector store schema, API routes, and Docker topology, then executed by specialized agents for backend (FastAPI + SQLAlchemy + ChromaDB), frontend (Next.js + shadcn/ui), and infrastructure (Docker Compose + Nginx).

---

## Featured Projects

### AI-Powered Employee Knowledge Assistant
[![GitHub](https://img.shields.io/badge/View_Repo-181717?style=flat-square&logo=github)](https://github.com/vijaykumarGK-Developer/employee-knowledge-assistant) [![MIT License](https://img.shields.io/badge/License-MIT-yellow?style=flat-square)](https://github.com/vijaykumarGK-Developer/employee-knowledge-assistant/blob/main/LICENSE)

An intelligent internal knowledge base that enables employees to query company documents using natural language. Features RAG-based Q&A with source citations, department-level access control, document management (PDF/DOCX/TXT/CSV), analytics dashboard, and a full REST API.

| Layer | Technology |
|---|---|
| **Backend** | Python 3.12+, FastAPI, SQLAlchemy, PostgreSQL/ChromaDB |
| **Frontend** | Next.js 16, React 19, TypeScript, Tailwind CSS 4, shadcn/ui |
| **Vector Store** | ChromaDB (cosine similarity search with Sentence-Transformers `all-MiniLM-L6-v2`) |
| **Q&A Engine** | Extractive (no LLM API needed — 100% local) |
| **Infrastructure** | Docker, Docker Compose, Nginx reverse proxy |

**API:** OpenAPI docs at `/docs` — endpoints for auth, document CRUD, chat with source citations, analytics, and admin management.

---

### Blood Donation Network — Rakta-Vahini
[![Web App](https://img.shields.io/badge/Web_App-3178C6?style=flat-square&logo=react)](https://github.com/vijaykumarGK-Developer/raktavahini-web) [![Android App](https://img.shields.io/badge/Android_App-7F52FF?style=flat-square&logo=kotlin)](https://github.com/vijaykumarGK-Developer/rakthavahini) [![HTML Version](https://img.shields.io/badge/HTML_Version-E34F26?style=flat-square&logo=html5)](https://github.com/vijaykumarGK-Developer/rakthavahini-html)

A **cross-platform, real-time blood donation ecosystem** connecting verified donors with hospitals and emergency requests. Deployed across three platforms sharing a common Firebase backend.

| Platform | Stack | Highlights |
|---|---|---|
| **Web App** | React 19, TypeScript, Vite 6, Tailwind CSS 4, shadcn/ui, Firebase 11, Leaflet | Interactive donor map with blood group markers, smart composite scoring, radius-based proximity search, one-tap SOS broadcast, Google Auth, dark mode, GitHub Pages CI/CD |
| **Android App** | Kotlin, Jetpack Compose, MVI Architecture, Firebase Auth & Firestore | Single `AppState` container, real-time snapshot listeners, certificate generation, dynamic theming |
| **Lightweight Web** | Vanilla HTML, CSS, JavaScript, Leaflet | Zero dependencies, works everywhere, single-file architecture |

**Core algorithms:** Haversine distance, composite smart scoring (`dist + responseSpeed × 0.1 + activeDaysAgo × 0.5 − freq × 0.2`), 90-day eligibility enforcement.

---

### Delta Crypto TradingView-Style Backtesting Framework
[![GitHub](https://img.shields.io/badge/View_Repo-181717?style=flat-square&logo=github)](https://github.com/vijaykumarGK-Developer/delta-crypto-trading-view-backtest-stratergy)

A free, Python-powered alternative to TradingView Pine Script for backtesting on Delta Exchange. Features a modular **7-block notebook architecture** with HMAC-SHA256 API authentication, multi-indicator strategies (VWAP, SMA, RSI, Bollinger Bands), and interactive Plotly visualizations.

**Strategies:** Day Trading (VWAP mean reversion), Multi-Indicator VWAP, and custom strategy template. Includes performance metrics (win rate, profit factor, Sharpe ratio, max drawdown) and live automation templates.

| Stack | Python, backtrader, pandas, NumPy, requests, Plotly, Delta Exchange v2 API |
|---|---|

---

### OmniStock — Inventory Management System
[![GitHub](https://img.shields.io/badge/View_Repo-181717?style=flat-square&logo=github)](https://github.com/vijaykumarGK-Developer/OmniStock-Inventory-Management) [![MIT License](https://img.shields.io/badge/License-MIT-yellow?style=flat-square)](https://github.com/vijaykumarGK-Developer/OmniStock-Inventory-Management/blob/main/LICENSE)

A full-stack inventory management platform with role-based access control (Admin/Manager/Staff), real-time stock tracking, POS billing, purchase order workflow, and interactive analytics dashboards.

| Layer | Technology |
|---|---|
| **Frontend** | React 19, TypeScript (strict), Tailwind CSS 4, Recharts, React Router v7 |
| **Backend** | Express 5, Prisma 7 ORM, Zod validation, JWT auth (bcryptjs + jsonwebtoken) |
| **Database** | SQLite via better-sqlite3 |
| **Build** | Vite 8 (frontend), tsx (backend) |

---

## Technical Proficiencies

### Languages
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)

### Frontend & UI
![React](https://img.shields.io/badge/React_19-61DAFB?style=flat-square&logo=react)
![Next.js](https://img.shields.io/badge/Next.js_16-000000?style=flat-square&logo=next.js&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS_4-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![shadcn/ui](https://img.shields.io/badge/shadcn%2Fui-000000?style=flat-square&logo=shadcnui&logoColor=white)
![React Router](https://img.shields.io/badge/React_Router-CA4245?style=flat-square&logo=reactrouter&logoColor=white)
![Leaflet](https://img.shields.io/badge/Leaflet-199900?style=flat-square&logo=leaflet&logoColor=white)
![Recharts](https://img.shields.io/badge/Recharts-22B5BF?style=flat-square)
![Jetpack Compose](https://img.shields.io/badge/Jetpack_Compose-4285F4?style=flat-square&logo=jetpackcompose&logoColor=white)

### Backend & Database
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=flat-square&logo=python&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black)
![Firestore](https://img.shields.io/badge/Firestore-FFCA28?style=flat-square&logo=firebase&logoColor=black)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FC6D26?style=flat-square)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

### Data Science & Algorithmic Trading
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)
![backtrader](https://img.shields.io/badge/backtrader-FF6600?style=flat-square)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=flat-square&logo=plotly&logoColor=white)

### DevOps & CI/CD
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white)
![GitHub Pages](https://img.shields.io/badge/GitHub_Pages-222222?style=flat-square&logo=githubpages&logoColor=white)
![Docker Compose](https://img.shields.io/badge/Docker_Compose-2496ED?style=flat-square&logo=docker&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)

---

## GitHub Analytics

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=vijaykumarGK-Developer&show_icons=true&theme=dark&hide_border=true&count_private=true&include_all_commits=true" alt="GitHub stats" width="48%" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=vijaykumarGK-Developer&layout=compact&theme=dark&hide_border=true&exclude_repo=vijaykumarGK-Developer" alt="Top languages" width="48%" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=vijaykumarGK-Developer&theme=dark&hide_border=true" alt="GitHub streak" width="48%" />
</p>

---

## Connect

<p align="center">
  <a href="mailto:vijaykumar2572003@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail" />
  </a>
  <a href="https://linkedin.com/in/vijay-kumar-b5311b280">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="https://github.com/vijaykumarGK-Developer">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
  </a>
</p>

<p align="center">
  <b>Location:</b> Bengaluru, Karnataka, India &nbsp;•&nbsp; <b>Education:</b> VTU University, 2026
</p>

---

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=vijaykumarGK-Developer&label=Profile+Views&color=D32F2F&style=flat" alt="Profile views" />
  <br><br>
  <i>"AI accelerates the routine. Engineering judgement drives the architecture."</i>
</p>
