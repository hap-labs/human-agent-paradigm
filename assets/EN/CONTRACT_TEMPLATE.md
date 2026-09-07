# Contract Template (execution layer)

Version: v1.0  
Hierarchy: constitution `HUMAN_AGENT_PARADIGM.md` v1.0 → derived specification `DERIVED_SPECIFICATION.md` v1.0 → this
template  
Status: execution-layer template · produced under the Owner's authorization  
Applicable scope: the P3 contract-establishment phase; the first basis of judgment for all subsequent work (provided it
does not conflict with the constitution or the derived specification)

## Usage rules

1. This template is filled in by the Agent at P3 and confirmed and signed by the human (the Owner); design and
   implementation may not begin before the contract is established.
2. None of C1–C10 may be omitted; small tasks may shorten each section, but must answer item by item "is it defined,
   what is the criterion, what is the evidence".
3. All thresholds, criteria, and budgets are proposed by the Agent and confirmed by the human; the Agent may not
   unilaterally relax them, and later changes must go through C10.
4. The contract ID is unique and versions traceable; every change must record the reason, affected clauses, and the
   human's approval.
5. This contract must not conflict with the constitution or the derived specification; on conflict the higher
   specification prevails and the matter returns to the contract process.

---

## Contract metadata

| Field                       | Content                                                      |
|:----------------------------|:-------------------------------------------------------------|
| Contract ID                 |                                                              |
| Version                     |                                                              |
| Product/task name           |                                                              |
| Upstream intent record      |                                                              |
| Direction-decision record   |                                                              |
| Constitutional traceability | constitution 5.2 P3, 3.2, 7.3; derived specification 2.1–2.4 |
| Status                      | `Draft` / `Signed` / `Changed` / `Terminated`                |

---

## C1 Background and Intent

**Original intent (stated by the human):**

**Agent restatement (must be confirmed by the human):**

**"What matters more" ranking:** 1. ______ 2. ______ 3. ______

**Key preferences and values:**

**Differences to confirm (if any):**

- [ ] The human has confirmed the above restatement and ranking.

---

## C2 Scope and Non-Goals

| No. | In-scope deliverables | Judgeable completion criteria (refer to C4/C5 criterion IDs) |
|:----|:----------------------|:-------------------------------------------------------------|
| S1  |                       |                                                              |
| S2  |                       |                                                              |

**Explicit non-goals (not delivered this time):**

**Product form:** (what deliverable, runnable, usable outcome is; not limited to software)

---

## C3 Constraints and Bottom Lines

| Category                | Constraint content | Non-negotiable criterion | Handling on conflict |
|:------------------------|:-------------------|:-------------------------|:---------------------|
| Time                    |                    |                          |                      |
| Cost                    |                    |                          |                      |
| Risk                    |                    |                          |                      |
| Safety                  |                    |                          |                      |
| Compliance              |                    |                          |                      |
| Privacy/confidentiality |                    |                          |                      |
| Technology/resources    |                    |                          |                      |

**Bottom-line statement:** safety and compliance are above all efficiency and need metrics; human authorization does not
override law or the basic safety bottom line.

---

## C4 Reliability Criteria

**Definition of done (DoD):** a "completed" claim is allowed only when all of the following hold:

1. The corresponding C2 deliverable is runnable/usable;
2. Every completion claim is attached to real evidence (evidence ID pointing into the evidence package);
3. C6 multi-view review passed, with no unresolved defect inside the contract scope;
4. Failures and incomplete items are listed truthfully.

**Claim–evidence mapping (made concrete for this project):**

| Claim type                   | Evidence form required                                                   | Evidence destination |
|:-----------------------------|:-------------------------------------------------------------------------|:---------------------|
| Feature/deliverable complete | runnable/usable artifact + run/use/test records                          | evidence package     |
| Quality met                  | review/test results + defect records + fix/re-verification records       | evidence package     |
| State report                 | snapshot of current real state + differences from the previous state     | evidence package     |
| Performance met              | measurement plan under contract conditions + results + environment notes | evidence package     |
| Asset reused                 | source + verification record + post-reuse results                        | evidence package     |

**State-sync method:** (when to sync, what to sync, expressed in which objective metrics)

**Failure-reporting method:** (how to report, what content and time limits when a failure/unmet standard is found; vague
wording forbidden)

**Prohibited behaviors:** reporting things that did not happen or were not completed; substituting simulation,
description, or imagination for real output; fabricating evidence or citing things that do not exist; replacing
checkable evidence with self-assessment.

---

## C5 Excellence Criteria (five dimensions, judgeable item by item)

**Filling rule:** every criterion must be writable as "object + condition + observable result + threshold/criterion +
evidence source"; adjectives alone are not allowed.

| Criterion ID | Dimension              | Object and condition | Observable result | Threshold/criterion | Evidence source and method |
|:-------------|:-----------------------|:---------------------|:------------------|:--------------------|:---------------------------|
| E6.1.x       | Sound design           |                      |                   |                     |                            |
| E6.2.x       | Complete functionality |                      |                   |                     |                            |
| E6.3.x       | Elegant implementation |                      |                   |                     |                            |
| E6.4.x       | Perfect experience     |                      |                   |                     |                            |
| E6.5.x       | Excellent performance  |                      |                   |                     |                            |

