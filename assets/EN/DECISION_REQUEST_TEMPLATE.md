# Decision Request and Necessary Information Request Template (execution layer)

Version: v1.0  
Hierarchy: constitution `HUMAN_AGENT_PARADIGM.md` v1.0 → derived specification `DERIVED_SPECIFICATION.md` v1.0 → this
template  
Status: execution-layer template · produced under the Owner's authorization  
Applicable scope: any interaction in P0–P7 that requires a human response; Part A is for necessary decisions
(preference/value, authorization/responsibility), Part B for necessary information completion in P0/P1

## Usage rules

1. Run the necessity test first: anything the Agent can ascertain, verify, or cover under existing authorization must
   not be sent to the human.
2. "How-to" capability questions are forbidden; executive work must not be shifted.
3. A Part A decision request must carry all six elements (background summary, substantive options, recommendation,
   reason, default choice, decision impact) and state a response window.
4. Preference/value type: when the human does not respond before the deadline, proceed on the default and disclose it;
   authorization/responsibility type: no default, must wait for an explicit decision.
5. Every request and the human's choice must be archived as proof of accountability and traceability.

---

## Part A Decision Request

### A0 Metadata

| Field         | Content                                                         |
|:--------------|:----------------------------------------------------------------|
| Request ID    |                                                                 |
| Contract ID   |                                                                 |
| Current phase |                                                                 |
| Request type  | `P preference/value` / `A authorization/responsibility`         |
| Risk level    | `High/Medium/Low` (determines the window and escalation method) |
| Created at    |                                                                 |

### A1 Necessity Test (required; must not be sent if it fails)

1. Can this matter be resolved by the Agent through information gathering, reasoning, verification, or existing
   authorization?
    - `Yes` → **Stop sending; the Agent decides.**
    - `No` → continue to step 2.
2. Is this matter essentially the human's preference/value, or authorization/responsibility? (choose only one, and state
   the basis)
3. If borderline: a wrong self-decision that is costly and irreversible → escalate; cheap and reversible → decide and
   disclose afterwards.
4. Why this request cannot be self-decided by the Agent:

### A2 Background Summary

**Enough for an independent third party to understand the facts needed for the decision, without irrelevant
information:**

**Contract clauses directly relevant to this decision:**

### A3 Substantive Options

**At least two for P-type; at least "approve/not approve" for A-type. For each option state the key difference, benefit,
cost, and risk.**

| Option   | Content | Key difference | Benefit | Cost/risk | Effect on standard strength |
|:---------|:--------|:---------------|:--------|:----------|:----------------------------|
| Option 1 |         |                |         |           |                             |
| Option 2 |         |                |         |           |                             |
| (if any) |         |                |         |           |                             |

**Substantive-difference check:** the above options differ discernibly on key dimensions such as scope/path/quality
strategy/cost-risk/experience orientation — not mere rewording.

### A4 Recommendation and Reason

| Field                                  | Content |
|:---------------------------------------|:--------|
| Recommended option                     |         |
| Reason for recommendation              |         |
| Cost of the recommendation             |         |
| Impact of rejecting the recommendation |         |

### A5 Default Choice and Overdue Handling

| Field                                | Content                                                                                   |
|:-------------------------------------|:------------------------------------------------------------------------------------------|
| Default option                       | fillable for P-type; A-type must read "no default, wait for an explicit decision"         |
| When the default takes effect        | only for preference/value type when the human does not respond within the response window |
| How default advancement is disclosed | traced in the decision record and the delivery report                                     |

### A6 Decision Impact

| Option   | Scope impact | Cost impact | Quality impact | Risk impact | Time impact |
|:---------|:-------------|:------------|:---------------|:------------|:------------|
| Option 1 |              |             |                |             |             |
| Option 2 |              |             |                |             |             |

### A7 Response Window

| Field                     | Content                                                                          |
|:--------------------------|:---------------------------------------------------------------------------------|
| Suggested response window |                                                                                  |
| Basis for the window      | risk, cost, time sensitivity                                                     |
| Overdue handling          | P-type: proceed on the A5 default and trace it; A-type: keep waiting, no default |

### A8 The Human's Decision and Trace

| Field                        | Content                                                               |
|:-----------------------------|:----------------------------------------------------------------------|
| The human's choice           |                                                                       |
| Basis for the choice         |                                                                       |
| Decision-impact confirmation |                                                                       |
| Decision time                |                                                                       |
| Traceability references      | constitution 4.3/4.4; derived specification 4.1–4.4; contract clauses |

---

## Part B Necessary Information Request (P0/P1 only)

### B0 Pre-check (must not be sent if it fails)

- [ ] This request occurs in P0/P1.
- [ ] Self-service has been tried, with at least one channel tried recorded.
- [ ] This information is necessary to continue and cannot be replaced by reasoning, verification, or existing
  authorization.
- [ ] Contains no "how-to" and does not require the human to do executive work.

### B1 Request Content

| Field                                                       | Content |
|:------------------------------------------------------------|:--------|
| Request ID                                                  |         |
| Contract/intent record                                      |         |
| Exact missing information                                   |         |
| Which fact judgment/contract clause this information is for |         |
| Self-service channels already tried                         |         |
| Why it cannot be obtained independently                     |         |
| How the Agent will degrade if it cannot be provided         |         |

### B2 The Human's Reply and Trace

| Field                          | Content                                                  |
|:-------------------------------|:---------------------------------------------------------|
| Information the human provided |                                                          |
| Record the information enters  | intent record / fact-and-constraint baseline             |
| Reply time                     |                                                          |
| Traceability references        | constitution 4.2, 5.2 P1; derived specification 4.1, 4.4 |

---

## Pre-send Self-Check

- [ ] Not a "how-to" question.
- [ ] Not a matter the Agent can decide itself.
- [ ] Part A has all six elements; P-type has ≥2 substantively different options; A-type has no default.
- [ ] Response window and overdue handling are stated.
- [ ] Disclosure is complete and unbiased; information advantage does not induce weaker standards.
