# 企业 API 接入

[English](../en/enterprise-api.md) | [简体中文](../zh-CN/enterprise-api.md)

[产品首页](../../README.zh-CN.md) · [文档导航](README.md)

业务系统经认证文件 API 和可选嵌入视图接入。客户流程、业务身份及项目映射留在适配层，由 CloudFile 执行文件授权和发布规则。

## 接入模型

`业务系统 → 业务适配 → CloudFile Hub API → 文件核心`

| 领域 | 接入用途 |
| --- | --- |
| 资源 | 库目录文件引用，保留实例及根作用域 |
| 文件 | 上传下载、历史及获准操作 |
| 权限 | 有效权限、库授权、目录 ACL 与分享 |
| 发现 | 搜索、标签、预览与可用动作 |
| 会话与任务 | 本地会话、提交回执与任务状态 |

本表说明接入领域，不新增接口契约。路径、字段、认证与开关以 [Hub API 参考](https://github.com/eaopen/cloudfile-hub/blob/dev/docs/API.md)为准，使用与安装版本匹配的说明；草案及开发分支接口可能变化。

## 作用域与安全

初始化目录只选择起始视图，不强制限定根。只有所选版本在列表、搜索、预览、历史、下载与写入上共同限定范围，才能声明子树隔离。资源键与菜单显隐属于导航，不是授权。

采用发行版本支持的认证与短期访问机制，前端配置及 URL 不保存令牌和存储凭据。服务端回执确认后才能标记提交完成；结果不明的操作按已定义的幂等与恢复机制处理。

技术导航：[Hub 扩展](https://github.com/eaopen/cloudfile-hub/blob/dev/docs/EXTENSIONS.md)、[跨层 ACL 契约](https://github.com/eaopen/cloudfile-docker/blob/dev/docs/acl-semantics.md)、[Agent](https://github.com/eaopen/cloudfile-local-agent/blob/dev/README.zh-CN.md)。

上述参考之外的演示接口不等于 CloudFile 已发布接口。
