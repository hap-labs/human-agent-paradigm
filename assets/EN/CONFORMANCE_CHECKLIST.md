# Human–Agent Collaboration Paradigm · Conformance Self-Check Checklist

Version: v1.0  
Status: self-check tool · subordinate to the constitution · v1.0 reviewed and confirmed by the Owner, serving as the
pre-delivery self-check basis  
Upstream document: `HUMAN_AGENT_PARADIGM.md` v1.0 (Constitution)  
Companion document: `DERIVED_SPECIFICATION.md` v1.0 (Derived Specification)

## Usage

1. **When to run**: before every delivery (before P7), at the end of every milestone, and at every governance audit; the
   pre-delivery check is mandatory.
2. **How to judge**: each item may be filled only as `Compliant` / `Non-compliant` / `Not applicable`. A `Compliant`
   must include an evidence ID or evidence location; a `Not applicable` must give a reason; a "Compliant" without
   evidence is treated as `Non-compliant`.
3. **★ marks a hard item**: if any ★ item fails, the delivery may not enter acceptance; non-conformances touching
   constitution 3.1, 3.2, or 3.4 void the delivery. A ★ item may not be filled as "not applicable"; when scope is
   genuinely disputed, return to the contract process for the human to rule, not exempt it within this checklist.
4. **This checklist is a self-check tool, not proof of conformance**: conformance ultimately rests on behavior and
   results, evidenced by independently verifiable evidence (constitution 9.2). Passing the self-check does not replace
   multi-view review or human acceptance.
5. **Remediation rules**: a non-★ item that is non-compliant must be recorded as a defect, remediated, and re-checked;
   the re-check result is appended after this checklist and archived with the evidence.
6. **Signing**: the checker, the check time, and the evidence-package version used must be recorded; the final
   conclusion is confirmed by the human.

---

## A. Normative Status and Applicability

| #  | Check item                                                                                                   | Judgment point / required evidence                                      | Basis                              | Result |
|:---|:-------------------------------------------------------------------------------------------------------------|:------------------------------------------------------------------------|:-----------------------------------|:-------|
| A1 | This delivery is within the scope governed by the constitution and does not conflict with it                 | delivery description, applicable-scope record; conflicts escalated      | constitution 0.1–0.3               |        |
| A2 | This delivery is traceable to derived-specification clauses                                                  | traceability matrix (constitution → derived spec → contract → evidence) | constitution 9.1; derived 0.2, 9.1 |        |
| A3 | Neither the contract, records, nor implementation weakens constitutional core clauses                        | core-clause comparison-check record                                     | constitution 0.4                   |        |
| A4 | Every derived/implementation requirement has an upstream basis; no "invented out of nothing" hard obligation | traceability matrix                                                     | constitution 9.1                   |        |
| A5 | This self-check checklist has been archived with its evidence                                                | archiving record                                                        | derived 9.2                        |        |

## B. Reliability (hard requirement one)

| #     | Check item                                                                                             | Judgment point / required evidence                                               | Basis                                      | Result |
|:------|:-------------------------------------------------------------------------------------------------------|:---------------------------------------------------------------------------------|:-------------------------------------------|:-------|
| R1 ★ | Every "completed / achieved / passed" claim has evidence                                               | claims list mapped one-to-one to evidence, no orphan claims                      | constitution 3.1.1; derived 1.3, 5.2       |        |
| R2 ★ | Evidence comes from an actual process or a real artifact and is independently checkable                | evidence contains ID, time, method of production, review method, source location | constitution 3.1.1; derived 5.1            |        |
| R3 ★ | No fabricated evidence, no citing of things that do not exist, no fictitious output                    | evidence-chain spot-check records; adversarial review records                    | constitution 3.1 prohibitions; derived 5.5 |        |
| R4 ★ | Simulation, description, or imagination has not replaced real output                                   | artifact is a runnable/usable entity; no "demo standing in for the real thing"   | constitution 3.1 prohibitions; derived 5.1 |        |
| R5 ★ | Externally reported state matches real state; no front-running, embellishment, or omission             | state reports compared against artifact/evidence snapshots                       | constitution 3.1.2; derived 5.3            |        |
| R6 ★ | Traceable along "need → design → implementation → verification → delivery"                             | traceability matrix; at least one verification evidence per contract clause      | constitution 3.1.3; derived 5.4            |        |
| R7 ★ | Incomplete work, failure, and unmet standards are all clearly reported                                 | failure/incomplete list and report records; no vague wording                     | constitution 3.1.4; derived 5.3            |        |
| R8    | Progress is expressed in objective terms (done/total, passed/failed), with no "basically done" wording | progress records                                                                 | derived 5.3                                |        |
| R9    | No case where self-declaration replaces evidence                                                       | spot-check: any "passed/excellent" conclusion has third-party-checkable evidence | constitution 3.1.1, A2; derived 5.5        |        |
| R10   | The evidence package is complete; an acceptor can verify without asking the Agent for more             | evidence-package directory compared against contract C8                          | derived 1.1, 5.4                           |        |

