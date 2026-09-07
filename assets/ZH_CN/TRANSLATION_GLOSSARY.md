# 翻译术语表 — 治理术语（EN ↔ 中文）

> English version: [TRANSLATION_GLOSSARY.md](../EN/TRANSLATION_GLOSSARY.md)

治理层文档（`assets/` 下六份冻结文档及其官方译本、以及由它们驱动的流程记录）翻译与一致性审校的统一基准。翻译或审校任何治理材料时使用下列对应关系；新增行须说明理由，并保持表格按英文术语排序。

| English                           | 中文                               | 语境/备注                                                            |
|:----------------------------------|:-----------------------------------|:---------------------------------------------------------------------|
| Human-Agent Paradigm (HAP)        | 人机协作范式 / 人与 Agent 协作范式 | 专有名词；产品名                                                     |
| constitution                      | 宪法                               | 唯一权威文档：`assets/ZH_CN/HUMAN_AGENT_PARADIGM.md`                 |
| derived specification             | 派生规范                           | `DERIVED_SPECIFICATION`                                              |
| conformance self-check checklist  | 符合性自检清单                     | `CONFORMANCE_CHECKLIST`                                              |
| contract                          | 契约                               | 已签署的 C1–C10 契约                                                 |
| contract template                 | 契约模板                           | `CONTRACT_TEMPLATE`                                                  |
| decision request                  | 决策请求                           | `DECISION_REQUEST_TEMPLATE`（Part A）                                |
| necessary information request     | 必要信息补全请求                   | 同一模板（Part B）                                                   |
| delivery report                   | 交付报告                           | `DELIVERY_REPORT_TEMPLATE`                                           |
| Owner                             | 人（所有者）/ 所有者               | 也称 “the human”；不译作“owner-company”                              |
| Agent                             | Agent                              | 全责公司；中文语境保留 “Agent”                                       |
| decision-maker                    | 决策者                             | 人的角色                                                             |
| mandatory file                    | 强制文件                           | P0–P7 阶段记录                                                       |
| hard gate                         | 硬门                               | 阻止推进的机器或人工门禁                                             |
| record                            | 记录                               | 流程产物，如 P0_intent.md                                            |
| evidence                          | 证据                               | 可独立复核的证明                                                     |
| evidence package                  | 证据包                             | 交付用证据集                                                         |
| multi-view review                 | 多视角审视                         | 下述四个视角                                                         |
| product perspective               | 产品视角                           | P6 视角词                                                            |
| user perspective                  | 用户视角                           | P6 视角词                                                            |
| engineering perspective           | 工程视角                           | P6 视角词                                                            |
| adversarial review / perspective  | 对抗性（审查）视角                 | P6 视角词                                                            |
| five excellence dimensions        | 优秀五维度                         | 6.1–6.5（见下）                                                      |
| sound design                      | 设计合理                           | 维度 6.1                                                             |
| complete functionality            | 功能完备                           | 维度 6.2                                                             |
| elegant implementation            | 实现优雅                           | 维度 6.3                                                             |
| perfect experience                | 体验完美                           | 维度 6.4                                                             |
| excellent performance             | 性能优异                           | 维度 6.5                                                             |
| autonomy budget                   | 自治预算                           | 契约 C7                                                              |
| decision point                    | 决策点                             | 流程术语                                                             |
| proposal                          | 提案                               | 可决策材料（P2）                                                     |
| intent                            | 意图                               | P0 对象                                                              |
| definition of done (DoD)          | 完成定义                           | 契约 C4                                                              |
| acceptance                        | 验收                               | P7 活动                                                              |
| owner signature / signing         | 签署                               | 以用户语言副本为准                                                   |
| reliability                       | 可靠                               | 硬性要求一                                                           |
| excellence                        | 优秀                               | 硬性要求二                                                           |
| safety and compliance bottom line | 安全与合规底线                     | 宪法底线                                                             |
| assets                            | 资产                               | 沉淀的可复用成果                                                     |
| product DNA                       | 产品 DNA                           | 沉淀的人偏好与价值观                                                 |
| run                               | run / 流程实例                     | `.hap/runs/<run-id>/`；中文记录中与 SKILL.md 一致使用 “run/流程实例” |
| governance root                   | 治理根                             | `.hap/` 目录                                                         |
| bilingual pair                    | 双语成对                           | 用户语言（无后缀）                                                   |

## 规则

1. P0–P7、C1–C10、A1–A7…J1–J7、★ 标记与版本串一律不翻译。
2. 冻结文档正文内的文件名引用指向同一语言目录下的同名文件（例如 `assets/EN/DERIVED_SPECIFICATION.md` 内引用
   `HUMAN_AGENT_PARADIGM`）；冻结中文原文正文内嵌的规范小写文件名引用保持原样（内容冻结不可改），工具复制到 `.hap/docs/`
   时使用规范小写名。
3. 已随代码注释、README（EN）与注入契约文本发布的既有英文措辞优先（如 “hard requirement”、“multi-view review”、“owner-decision
   contract”）。
4. 记录的双语副本同轮书写同一事实——事实与 ID 必须一致，措辞可随语言调整； **英文副本供 Agent 读取与推理（Agent 读取记录事实一律读
   `records/EN/`）**，中文副本供用户（所有者）审批阅读与签署。

## 语言目录与新增语言

仓库语言文档按语言分目录，语言码大写、复合码用下划线：`assets/ZH_CN/`（冻结中文原文）、`assets/EN/`（英文译本）、`docs/EN/`、
`docs/ZH_CN/`——目录内文件名为纯 `<NAME>.md`（大写+下划线连接，无语言后缀）。

新增语言：

1. 在 `assets/` 下建立同名语言目录（如 `JA/`；复合码用下划线），把文档译为目录内纯 `<NAME>.md`；
2. 使用前在本术语表与 README「语言规则」节登记。
