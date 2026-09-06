# 02 — RAID Log

RAID = Risks, Assumptions, Issues, and Dependencies.

| ID | Type | Item | Impact | Owner | Response / Next Action | Status |
|---|---|---|---|---|---|---|
| R-01 | Risk | Checkout redesign may create regression defects | High | Engineering Lead | Regression suite + UAT before release | Monitoring |
| R-02 | Risk | Analytics events may be incomplete | High | Analytics Lead | Define event taxonomy and validate in QA | Open |
| R-03 | Risk | Scope expansion during design | Medium | PM / Product Owner | Change-control review for new requests | Monitoring |
| A-01 | Assumption | Existing payment APIs remain available | High | Engineering | Validate during technical discovery | Validating |
| A-02 | Assumption | Product owner is available for sprint decisions | Medium | Product Owner | Reserve weekly decision window | Valid |
| I-01 | Issue | Mobile checkout acceptance criteria need clarification | High | PM / Product Owner | Finalize criteria before Sprint 2 planning | Open |
| I-02 | Issue | QA test data is not yet aligned to production scenarios | Medium | QA Lead | Create representative test-data set | Open |
| D-01 | Dependency | Design approval required before development handoff | High | UX Lead | Approval checkpoint at end of Sprint 1 | On track |
| D-02 | Dependency | Analytics instrumentation depends on engineering release branch | Medium | Analytics / Engineering | Coordinate implementation and validation | On track |

## Escalation Rules
- **High impact + blocked:** escalate within 24 hours.
- **Potential schedule impact > 2 business days:** raise in weekly status report.
- **Scope changes:** document decision, owner, impact, and approval before commitment.

## Review Cadence
RAID items are reviewed during sprint planning and the weekly project status checkpoint. Closed items remain documented for auditability and retrospective learning.