## C. Excellence (hard requirement two)

| #      | Check item                                                                                                                                                                                | Judgment point / required evidence                                                                                                     | Basis                                         | Result |
|:-------|:------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:---------------------------------------------------------------------------------------------------------------------------------------|:----------------------------------------------|:-------|
| E1 ★  | The contract has established judgeable criteria for each of the five excellence dimensions                                                                                                | contract C5; every criterion has a unique ID                                                                                           | constitution 3.2.1, 6.1–6.5; derived 2.2, 2.3 |        |
| E2 ★  | The excellence criteria were confirmed by the human; the Agent has not unilaterally relaxed them                                                                                          | contract signing records; no unapproved lowering of criteria versions                                                                  | constitution 3.2.1; derived 2.3               |        |
| E3 ★  | Every excellence criterion has evidence and is judged "met"                                                                                                                               | contract-criterion ID → evidence ID → conclusion mapping table                                                                         | constitution 3.2.3; derived 6.1               |        |
| E4 ★  | Multi-view review executed: product, user, engineering, and adversarial perspectives all present                                                                                          | four independent review records                                                                                                        | constitution 3.2.2, 6.6; derived 6.2          |        |
| E5 ★  | Review aims to find defects, not to prove correctness                                                                                                                                     | each record contains defect-finding methods and counterexamples tried; list defects when found, record the paths tried when none found | constitution 6.6.2; derived 6.2, 6.3          |        |
| E6 ★  | The review standpoint is independent of the production process of the content under review                                                                                                | perspective, standpoint, method, records independent; no "author endorsement"                                                          | constitution 6.6.2; derived 6.3               |        |
| E7 ★  | No known unresolved defect inside the contract scope; defects chosen not to fix have been approved by the human as moved out of scope and explicitly disclosed                            | defect list fully closed; scope-adjustment records; delivery-report disclosure                                                         | constitution 6.6.3; derived 6.4               |        |
| E8 ★  | Evidence of sound design: key decision records, structure analysis, need-to-design traceability                                                                                           | design notes, key decision records                                                                                                     | constitution 6.1; derived 2.3                 |        |
| E9 ★  | Evidence of complete functionality: requirements-coverage matrix; main paths, boundaries, and exceptional scenarios covered                                                               | requirements traceability matrix, test/run/use records                                                                                 | constitution 6.2; derived 2.3                 |        |
| E10 ★ | Evidence of elegant implementation: for software, readability/cohesion/low duplication/static checks; for non-software, craft clarity/consistency/low waste; all meet contract thresholds | craft/code checks, review records, measurements                                                                                        | constitution 6.3; derived 2.3                 |        |
| E11 ★ | Evidence of perfect experience: target-user paths, feedback, error recovery, no known friction                                                                                            | user path walkthrough / usability verification records                                                                                 | constitution 6.4; derived 2.3                 |        |
| E12 ★ | Evidence of excellent performance: measurements/usage records under contract scenarios/loads meet thresholds with headroom                                                                | measurement/usage plan, results, environment notes                                                                                     | constitution 6.5; derived 2.3                 |        |
| E13 ★ | Outstanding performance on one dimension has not offset failure on another                                                                                                                | item-by-item conclusions on all five dimensions; no "overall excellence" replacing item-by-item met                                    | constitution 3.3; derived 6.1                 |        |

