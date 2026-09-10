# Human-Agent Paradigm

The **governance content package** of the Human-Agent Paradigm (HAP): six frozen governance documents and their
structural self-check tool, published as a standalone npm package so that the content.

**English** | [简体中文](docs/ZH_CN/README.md)

## Contents

| Path            | Purpose                                                                                                                                                                                                                                                                                                             |
|:----------------|:--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `assets/ZH_CN/` | The six governance documents (Simplified Chinese originals): `HUMAN_AGENT_PARADIGM.md` (Constitution v1.0), `DERIVED_SPECIFICATION.md` (Derived Specification v1.0), `CONFORMANCE_CHECKLIST.md` (Conformance Checklist v1.0), `CONTRACT_TEMPLATE.md`, `DECISION_REQUEST_TEMPLATE.md`, `DELIVERY_REPORT_TEMPLATE.md` |
| `assets/EN/`    | The official English translations of the same six documents                                                                                                                                                                                                                                                         |

## Usage

Consumers copy the `assets/` language directory into the governance root of their own workspace. Standalone use.

## Version strategy

| Content version                               | Package version         | Trigger                  |
|:----------------------------------------------|:------------------------|:-------------------------|
| Constitution v1.0                             | 1.0.0 (baseline)        | Initial release          |
| Constitution amendment (major)                | major increment         | New constitution version |
| Derived spec / checklist / template revisions | minor / patch increment | Derived-family edits     |

The constitution version governs, and the package version follows it. Any content revision must be explicitly approved
by the Owner within a HAP run (Constitution §0.4, Derived Specification §0.4). Tool-only changes to the self-check tool
do not change the governance content.

## Governance

This repository is governed by its own content (the HAP Constitution). Revisions happen through a HAP run with the
Owner's signature; publishing is an Owner-authorized action.
