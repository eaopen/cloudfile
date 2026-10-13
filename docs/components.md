# Components / 组件导航

[Product home / 产品首页](../README.md) · [中文首页](../README.zh-CN.md)

Choose the components needed for your deployment. This directory describes their roles; it does not promise that every combination is supported by every release.

按部署需要选用组件。本页说明组件用途，不代表每个发行版本都支持所有组合。

| Component / 组件 | Purpose / 用途 |
| --- | --- |
| [CloudFile](https://github.com/eaopen/cloudfile) | Product home and user feedback / 产品入口与用户反馈 |
| [Docker](https://github.com/eaopen/cloudfile-docker) | Installation, deployment and releases / 安装、部署与发行 |
| [Hub](https://github.com/eaopen/cloudfile-hub) | Web interface and APIs / Web 界面与 API |
| [Server](https://github.com/eaopen/cloudfile-server) | File core, storage and permission enforcement / 文件核心、存储与权限执行 |
| [Local Agent](https://github.com/eaopen/cloudfile-local-agent) | Optional local application companion / 可选本地应用助手 |
| [Chrome Extension](https://github.com/eaopen/cloudfile-chrome-extension) | Browser-to-Agent bridge / 浏览器与本地助手连接 |
| [Fileview](https://github.com/eaopen/eap-fileview) | Optional enhanced previews / 可选增强预览 |
| [Filestash](https://github.com/eaopen/cloudfile-filestash) | Optional external file access / 可选外部文件访问 |
| [Filestash OIDC](https://github.com/eaopen/filestash-auth-oidc) | OIDC authentication integration / OIDC 认证集成 |

Storage can use local filesystems or a supported S3-compatible service such as [RustFS](https://github.com/rustfs/rustfs). Storage, external file browsing, previews and the local Agent are optional components. Permissions, search, AI-assisted file workflows and enterprise APIs are product capability areas; availability follows the installed release.

存储可选择本地文件系统，或发行版本支持的 S3 兼容服务，例如 [RustFS](https://github.com/rustfs/rustfs)。存储服务、外部文件浏览、预览和本地 Agent 按需组合；权限、搜索、AI 文件工作流与企业 API 是产品能力方向，具体支持范围以安装版本为准。
