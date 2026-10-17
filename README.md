# AI Customer Support Platform - Project Management Case Study

> **This is a self-directed simulated Project Management case study created to demonstrate Project Management skills. It is not professional client work or employment experience.**
> The company, people, data, team, status and closure figures are fictional. Every numeric KPI is labelled a *Proposed Project Target* and is not an actual result.

**Author:** [Your Name] &nbsp;|&nbsp; **LinkedIn:** [your-profile-link] &nbsp;|&nbsp; **Background:** AI graduate transitioning into Technical Project Management / PMO

---

## Project at a glance

| | |
|---|---|
| **Project type** | Self-directed simulated PM case study (portfolio piece) |
| **Fictional company** | Kestrel Commerce Ltd. - B2B SaaS for online retailers (about 180 staff) |
| **Product** | AI customer support platform: chatbot answering from a knowledge base, human escalation, admin tools, analytics |
| **Methodology** | Scrum, 5 two-week sprints (proposed delivery methodology in a simulation) |
| **Duration** | 10 weeks, 5 Jan - 13 Mar 2026 (simulated window), pilot release 11 Mar |
| **Team (simulated)** | Project Manager, Product Manager, AI/ML Engineer, Backend Developer, Frontend Developer, UI/UX Designer, QA Engineer, DevOps Engineer - 61 person-weeks |
| **Plan size** | 46 work packages, 126 sub-tasks, 30 user stories (161 story points), 61 requirements, 17 risks, 9 milestones, 15 stakeholders |

## 5-minute reviewer path

1. This README
2. [Project Charter](01-Project-Charter/01_Project_Charter.pdf) - business case, scope, governance, milestones
3. [Gantt preview](05-Planning/08_Gantt_Chart_Preview.png) - then the editable [Gantt chart](05-Planning/08_Gantt_Chart.xlsx)
4. [Risk Register](07-Risk-Management/11_Risk_Register.xlsx) - scored risks with triggers, owners and a heat map
5. [Simulated Status Report](09-Status-Reporting/13_Project_Status_Report.pdf) - RAG status, burn-up, decisions required
6. [PM Case Study](11-Case-Study/16_PM_Case_Study.pdf) - the whole story in four pages

## Business problem

Merchants wait about 6.5 hours (baseline assumption) for answers that already exist in the help center, and roughly 45% of tickets are routine. Agents repeat answers all day, hiring is slow and expensive, and wrong AI answers on billing or privacy topics could damage trust. The company needs speed **with control**.

## Project objective

Deliver, within 10 weeks and a 5,500 USD non-labour budget (planning assumption), a pilot-ready AI customer support platform that answers from approved knowledge-base content with sources, escalates to humans with full context, lets admins manage content, shows managers basic analytics, and protects customer data.

**Proposed Project Targets** (not results): at least 35% of conversations resolved without handover within 8 weeks of go-live; AI answers in 8 seconds or less (p95); golden-set accuracy of at least 85% and at most 5% unsupported answers before go-live; pilot released 11 Mar 2026.

## Proposed solution

Retrieval-augmented generation: find the best knowledge-base passages, ask an LLM to answer only from them, cite sources, and fall back to a human when confidence is low. Stack (proposed): React, FastAPI, PostgreSQL + pgvector, LLM/embedding API behind an abstraction layer, email provider, managed cloud hosting. See [Solution Architecture Overview](03-Requirements/22_Solution_Architecture_Overview.pdf).

## My role (in the simulation)

Project Manager. I own scope baseline, schedule, capacity, risks, issues, dependencies, change control, stakeholder communication and status reporting. I do **not** design, code, tune prompts or test; those belong to the simulated delivery roles. Decision rights are defined in the Charter and RACI.

## Key PM artifacts

