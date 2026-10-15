# Documentation Audience / 文档受众

This is the public CloudFile product home for customers and users. Maintain English and Chinese content. Focus on product value, available capabilities, installation and usage guidance, licensing, and professional services.

本仓库是面向客户与使用者的 CloudFile 公开产品入口。维护英文和中文内容，重点说明产品价值、可用能力、安装使用、许可与专业服务。

Do not publish internal management records, development plans, progress logs, acceptance evidence, customer-specific information or private repository dependencies here. Describe limitations only as needed for users to choose and use the product accurately. Keep developer implementation details in the appropriate component reference or internal records.

不要在此发布内部管理记录、研发计划、进度日志、验收证据、客户专属信息，也不要让使用说明依赖私有仓库。能力限制仅按帮助用户正确选用产品所需的程度说明。开发实现细节归入相应组件技术参考或内部记录。

Before adapting internal material, extract confirmed user-facing conclusions and remove internal or confidential details. Public documentation must stand on its own.

将内部材料转为公开内容前，提炼已确认且面向使用者的结论，去除内部与保密信息。公开文档必须能够独立阅读。

## Language Editions / 语言版本

Keep public product prose in separate `docs/en/` and `docs/zh-CN/` files with matching names and sections. `README.md` is English; `README.zh-CN.md` is Simplified Chinese. Each translated page links to its counterpart and stays within its language for local navigation. Update both editions in the same change; identify untranslated references explicitly. Old `docs/*.md` paths are compatibility language selectors, not duplicate bodies.

公开产品正文分别维护在 `docs/en/` 与 `docs/zh-CN/`，文件名与章节对应；根 README 分为英文与简体中文。页面提供语言切换，站内导航保持所选语言。同一变更同步两版，未翻译参考资料明确标注原文语言；旧路径仅保留兼容导航，不再复制正文。
