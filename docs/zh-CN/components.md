# 组件导航

[English](../en/components.md) | [简体中文](../zh-CN/components.md)

[产品首页](../../README.zh-CN.md) · [文档导航](README.md)

按部署需要选用组件。本页说明组件用途，不代表每个发行版本都支持所有组合。

| 组件 | 用途 |
| --- | --- |
| [CloudFile](https://github.com/eaopen/cloudfile) | 产品入口与用户反馈 |
| [Docker](https://github.com/eaopen/cloudfile-docker/blob/dev/README.zh-CN.md) | 安装、部署与发行 |
| [Hub](https://github.com/eaopen/cloudfile-hub/blob/dev/README.zh-CN.md) | Web 界面与 API |
| [Server](https://github.com/eaopen/cloudfile-server/blob/dev/README.zh-CN.md) | 文件核心、存储与权限执行 |
| [Local Agent](https://github.com/eaopen/cloudfile-local-agent/blob/dev/README.zh-CN.md) | 可选本地应用助手 |
| [Chrome Extension](https://github.com/eaopen/cloudfile-chrome-extension/blob/dev/README.zh-CN.md) | 浏览器与本地助手连接 |
| [Fileview](https://github.com/eaopen/eap-fileview) | 可选增强预览 |
| [Filestash](https://github.com/eaopen/cloudfile-filestash) | 可选外部文件访问 |
| [Showcase](https://github.com/eaopen/cloudfile-showcase/blob/main/README.zh-CN.md) | 展示门户与接入样例 |
| [Filestash OIDC](https://github.com/eaopen/filestash-auth-oidc/blob/main/README.zh-CN.md) | OIDC 认证集成 |

存储可选择本地文件系统，或所选发行版本已验证的 S3 兼容服务。[RustFS](https://github.com/rustfs/rustfs) 集成仍在验证，分支后端测试不代表生产迁移已受支持。存储服务、外部文件浏览、预览和本地 Agent 按需组合；权限、搜索、AI 文件工作流与企业 API 是产品能力方向，具体支持范围以安装版本为准。
