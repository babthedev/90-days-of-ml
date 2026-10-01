# Forward Deployed Engineer: Interactive Master Timeline & Checklist 🗓️

> [!TIP]
> This roadmap runs alongside the ML plan (Oct–Dec 2026). Mon–Sat: 45 min/day. Sun: +15 min review.
> Every day is clickable and links directly into its note in `timeline/`.

---

## 🏆 Deliverables & Milestone Gates

| Deliverable | Proves | Ships |
| :--- | :--- | :--- |
| **E1** | A real client engagement: discovery → SOW → AI workflow wired into tools → go-live → handover, with ROI measured | Nov 30 |
| **E2** | Enterprise reference deployment: permission-aware RAG over Google Drive with SSO, audit logs, private-VPC infrastructure and security pack | Dec 19 |
| **Kit** | Field kit: discovery question bank, SOW template, status-update template, security questionnaire answers, runbook, demo script | Ongoing |

### 🎯 Key Gates
- [ ] **Gate A (Oct 31):** SOW signed, v0 demoed (Day 31)
- [ ] **Gate B (Nov 30):** E1 live, client using it (Day 61)
- [ ] **Gate C (Dec 31):** E2 shipped, 10 FDE applications sent (Day 92)

---

## 📅 Phase A — October: Consulting Craft + Integrations (Days 1–31)

**Monthly Goal:** Land a real client, scope their problem in writing, and connect to tools businesses actually run on.

- [ ] **[[Day 01 - Know the role|Day 01 (Thu Oct 1)]]**: **Know the role**
  - **Do (45 min):** Read the Exponent and MarkTechPost pieces + 5 live FDE job posts. List every recurring requirement.
  - **Done when:** Requirements vs your skills matrix

- [ ] **[[Day 02 - Find the client|Day 02 (Fri Oct 2)]]**: **Find the client**
  - **Do (45 min):** List 5 candidates from your UK automation clients and Oryzon beta partners. Offer 3 of them a scoped AI pilot.
  - **Done when:** 3 messages sent

- [ ] **[[Day 03 - Discovery|Day 03 (Sat Oct 3)]]**: **Discovery**
  - **Do (45 min):** The Mom Test ch 1–3. Build a 20-question discovery bank for your field kit.
  - **Done when:** 20-question discovery bank (field kit)

- [ ] **[[Day 04 - Review +15|Day 04 (Sun Oct 4)]]**: **Review +15**
  - **Do (45 min):** Update the matrix and follow up on replies from potential clients.
  - **Done when:** Client follow-ups sent & matrix updated

- [ ] **[[Day 05 - Call prep|Day 05 (Mon Oct 5)]]**: **Call prep**
  - **Do (45 min):** Discovery agenda + stakeholder map (who decides, who uses, who blocks).
  - **Done when:** Templates in field kit

- [ ] **[[Day 06 - API design|Day 06 (Tue Oct 6)]]**: **API design**
  - **Do (45 min):** Stripe API reference: idempotency, pagination, errors, rate limits.
  - **Done when:** 10-point API integration checklist

- [ ] **[[Day 07 - Webhooks|Day 07 (Wed Oct 7)]]**: **Webhooks**
  - **Do (45 min):** Build a webhook receiver that verifies signatures (Stripe or GitHub).
  - **Done when:** Forged request rejected

- [ ] **[[Day 08 - OAuth theory|Day 08 (Thu Oct 8)]]**: **OAuth theory**
  - **Do (45 min):** OAuth 2.0 Simplified: authorization code + PKCE, refresh tokens, scopes.
  - **Done when:** Flow diagram drawn

- [ ] **[[Day 09 - OAuth practice|Day 09 (Fri Oct 9)]]**: **OAuth practice**
  - **Do (45 min):** 'Sign in with Google' in a small app, with token refresh.
  - **Done when:** Login + refresh work

- [ ] **[[Day 10 - E1- discovery call|Day 10 (Sat Oct 10)]]**: **E1: discovery call**
  - **Do (45 min):** Run the call. Listen 80% of the time; ask about the last time the problem happened.
  - **Done when:** Call notes documented

- [ ] **[[Day 11 - Review +15|Day 11 (Sun Oct 11)]]**: **Review +15**
  - **Do (45 min):** Pull 3 quotes of pain from the call notes.
  - **Done when:** 3 quotes extracted into FIELD-KIT.md

