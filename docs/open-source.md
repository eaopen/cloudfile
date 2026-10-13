# Open Source / 开源与许可

[Product home / 产品首页](../README.md) · [中文首页](../README.zh-CN.md)

[Open source and commercialization principles / 开源与商业化基本原则](principles.md)

CloudFile prioritizes open source and sustainable maintenance through professional services. New independent code prefers Apache 2.0; existing upstream licenses and copyright notices are preserved. A component's own license files govern its use.

CloudFile 坚持开源优先，通过专业服务支持持续维护。新的独立代码优选 Apache 2.0；保留已有上游许可证和版权声明。各组件的实际使用以自身许可证文件为准。

| Component / 组件 | License policy / 许可说明 |
| --- | --- |
| Product home / 产品入口 | [Apache 2.0](../LICENSE) |
| Server | [AGPLv3 with upstream OpenSSL permission; Python directory Apache 2.0 / 保留上游 OpenSSL 附加许可，Python 目录为 Apache 2.0](https://github.com/eaopen/cloudfile-server/blob/dev/LICENSE.txt) |
| Hub | [Apache 2.0; third-party notices also apply / 同时保留第三方声明](https://github.com/eaopen/cloudfile-hub/blob/dev/LICENSE.txt) |
| Docker | [Apache 2.0](https://github.com/eaopen/cloudfile-docker/blob/dev/LICENSE.txt) |
| Local Agent / Chrome Extension | Apache 2.0 for CloudFile-owned code; bundled dependencies retain their licenses / CloudFile 自有代码采用 Apache 2.0，随附依赖保留自身许可 |
| Filestash | AGPLv3; upstream notices preserved / 保留上游声明 |
| Filestash OIDC | [MIT](https://github.com/eaopen/filestash-auth-oidc/blob/main/LICENSE) |
| RustFS / Fileview | Apache 2.0; consult the selected distribution / 请核对所选发行包 |

Apache 2.0 is not a relicensing of AGPL-derived code. A plugin, separate repository or container does not by itself remove applicable license obligations. Customer-specific integrations follow their code provenance, applicable licenses and contract terms.

Apache 2.0 不代表对 AGPL 派生代码重新许可。插件、独立仓库或容器本身不会免除适用的许可义务。客户专属集成按代码来源、适用许可证及合同约定处理。

We thank Seafile, RustFS, Filestash, Meilisearch and the wider open-source community. CloudFile aims to contribute useful fixes and general improvements upstream, respect maintainers' product boundaries and avoid unauthorized proprietary code. Each upstream project retains its own identity and trademarks.

感谢 Seafile、RustFS、Filestash、Meilisearch 及开源社区。CloudFile 力所能及地回馈通用修复与改进，尊重上游维护者的产品边界，不使用未经授权的专有代码。上游项目保留各自品牌和商标。

References / 参考：[Apache 2.0](https://www.apache.org/licenses/LICENSE-2.0) · [GNU AGPLv3](https://www.gnu.org/licenses/agpl-3.0.html).
