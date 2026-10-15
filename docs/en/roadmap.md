# Roadmap

[English](../en/roadmap.md) | [简体中文](../zh-CN/roadmap.md)

[Product home](../../README.md) · [Documentation](README.md)

Direction updated 2026-10-13. Priorities are public; dates, future version numbers and planned integrations are not release commitments. Experimental optional features may remain disabled while a reliable core is released.

## Delivery Stages

| Stage | Focus | Exit criteria |
| --- | --- | --- |
| Current integration | File compatibility, Windows/macOS Agent, browser bridge and editing recovery | Installed desktop-to-server workflows, conflict handling, upgrades and recovery verified |
| Enterprise foundation | Permissions and scoped sharing, stable APIs, embedded browsing, search consistency | Cross-entry authorization and a reproducible business integration |
| Composable release | Optional S3/RustFS, previews, external references and basic AI integration | Documented installation, upgrade and restore; optional components fail independently |
| Ecosystem | SDKs, migration, diagnostics, reusable adapters and selective AI automation | Public source and examples can be independently built, deployed and maintained |

The v0.8 work is a development candidate in the current integration stage. The v0.9 scope now includes directory access without library membership, shared directories with default read access adjusted by directory permissions, shared-directory listing and address access APIs, and delegated directory management APIs. Sharing configuration will extend the existing directory permissions UI; no delegated-management UI is planned. Integrating applications provide the business directory list and URL handling. This scope is planned, not delivered or assigned a release date; v1.0 remains unscheduled. A stable milestone requires deployability, upgrades and recovery rather than completion of every optional feature.

## Long-Term Direction

| Horizon | Durable value | Development direction |
| --- | --- | --- |
| Foundation | Reliable files, access and versions | Delivery quality, professional editing and public integration contracts |
| Knowledge access | Authorized, traceable information | Parsing, OCR, hybrid retrieval and source-version citations |
| Controlled execution | Reversible, accountable business outcomes | AI proposals, review, constrained operations and audit |
| Multi-source growth | Useful access without mandatory central migration | Authorized reference access, rebuildable projections and scale-driven federation |

The long-term 2026–2031 perspective is a planning horizon, not annual delivery promises. Cluster high availability, complex federation and CAD geometry understanding depend on demonstrated demand and validated components.

[AI direction](ai-strategy.md) · [Current adoption limits](capabilities.md)