| # | Artifact | Format |
|---|---|---|
| 00 | [Project Brief](00-Project-Brief/00_Project_Brief.pdf) - company, problem, KPIs, personas, MoSCoW features | PDF |
| 01 | [Project Charter](01-Project-Charter/01_Project_Charter.pdf) | PDF |
| 02 | [Project Scope](02-Scope/02_Project_Scope.pdf) - in/out, boundaries, scope-control approach | PDF |
| 03 | [Requirements](03-Requirements/03_Requirements.pdf) - 61 traceable requirements | PDF |
| 04 | [Product Backlog](04-Backlog-and-User-Stories/04_Product_Backlog.xlsx) | XLSX |
| 05 | [User Stories](04-Backlog-and-User-Stories/05_User_Stories.xlsx) | XLSX |
| 06 | [Work Breakdown Structure](05-Planning/06_Work_Breakdown_Structure.xlsx) + capacity check | XLSX |
| 07 | [Project Timeline](05-Planning/07_Project_Timeline.pdf) - dependencies and critical path | PDF |
| 08 | [Gantt Chart](05-Planning/08_Gantt_Chart.xlsx) + [PNG](05-Planning/08_Gantt_Chart_Preview.png) / [PDF](05-Planning/08_Gantt_Chart_Preview.pdf) preview | XLSX, PNG, PDF |
| 09 | [Stakeholder Register](06-Stakeholder-Management/09_Stakeholder_Register.xlsx) + power/interest grid | XLSX |
| 10 | [RACI Matrix](06-Stakeholder-Management/10_RACI_Matrix.xlsx) + team roles and PM needs | XLSX |
| 11 | [Risk Register](07-Risk-Management/11_Risk_Register.xlsx) - 17 risks, heat map | XLSX |
| 12 | [Sprint Plan](08-Agile/12_Sprint_Plan.xlsx) - sprints, sprint backlog, DoD/DoR, de-scope plan | XLSX |
| 13 | [Simulated Project Status Report](09-Status-Reporting/13_Project_Status_Report.pdf) | PDF |
| 14 | [Project Closure Report](10-Closure/14_Project_Closure_Report.pdf) (simulated scenario) | PDF |
| 15 | [Lessons Learned](10-Closure/15_Lessons_Learned.pdf) (simulated) | PDF |
| 16 | [PM Case Study](11-Case-Study/16_PM_Case_Study.pdf) | PDF |
| 17 | [Issue Log](09-Status-Reporting/17_Issue_Log.xlsx) | XLSX |
| 18 | [Dependency Log](09-Status-Reporting/18_Dependency_Log.xlsx) | XLSX |
| 19 | [Communication Plan](06-Stakeholder-Management/19_Communication_Plan.pdf) | PDF |
| 20 | [UAT Plan](12-Change-and-UAT/20_UAT_Plan.pdf) - 20 scenarios | PDF |
| 21 | [Sample Change Request (CR-001)](12-Change-and-UAT/21_Change_Request.pdf) | PDF |
| 22 | [Solution Architecture Overview](03-Requirements/22_Solution_Architecture_Overview.pdf) | PDF |
| 23 | [AI-Assisted PM Workflow](11-Case-Study/23_AI_Assisted_PM_Workflow.pdf) | PDF |

## Risk management

17 risks scored on a 5x5 matrix (5 Critical, 5 High, 7 Medium) with owner, mitigation, contingency, measurable trigger, residual score and status. Headline risks: AI hallucination (R01), poor knowledge-base content (R03), privacy and security (R04, R05), scope creep (R08) and LLM dependency and cost (R06, R07). The simulated status report shows R03 partly materialising and being managed through the issue log.

## Stakeholder management

15 stakeholders scored for interest and influence with a tailored engagement approach each; RACI with exactly one accountable role per activity (checked by formula); decision rights and change thresholds in the Charter; communication cadence aligned to sprint ceremonies.

## AI-assisted PM workflow

AI is used as an **assistant**: first drafts, risk brainstorming, summaries, dependency checks and retrospective clustering. The PM reviews, validates, prioritises, decides, communicates and approves. See [AI-Assisted PM Workflow](11-Case-Study/23_AI_Assisted_PM_Workflow.pdf). These documents were themselves drafted with AI assistance and are the author's responsibility to review and validate.

## Lessons learned (simulated)

Book vendor/legal reviews and SME time in Week 1; put AI evaluation in the Definition of Done; publish the Won't-Have list at the requirements baseline; schedule security-related Should items before the last sprint; re-forecast from actual velocity after two sprints.

## Repository structure

```
AI-Customer-Support-Platform-PM/
|-- README.md
|-- 00-Project-Brief/            00_Project_Brief.pdf
|-- 01-Project-Charter/          01_Project_Charter.pdf
|-- 02-Scope/                    02_Project_Scope.pdf
|-- 03-Requirements/             03_Requirements.pdf, 22_Solution_Architecture_Overview.pdf
|-- 04-Backlog-and-User-Stories/ 04_Product_Backlog.xlsx, 05_User_Stories.xlsx
|-- 05-Planning/                 06_Work_Breakdown_Structure.xlsx, 07_Project_Timeline.pdf,
|                                08_Gantt_Chart.xlsx, 08_Gantt_Chart_Preview.png/.pdf
|-- 06-Stakeholder-Management/   09_Stakeholder_Register.xlsx, 10_RACI_Matrix.xlsx, 19_Communication_Plan.pdf
|-- 07-Risk-Management/          11_Risk_Register.xlsx
|-- 08-Agile/                    12_Sprint_Plan.xlsx
|-- 09-Status-Reporting/         13_Project_Status_Report.pdf, 17_Issue_Log.xlsx, 18_Dependency_Log.xlsx
|-- 10-Closure/                  14_Project_Closure_Report.pdf, 15_Lessons_Learned.pdf
|-- 11-Case-Study/               16_PM_Case_Study.pdf, 23_AI_Assisted_PM_Workflow.pdf
`-- 12-Change-and-UAT/           20_UAT_Plan.pdf, 21_Change_Request.pdf
```

## Consistency by design

IDs, dates, story points and dependencies cross-reference across artifacts: every story links to a requirement and to a WBS work package; every story's sprint matches the sprint in which its linked tasks finish; milestones equal task end dates; sprint points total 161; WBS effort (275 person-days) fits team capacity (305 person-days) with about 10% buffer; the status report, issue log, dependency log and risk statuses all describe the same simulated date (30 Jan 2026).

---

*Self-directed simulated Project Management case study - not professional client work or employment experience.*
