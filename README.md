# 🤖 n8n AI Agent Portfolio

<div align="center">

![Agents](https://img.shields.io/badge/Agents-20-22d3ee?style=for-the-badge&logo=robot&logoColor=white)
![Industries](https://img.shields.io/badge/Industries-11-a78bfa?style=for-the-badge)
![Built with n8n](https://img.shields.io/badge/Built%20with-n8n-EA4B71?style=for-the-badge&logo=n8n&logoColor=white)
![Powered by GPT](https://img.shields.io/badge/Powered%20by-GPT--4o-10b981?style=for-the-badge&logo=openai&logoColor=white)
![GitHub Pages](https://img.shields.io/badge/Deployed%20on-GitHub%20Pages-181717?style=for-the-badge&logo=github&logoColor=white)

**A collection of 20 production-grade AI automation agents — each solving a real industry problem with measurable impact.**

[🚀 Live Portfolio](https://data-geek-astronomy.github.io/n8n-ai-agent-portfolio/) · [GitHub Profile](https://github.com/data-geek-astronomy)

</div>

---

## ✨ What's Inside

Each agent card shows:
- **Problem Statement** in Google XYZ format *(Accomplished X, as measured by Y, by doing Z)*
- **Live Architecture Diagram** auto-rendered from the actual n8n workflow graph
- **Tech stack**, trigger type, and active/inactive status

Click any card to expand the full architecture flow.

---

## 🗂️ Agent Categories

| Category | Agents | Key Integrations |
|---|---|---|
| 🏥 Healthcare | Patient Discharge, Prior Auth, Clinical Trials, Medical Report Analyzer, Medication Safety | EHR, Gemini AI, GPT-4o-mini |
| 🚛 Transportation | Fleet Maintenance, Route Optimization, Freight Exceptions | Telematics API, Google Maps |
| 🏗️ Construction | OSHA Safety, Invoice Reconciliation, Material Procurement | ERP, GPT-4o-mini, Slack |
| 💰 Finance | Loan Pre-Screening, TariffIQ | DTI Calc, Federal Register, CBP |
| 💼 HR & Ops | Employee Offboarding, Job Placement Tracker | Google Workspace, LinkedIn, Slack |
| 🤖 AI & ML | Snorkel RAG Eval Pipeline, RAG Query + Ingestion | Supabase Vector, GPT-4o, Embeddings |
| 📱 Customer Success | Churn Risk Savior, Multi-Lingual Support Hub | Sentiment AI, Translation, Slack |
| ✍️ Marketing | Content Repurposing Pipeline | Buffer, Gmail, Twitter, LinkedIn |
| 🌱 AgriTech | Smart Farm Crisis Response | IoT Sensors, OpenWeatherMap, Twilio |
| 📦 E-Commerce | Inventory Crisis Agent | Shopify, Slack, Suppliers |
| 🧠 Productivity | AI Meeting Intelligence | Zoom, Asana, Gmail |

---

## 🔬 Featured Agents

### 🧠 Snorkel RAG Evaluation Pipeline
> *Automated RAG quality gating — synthetic adversarial question generation → programmatic scoring → 90% pass-rate gate → expert human-in-the-loop calibration*

### 🌱 Smart Farm Crisis Response Agent
> *Real-time crop protection — polls OpenWeatherMap + IoT soil sensors every 15 min, detects drought/frost/flooding, triggers irrigation, WhatsApp-alerts farmer, emails buyers*

### 🏥 Patient Discharge & Care Continuity Agent
> *Reduces 30-day readmissions — AI-scores every EHR discharge event for readmission risk and routes to urgent physician alerts, patient follow-ups, or routine care logging*

### 🔐 Employee Offboarding Security Agent
> *Zero-touch access revocation — auto-revokes Google Workspace, Slack, and GitHub in parallel, transfers Drive files, generates AI audit report for IT & Legal in under 5 minutes*

---

## 🛠️ Tech Stack

```
Orchestration  →  n8n (self-hosted / cloud)
AI / LLM       →  OpenAI GPT-4o, GPT-4o-mini · Google Gemini
Vector Store   →  Supabase (pgvector)
Embeddings     →  OpenAI text-embedding-3-small
Messaging      →  Twilio (WhatsApp/SMS) · Slack · Gmail
Data Sources   →  Shopify · Zoom · LinkedIn · EHR · Telematics
Frontend       →  Vanilla HTML/CSS/JS · SVG flow renderer
Hosting        →  GitHub Pages
```

---

## 🚀 Deploy Your Own Copy

This is a single-file static site — no build step, no dependencies.

**1. Fork this repo**

**2. Enable GitHub Pages**
```
Settings → Pages → Source: Deploy from branch → main / (root) → Save
```

**3. Your site is live at:**
```
https://<your-username>.github.io/n8n-ai-agent-portfolio/
```

To customize the agents, edit the `agents` array in `index.html` — each entry takes a name, description, Google XYZ statement, and a node/edge graph definition that auto-renders as an SVG flow diagram.

---

## 📁 Structure

```
n8n-ai-agent-portfolio/
├── index.html      # Complete portfolio — all CSS, JS, and agent data in one file
└── .nojekyll       # Tells GitHub Pages to skip Jekyll processing
```

---

## 🤝 Connect

Built and maintained by [@data-geek-astronomy](https://github.com/data-geek-astronomy)

If you find this useful, drop a ⭐ on the repo!
