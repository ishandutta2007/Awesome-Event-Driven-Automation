# Awesome-Event-Driven-Automation

## Top Event-Driven Automation Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Workflow Orchestration, Event Triggers & Self-Hosted Automation Platforms*  

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Event-Driven Automation**. These tools enable individuals and organizations to connect applications, automate repetitive tasks, and build workflows that react to events—webhooks, schedules, messages, or sensor data—without writing full backend services.



**Examples** include IFTTT, Zapier, Make, Automate.io, Integrately, Pabbly Connect, Albato, Power Automate, Tray.io, and Pipedream (the category leaders).



**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, custom connector development, and transparent automation infrastructure—ideal for teams that prioritize data sovereignty, avoid per-task SaaS fees, and require auditable workflows. The open-source event-driven automation landscape is anchored by **n8n** (the most mature Zapier alternative), **Activepieces** (MIT-licensed and AI-native), **Node-RED** (the IoT and event-wiring standard), and **Huginn** (the original agent-based monitor), with strong developer-focused options in **Windmill** and **Platypush**.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[IFTTT](https://ifttt.com/)**  

  The original consumer automation platform, connecting consumer apps and smart home devices through simple "if this, then that" applets. Free tier allows limited applets; Pro unlocks multi-step applets and faster execution.



- **[Zapier](https://zapier.com/)**  

  The market leader in business automation with 7,000+ app integrations. Task-based pricing scales with usage; complex multi-step Zaps consume more tasks. Best for teams that need maximum integration coverage and minimal setup effort.



- **[Make (Integromat)](https://www.make.com/)**  

  Visual automation platform with a scenario builder supporting branching, iteration, and error handling. Operations-based pricing. More flexible than Zapier for complex logic at comparable or lower cost.



- **[Automate.io](https://automate.io/)**  

  Business automation platform with a focus on marketing, sales, and team workflows. Acquired by Notion and being integrated into their ecosystem; new signups may be limited.



- **[Integrately](https://integrately.com/)**  

  Automation platform offering "1-click automations" with pre-built templates. Pricing is based on tasks, with a free tier for basic workflows.



- **[Pabbly Connect](https://www.pabbly.com/connect/)**  

  Budget-focused automation platform with lifetime pricing options. Offers unlimited workflows and internal tasks on paid plans, making it attractive for cost-sensitive teams.



- **[Albato](https://albato.com/)**  

  No-code automation platform with a focus on ease of use and affordability. Offers white-label options for agencies.



- **[Power Automate (Microsoft)](https://powerautomate.microsoft.com/)**  

  Microsoft's automation platform integrated with Office 365, Dynamics, and Azure. Desktop flows (RPA) extend beyond cloud-only automation. Best for organizations already in the Microsoft ecosystem.



- **[Tray.io](https://tray.io/)**  

  Enterprise automation platform with a visual workflow builder and low-code customization. Positioned for complex, mission-critical automations with governance controls.



- **[Pipedream](https://pipedream.com/)**  

  Developer-first automation platform with code-level control (Node.js, Python, Go). Event sources, workflows, and HTTP endpoints. Best for developers who want to write custom logic alongside integrations.



## Open-Source GitHub Projects



- **[n8n](https://github.com/n8n-io/n8n)**  

  The most mature open-source Zapier alternative. Visual workflow editor with 500+ integrations, AI nodes (LangChain-based), and inline JavaScript/Python for custom logic. Community Edition is free to self-host with unlimited workflows and executions . **Licensing note**: n8n uses a "fair-code" Sustainable Use License, not an OSI-approved open-source license—reselling n8n as a SaaS is prohibited . Self-hosting requires Docker, PostgreSQL, and Redis for production-scale queue mode . Best for teams that want enterprise-grade workflow automation with full data control.



- **[Activepieces](https://github.com/activepieces/activepieces)**  

  MIT-licensed, AI-first automation platform and self-hostable Zapier alternative. Features 400+ integrations ("pieces"), native AI steps, and custom pieces written in TypeScript . No per-task fees when self-hosted. Deploys with PostgreSQL and Redis via Docker Compose or Railway . Best for teams that want true open-source licensing (MIT) with a modern, no-code interface.



- **[Node-RED](https://github.com/node-red/node-red)**  

  The standard for flow-based, event-driven automation, especially in IoT and edge environments. Browser-based visual editor where nodes are wired together to handle MQTT, HTTP, WebSocket, and 3,000+ community nodes . Apache 2.0 licensed. Runs on Raspberry Pi, Docker, and cloud servers. Best for IoT, home automation, and lightweight integration work where hardware and APIs need to talk .



- **[Huginn](https://github.com/huginn/huginn)**  

  The original open-source agent-based automation platform. "Agents" monitor events (web pages, RSS, email, APIs) and trigger actions on your behalf. Lightweight, with a dedicated community. Best for monitoring and alerting scenarios where you want a set-and-forget agent . Single-instance concurrency is modest (~500 events/sec) compared to n8n .



- **[Windmill](https://github.com/windmill-labs/windmill)**  

  Developer platform that turns scripts (Python, TypeScript, Go, Bash, SQL) into workflows, internal apps, and APIs. Open-source alternative to Pipedream and Airplane . Self-hostable via Helm or Docker Compose, with a VS Code extension and Git-based deployment . Best for developer teams that want code-first automation without building infrastructure from scratch.



- **[Platypush](https://github.com/BlackLight/platypush)**  

  Event-driven automation platform with a focus on IoT, home automation, and custom integrations. Exposes custom routines as webhooks, reacts to entity updates (sensors, lights, media players), and supports voice assistant triggers . Best for makers and tinkerers who want a Python-native automation layer across heterogeneous devices.



### Additional Strong Open-Source Options



- **Rundeck** — Open-source runbook automation for IT operations. Define, schedule, and execute command-line jobs with role-based access and audit trails. Best for ops teams automating scripts and maintenance tasks .

- **Apache Airflow** — The standard for data pipeline orchestration with DAGs. Airflow 3.0 adds native event-driven scheduling for SQS and Kafka, making it suitable for event-triggered data workflows . Overkill for simple app-to-app automation but essential for complex data pipelines.

- **Prefect** — Pythonic workflow orchestration with dynamic DAGs and a gentler learning curve than Airflow. Best for data teams that want modern, code-first pipelines .

- **Frameworks for building custom systems**: Combine **n8n** for business workflow automation with **Node-RED** for IoT/device events, and **Windmill** for code-heavy background jobs. Use **Activepieces** when MIT licensing is a hard requirement. For pure monitoring agents, **Huginn** remains a lightweight option.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- "Open-source" labels vary: n8n uses a fair-code license that restricts resale, while Activepieces is MIT-licensed. Verify licensing before commercial deployment .

- Self-hosted automation platforms require proper security configuration (webhook authentication, SSL, secrets management) and infrastructure maintenance.



---



**Made for automation engineers, DevOps teams, makers, and organizations building private, event-driven workflows.**  

Let's make event-driven automation more open, controllable, and accessible.