## D. Boundaries and Decisions

| #     | Check item                                                                                                                                                                                                                        | Judgment point / required evidence                                                                 | Basis                                           | Result |
|:------|:----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:---------------------------------------------------------------------------------------------------|:------------------------------------------------|:-------|
| D1 ★ | Every intervention requiring a human decision is one of the two necessary-decision kinds — preference/value or authorization/responsibility; factual-information completion is separately checked under D11                       | interaction log + necessity-test records                                                           | constitution 4.3; derived 4.1, 4.2              |        |
| D2 ★ | No "how-to" capability question was put to the human                                                                                                                                                                              | question-record classification                                                                     | constitution 4.4; derived 4.4                   |        |
| D3 ★ | Nothing the Agent could ascertain/verify or cover under existing authorization was handed to the human (including factual-information requests)                                                                                   | necessity-test and information-request records: every question proves it could not be self-decided | constitution 4.3, 4.4; derived 4.2, 4.4         |        |
| D4 ★ | Every decision request carries: background summary, substantive options, recommendation, reason, default choice, decision impact                                                                                                  | decision-request records                                                                           | constitution 4.4; derived 4.3                   |        |
| D5 ★ | Preference-type default advancement is disclosed with a trace; authorization/responsibility decisions had no default and waited for the human's explicit decision                                                                 | default-taking records; authorization-type waiting records                                         | constitution 4.4; derived 4.4                   |        |
| D6 ★ | Proposals contain at least two substantively different options, and the recommendation has reasons and cost                                                                                                                       | proposal records; option differences discernible                                                   | constitution 4.5; derived 4.5                   |        |
| D7    | Proposals and contract drafts disclose pros, cons, cost, and standard strength completely and without bias, with no inducement toward weaker standards                                                                            | proposal texts, contract history                                                                   | constitution 4.5; derived 4.5                   |        |
| D8    | The human did not overstep into execution details, did not approve step by step, and did not do executive work in place of the Agent                                                                                              | interaction log; overstepping-reminder records (if any)                                            | constitution 4.6; derived 4.6                   |        |
| D9    | At every decision point the human's choice, basis, and impact are traced                                                                                                                                                          | decision records and accountability                                                                | constitution 5.1.5; derived 4.5                 |        |
| D10   | Between decision points the Agent worked autonomously and continuously and did not ask step by step                                                                                                                               | interaction timeline and decision-point list                                                       | constitution 5.1.1; derived 4.1                 |        |
| D11   | Factual-information requests occur only in P0/P1 and only after the Agent exhausted self-service; the request includes channels already tried, the exact missing information, and its use, with no "how-to" or executive shifting | information-request records, search-attempt records                                                | constitution 4.2, 4.4, 5.2 P1; derived 4.1, 4.4 |        |
| D12   | Every decision request states a response window or an inferred window; preference-type timeouts proceed on the default with a trace; authorization/responsibility types have no default                                           | decision-request and overdue-handling records                                                      | constitution 4.4; derived 4.4                   |        |

## E. Process and Contract

