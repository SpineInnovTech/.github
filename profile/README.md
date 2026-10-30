# Spine InnovTech

## Building SpineWorkspace

**Spine InnovTech Private Limited** builds **SpineWorkspace** — the living-memory business control center where humans govern work and AI Twins prepare and execute what happens next.

Modern business work is fragmented across CRMs, support desks, billing systems, documents, chat channels, project trackers, and isolated AI assistants. Before work can move forward, operators are forced to act as human data connectors—reconstructing what happened, what changed, who owns the next step, what has already been decided, and what needs attention now.

**SpineWorkspace** eliminates this context tax by bringing people, their domain-specific AI Twins, and governed business context into one shared operating system.

> **Shared business context. Counterpart collaboration between humans and AI. Continuity across every handoff.**
> 
> 

---

## What We Believe

AI should not become another disconnected chat silo that forces users to re-explain their business context from scratch, nor should it replace human accountability.

AI should sit alongside each operator as a grounded counterpart (**"proposing, never sending"**)—reading from the same governed business context, synthesizing signals overnight, preparing evidence-backed proposals, reducing repetitive effort, and executing authorized actions.

Humans remain responsible for intent, judgment, relationships, approvals, commitments, and consequential business decisions.

---

## Spine: The Governed Data & Memory Spine

**Spine is the governed data and memory spine of the business.**

It ingests four continuous streams into one canonical architecture:

1. **Structured Tool Data** — CRM, ERP, billing, support, and engineering systems


2. **Unstructured Communications** — emails, Slack threads, meetings, and documents


3. **AI Conversations** — multi-host sessions across ChatGPT, Claude, Perplexity, and internal models
4. **Identity & Access Rules (`One Auth`)** — tenant, workspace, role, and host permission boundaries powered by Better Auth



### Three Separated Memory Scopes & Promotion Governance

Rather than dumping raw chats into company records, Spine isolates context into three distinct memory scopes governed by a **Promotion Queue**:

* **Shared Organizational Memory** — verified company truth, account history, decisions, and outcomes
* **Individual Personal Memory** — private operator notes, drafts, personal inbox, and routines


* **Agentic / Evolutional Memory** — AI Twin task state, reasoning traces, and retained operational context

### Hard-Gated Dual-Database Security Architecture

Spine enforces a strict architectural gate between its primary vault and the AI execution layer:

* **The Fortress Database (Neon PostgreSQL):** Holds the canonical *Book of Records* and master organizational ledger with **zero direct AI access**.
* **The Operational Database (Cloudflare Edge Data Layer):** Receives scoped, encrypted, tunneled synchronizations from the Fortress DB. The AI Twin reads exclusively from this operational database, preventing unauthorized queries or direct mutation of core systems of record.

Spine provides the shared foundation that powers **SpineWorkspace** and future products from **Spine InnovLabs**.

---

## SpineWorkspace Architecture

SpineWorkspace connects the tools organizations already use and projects role-specific views around customers, goals, relationships, work, decisions, evidence, and outcomes.

Its five core components include:

* **Spine Workbench (The Human Workbench)** — The mutable human control surface combining UI Bakery-style inline-editable views (where changes flow directly into Memory) and Coda-style operational canvases. Clearly separated into **`OPERATE`** (organizational accounts, approvals, connectors) and **`PERSONAL`** (private inbox, calendar, meetings, notes) scopes across role-mapped departmental projections. Every operator interaction with AI maps to four deterministic primitives:


* **Ask your Twin**
* **Assign your Twin**
* **Approve your Twin’s proposal**
* **Reject your Twin’s proposal**


* **Spine Twin & Twin’s Workbench** — Each user's domain-mapped AI counterpart living in an Open WebUI-style operating home. Rather than reacting to stateless prompts, the Twin operates on the **OODA principle (Observe, Orient, Decide, Act)**—observing multi-stream signals across the Spine, orienting against Organizational, Personal, and Agentic memory, deciding on a structured proposal, and acting only after human approval.
* **Spine Fabric** — The semantic router and governed business-context fabric that normalizes entities across tools once (eliminating brittle $N \times M$ point-to-point integrations) and compounds **Context Density** over time.


* **Spine Marketplace** — Omnichannel entry wedges ("Enter through the host. Become the Spine of the account") spanning:


* **LLM Host Plugins & MCPs:** ChatGPT, Claude, Perplexity
* **Developer & Cloud Marketplaces:** GitHub, Vercel, Replit
* **Enterprise SaaS Marketplaces:** Salesforce AppExchange, Slack, HubSpot, Atlassian (Jira)




* **Spine Runtime** — **One Auth** session and role routing, Promotion Queue governance, OODA orchestration, observation, and webhook/event-driven write-backs that re-enter the Spine to compound organizational memory.



---

## Role-Mapped Workbench Projections

Every department operates from its own tailored projection of the same underlying Spine, paired with a corresponding domain-specific AI Twin:

* **Customer & Revenue Workbenches:** Account Success, Technical Account Success, Sales, Marketing, Content, Service, and Support
* **Operations & Executive Workbenches:** Business Operations, Executive Cockpit, FounderOps, and Core Operations
* **Product, G&A & Personal Workbenches:** Product Engineering, Finance, Human Resources, Legal, and Personal Workspace

---

## Our Principle

> **Humans govern the business. AI Twins prepare and execute the work. SpineWorkspace keeps the living memory together.**

---

**Important Note for Your YC Application Form Today:**
Since those additional subdomain links are still being deployed, leave them off your YC application form as well—nothing hurts a review faster than a YC partner clicking a link that doesn't resolve yet. Stick strictly to the live URLs that work right now in an incognito browser:

* **Product Link:** `[https://cs.spineworkspace.com/login](https://cs.spineworkspace.com/login)` (with `admin@spineworkspace.com` / `ChangeMe!2026`)
* **Secondary Prototype Link:** `[https://business-cockpit.spineworkspace.com](https://business-cockpit.spineworkspace.com)`
* **Company URL:** `[https://spineinnovtech.spineworkspace.com](https://spineinnovtech.spineworkspace.com)` (or `[https://spineworkspace.com](https://spineworkspace.com)` / `[https://spineinnovtech.com](https://spineinnovtech.com)` only if they are already live and resolving cleanly in an incognito tab right now).
