<div align="center">

# Iñaki Nicolás Antonena

**Full Stack Engineer | AI Agents & Application Security**

Rawson, Chubut, Argentina 🇦🇷 · UTC-3 · Open to remote work (US, EU, LATAM)

[LinkedIn](https://www.linkedin.com/in/ia-dev/) · [Email](mailto:iadev.antonena@gmail.com)

</div>

## About

I build full stack web applications and LLM-based agents, and I secure them. I have 3+ years in web development, the last two full stack with TypeScript (React, Next.js, Node.js) and Python.

Recent work includes enterprise integrations on Azure Functions and Power Platform, a RAG-based triage agent and booking platform for healthcare clinics, and open-source security tooling for AI coding agents. I'm studying a Bachelor's in Cyberdefense (Secure Coding & Cyber Risk).

## Featured projects

### 🛡️ [agentsapper](https://github.com/inakidev/agentsapper) · open-source security CLI

![npm](https://img.shields.io/npm/v/agentsapper?style=flat-square) ![license](https://img.shields.io/badge/license-MIT-blue?style=flat-square)

Scans an untrusted repository for what it can execute or inject **before** an AI coding agent (Claude Code, Cursor) opens it.

- 22 deterministic rules across git, filesystem, agent config, instruction files, IDE and package scripts. No LLM, zero runtime dependencies.
- Output in text, JSON or SARIF, so it plugs into CI and GitHub code scanning.
- Tested with 39 malicious fixtures from published attacks, 5,000 generated git configs compared against git's own parser, and 16 popular repositories as a false-positive check.

```sh
npx agentsapper ./downloaded-repo
```

### 🔍 [Sentry-VulnScan](https://github.com/inakidev/sentry-vulnscan) · passive web vulnerability scanner

A full stack app (FastAPI + React 19) that checks a site's server configuration, SSL/TLS certificate and security headers (CSP, HSTS, X-Frame-Options) without intrusive payloads, and returns a risk score. The backend includes SSRF protection and Cloudflare Turnstile verification.

## How I work

- **Security by design.** I review code against the OWASP Top 10 from the start, not at the end.
- **AI-assisted, human-reviewed.** I use LLM tooling (Claude Code) to move faster, and I keep the specs, architecture decisions and review in my hands.
- **Team-ready standards.** Git Flow, semantic commits and written technical documentation, including guides for non-technical users.

## Stack

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB) ![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white) ![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)

![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square) ![Microsoft Azure](https://img.shields.io/badge/Azure_Functions-0078D4?style=flat-square) ![Power Platform](https://img.shields.io/badge/Power_Platform-742774?style=flat-square) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white) ![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white) ![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black)

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white) ![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

## Currently

- Building security tooling for AI coding agents and agentic workflows.
- Open to **remote full-time roles** and **freelance projects**: AI agents and automation, web platforms, and security reviews.

## Let's connect

I'm happy to talk about secure architecture, AI integration or new opportunities.

- 📧 [iadev.antonena@gmail.com](mailto:iadev.antonena@gmail.com)
- 💼 [LinkedIn: Iñaki Nicolás Antonena](https://www.linkedin.com/in/ia-dev/)