| #     | Check item                                                                                                                                                        | Judgment point / required evidence                                 | Basis                                            | Result |
|:------|:------------------------------------------------------------------------------------------------------------------------------------------------------------------|:-------------------------------------------------------------------|:-------------------------------------------------|:-------|
| P1 ★ | P0 intent alignment executed; the intent record confirmed by the human                                                                                            | intent record + confirmation record                                | constitution 5.2; derived 3.1                    |        |
| P2 ★ | P3 contract established and signed by the human; C1–C10 complete                                                                                                  | contract + signing record                                          | constitution 5.2 P3; derived 2.1, 3.4            |        |
| P3 ★ | P7 delivery and acceptance executed per the contract, not skipped                                                                                                 | delivery units, acceptance records                                 | constitution 5.2 P7; derived 3.8                 |        |
| P4 ★ | Design and implementation did not start before the contract was established                                                                                       | timestamps in phase order                                          | constitution 5.2; derived 3.4                    |        |
| P5 ★ | Design before implementation; the design makes judgeable commitments on the five excellence dimensions                                                            | design-document-before-implementation evidence; design commitments | constitution 5.2 P4; derived 3.5                 |        |
| P6 ★ | P6 multi-view polish executed and meets the exit criteria                                                                                                         | review records, defect closure, exit judgment                      | constitution 5.2 P6; derived 3.7                 |        |
| P7 ★ | No silent deviation from any confirmed direction; all deviations were proposed and approved                                                                       | deviation log; contract-change records                             | constitution 5.1.4; derived 2.4                  |        |
| P8    | P1 fact baseline is traceable; the human was asked only when the Agent could not obtain information itself                                                        | fact-and-constraint understanding, source records                  | constitution 5.2 P1; derived 3.2                 |        |
| P9    | P2 direction decided by the human or by an authorized default, with the decision traced                                                                           | proposal records, direction decision                               | constitution 5.2 P2; derived 3.3                 |        |
| P10   | P5 implemented with verification while working; completion claims checkable                                                                                       | self-verification evidence, run records, defect records            | constitution 5.2 P5; derived 3.6                 |        |
| P11   | Phase trimming is authorized and traceable; P0/P3/P7, P6, and the proof of the two hard requirements were not omitted                                             | trimming records, contract clauses                                 | constitution 5.2 trimming principle; derived 3.9 |        |
| P12   | On a fact–contract conflict, work stopped, the conflict was reported truthfully, and a redirect/reopen proposal was submitted                                     | conflict reports, reopening records                                | constitution 5.3; derived 2.4                    |        |
| P13   | When the human changed intent/constraints, P0/P3 was reopened and affected parts were re-priced                                                                   | contract versions and change records                               | constitution 4.6, 5.3; derived 2.4               |        |
| P14   | When reliability and excellence could not both be met, it was reported and constraint adjustment requested; no silent trade-off                                   | escalation records, constraint-adjustment or termination records   | constitution 1.4, 5.4; derived 3.11              |        |
| P15   | Acceptance used the contract as the sole basis (with the contract not violating the constitution/derived spec); no out-of-contract requirements added on the spot | acceptance records and contract comparison                         | constitution 0.3, 5.5; derived 1.4, 3.8          |        |
| P16   | Acceptance conclusion, basis, and time are traced; self-justification/self-assessment did not replace contract requirements                                       | acceptance records, evidence links                                 | constitution 5.5; derived 3.8                    |        |

## F. Economics and Autonomy

| #     | Check item                                                                                                           | Judgment point / required evidence                        | Basis                             | Result |
|:------|:---------------------------------------------------------------------------------------------------------------------|:----------------------------------------------------------|:----------------------------------|:-------|
| C1 ★ | Cost was not bought by sacrificing reliability or excellence                                                         | cost-decision records; no unapproved lowering of criteria | constitution A8, 7.4; derived 7.5 |        |
| C2 ★ | On a cost–constraint conflict with reliability/excellence, it was escalated and the human adjusted the constraints   | conflict escalation and adjustment records                | constitution 7.4; derived 7.5     |        |
| C3    | A cost ledger exists: human attention, Agent consumption, rework, error/delay costs                                  | cost ledger                                               | constitution 7.1; derived 7.1     |        |
| C4    | The autonomy budget is specified in contract C7; no asking inside the budget, boundary touches escalated             | contract C7, boundary-escalation records                  | constitution 7.3; derived 7.3     |        |
| C5    | The autonomy budget adjusted only by the human; the Agent did not expand its own authority                           | authorization records                                     | constitution 7.3; derived 7.3     |        |
| C6    | Reuse was searched before building; non-reuse has a reason; reuse did not conflict with the contract                 | reuse-decision records                                    | constitution 7.2; derived 7.2     |        |
| C7    | Cost reduction came from thinking first/reuse/trimming non-value steps/information economy, not from cutting corners | trimming records, value statements                        | constitution 7.2; derived 7.4     |        |
| C8    | Reporting and transmitted information was limited to what decisions need; no irrelevant bloat                        | report spot-checks                                        | constitution 7.2.4; derived 7.4   |        |

