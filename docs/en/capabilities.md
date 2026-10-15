# Capabilities

[English](../en/capabilities.md) | [简体中文](../zh-CN/capabilities.md)

[Product home](../../README.md) · [Documentation](README.md)

This describes product areas as of 2026-10-13, not a support matrix for a particular release. Consult the selected release's configuration and compatibility notes before deployment.

| Area | What users gain | Adoption boundary |
| --- | --- | --- |
| Files and versions | Libraries, uploads, downloads, history and sharing | Based on Seafile CE; verify the release's supported entry points |
| Enterprise permissions | Library access, directory rules and scoped collaboration | ACL and sharing vary by entry point and release; scoped sharing is not unrestricted library access |
| Identity and APIs | Enterprise login and business integration | IdP claims and adapters require configuration; not every draft API is stable |
| Search and metadata | File discovery, descriptions and tags | Optional index service; name/tag search does not guarantee full text for every format |
| Previews | Native previews and optional enhanced formats | eap-fileview requires separate configuration; format support follows its version |
| Local applications | Open files in professional desktop software | Platform and package support differ; local save becomes a server version only after successful submission |
| Controlled local editing | Checkout, submission, recovery and task visibility | Development candidates require desktop-to-server validation; not enabled by a roadmap entry |
| Storage | Local per-library placement and compatible S3 classes | RustFS branch-level backend checks are not production migration certification |
| External references | Optional read-only browsing without mandatory bulk migration | Source authorization and root isolation require separate verification |
| AI | Optional AI-assisted workflows | Configuration exists; permission-aware knowledge access and automation remain development directions |

For technical status and evidence, see the [component capability matrix (Chinese)](https://github.com/eaopen/cloudfile-docker/blob/dev/docs/feature-matrix.md). That development snapshot does not override a released package's support scope.
