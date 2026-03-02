# OctoAcme Roles Interaction Matrix

This document maps how all eight OctoAcme roles interact with one another, providing guidance on communication frequency, decision-making authority, and escalation paths.

---

## Cross-Functional Dependency Matrix

The table below shows which roles have a direct working relationship. A ✓ indicates a regular interaction; a blank cell means no primary dependency.

| Role | Sponsor | PdM | PM | Developer | UX Designer | QA Lead | Scrum Master | Tech Writer |
|---|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| **Sponsor** | — | ✓ | ✓ | | | | | |
| **Product Manager (PdM)** | ✓ | — | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ |
| **Project Manager (PM)** | ✓ | ✓ | — | ✓ | | ✓ | ✓ | ✓ |
| **Developer** | | ✓ | ✓ | — | ✓ | ✓ | ✓ | ✓ |
| **UX Designer** | | ✓ | | ✓ | — | ✓ | | |
| **QA Lead** | | ✓ | ✓ | ✓ | ✓ | — | ✓ | |
| **Scrum Master** | | ✓ | ✓ | ✓ | | ✓ | — | |
| **Technical Writer** | | ✓ | ✓ | ✓ | | | | — |

---

## Communication Frequency Guidance

| Interaction | Frequency | Channel |
|---|---|---|
| Sponsor ↔ PM/PdM | Monthly (or per milestone) | Status summary, escalation meeting |
| PdM ↔ PM | Weekly | Sync meeting, shared backlog |
| PdM ↔ UX Designer | Sprint cycle | Design review, user research sessions |
| PM ↔ Scrum Master | Weekly | Sprint coordination, dependency review |
| Developers ↔ QA Lead | Per sprint | Defect triage, test planning |
| Developers ↔ UX Designer | Per feature | Design handoff, implementation review |
| Developers ↔ Technical Writer | Per release | Documentation review, API docs |
| QA Lead ↔ PM | Per release | Release readiness assessment |
| Scrum Master ↔ QA Lead | Per sprint | Sprint capacity and readiness check |
| PdM ↔ Technical Writer | Per release | User-facing content review |

---

## Decision-Making Authority

| Decision Type | Owner | Consulted | Informed |
|---|---|---|---|
| Strategic scope or budget change | Sponsor | PdM, PM | All roles |
| Feature prioritization | PdM | Sponsor, PM, UX Designer | Developers, QA Lead |
| Release go/no-go | QA Lead | PM, PdM | Sponsor, all roles |
| Sprint scope | Scrum Master + Developers | PM, PdM | QA Lead |
| Technical architecture | Developers | QA Lead, PM | PdM, Tech Writer |
| UX/design standards | UX Designer | PdM, Developers | QA Lead |
| Documentation scope | Technical Writer | PdM, PM | All roles |
| Risk escalation path | PM | Sponsor, PdM | All roles |

---

## Escalation Paths

1. **Blocker within the team**: Scrum Master facilitates resolution; involves PM if cross-team dependency.
2. **Scope or budget change request**: PM documents and escalates to Sponsor via PdM.
3. **Release quality risk**: QA Lead raises risk to PM; PM informs Sponsor if milestone impact is significant.
4. **Usability or design conflict**: UX Designer raises to PdM; PdM makes final prioritization decision.
5. **Documentation gap blocking release**: Technical Writer raises to PM; PM adjusts release checklist.

---

## RACI Matrix for Common Project Activities

**R** = Responsible, **A** = Accountable, **C** = Consulted, **I** = Informed

| Activity | Sponsor | PdM | PM | Developer | UX Designer | QA Lead | Scrum Master | Tech Writer |
|---|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| Define project scope | A | R | C | I | C | I | I | I |
| Backlog prioritization | I | A/R | C | C | C | C | C | I |
| Sprint planning | I | C | C | R | C | C | A/R | I |
| Feature design & prototyping | I | C | I | C | A/R | I | I | I |
| Test planning | I | C | C | C | C | A/R | I | I |
| Code implementation | I | I | I | A/R | I | C | I | I |
| Release certification | A | C | C | C | C | R | I | I |
| User documentation | I | C | I | C | I | I | I | A/R |
| Stakeholder status update | I | C | A/R | I | I | I | I | I |
| Retrospective facilitation | I | I | C | C | I | C | A/R | I |