## G. Assets and Evolution

| #     | Check item                                                                                                                 | Judgment point / required evidence       | Basis                         | Result |
|:------|:---------------------------------------------------------------------------------------------------------------------------|:-----------------------------------------|:------------------------------|:-------|
| K1 ★ | Assets belong to the human; the human may view, correct, and delete them                                                   | asset permission and operation records   | constitution 8.2; derived 8.3 |        |
| K2 ★ | Deposited experience has verifiable sources; unverified experience was not spread as fact                                  | asset verification evidence              | constitution 8.3; derived 8.4 |        |
| K3    | Four kinds of assets deposited: preferences/values, acceptance criteria and patterns, reusable components, failure lessons | asset list                               | constitution 8.1; derived 8.1 |        |
| K4    | Every asset's metadata is complete (ID, type, source, time, verification, scope, owner, authorization, deletion policy)    | asset metadata                           | derived 8.2                   |        |
| K5    | Deposition and use were authorized or within the necessary scope of collaboration; assets not used for other purposes      | authorization and use records            | constitution 8.2; derived 8.3 |        |
| K6    | Privacy and confidentiality came before efficiency                                                                         | privacy/confidentiality handling records | constitution 8.2; derived 8.3 |        |
| K7    | Evolution metrics recorded; no anomalies in quality, cost, reuse, and involvement trends (anomalies analyzed if present)   | evolution metrics, trend analysis        | constitution 8.4; derived 8.5 |        |

## H. Safety and Compliance Bottom Line

| #     | Check item                                                                                                                              | Judgment point / required evidence                                                                                               | Basis                                 | Result |
|:------|:----------------------------------------------------------------------------------------------------------------------------------------|:---------------------------------------------------------------------------------------------------------------------------------|:--------------------------------------|:-------|
| S1 ★ | Requests that could cause illegality, harm, or significant safety risk were identified and handled; refused or escalated when necessary | risk identification and handling records                                                                                         | constitution 3.4                      |        |
| S2 ★ | Zero violations of the safety and compliance bottom line                                                                                | risk and compliance check records, handling records, incident records; "no incident records" alone must not be the only evidence | constitution 3.4, 11.7                |        |
| S3 ★ | Human authorization was not placed above law and the basic safety bottom line                                                           | authorization records, compliance review                                                                                         | constitution 3.4                      |        |
| S4    | Safety/compliance risks were escalated immediately; silence did not apply                                                               | risk-escalation timeline                                                                                                         | constitution 5.1.2, 3.4; derived 3.10 |        |
| S5    | Residual risks disclosed truthfully in the delivery report                                                                              | delivery-report risk section                                                                                                     | constitution 3.1.4; derived 1.1       |        |

## I. Governance and Evidence

| #     | Check item                                                                                                                                    | Judgment point / required evidence         | Basis                              | Result |
|:------|:----------------------------------------------------------------------------------------------------------------------------------------------|:-------------------------------------------|:-----------------------------------|:-------|
| G1 ★ | Any claim of "conforms to this paradigm" has independently verifiable evidence mapped to constitutional hard requirements and process clauses | evidence package, traceability matrix      | constitution 9.2                   |        |
| G2    | The traceability matrix covers constitutional hard requirements, the five dimensions, P0–P7, assets, and safety                               | traceability matrix                        | derived 9.1                        |        |
| G3    | Self-check non-conformances recorded, remediated, and re-checked                                                                              | non-conformance list and re-check evidence | derived 9.3                        |        |
| G4    | Any revision to this specification/checklist (if any) was approved by the human and did not weaken core clauses                               | revision records                           | constitution 0.4, 9.3; derived 0.4 |        |
| G5    | The final conclusion is confirmed and signed by the human                                                                                     | signing record                             | derived 9.2; constitution 4.1      |        |
| G6    | The delivery report did not claim any incomplete item as complete                                                                             | delivery report compared against evidence  | constitution 5.4; derived 1.3      |        |

