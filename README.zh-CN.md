# CloudFile

[English](README.md) | [简体中文](README.zh-CN.md)

**免费开源、面向企业集成的文件管理与协作平台。**

CloudFile 基于 Seafile Community Edition，将文件库、分享、版本管理与企业集成连接起来。支持自主部署，并与团队现有业务系统组合使用。

## 可以用来做什么

- 用资料库组织团队文件，协作分享并保留版本历史。
- 管理库访问权限、库内目录权限，并向没有库权限的人分享指定资源。
- 按需配置 Meilisearch 搜索，为受支持的文件工作流接入可选 AI 服务。
- 通过可选组件增强在线预览，调用本地专业软件打开文件。
- 通过 API 对接业务系统，根据部署需求选择本地或兼容 S3 的存储。

具体能力取决于所安装的发行版本与组件配置。启用可选服务前，请阅读对应版本的说明。

## 开始使用

[安装与升级](docs/getting-started.md) · [组件导航](docs/components.md) · [专业服务](docs/services.md)

从[部署指南](https://github.com/eaopen/cloudfile-docker/blob/dev/deploy/compose/README.md)开始，在 [CloudFile Releases](https://github.com/eaopen/cloudfile-docker/releases) 获取已发布制品，并使用所选版本对应的文档。

本仓库是 **CloudFile 产品总入口**。部署配方和发布制品由 `cloudfile-docker` 维护，各组件源码仍保留在自己的仓库中。

## 帮助与社区

使用 [Issues](https://github.com/eaopen/cloudfile/issues) 提问、建议功能或反馈可复现的问题。请提供版本和脱敏后的现象，不要提交密码、访问令牌或客户私有文件。代码贡献请提交到相应的[组件仓库](docs/components.md)。

## 开源与服务

[CloudFile 开源与商业化基本原则](docs/principles.md)

CloudFile 坚持开源优先，软件按适用许可证免费使用，通过咨询、实施、迁移、定制开发和技术支持服务持续发展。客户专属集成可独立维护，具有通用价值的改进回到公开产品。

新的独立 CloudFile 项目优选 Apache 2.0。已有上游许可证保持有效，包括 Server 核心及 Filestash 的 AGPLv3，以及 OIDC 插件的 MIT。详见[开源许可与上游致谢](docs/open-source.md)。CloudFile 独立维护，不是 Seafile 官方版本。

本产品入口仓库采用 [Apache 2.0](LICENSE)。
