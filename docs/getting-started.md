# Getting Started / 开始使用

[Product home / 产品首页](../README.md) · [中文首页](../README.zh-CN.md)

## Install / 安装

Choose a published version from [Releases](https://github.com/eaopen/cloudfile-docker/releases), then follow its deployment instructions. The [deployment guide](https://github.com/eaopen/cloudfile-docker/blob/dev/deploy/compose/README.md) explains Compose configuration, domains, persistent data and optional services. The `dev` guide may describe changes beyond your installed version.

从 [Releases](https://github.com/eaopen/cloudfile-docker/releases) 选择已发布版本，按该版本说明安装。[部署指南](https://github.com/eaopen/cloudfile-docker/blob/dev/deploy/compose/README.md)介绍 Compose 配置、域名、持久化数据及可选服务；`dev` 文档可能包含已安装版本尚未提供的内容。

## Choose Components / 选择组件

Start with the file platform and add search, enhanced previews, local application access or storage services as needed. Optional services have their own configuration and licenses. See [components](components.md).

先部署文件平台，再按需增加搜索、增强预览、本地应用访问或存储服务。可选服务有各自的配置和许可证，见[组件导航](components.md)。

Local storage remains a valid choice. RustFS is an optional S3-compatible backend; use only a release that documents support for your deployment. Changing an endpoint does not migrate existing libraries. S3 objects represent Seafile internal data and are not a directly browsable copy of your original files.

本地存储仍是可选方案。RustFS 作为可选 S3 兼容后端使用，请选择明确支持目标部署方式的发行版本。修改 endpoint 不会自动迁移已有资料库。S3 中保存的是 Seafile 内部对象，不是可直接浏览的原始文件目录。

## Upgrade Or Migrate / 升级与迁移

Read the target release notes, back up both databases and file data, and verify restoration before changing an existing installation. Migration from Seafile and imports from historical file stores require a plan suited to the source version, permissions and data volume. [Professional services](services.md) can help with that work.

升级前阅读目标版本说明，同时备份数据库和文件数据，并验证恢复。Seafile 升级和历史资料导入需要结合原版本、权限与数据规模制定方案，可通过[专业服务](services.md)协助实施。

## Use And Get Help / 使用与求助

Begin with a team library, assign library access, and then configure directory restrictions or share individual resources. Search, previews and integrations must respect the same resource permissions. Report questions through [Issues](https://github.com/eaopen/cloudfile/issues) with your installed version and sanitized reproduction steps.

从团队资料库开始，分配库访问权限，再设置库内目录限制或分享指定资源。搜索、预览和集成访问应遵循同一资源权限。遇到问题可通过 [Issues](https://github.com/eaopen/cloudfile/issues) 提供安装版本和脱敏后的复现步骤。