- [ ] **[[Day 12 - Decompose|Day 12 (Mon Oct 12)]]**: **Decompose**
  - **Do (45 min):** Current state vs desired state, process map, where the hours go.
  - **Done when:** 1-page problem statement

- [ ] **[[Day 13 - Scope|Day 13 (Tue Oct 13)]]**: **Scope**
  - **Do (45 min):** Design Docs at Google. Must/should/won't, assumptions, risks.
  - **Done when:** Scope draft written

- [ ] **[[Day 14 - SOW|Day 14 (Wed Oct 14)]]**: **SOW**
  - **Do (45 min):** Deliverables, milestones, acceptance criteria, change requests, price or pilot terms.
  - **Done when:** SOW template in field kit

- [ ] **[[Day 15 - CRM integration|Day 15 (Thu Oct 15)]]**: **CRM integration**
  - **Do (45 min):** HubSpot free developer account: read/write contacts, subscribe to webhooks.
  - **Done when:** Sync script works

- [ ] **[[Day 16 - Chat integration|Day 16 (Fri Oct 16)]]**: **Chat integration**
  - **Do (45 min):** Slack bot: posts messages + one slash command.
  - **Done when:** Bot live in a test workspace

- [ ] **[[Day 17 - E1- SOW|Day 17 (Sat Oct 17)]]**: **E1: SOW**
  - **Do (45 min):** Send the SOW and walk the client through it on a call.
  - **Done when:** SOW sent (if no client yet, trigger the fallback)

- [ ] **[[Day 18 - Review +15|Day 18 (Sun Oct 18)]]**: **Review +15**
  - **Do (45 min):** Note every question the client asked about the SOW.
  - **Done when:** Client questions logged

- [ ] **[[Day 19 - Google Workspace|Day 19 (Mon Oct 19)]]**: **Google Workspace**
  - **Do (45 min):** Drive + Sheets APIs. Service account vs OAuth, and choosing minimal scopes.
  - **Done when:** Reads files from a shared Drive

- [ ] **[[Day 20 - Microsoft 365|Day 20 (Tue Oct 20)]]**: **Microsoft 365**
  - **Do (45 min):** Graph Explorer: users, groups, SharePoint files. Enterprises mostly run on M365.
  - **Done when:** 3 working Graph queries

- [ ] **[[Day 21 - Data sync|Day 21 (Wed Oct 21)]]**: **Data sync**
  - **Do (45 min):** Incremental CRM -> Postgres sync with idempotent upserts.
  - **Done when:** Re-running creates no duplicates

- [ ] **[[Day 22 - Resilience|Day 22 (Thu Oct 22)]]**: **Resilience**
  - **Do (45 min):** Retries with backoff, a dead-letter queue, rate-limit handling.
  - **Done when:** A simulated API outage recovers

- [ ] **[[Day 23 - Status updates|Day 23 (Fri Oct 23)]]**: **Status updates**
  - **Do (45 min):** Bottom line up front: done, next, blocked, decisions needed.
  - **Done when:** First weekly update sent to the client

- [ ] **[[Day 24 - E1- kickoff|Day 24 (Sat Oct 24)]]**: **E1: kickoff**
  - **Do (45 min):** SOW signed or pilot agreed. Get access to their systems (least privilege).
  - **Done when:** Signed & access granted

- [ ] **[[Day 25 - Review +15|Day 25 (Sun Oct 25)]]**: **Review +15**
  - **Do (45 min):** Build a risk log for E1.
  - **Done when:** Risk log initialized in LEARNING.md

- [ ] **[[Day 26 - Explain simply|Day 26 (Mon Oct 26)]]**: **Explain simply**
  - **Do (45 min):** Explain LLMs and RAG to a non-technical exec in 2 minutes. Record it.
  - **Done when:** Recording you'd send to a client

- [ ] **[[Day 27 - E1- architecture|Day 27 (Tue Oct 27)]]**: **E1: architecture**
  - **Do (45 min):** Components, data flow, integrations, failure points.
  - **Done when:** Diagram shared with the client

- [ ] **[[Day 28 - E1- setup|Day 28 (Wed Oct 28)]]**: **E1: setup**
  - **Do (45 min):** Repo, environments, secrets, access to client systems.
  - **Done when:** Dev environment runs

