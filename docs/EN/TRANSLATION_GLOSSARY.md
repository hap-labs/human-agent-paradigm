# Translation Glossary — Governance Terms (EN ↔ Simplified Chinese)

> 简体中文版本：[TRANSLATION_GLOSSARY.md](../ZH_CN/TRANSLATION_GLOSSARY.md)

The unified basis for translating and reviewing the consistency of governance-layer documents (the six frozen documents
under `../../assets` and their official translations, plus the process records they drive). Use the following
correspondences whenever translating or reviewing any governance material; any new row must state its rationale and keep
the table sorted by the English term.

| English                           | Chinese                            | Context / Notes                                                                         |
|:----------------------------------|:-----------------------------------|:----------------------------------------------------------------------------------------|
| Human-Agent Paradigm (HAP)        | 人机协作范式 / 人与 Agent 协作范式 | Proper noun; product name                                                               |
| constitution                      | 宪法                               | Sole authoritative document: `../../assets/ZH_CN/HUMAN_AGENT_PARADIGM.md`               |
| derived specification             | 派生规范                           | `DERIVED_SPECIFICATION`                                                                 |
| conformance self-check checklist  | 符合性自检清单                     | `CONFORMANCE_CHECKLIST`                                                                 |
| contract                          | 契约                               | A signed C1–C10 contract                                                                |
| contract template                 | 契约模板                           | `CONTRACT_TEMPLATE`                                                                     |
| decision request                  | 决策请求                           | `DECISION_REQUEST_TEMPLATE` (Part A)                                                    |
| necessary information request     | 必要信息补全请求                   | Same template (Part B)                                                                  |
| delivery report                   | 交付报告                           | `DELIVERY_REPORT_TEMPLATE`                                                              |
| Owner                             | 人（所有者）/ 所有者               | Also "the human"; not translated as "owner-company"                                     |
| Agent                             | Agent                              | Full-responsibility company; keep "Agent" in Chinese                                    |
| decision-maker                    | 决策者                             | The human's role                                                                        |
| mandatory file                    | 强制文件                           | Records for phases P0–P7                                                                |
| hard gate                         | 硬门                               | A machine or human gate that blocks progress                                            |
| record                            | 记录                               | A process artifact, e.g. P0_intent.md                                                   |
| evidence                          | 证据                               | Proof that can be independently verified                                                |
| evidence package                  | 证据包                             | The evidence set for delivery                                                           |
| multi-view review                 | 多视角审视                         | The four perspectives listed below                                                      |
| product perspective               | 产品视角                           | P6 perspective term                                                                     |
| user perspective                  | 用户视角                           | P6 perspective term                                                                     |
| engineering perspective           | 工程视角                           | P6 perspective term                                                                     |
| adversarial review / perspective  | 对抗性（审查）视角                 | P6 perspective term                                                                     |
| five excellence dimensions        | 优秀五维度                         | 6.1–6.5 (see below)                                                                     |
| sound design                      | 设计合理                           | Dimension 6.1                                                                           |
| complete functionality            | 功能完备                           | Dimension 6.2                                                                           |
| elegant implementation            | 实现优雅                           | Dimension 6.3                                                                           |
| perfect experience                | 体验完美                           | Dimension 6.4                                                                           |
| excellent performance             | 性能优异                           | Dimension 6.5                                                                           |
| autonomy budget                   | 自治预算                           | Contract C7                                                                             |
| decision point                    | 决策点                             | A process term                                                                          |
| proposal                          | 提案                               | Decision-ready material (P2)                                                            |
| intent                            | 意图                               | The object of P0                                                                        |
| definition of done (DoD)          | 完成定义                           | Contract C4                                                                             |
| acceptance                        | 验收                               | A P7 activity                                                                           |
| owner signature / signing         | 签署                               | The user-language copy is authoritative                                                 |
| reliability                       | 可靠                               | Hard requirement one                                                                    |
| excellence                        | 优秀                               | Hard requirement two                                                                    |
| safety and compliance bottom line | 安全与合规底线                     | Constitutional bottom line                                                              |
| assets                            | 资产                               | Deposited reusable outcomes                                                             |
| product DNA                       | 产品 DNA                           | Deposited human preferences and values                                                  |
| run                               | run / 流程实例                     | `.hap/runs/<run-id>/`; in Chinese records, use "run/流程实例", consistent with SKILL.md |
| governance root                   | 治理根                             | The `.hap/` directory                                                                   |
| bilingual pair                    | 双语成对                           | User language (no suffix)                                                               |

## Rules

1. P0–P7, C1–C10, A1–A7…J1–J7, the ★ marker, and version strings are never translated.
2. Within a frozen document's body, a file-name reference points to the same-named file in the same language directory
   (e.g. a reference inside `../../assets/EN/DERIVED_SPECIFICATION.md` to `HUMAN_AGENT_PARADIGM`); the lowercase
   canonical file-name references embedded in the frozen Simplified Chinese original remain unchanged (the content is
   frozen and must not be altered), and the tool copies them to `.hap/docs/` under their canonical lowercase names.
3. Existing English wording already published with code comments, the README (EN), and injected contract text takes
   precedence (e.g. "hard requirement", "multi-view review", "owner-decision contract").
4. The bilingual copies of a record are written in the same round to state the same fact — facts and IDs must match,
   while wording may adjust to each language; **the English copy is for the Agent to read and reason with (always read
   record facts from `records/EN/`)**, and the Chinese copy is for the user (the Owner) to review, approve, and sign.

## Language directories and adding a language

Repository language documents are organized by language directory, language codes uppercase and composite codes
underscored: `../../assets/ZH_CN` (frozen Simplified Chinese originals), `../../assets/EN` (English translations), ``,
`../ZH_CN` — files inside a directory use a plain `<NAME>.md` (uppercase + underscore, no language suffix).

Adding a language:

1. Create a same-named language directory under `../../assets` (e.g. `JA/`; composite codes underscored), and translate
   the documents into plain `<NAME>.md` files inside it;
2. Register it here in this glossary and in the README "Language rules" section before use.
