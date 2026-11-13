# Awesome-Customer-Service-Agent-Workspace

# Top Customer Service Agent Workspace Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Unified Agent Inboxes, Omnichannel Ticketing & AI-Assisted Resolution*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Customer Service Agent Workspace**. These tools give support agents a single unified interface to manage conversations across email, chat, social, and voice—consolidating customer history, ticket details, and AI assistance so agents can resolve issues without swivel-chairing between tabs.

**Examples** include Freshworks Freshdesk Omni, Zendesk Agent Workspace, Salesforce Service Console, ServiceNow Agent Workspace, Intercom Inbox, Help Scout, Front, Kustomer, LiveAgent, and open-source alternatives like TGO (the category leaders).

**Open-source emphasis**: This section highlights every major active project for self-hosted agent workspaces, open-source helpdesk platforms, and community-driven customer service tooling—ideal for organizations seeking data sovereignty and predictable costs over per-seat SaaS pricing. Note that purpose-built open-source agent workspaces are genuinely nascent; the practical path is composing helpdesk platforms with AI orchestration layers.

Contributions welcome! Open an PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

| Product | Description | Pricing (Starting) | Free Tier / Trial Limits |
|---------|-------------|-------------------|--------------------------|
| **[Freshworks Freshdesk Omni](https://www.freshworks.com/freshdesk/omni/agent-workspace/)** | Unified agent workspace bringing channels, customer history, ticketing, and teams together. Includes a conversational team inbox, 360-degree customer record with key activities and past interactions, and built-in AI for tone, content, and next steps. Ticket inbox supports assignment to individuals/groups, filtering, and custom fields [citation:1]. | Quote-only (Freshdesk plans start from ~$15/agent/month for Growth) | **14-day free trial**, no credit card required [citation:1] |
| **[Zendesk Agent Workspace](https://support.zendesk.com/hc/en-us/sections/4405303726490)** | Unified interface for managing all channels (Chat, Support, email, social) in a single workspace. Context panel provides customer information; automatic upgrade program available for selected accounts [citation:2]. Customizable layout builder and custom objects enable deeper personalization [citation:13]. | Quote-only (Zendesk Suite plans) | No free tier; trial via sales |
| **[Salesforce Service Console](https://trailhead.salesforce.com/)** | Three-column agent workspace with case details, customer highlights panel, case feed, and customizable utility bar. Consolidates email, phone, web chat, and social channels in one screen. Split view and keyboard shortcuts reduce clicking and scrolling [citation:3][citation:14]. | Quote-only (Service Cloud licensing) | No free tier; trial via Salesforce sales |
| **[ServiceNow Agent Workspace](https://www.servicenow.com/community/)** | Graphical workspace putting multiple tools on one page for tier 1 agents. Supports inline list editing, playbooks with Process Automation Designer, dynamic response templates, and Virtual Agent autopilot integration. NOW Experience Dashboard Builder available inside workspace . | Quote-only (enterprise contract) | No free tier; demo via sales |
| **[Intercom Inbox](https://www.intercom.com/)** | Shared inbox with AI assistant (Copilot) embedded for finding answers, drafting replies, and troubleshooting. Fin AI agent resolves conversations autonomously; Copilot assists human agents. All full-seat teammates get 10 Copilot conversations/month included [citation:8]. | Essential: $29/seat/month (annual); Advanced: $85/seat/month | No permanent free tier; trial available. Copilot unlimited add-on at $35/user/month [citation:8] |
| **[Help Scout](https://www.helpscout.com/pricing/)** | Shared inbox with AI Inbox assistant on Standard plan and unlimited AI Drafts on Plus. Multiple inboxes, live chat, knowledge bases, and basic workflows. Pro adds SSO/SAML, HIPAA compliance, and up to 50 light users [citation:9]. | Standard: $25/user/month (annual); Plus: $45; Pro: $75 | **Free plan**: 5 users, 1 Inbox, 1 Docs site [citation:9] |
| **[Front](https://front.com/)** | Collaborative inbox for teams managing shared email, chat, and messaging. 14-day trial of Professional plan includes 15 teammates, 5 workspaces, 30 channels, and 5,000 message limit [citation:7]. | Starter/Professional/Enterprise (quote-only) | **14-day free trial** of Professional plan (no credit card) [citation:7] |
| **[Kustomer](https://www.kustomer.com/)** | Timeline-based customer service platform. Direct order refunds/cancellations from timeline. Available via Shopify App Store [citation:6]. | From **$89/user/month** (Enterprise) or **$139/user/month** (Ultimate) [citation:6] | Free installation via Shopify; no permanent free tier |
| **[LiveAgent](https://www.liveagent.com/pricing/)** | Helpdesk with universal inbox for tickets, chats, calls, and social. AI assistants run on your own AI provider account (no charge from LiveAgent). Business and Enterprise add department roles, audit logs, and SSO [citation:10]. | Starter: per-agent pricing (up to 5 agents); Team: up to 15; Business: any size; Enterprise: flat fee + 80 agents [citation:10] | Free trial available; no permanent free tier |
| **[Gladly](https://www.gladly.com/)** | Retail-focused customer service platform with unified customer timeline. Enterprise-only pricing starting at **$100K+/year**, excluding SMB and small DTC brands [citation:5]. | **$100K+/year** (enterprise) [citation:5] | No free tier; full demo and enterprise sales required [citation:5] |

## Open-Source GitHub Projects

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[TGO (tgoai/tgo)](https://github.com/tgoai/tgo)** | [![Stars](https://img.shields.io/github/stars/tgoai/tgo?style=social&color=white)](https://github.com/tgoai/tgo/stargazers) | **The most complete open-source AI agent customer service platform with a human agent workspace.** Integrates multi-channel access (Web Widget, WeChat, Telegram, Slack, email), multi-agent LLM orchestration (OpenAI, Anthropic), RAG knowledge base (document, Q&A, website crawling), MCP tool store, and **human-AI collaboration with smart handoff and unified Agent Workspace**. Real-time communication via WebSocket. One-click deployment: `curl -fsSL .../bootstrap.sh | bash`. Python/FastAPI backend with TypeScript CLI/MCP server . |

### Additional Strong Open-Source Options

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[FreeScout](https://github.com/freescout-help-desk/freescout)** | [![Stars](https://img.shields.io/github/stars/freescout-help-desk/freescout?style=social&color=white)](https://github.com/freescout-help-desk/freescout/stargazers) | Open-source helpdesk and shared mailbox (PHP/Laravel). Positioned as a free alternative to Help Scout and Zendesk. Supports multiple mailboxes, collision detection, workflows, and knowledge base. Self-hosted with Docker. |
| **[Zammad](https://github.com/zammad/zammad)** | [![Stars](https://img.shields.io/github/stars/zammad/zammad?style=social&color=white)](https://github.com/zammad/zammad/stargazers) | Open-source helpdesk and customer support system (Ruby on Rails). Multi-channel (email, chat, phone, social), ticket management, and reporting. Self-hosted with Docker. |

**Frameworks for building custom systems**: Combine **TGO** for AI-agent orchestration with human handoff and unified workspace, **FreeScout** or **Zammad** for traditional shared-inbox ticketing, and a self-hosted LLM provider for AI assistance—creating a fully open-source agent workspace without per-seat SaaS fees. Note that TGO is the only project in this list that explicitly ships a human "Agent Workspace" alongside AI agents .

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Agent workspaces handle sensitive customer conversations and PII; enforce role-based access, audit logging, and compliance with applicable data protection regulations.
- **Pricing transparency varies dramatically in this category.** Help Scout publishes transparent per-user rates ($25–$75) with a free plan for 5 users [citation:9]. Intercom publishes seat pricing plus AI resolution costs [citation:8]. Kustomer lists $89–$139/user/month [citation:6]. Front, Zendesk, Freshworks, Salesforce, ServiceNow, and LiveAgent are quote-only. Gladly explicitly targets enterprise with $100K+/year minimums [citation:5]. **Purpose-built open-source agent workspaces are genuinely sparse.** TGO is the most complete option with an explicit human Agent Workspace, but it is early-stage (April 2026 release) and requires self-hosting effort . FreeScout and Zammad provide mature shared-inbox ticketing but lack the AI orchestration layer that commercial platforms now ship natively.

---

**Made for support operations managers, CX leaders, helpdesk administrators, and developers building agent tooling infrastructure.**  
Let's make customer service agent workspaces more open, unified, and AI-assisted.