- [ ] **[[Day 29 - E1- integrations|Day 29 (Thu Oct 29)]]**: **E1: integrations**
  - **Do (45 min):** Connect their CRM, inbox or sheets.
  - **Done when:** Real data flows

- [ ] **[[Day 30 - E1- AI step|Day 30 (Fri Oct 30)]]**: **E1: AI step**
  - **Do (45 min):** LLM classification, extraction or drafting with structured output.
  - **Done when:** Works on 20 real examples

- [ ] **[[Day 31 - E1- v0 demo|Day 31 (Sat Oct 31)]]**: **E1: v0 demo**
  - **Do (45 min):** Demo to the client and capture their feedback.
  - **Done when:** Gate A: SOW signed, v0 demoed


---

## 📅 Phase B — November: Cloud Architecture, Identity, Enterprise Constraints (Days 32–61)

**Monthly Goal:** Take E1 to production and learn what an enterprise security team will ask before letting you in.

- [ ] **[[Day 32 - Review +15|Day 32 (Sun Nov 1)]]**: **Review +15**
  - **Do (45 min):** Gate A check. Update the E1 risk log.
  - **Done when:** Gate A verified & risk log updated

- [ ] **[[Day 33 - Well-Architected|Day 33 (Mon Nov 2)]]**: **Well-Architected**
  - **Do (45 min):** The 6 pillars. Score E1 against each one.
  - **Done when:** Scorecard completed

- [ ] **[[Day 34 - Networking|Day 34 (Tue Nov 3)]]**: **Networking**
  - **Do (45 min):** VPC, public and private subnets, NAT, security groups.
  - **Done when:** 2-tier VPC diagram

- [ ] **[[Day 35 - Terraform|Day 35 (Wed Nov 4)]]**: **Terraform**
  - **Do (45 min):** Build that VPC with Terraform (HashiCorp AWS tutorial).
  - **Done when:** apply + destroy both clean

- [ ] **[[Day 36 - IAM|Day 36 (Thu Nov 5)]]**: **IAM**
  - **Do (45 min):** Roles, policies, cross-account access: how you'd get into a customer's AWS.
  - **Done when:** Assumed a role across 2 accounts

- [ ] **[[Day 37 - E1- deploy|Day 37 (Fri Nov 6)]]**: **E1: deploy**
  - **Do (45 min):** Deploy to AWS with secrets in Secrets Manager.
  - **Done when:** Runs in the cloud

- [ ] **[[Day 38 - E1- v1 demo|Day 38 (Sat Nov 7)]]**: **E1: v1 demo**
  - **Do (45 min):** Client check-in and v1 demo.
  - **Done when:** Feedback logged

- [ ] **[[Day 39 - Review +15|Day 39 (Sun Nov 8)]]**: **Review +15**
  - **Do (45 min):** Send the weekly status update to the client.
  - **Done when:** Status update sent

- [ ] **[[Day 40 - Identity theory|Day 40 (Mon Nov 9)]]**: **Identity theory**
  - **Do (45 min):** OIDC vs SAML, and group claims (Okta developer docs).
  - **Done when:** One-page comparison

- [ ] **[[Day 41 - SSO|Day 41 (Tue Nov 10)]]**: **SSO**
  - **Do (45 min):** Add OIDC SSO (Okta or Auth0 free tenant) to E1's admin UI.
  - **Done when:** Login through the identity provider

- [ ] **[[Day 42 - Multi-tenancy|Day 42 (Wed Nov 11)]]**: **Multi-tenancy**
  - **Do (45 min):** RBAC + Postgres row-level security for tenant isolation.
  - **Done when:** Tenant A can't read tenant B's rows (tested)

- [ ] **[[Day 43 - Audit logs|Day 43 (Thu Nov 12)]]**: **Audit logs**
  - **Do (45 min):** Who did what, when; retention policy.
  - **Done when:** Audit query answers 'who touched record X'

- [ ] **[[Day 44 - E1- operate|Day 44 (Fri Nov 13)]]**: **E1: operate**
  - **Do (45 min):** Error handling, CloudWatch alarms, on-call notes.
  - **Done when:** Alarm fires on a forced error

- [ ] **[[Day 45 - E1- UAT|Day 45 (Sat Nov 14)]]**: **E1: UAT**
  - **Do (45 min):** User acceptance test with the client against the SOW criteria.
  - **Done when:** Issue list documented

