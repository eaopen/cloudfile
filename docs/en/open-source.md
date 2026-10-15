# Open Source

[English](../en/open-source.md) | [简体中文](../zh-CN/open-source.md)

[Product home](../../README.md) · [Documentation](README.md)

[Open source and commercialization principles](principles.md)

CloudFile prioritizes open source and sustainable maintenance through professional services. New independent code prefers Apache 2.0; existing upstream licenses and copyright notices are preserved. A component's own license files govern its use.

| Component | License policy |
| --- | --- |
| Product home | [Apache 2.0](../../LICENSE) |
| Server | [AGPLv3 with upstream OpenSSL permission; Python directory Apache 2.0](https://github.com/eaopen/cloudfile-server/blob/dev/LICENSE.txt) |
| Hub | [Apache 2.0; third-party notices also apply](https://github.com/eaopen/cloudfile-hub/blob/dev/LICENSE.txt) |
| Docker | [Apache 2.0](https://github.com/eaopen/cloudfile-docker/blob/dev/LICENSE.txt) |
| Local Agent / Chrome Extension | Apache 2.0 for CloudFile-owned code; bundled dependencies retain their licenses |
| Filestash | AGPLv3; upstream notices preserved |
| Filestash OIDC | [MIT](https://github.com/eaopen/filestash-auth-oidc/blob/main/LICENSE) |
| RustFS / Fileview | Apache 2.0; consult the selected distribution |

Apache 2.0 is not a relicensing of AGPL-derived code. A plugin, separate repository or container does not by itself remove applicable license obligations. Customer-specific integrations follow their code provenance, applicable licenses and contract terms.

We thank Seafile, RustFS, Filestash, Meilisearch and the wider open-source community. CloudFile aims to contribute useful fixes and general improvements upstream, respect maintainers' product boundaries and avoid unauthorized proprietary code. Each upstream project retains its own identity and trademarks.

References: [Apache 2.0](https://www.apache.org/licenses/LICENSE-2.0) · [GNU AGPLv3](https://www.gnu.org/licenses/agpl-3.0.html).
