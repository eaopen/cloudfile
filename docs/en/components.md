# Components

[English](../en/components.md) | [简体中文](../zh-CN/components.md)

[Product home](../../README.md) · [Documentation](README.md)

Choose the components needed for your deployment. This directory describes their roles; it does not promise that every combination is supported by every release.

| Component | Purpose |
| --- | --- |
| [CloudFile](https://github.com/eaopen/cloudfile) | Product home and user feedback |
| [Docker](https://github.com/eaopen/cloudfile-docker) | Installation, deployment and releases |
| [Hub](https://github.com/eaopen/cloudfile-hub) | Web interface and APIs |
| [Server](https://github.com/eaopen/cloudfile-server) | File core, storage and permission enforcement |
| [Local Agent](https://github.com/eaopen/cloudfile-local-agent) | Optional local application companion |
| [Chrome Extension](https://github.com/eaopen/cloudfile-chrome-extension) | Browser-to-Agent bridge |
| [Fileview](https://github.com/eaopen/eap-fileview) | Optional enhanced previews |
| [Filestash](https://github.com/eaopen/cloudfile-filestash) | Optional external file access |
| [Showcase](https://github.com/eaopen/cloudfile-showcase) | Demonstration portal and integration example |
| [Filestash OIDC](https://github.com/eaopen/filestash-auth-oidc) | OIDC authentication integration |

Storage can use local filesystems or an S3-compatible service validated for the selected release. [RustFS](https://github.com/rustfs/rustfs) integration is under validation; branch-level backend tests do not establish production migration support. Storage, external file browsing, previews and the local Agent are optional components. Permissions, search, AI-assisted file workflows and enterprise APIs are product capability areas; availability follows the installed release.