- [ ] **[[Day 46 - Review +15|Day 46 (Sun Nov 15)]]**: **Review +15**
  - **Do (45 min):** Send the weekly status update to the client.
  - **Done when:** Status update sent

- [ ] **[[Day 47 - Security questionnaires|Day 47 (Mon Nov 16)]]**: **Security questionnaires**
  - **Do (45 min):** Answer 30 CAIQ-style questions for E1.
  - **Done when:** Answers in field kit

- [ ] **[[Day 48 - Threat model|Day 48 (Tue Nov 17)]]**: **Threat model**
  - **Do (45 min):** Data-flow diagram + STRIDE threat model for E1.
  - **Done when:** Top 5 threats and their mitigations

- [ ] **[[Day 49 - Data protection|Day 49 (Wed Nov 18)]]**: **Data protection**
  - **Do (45 min):** UK GDPR (ICO) basics for UK clients; Nigeria's NDPA via NDPC.
  - **Done when:** One-page data-processing summary for E1

- [ ] **[[Day 50 - Customer-cloud deploys|Day 50 (Thu Nov 19)]]**: **Customer-cloud deploys**
  - **Do (45 min):** Deploying into a customer's own VPC, private endpoints, restricted and offline environments.
  - **Done when:** Notes: 3 deployment models + tradeoffs

- [ ] **[[Day 51 - E1- fix|Day 51 (Fri Nov 20)]]**: **E1: fix**
  - **Do (45 min):** Close UAT issues.
  - **Done when:** Every issue closed or explicitly deferred

- [ ] **[[Day 52 - E1- go-live|Day 52 (Sat Nov 21)]]**: **E1: go-live**
  - **Do (45 min):** Production launch with the client.
  - **Done when:** System is Live in production

- [ ] **[[Day 53 - Review +15|Day 53 (Sun Nov 22)]]**: **Review +15**
  - **Do (45 min):** Send the weekly status update to the client.
  - **Done when:** Status update sent

- [ ] **[[Day 54 - E1- hypercare|Day 54 (Mon Nov 23)]]**: **E1: hypercare**
  - **Do (45 min):** Watch logs, fix fast, and track usage.
  - **Done when:** Daily check done

- [ ] **[[Day 55 - Docs|Day 55 (Tue Nov 24)]]**: **Docs**
  - **Do (45 min):** Runbook + admin guide for the client.
  - **Done when:** Delivered to client

- [ ] **[[Day 56 - Training|Day 56 (Wed Nov 25)]]**: **Training**
  - **Do (45 min):** 30-minute training session for the client's users. Record it.
  - **Done when:** Session held & recorded

- [ ] **[[Day 57 - Field notes|Day 57 (Thu Nov 26)]]**: **Field notes**
  - **Do (45 min):** Memo: what would make this repeatable as a product. This is the FDE -> product feedback loop.
  - **Done when:** Product feedback memo written

- [ ] **[[Day 58 - ROI|Day 58 (Fri Nov 27)]]**: **ROI**
  - **Do (45 min):** Before vs after: hours saved, response time, errors.
  - **Done when:** Numbers the client agrees with

- [ ] **[[Day 59 - Case study|Day 59 (Sat Nov 28)]]**: **Case study**
  - **Do (45 min):** Problem -> approach -> result, with permission or anonymized.
  - **Done when:** Case study published

- [ ] **[[Day 60 - Review +15|Day 60 (Sun Nov 29)]]**: **Review +15**
  - **Do (45 min):** Ask the client for a testimonial and a reference.
  - **Done when:** Testimonial requested

- [ ] **[[Day 61 - E1- close-out|Day 61 (Mon Nov 30)]]**: **E1: close-out**
  - **Do (45 min):** Sign-off + a proposal for phase 2.
  - **Done when:** Gate B: E1 live, client using it


---

## 📅 Phase C — December: Enterprise AI Deployment + FDE Interviews (Days 62–92)

**Monthly Goal:** Turn your ML plan's RAG app into something an enterprise security team would approve, then practise the FDE interview loop.

- [ ] **[[Day 62 - E2- requirements|Day 62 (Tue Dec 1)]]**: **E2: requirements**
  - **Do (45 min):** Write requirements as if for a law firm: permissions, freshness, citations, PII, audit.
  - **Done when:** Requirements doc

