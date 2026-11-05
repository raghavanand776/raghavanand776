### Hi, I'm Raghav 👋

Technical product and engineering leader with nearly two decades across **fintech, cloud security, logistics and retail**, at Dave, Flexport, Oracle Cloud (OCI), Nordstrom and Walgreens. I started as a software engineer and moved into product, so I can go deep on architecture and still keep the customer in the room.

Today I lead **mobile, analytics and UX engineering at Costco Wholesale**, including the backend-for-frontend (BFF) platform: the API layer that sits between Costco's iOS and Android apps and its core services, shaping what millions of members see and do on mobile. My teams own the path from backend services to the app experience, with the reliability, security and release discipline that retail at that scale demands.

These days I build **AI prototypes for messy, regulated workflows**: places where rules handle the exact work and AI handles the leftovers a person would otherwise grind through by hand. Every project is measured against a labeled answer key, and the AI only advises. A person makes the call.

---

### AI prototypes

| Project | What it does | Result |
| --- | --- | --- |
| [**Claim Pre-Check Agent**](https://github.com/raghavanand776/claim-precheck-agent) | Reviews therapy insurance claims *before* submission and flags what would get them denied. Includes a real-time pharmacy (Rx) adjudication API. | Agent: **7/7** on the eval set vs. **1/3** for rules alone on problems hidden in free-text notes. API: sub-millisecond p95 under load. |
| **3-Way Reconciliation Copilot** *(in progress)* | Reconciles cash-advance money across the app ledger, the payment processor and the sponsor bank. Rules match the clean records; an AI investigator explains each break (timing, holidays, ACH returns, fees, batch netting) and recommends wait, book a fee, reverse or escalate. | Based on a problem I owned at Dave. Hard rule in the eval: it must never mark a real problem as "just wait." |
| [**Text Summarizer CLI**](https://github.com/raghavanand776/text-summarizer-cli) | Command-line summarizer on the Claude API, with input guardrails, error handling and a cost estimate checked against actual token usage. | My first direct API project. |

**How I build:** Python · Claude API (tool use, agent loops) · FastAPI · pytest · evals with labeled answer keys · synthetic data only

---

### Background

- **Fintech:** led financial products at Dave, including reconciliation for cash advances
- **Cloud security:** OCI cybersecurity at Oracle; FedRAMP, PCI, IAM/MFA
- **Mobile platforms at scale:** lead Costco's mobile, analytics and UX engineering, including the BFF API platform behind its iOS and Android apps; CI/CD and release engineering

### Connect

[LinkedIn](https://linkedin.com/in/raghavanand) · [raghavanand.us](https://raghavanand.us) · contact@raghavanand.us
