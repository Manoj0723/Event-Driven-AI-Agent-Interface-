# AG-UI — Agent-User Interaction Protocol

> **A powerful open-source protocol I built to connect AI Agents with Frontend Applications in real time.**

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
[![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://github.com/Manoj0723/Event-Driven-AI-Agent-Interface-/pulls)
[![Built by Manoj](https://img.shields.io/badge/Built%20by-Manoj-blue)](https://github.com/Manoj0723/Event-Driven-AI-Agent-Interface-)

---

##  About This Project

I built **AG-UI** to solve a real problem — there was no clean, standardized way to connect AI agents to frontend applications.

AG-UI is my answer to that. It's a **lightweight, event-driven protocol** that acts as the communication layer between AI agents and modern web UIs. Whether you're building a chatbot, an AI dashboard, or a fully agentic web app — AG-UI handles the real-time streaming, state management, and agent-to-UI messaging for you.

This project is written entirely in **TypeScript**, designed to be framework-agnostic, and built with developer experience in mind.

---

##  What I Built

-  **Real-time Event Streaming** — Live agent responses with zero lag
-  **Framework Agnostic** — Plug into React, Vue, plain JS — anything
-  **Fully Typed TypeScript SDKs** — No guessing, full autocomplete support
-  **Multi-Framework Agent Support** — LangChain, CrewAI, Pydantic AI, Mastra & more
-  **Custom Middleware Layer** — Add auth, logging, or transformations easily
-  **MCP Compatible** — Works with Model Context Protocol servers out of the box
-  **Clean Monorepo Structure** — Everything organized, nothing bloated

---

##  Project Structure

```
ag-ui/
├── apps/          # Demo apps including the Dojo reference app
├── docs/          # Full MDX documentation
├── integrations/  # Agent framework connectors
├── middlewares/   # Custom middleware packages
├── sdks/          # TypeScript + community SDKs
└── scripts/       # Build, release, and automation scripts
```

---

##  Getting Started

### What You Need

- [Node.js](https://nodejs.org/) v18 or higher
- [pnpm](https://pnpm.io/) v10 or higher
- Git

### Run It Locally

```bash
# Step 1 — Enter the project folder
cd ag-ui

# Step 2 — Install all dependencies
pnpm install

# Step 3 — Start the app
cd sdks/typescript
pnpm dev
```

Open your browser and go to: **http://localhost:3000** 

---

##  Supported Agent Frameworks

I built integrations for all the major AI agent frameworks so you can plug in whatever you're already using:

| Framework     | Status        |
|---------------|---------------|
| LangChain     | ✅ Supported  |
| LangGraph     | ✅ Supported  |
| CrewAI        | ✅ Supported  |
| Mastra        | ✅ Supported  |
| Pydantic AI   | ✅ Supported  |
| AWS Strands   | ✅ Supported  |
| Google ADK    | ✅ Supported  |

---

##  How It Works

```
Your Web App (Frontend)
        ↕   AG-UI Protocol Events
  Middleware Layer
        ↕   Standardized Messages
  AI Agent Backend (LangChain / CrewAI / etc.)
```

1. User sends a message from the **frontend**
2. AG-UI routes it through the **middleware layer**
3. The **AI agent** processes it and streams back a response
4. The **UI updates live** as events come in — no page refresh, no waiting

---

##  SDKs

| SDK            | Language   | Path                     |
|----------------|------------|--------------------------|
| Main SDK       | TypeScript | `sdks/typescript`        |
| Python SDK     | Python     | `sdks/python`            |
| Kotlin SDK     | Kotlin     | `sdks/community/kotlin`  |

---

##  Documentation

Full documentation covering every part of this project:

 **[docs.ag-ui.com](https://docs.ag-ui.com)**

Includes:
- Protocol specification
- SDK reference
- Integration guides
- Middleware development
- Example apps and walkthroughs

---

##  Contributing

I'd love your help making this better! Here's how to contribute:

```bash
# Step 1 — Create your own branch
git checkout -b feature/your-idea

# Step 2 — Make your changes and commit
git add .
git commit -m "Add your feature"

# Step 3 — Push your changes
git push origin feature/your-idea

# Step 4 — Open a Pull Request
```

---

##  License

Licensed under the **MIT License** — free to use, modify, and distribute.
See the [LICENSE](LICENSE) file for full details.

---

##  Links

-  Website: [ag-ui.com](https://ag-ui.com)
-  Docs: [docs.ag-ui.com](https://docs.ag-ui.com)
-  Discussions: [GitHub Discussions](https://github.com/Manoj0723/Event-Driven-AI-Agent-Interface-/discussions)
-  Report a Bug: [GitHub Issues](https://github.com/Manoj0723/Event-Driven-AI-Agent-Interface-/issues)

---

<p align="center">Built with ❤️ by <strong>YOUR NAME</strong></p>