- [ ] **[[Day 63 - E2- connector|Day 63 (Wed Dec 2)]]**: **E2: connector**
  - **Do (45 min):** Google Drive connector with incremental sync (changes API) that stores each file's permissions.
  - **Done when:** New and edited files sync

- [ ] **[[Day 64 - E2- permissions|Day 64 (Thu Dec 3)]]**: **E2: permissions**
  - **Do (45 min):** Store ACLs with chunks and filter at query time by the user's groups.
  - **Done when:** User A can't retrieve user B's private doc (tested)

- [ ] **[[Day 65 - E2- PII|Day 65 (Fri Dec 4)]]**: **E2: PII**
  - **Do (45 min):** Detect and redact PII with Presidio before indexing.
  - **Done when:** Redaction test passes

- [ ] **[[Day 66 - E2- wire-up|Day 66 (Sat Dec 5)]]**: **E2: wire-up**
  - **Do (45 min):** Plug E2's connector and permission filter into ML P2 (built today in the ML plan).
  - **Done when:** End-to-end answer with citations

- [ ] **[[Day 67 - Review +15|Day 67 (Sun Dec 6)]]**: **Review +15**
  - **Do (45 min):** Field kit: add the requirements template.
  - **Done when:** Template added to field kit

- [ ] **[[Day 68 - E2- SSO|Day 68 (Mon Dec 7)]]**: **E2: SSO**
  - **Do (45 min):** OIDC login. Group claims drive the permission filter.
  - **Done when:** Different users see different answers

- [ ] **[[Day 69 - E2- audit|Day 69 (Tue Dec 8)]]**: **E2: audit**
  - **Do (45 min):** Log every query and every document retrieved.
  - **Done when:** Audit trail for any answer

- [ ] **[[Day 70 - E2- private infra|Day 70 (Wed Dec 9)]]**: **E2: private infra**
  - **Do (45 min):** Terraform into private subnets, no public database, LLM called through a private endpoint where possible.
  - **Done when:** Nothing but the app is public

- [ ] **[[Day 71 - E2- acceptance|Day 71 (Thu Dec 10)]]**: **E2: acceptance**
  - **Do (45 min):** Turn the ML Day 68 eval set into customer acceptance thresholds.
  - **Done when:** Pass/fail report

- [ ] **[[Day 72 - E2- security pack|Day 72 (Fri Dec 11)]]**: **E2: security pack**
  - **Do (45 min):** Architecture, data flow, threat model, questionnaire answers.
  - **Done when:** Pack is a PDF

- [ ] **[[Day 73 - E2- demo|Day 73 (Sat Dec 12)]]**: **E2: demo**
  - **Do (45 min):** 5-minute demo script that starts with the result, not the setup. Record it.
  - **Done when:** Demo video recorded

- [ ] **[[Day 74 - Review +15|Day 74 (Sun Dec 13)]]**: **Review +15**
  - **Do (45 min):** Watch the demo back and cut 60 seconds.
  - **Done when:** Tighter 4-minute demo

- [ ] **[[Day 75 - Safe agents|Day 75 (Mon Dec 14)]]**: **Safe agents**
  - **Do (45 min):** Add a tool that writes data, gated by a human approval step.
  - **Done when:** Nothing is written without approval

- [ ] **[[Day 76 - Cost model|Day 76 (Tue Dec 15)]]**: **Cost model**
  - **Do (45 min):** Monthly cost at 100, 1k and 10k users.
  - **Done when:** Cost sheet completed

- [ ] **[[Day 77 - Rollout plan|Day 77 (Wed Dec 16)]]**: **Rollout plan**
  - **Do (45 min):** Pilot -> phased -> general availability, with change management and success metrics.
  - **Done when:** 1-page rollout plan

- [ ] **[[Day 78 - Hard moments|Day 78 (Thu Dec 17)]]**: **Hard moments**
  - **Do (45 min):** Scripts for scope creep, a missed deadline and an angry executive.
  - **Done when:** 3 scripts in field kit

- [ ] **[[Day 79 - E2- polish|Day 79 (Fri Dec 18)]]**: **E2: polish**
  - **Do (45 min):** README + architecture decision records.
  - **Done when:** 3 decision records written