- [ ] All five dimension criteria are defined; no blank "adjective as acceptance" cell.
- [ ] The human has confirmed all thresholds; the Agent has not unilaterally relaxed them.

---

## C6 Multi-View Review Requirements

| Perspective | Problems that must be sought                                                                         | Review-record requirements                                          |
|:------------|:-----------------------------------------------------------------------------------------------------|:--------------------------------------------------------------------|
| Product     | intent drift, scope omission, non-goal bloat, value proposition not holding                          | independent standpoint, defect-finding method, findings, conclusion |
| User        | whether target users can complete independently, path, feedback, error recovery, friction            | same as above                                                       |
| Engineering | design soundness, implementation craft, maintainability, quality debt, boundaries                    | same as above                                                       |
| Adversarial | assume completion claims are false; find counterexamples, exceptional paths, safety/compliance holes | same as above                                                       |

**Independence:** the review standpoint, method, and records are independent of the production process of the content
under review; when the same entity performs the review, it must explicitly switch standpoint and use independent
methods.

**Defect closure:** Blockers/Majors must be fixed and re-verified; Minors should be fixed; any defect chosen not to fix
must reopen the contract, be approved by the human as moved out of scope, and be explicitly disclosed.

**Exit criteria:** all C5 criteria met, with no known unresolved defect inside the contract scope.

---

## C7 Autonomy Budget

| Item                   | Content              |
|:-----------------------|:---------------------|
| Authorized scope       |                      |
| Risk threshold         | escalate if exceeded |
| Cost cap               | escalate if exceeded |
| Self-decidable matters |                      |
| Must-escalate matters  |                      |
| Boundary-touch action  |                      |

**Rules:** no asking inside the boundaries; escalate immediately on touching a boundary; the autonomy budget may only be
adjusted by the human in a contract or explicit authorization; in-budget self-decisions must not conflict with the
contract or effectively lower the reliability or excellence standard.

---

## C8 Deliverables and Evidence List

| Category         | Concrete deliverable | Corresponding evidence/location |
|:-----------------|:---------------------|:--------------------------------|
| Product itself   |                      |                                 |
| Evidence package |                      |                                 |
| Reusable assets  |                      |                                 |
| Delivery report  |                      |                                 |

---

## C9 Acceptance Method

**Sole acceptance basis:** this contract (C2–C5, C6, C8).

**Acceptance action:** the human verifies evidence item by item against the contract and signs the acceptance conclusion
with a time; the Agent must not replace contract requirements with self-justification, self-assessment, or "looks
compliant".

**Prohibited:** adding out-of-contract requirements at acceptance time; new requirements must return to P0/P3 to be
re-aligned and re-priced.

---

## C10 Change, Termination, and Failure Handling

| Triggering situation                                                 | Handling                                                                                                                     |
|:---------------------------------------------------------------------|:-----------------------------------------------------------------------------------------------------------------------------|
| The human changes intent/constraints                                 | return to P0/P3; affected parts re-priced                                                                                    |
| Facts conflict with the contract                                     | stop, report truthfully, submit redirect/reopen proposal                                                                     |
| New situation the contract does not cover and that affects direction | return to P3 to amend the contract                                                                                           |
| Deviation from a confirmed direction                                 | must be proposed and approved first; acting first and telling later, or acting and staying silent, forbidden                 |
| Reliability and excellence cannot both be met within constraints     | stop, escalate the trade-off, request constraint adjustment; no silent trade-off                                             |
| The human stops the project                                          | deliver what was actually completed, evidence, and an incomplete-state statement; nothing incomplete may be claimed complete |
| Acceptance fails                                                     | fix per the contract defect list, or reopen the contract to adjust criteria                                                  |

---

## Traceability and Effect

| Contract section | Constitutional clauses served | Derived specification served |
|:-----------------|:------------------------------|:-----------------------------|
| C1               | 1.2 S3, 4.1, 5.2 P0           | 3.1                          |
| C2               | 1.4, 5.2 P3                   | 2.1                          |
| C3               | 3.4, 7.3, 7.4                 | 2.1, 7.3                     |
| C4               | 3.1, 5.5                      | 2.1, 5                       |
| C5               | 3.2, 6.1–6.6                  | 2.2, 2.3, 6                  |
| C6               | 3.2, 6.6                      | 6.2–6.5                      |
| C7               | 7.3, A4                       | 7.3                          |
| C8               | 1.3, 5.5                      | 1.1                          |
| C9               | 5.5                           | 3.8                          |
| C10              | 5.3, 5.4, 1.4                 | 2.4, 3.11                    |

**Pre-delivery gate:** run the Conformance Self-Check Checklist v1.0 groups A–I; all ★ items pass; if "the paradigm has
been implemented" is claimed, J1–J7 must also all pass.

---

## Signature and Revision

| Role                    | Content                                                                  | Signature | Time |
|:------------------------|:-------------------------------------------------------------------------|:----------|:-----|
| Agent drafted           | complete, unbiased disclosure of pros, cons, cost, and standard strength |           |      |
| Human (Owner) confirmed | confirm intent, constraints, criteria, and budget                        |           |      |

| Version | Date | Change content | Affected clauses | Human approval |
|:--------|:-----|:---------------|:-----------------|:---------------|
|         |      |                |                  |                |
