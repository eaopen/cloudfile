# AI Strategy

[English](../en/ai-strategy.md) | [简体中文](../zh-CN/ai-strategy.md)

[Product home](../../README.md) · [Documentation](README.md)

CloudFile aims to make enterprise files trustworthy resources for AI and business systems. Model quality alone cannot determine the authorized user, effective version, business context or approved action. Files, permissions, provenance and integration contracts remain long-term product investments.

## Planned Capabilities

| Capability | Required result |
| --- | --- |
| Parsing and extraction | Derived text, fields and summaries linked to a source version |
| Permission-aware retrieval | Candidates and returned citations respect current authorization |
| Traceable answers | Identify file, version and passage; stale results are invalidated |
| Business context | Connect external business references without replacing ERP/PLM models |
| Controlled actions | Limited credentials, server checks, review when needed and recoverable results |
| Multiple sources | Source authorization, explicit roots and rebuildable indexes |

## Integration Approach

Reuse Seafile AI where suitable and evaluate independent parsers, search engines and RAG/Agent services through adapters. Docling, RAGFlow and Paperless-ngx are research candidates, not promised integrations. Compare actual supported formats, deployment cost, licensing, source citations, revocation behavior and failure recovery before selection. Learn from open-source competitors' public designs while respecting their licenses.

Start with read-only extraction and retrieval, then reviewed metadata suggestions, then limited execution. AI outputs and indexes remain derived data; they do not replace original files, authoritative permissions or human approval of formal business results. Sensitive file content must follow the organization's model deployment and data-access policy.

Success is measured by task completion, usable citations, authorization correctness and reduced manual work. CAD/3D starts with attributes, previews and extractable text; geometry and BOM understanding require suitable professional parsers and real use cases.
