# Awesome-Generative-AI-For-CRM

## Top Generative AI for CRM Tools Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on AI Copilots, Autonomous Sales Agents & Natural Language CRM Interfaces*  

**Last updated: March 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Generative AI for CRM**. These tools embed large language models directly into customer relationship management workflows — enabling natural language queries, autonomous lead research, email drafting, call coaching, and agentic automation without leaving the CRM interface.



**Examples** include Salesforce Einstein GPT, Microsoft Dynamics 365 Copilot, HubSpot AI, Zoho Zia, Freshworks Freddy AI, SugarCRM Sugarcube, Creatio Copilot, Pegasystems GenAI, Oracle Fusion Sales AI, and SAP CX AI (the category leaders).



**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, custom LLM integration, and transparent AI agent workflows — ideal for teams prioritizing data sovereignty, developers building AI-native CRM platforms, and organizations avoiding per-seat AI taxes.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Salesforce Einstein GPT](https://www.salesforce.com/)**  

  Generative AI layer across Salesforce products with natural language prompts for CRM data, email generation, and Agentforce autonomous agents.



- **[Microsoft Dynamics 365 Copilot](https://www.microsoft.com/en-us/dynamics-365)**  

  AI assistant embedded across Dynamics 365 with natural language interaction for sales, service, and customer insights.



- **[HubSpot AI](https://www.hubspot.com/)**  

  AI-powered content generation, predictive lead scoring, and chatbot capabilities integrated across HubSpot CRM.



- **[Zoho Zia](https://www.zoho.com/)**  

  AI assistant within Zoho CRM providing predictive lead scoring, best time to contact, sentiment analysis, and voice assistant.



- **[Freshworks Freddy AI](https://www.freshworks.com/)**  

  AI engine across Freshworks products with ticket summarization, response suggestions, and predictive deal insights.



- **[SugarCRM Sugarcube](https://www.sugarcrm.com/)**  

  AI-powered predictive analytics and intelligent CRM capabilities within SugarCRM platform.



- **[Creatio Copilot](https://www.creatio.com/)**  

  Generative AI assistant for CRM and workflow automation with natural language interface.



- **[Pegasystems GenAI](https://www.pega.com/)**  

  Enterprise AI capabilities within Pega Platform for customer decisioning and workflow automation.



- **[Oracle Fusion Sales AI](https://www.oracle.com/)**  

  AI-powered sales intelligence and automation within Oracle Fusion Cloud CX.



- **[SAP CX AI](https://www.sap.com/)**  

  AI capabilities across SAP Customer Experience solutions for sales, service, and commerce.



## Open-Source GitHub Projects



- **[zeropipeline-mcp](https://github.com/ainative/zeropipeline-mcp)**  

  AI-native CRM that runs as an MCP server, giving Claude, Codex, Cursor, and any AI agent full access to sales pipelines, deals, customers, and activities. **Zero config required** — auto-provisions a free CRM account on first launch. Features 30+ CRM tools including pipeline management, deal scoring, contact management, activity tracking, task management, and outreach campaigns. Free, open-source alternative to HubSpot, Salesforce, and Pipedrive with native AI agent interface .



- **[BasaltCRM](https://github.com/BasaltHQ/crm-official)**  

  Premium open-source CRM built on Next.js 16 with AI-first architecture. Features **LeadGen Wizard** for autonomous AI web crawling to discover and qualify leads, AI Insights Widget for real-time revenue risk and data integrity checks, integrated dialer with voice AI agent via AWS Chime, multi-model support (OpenAI, Anthropic, Azure, Google, Mistral, DeepSeek), and full GTM pipeline from campaigns through invoices. MIT licensed .



- **[Cordys CRM](https://github.com/1Panel-dev/cordys-crm)**  

  Open-source AI CRM system from Fit2Cloud with **server-side AI agent CORDYS AI** (v1.9.0). Runs as an embedded assistant within the CRM, translating natural language instructions into structured operations on leads, customers, and opportunities. Operates within the same trust domain as CRM data model and RBAC permissions. Features transparent thinking process, security-graded execution (read/write/delete), and real-time data grounding with source citations. Over 300,000 downloads since open-sourcing in November 2025 .



- **[Anti-CRM](https://github.com/anti-crm/anti-crm)**  

  Local-first, encrypted CRM exposed through CLI, MCP server, and read-only API. Stores people, organizations, activities, pipelines, and stages with SQLCipher encryption at rest. Features Gmail sync, Google Calendar ingest, BDR draft generation with approval gating, and plugin architecture for enrichment APIs. Designed for privacy-conscious teams that want sales data never leaving their infrastructure. MCP safe allowlist for agent-driven creates, updates, and activity logging .



- **[Project Wingman (ClientLens)](https://github.com/avinashgaurav/project-wingman-ClientLens)**  

  Open-source AI sales copilot for browser sidebar with live call coaching during Google Meet. Features pre-call pitch generation grounded in your knowledge base, five real-time agents (sentiment, agenda pacing, next-best-sentence coach, objection handling, fact-checking validator), and post-call structured summaries pushed to Zoho CRM. Self-hosted on your own LLM keys — no vendor server. Python 3.11+ required, Node 20+ for extension .



- **[SDRbot](https://github.com/NForce-ai/SDRbot)**  

  Open-source, terminal-native RevOps agent for CRM tasks, prospect research, and sales workflows. Uses your own API keys with full local operation. Features tool scope controls (Standard/Extended/Privileged), auto-approve mode, shell allow-list for read-only commands, IMAP/SMTP email integration, and non-interactive mode for CI/CD automation. Supports MCP servers and custom skills .



- **[OpenCloser](https://github.com/issacops/opencloser-v2)**  

  Open-source AI SDR and sales platform running locally on desktop. Features AI Sales Strategist for ICP generation, AI Lead Researcher with Kanban pipeline, AI Caller with Twilio phone lines and real-time voice agent, AI Sales Coach for objection sparring, and AI Sales Manager for post-call debriefs. Built with Tauri, React, Rust, and Gemini. **Demo mode works without API keys**. MIT licensed .



- **[Krayin CRM](https://github.com/krayin/laravel-crm)**  

  Open-source CRM framework for SMEs built on Laravel, Vue.js, and Tailwind CSS. Features lead pipeline with kanban visualization, activities tracking, contacts management, products and quotes, and ACL-based access control. Provides **Agent Skills** (`krayin/agent-skills`) for Claude Code and Cursor, plus AI context files (`llms.txt`) for Copilot, ChatGPT, and custom RAG integrations .



- **[Comp AI CRM](https://github.com/comp-ai/crm)**  

  Open-source CRM released under MIT license, built for teams under 10 people. Manages contacts, companies, deals, tasks, and sales pipelines with Gmail and Google Calendar sync. Features Perplexity web research, RapidAPI LinkedIn enrichment, and investigation agents. Single-tenant architecture with self-hosting via Bun, Docker, and PostgreSQL. Built on Google and Vercel infrastructure .



- **[gavvy-salesmaster](https://github.com/gavvy-ai/gavvy-salesmaster)**  

  Open-source sales engine combining CRM with AI virtual sales team and automated pipeline. **Core CRM, payment, channels, RBAC, quotes, e-sign, workflow, SaaS, knowledge, and analytics modules are MIT-licensed and fully open**. Enterprise edition adds AI sales team (SalesOrchestrator + 7 Agents + LeadScorer + SafetyGuard) and learning memory. Install via `pip install gavvy-salesmaster` — no database or API key needed to start .



### Additional Strong Open-Source Options



- **[CiviCRM AI Integration](https://civicrm.org/)** — Self-hosted AI for CiviCRM via Drupal AI module, CiviCRM Entity, and Search API. Enables chatbots, semantic search, agentic workflows, translation, and narrative report generation using open-source LLMs (Llama, Mistral) with RAG. Data never leaves your infrastructure .

- **[Apache Camel MCP for CRM](https://camel.apache.org/)** — Connect local AI to business systems via MCP server. Define CRM tools as Camel routes with `ai-tool` component — each route implements one purposeful business capability (find customers, read history, create notes). MCP annotations provide `readOnlyHint` and `idempotentHint` metadata for AI clients .

- **LLM Integration Libraries** — LangChain, LlamaIndex for building custom CRM AI pipelines.

- **Vector Databases** — Qdrant, Weaviate, Milvus for semantic search across CRM data.

- **Local LLM Runtimes** — Ollama, LM Studio for fully offline AI CRM capabilities.



**Frameworks for building custom systems**: Combine **Cordys CRM** for server-side AI agent with RBAC, **zeropipeline-mcp** for AI agent CRM access via MCP, **BasaltCRM** for AI-native revenue operations, **Project Wingman** for live call coaching, and **Anti-CRM** for local-first encrypted CRM to build a complete self-hosted generative AI CRM stack.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Generative AI for CRM must comply with data protection regulations (GDPR, CCPA, HIPAA), AI transparency requirements, and ethical AI guidelines for automated decisioning.

- Self-hosted open-source solutions require proper security hardening, LLM output validation, and prompt injection defenses.



---



**Made for revenue operations teams, sales leaders, CRM administrators, and developers building AI-native CRM platforms.**  

Let's make generative AI for CRM more open, explainable, and data-sovereign.