- [ ] **[[Day 80 - E2 ship|Day 80 (Sat Dec 19)]]**: **E2 ship**
  - **Do (45 min):** Public repo, demo video, security pack.
  - **Done when:** E2 shipped

- [ ] **[[Day 81 - Review +15|Day 81 (Sun Dec 20)]]**: **Review +15**
  - **Do (45 min):** Final pass on the field kit.
  - **Done when:** Field kit verified

- [ ] **[[Day 82 - Decomposition #1|Day 82 (Mon Dec 21)]]**: **Decomposition #1**
  - **Do (45 min):** 'A hospital wants AI to cut ER wait times.' 40 min, out loud, then write up the structure.
  - **Done when:** Decomposition #1 write-up

- [ ] **[[Day 83 - Decomposition #2|Day 83 (Tue Dec 22)]]**: **Decomposition #2**
  - **Do (45 min):** 'Dispatchers at a logistics company spend 3 h a day on email.' 40 min decomposition.
  - **Done when:** Decomposition #2 write-up

- [ ] **[[Day 84 - Client simulation|Day 84 (Wed Dec 23)]]**: **Client simulation**
  - **Do (45 min):** Role-play with Claude as a sceptical CTO. Record it.
  - **Done when:** 3 fixes noted

- [ ] **[[Day 85 - FDE system design|Day 85 (Thu Dec 24)]]**: **FDE system design**
  - **Do (45 min):** Deploy an LLM assistant inside a bank's private cloud.
  - **Done when:** 1-page design

- [ ] **[[Day 86 - Practical coding|Day 86 (Fri Dec 25)]]**: **Practical coding**
  - **Do (45 min):** Timed 45 min: sync a paginated, rate-limited API into Postgres.
  - **Done when:** Passes your tests

- [ ] **[[Day 87 - Behavioral|Day 87 (Sat Dec 26)]]**: **Behavioral**
  - **Do (45 min):** 6 STAR stories from E1, Oryzon and your UK clients.
  - **Done when:** Stories written

- [ ] **[[Day 88 - Review +15|Day 88 (Sun Dec 27)]]**: **Review +15**
  - **Do (45 min):** Rehearse E1 as a 3-minute story.
  - **Done when:** Rehearsal completed

- [ ] **[[Day 89 - FDE CV|Day 89 (Mon Dec 28)]]**: **FDE CV**
  - **Do (45 min):** Lead with E1's client impact, then E2 and integrations. Add an FDE LinkedIn headline variant.
  - **Done when:** CV variant ready

- [ ] **[[Day 90 - Targets|Day 90 (Tue Dec 29)]]**: **Targets**
  - **Do (45 min):** 20 roles: associate FDE, FDE at startups, AI deployment engineer, solutions engineer. Send 5.
  - **Done when:** 5 applications sent

- [ ] **[[Day 91 - Applications|Day 91 (Wed Dec 30)]]**: **Applications**
  - **Do (45 min):** Send 5 more. Share the E1 testimonial on LinkedIn.
  - **Done when:** 10 applications sent

- [ ] **[[Day 92 - Retro (Gate C)|Day 92 (Thu Dec 31)]]**: **Retro (Gate C)**
  - **Do (45 min):** Choose Q1's main track: FDE or ML engineer (the Months 4–6 plan).
  - **Done when:** Gate C: E2 shipped, 10 FDE applications

---

## 🎯 FDE-Readiness Checklist (Target: All Ticked by Dec 31)

- [ ] **Client ownership:** E1 is live, with a signed SOW, ROI numbers and a client reference
- [ ] **Scoping:** A problem statement, a SOW and a rollout plan you wrote yourself
- [ ] **Integrations:** Working code against HubSpot, Slack, Google Drive and a webhook receiver
- [ ] **Identity:** OIDC SSO, RBAC and row-level security implemented and tested
- [ ] **Cloud:** A VPC and deploys in Terraform, IAM cross-account access, alarms
- [ ] **Enterprise AI:** E2 enforces permissions, redacts PII, keeps an audit log and runs on private infrastructure
- [ ] **Security reviews:** A threat model, a data-flow diagram and questionnaire answers
- [ ] **Interview reps:** 2 decomposition write-ups, 1 client simulation, 1 system design, 6 STAR stories
- [ ] **Field kit:** Discovery bank, SOW, status update, runbook and demo script templates
- [ ] **Applications:** 10 targeted FDE applications sent
