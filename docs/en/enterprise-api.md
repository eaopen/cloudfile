# Enterprise Integration

[English](../en/enterprise-api.md) | [简体中文](../zh-CN/enterprise-api.md)

[Product home](../../README.md) · [Documentation](README.md)

Business systems connect through authenticated file APIs and optional embedded views. Keep customer workflows, business identities and project mappings in an adapter; let CloudFile enforce file access and publishing rules.

## Integration Model

`Business system → business adapter → CloudFile Hub API → file core`

| Area | Integration purpose |
| --- | --- |
| Resources | Library, directory and file references; preserve instance and root scope |
| Files | Upload, download, history and permitted file operations |
| Permissions | Effective access, library grants, directory ACL and sharing |
| Discovery | Search, tags, preview and available actions |
| Sessions and tasks | Local application sessions, submission receipts and task states |

This table describes integration areas, not a new API contract. Paths, fields, authentication and feature flags are defined in [Hub API reference (Chinese)](https://github.com/eaopen/cloudfile-hub/blob/dev/docs/API.md). Use the reference matching your installed version. Draft interfaces and development branches can change.

## Scope And Security

An initial folder selects the starting view; it does not enforce a restricted root. Do not claim subtree isolation unless the chosen release enforces it across listing, search, preview, history, downloads and writes. Resource keys and hidden menus are navigation, not authorization.

Use the authentication and short-lived access mechanisms supported by the release. Keep tokens and storage credentials out of front-end configuration and URLs. Check server receipts before marking submission complete; use documented idempotency and recovery mechanisms for operations with uncertain outcomes.

Technical navigation: [Hub extensions (Chinese)](https://github.com/eaopen/cloudfile-hub/blob/dev/docs/EXTENSIONS.md), [shared ACL contract (Chinese)](https://github.com/eaopen/cloudfile-docker/blob/dev/docs/acl-semantics.md), [Agent](https://github.com/eaopen/cloudfile-local-agent).

Demonstration endpoints described outside these references are not released CloudFile interfaces.
