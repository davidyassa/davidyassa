<div align="center">

# Hey, I'm David 👋

**Computer & Communications Engineering student · Backend & AI Engineering**

📍 Alexandria, Egypt &nbsp;•&nbsp; 🎓 Faculty of Engineering, Alexandria University

[![LinkedIn](https://img.shields.io/badge/LinkedIn-david--mansourr-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/david-mansourr/)

</div>

---

## 🧑‍💻 About Me

I'm a third-year Computer and Communications Engineering student who enjoys building the parts of software you don't see: APIs, databases, and AI pipelines. I like clean architecture, shipping things that actually run in Docker, and learning by building.

- 🔭 Building backend systems and AI-powered apps (RAG, agents, pipelines)
- 🌱 Currently deepening my knowledge of system design, ML, and operating systems
- 💬 Ask me about Node.js, PostgreSQL, Docker, or RAG
- ⚡ Fun fact: I earned the **Quickdraw** achievement on GitHub

---

## 🛠️ Tech Stack

**Backend**

![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white)

**Data & Infra**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)

**AI / ML**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![Qdrant](https://img.shields.io/badge/Qdrant-DC244C?style=for-the-badge&logo=qdrant&logoColor=white)
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=for-the-badge&logo=n8n&logoColor=white)

**Languages**

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)

---

## 🚀 Featured Projects

| Project | Description | Stack |
| :-- | :-- | :-- |
| [**CRUD_API**](https://github.com/davidyassa/CRUD_API) | Task CRUD API with swappable SQLite/Postgres backends, Supabase auth, Redis, and Docker. One codebase, two databases. | `JavaScript` `PostgreSQL` `Redis` `Docker` |
| [**SkillForge**](https://github.com/davidyassa/SkillForge) | A Coursera-like learning platform. | `Java` |
| [**Sudoku**](https://github.com/davidyassa/Sudoku) | 9×9 Sudoku game with a GUI, validation, solver, and difficulty-based puzzle generation. | `Java` |

---

## 🤖 AI Automation & n8n

I build AI-assisted workflows with **n8n**, connecting applications, processing data, and turning multi-step tasks into automated processes. My hands-on experience includes the **Digital Egypt Pioneers Initiative (DEPI)** *AI Automation Workflow with n8n Professional* track, where I've worked on AI agents, API integrations, and business workflow automation.

### Practical Experience

- **Workflow design:** form, spreadsheet, webhook, and chat triggers; conditional routing; reusable workflows; automated notifications
- **AI integration:** language models via Gemini, Groq, and OpenRouter; AI agents with application tools and conversational memory
- **Data processing:** input validation, JavaScript transformations, spreadsheet updates, workflow error logging
- **Application integration:** Google Workspace, Microsoft Outlook, Telegram, Wolfram Alpha
- **Local deployment:** n8n on Docker Compose with persistent storage and environment-based configuration
- **Project planning:** defining business problems, mapping workflows, setting MVP scope, planning error handling and testing

### Selected n8n Projects

<details>
<summary><b>🎓 Student AI Assistant</b></summary>
<br>

An n8n AI agent that brings everyday student tasks into one conversational workflow. Its tools cover Google Calendar scheduling, Gmail reading and sending, Google Drive search, Google Sheets reading and updating, and Wolfram Alpha calculations, with conversational memory and Gemini/Groq integrations.

**Tools:** n8n AI Agent, Simple Memory, Google Calendar, Gmail, Google Drive, Google Sheets, Wolfram Alpha, Gemini, Groq

</details>

<details>
<summary><b>📨 Request Processing & Notification Automation</b></summary>
<br>

A workflow that takes form submissions into Google Sheets, validates incoming data, applies LLM analysis, and processes the results with JavaScript. Switch-based routing sends each request to the right branch, with Telegram/Gmail notifications, spreadsheet updates, and error logging.

**Flow:** Form submission → Google Sheets → Validation → AI analysis → JavaScript processing → Conditional routing → Notifications and record updates

**Tools:** n8n, Google Forms/Sheets, OpenRouter, JavaScript, Switch, Telegram, Gmail

</details>

<details>
<summary><b>📬 Outlook AI Agent</b></summary>
<br>

An AI agent connected to Microsoft Outlook, combining email tools and Outlook folders with Gemini/Groq integrations, including workflow-triggered reuse of automation logic.

**Tools:** n8n AI Agent, Microsoft Outlook, Gemini, Groq, workflow triggers

</details>

<details>
<summary><b>🧑‍💼 HR Conversational System</b> &nbsp;<i>(in development)</i></summary>
<br>

An HR system built around n8n chat agents. The design focuses on authenticating users and routing administrators and employees to separate chat experiences, all within n8n. Authentication and role-based routing are the active design work.

**Focus:** chat workflows, authentication flow design, separate administrator/employee agent experiences

</details>

<details>
<summary><b>🛡️ SLA Guard</b> &nbsp;<i>(DEPI graduation project, planning & design)</i></summary>
<br>

A collaborative automation project connecting service incident records, vendor contracts, and compensation assessment across IT, Contracts, and Finance. The proposed workflow receives outage events through a webhook, finds the relevant agreement, assesses contractual entitlement, and prepares claims for human review.

Planning covers workflow mapping, structured inputs and outputs, contract-term extraction, rule-based calculations, error handling, MVP scope, and test scenarios.

**Planned flow:** Outage event → Contract lookup → SLA assessment → Credit calculation → Human approval → Claim draft and case record

**Focus:** n8n orchestration, webhooks, AI-assisted document extraction, business rules, human approval

</details>

---

## 📊 GitHub Stats

<div align="center">

[![GitHub stats](https://github-readme-stats-fast.vercel.app/api/?username=davidyassa&show_icons=true)](https://github.com/pranesh-2005/github-readme-stats-fast) [![GitHub stats](https://github-readme-stats-fast.vercel.app/api/top-langs/?username=davidyassa&show_icons=true)](https://github.com/pranesh-2005/github-readme-stats-fast)
</div>

---

## 🤝 Let's Connect

I'm always happy to talk backend, AI, or student projects. The best way to reach me is on [LinkedIn](https://www.linkedin.com/in/david-mansourr/).

<div align="center">

<sub>Thanks for stopping by ✨</sub>

</div>