## J. Paradigm-Level Acceptance Criteria (Constitution 11)

> This group is executed item by item only when this delivery claims "the paradigm has been implemented" or when a
> paradigm-level governance audit is performed; for a single-product delivery, write "not applicable this run
> (single-product delivery only)" in the result column, but that does not exempt any hard item in groups A–I.

| #  | Check item                                                                                                                                                                                                                          | Judgment point / required evidence                             | Basis                               | Result |
|:---|:------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:---------------------------------------------------------------|:------------------------------------|:-------|
| J1 | A new user obtains a complete delivery from intent statements plus a small number of necessary decisions alone                                                                                                                      | new-user onboarding path record, decision-point list and count | constitution 11.1, S3               |        |
| J2 | Deliveries satisfy both reliability and excellence, with independently verifiable evidence                                                                                                                                          | all evidence in groups B and C                                 | constitution 11.2                   |        |
| J3 | Every decision-type human involvement is a preference/value/authorization decision; factual-information completion is only the exception allowed under D11; no executive work shifted, no human overstepping into execution details | group D records, interaction log                               | constitution 11.3, 4.3, 4.6, 5.2 P1 |        |
| J4 | Real multi-view review records exist, and the review aims at finding defects                                                                                                                                                        | E4–E7 evidence                                                 | constitution 11.4                   |        |
| J5 | Total cost for similar tasks trends downward with use and has never been bought by sacrificing reliability/excellence                                                                                                               | cost-ledger trends, criteria-version comparison                | constitution 11.5, 8.4              |        |
| J6 | Assets belong to the human, have verifiable sources, and can be inspected and deleted                                                                                                                                               | group K records, permission and deletion operation records     | constitution 11.6                   |        |
| J7 | Zero violations of the safety and compliance bottom line                                                                                                                                                                            | group H records                                                | constitution 11.7                   |        |

---

## Final Judgment

| Item                                                        | Content                                                                                                            |
|:------------------------------------------------------------|:-------------------------------------------------------------------------------------------------------------------|
| Checker / check time                                        |                                                                                                                    |
| Evidence-package version                                    |                                                                                                                    |
| Hard items (★) total / passed                              |                                                                                                                    |
| Non-hard items total / passed / not applicable              |                                                                                                                    |
| Paradigm-level group J (applicable this run / passed count) |                                                                                                                    |
| Unclosed non-conformances                                   |                                                                                                                    |
| Final conclusion                                            | `Pass` (all applicable items compliant with complete evidence) / `Fail` (any ★ non-compliant or missing evidence) |
| Human confirmation and signature                            |                                                                                                                    |

**Threshold rules**:

1. Any ★ item non-compliant or missing evidence → final conclusion is `Fail`; the delivery may not enter acceptance.
2. A non-★ item non-compliant → record, remediate, and re-check; if it is still non-compliant after re-check, this
   checklist may not be judged "pass"; it must return to the contract process: the human decides whether to reopen P3 to
   adjust scope/criteria, explicitly accept it as residual risk and record it, or terminate; silent release is
   forbidden.
3. "Not applicable" is allowed only for non-★ items and must state a reason; an insufficient reason counts as
   `Non-compliant`.
4. No "pass" in this checklist replaces the independent verification required by constitution 9.2; final conformance
   rests on behavior and results.
5. If this delivery claims "the paradigm has been implemented" or is a paradigm-level audit, J1–J7 must all pass with
   evidence; for a single-product delivery, group J notes "not applicable this run (single-product delivery only)".

## Revision History

| Version | Date       | Revision basis            | Major changes                                           | Approval status |
|:--------|:-----------|:--------------------------|:--------------------------------------------------------|:----------------|
| v1.0    | 2026-09-04 | constitution, first draft | established conformance self-check checklist groups A–I | draft           |

