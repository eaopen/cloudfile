# CloudFile

[English](README.md) | [简体中文](README.zh-CN.md)

**An open-source file management and collaboration platform for enterprise integration.**

Built on Seafile Community Edition, CloudFile brings file libraries, sharing, version history and enterprise integration into one platform. Use it on your own infrastructure and connect it to the systems your team already uses.

## What You Can Do

- Organize team files in libraries, share resources and retain version history.
- Manage library access, restrict directories within a library and use the sharing modes supported by your release.
- Add search with Meilisearch and connect optional AI services for supported file workflows.
- Extend online previews and open files with local applications through optional companion components.
- Connect business systems through APIs and choose local or compatible S3 storage for your deployment.

Available features depend on the installed release and configured components. Follow that release's documentation before enabling optional services.

[Product documentation](docs/en/README.md) · [Roadmap](docs/en/roadmap.md) · [AI direction](docs/en/ai-strategy.md)

## Get Started

[Installation and upgrades](docs/en/getting-started.md) · [Components](docs/en/components.md) · [Professional services](docs/en/services.md)

Start with the [deployment guide (Chinese)](https://github.com/eaopen/cloudfile-docker/blob/dev/deploy/compose/README.md). Download published packages from [CloudFile releases](https://github.com/eaopen/cloudfile-docker/releases); use the documentation matching your selected release.

This repository is the **CloudFile product home**. Deployment recipes and release artifacts are maintained in `cloudfile-docker`; component source code stays in its own repository.

## Help And Community

Use [Issues](https://github.com/eaopen/cloudfile/issues) for questions, feature requests and reproducible problems. Include your version and a sanitized description; never include passwords, access tokens or private customer files. Code contributions belong in the relevant [component repository](docs/en/components.md).

## Open Source And Services

[CloudFile Open Source And Commercialization Principles](docs/en/principles.md)

CloudFile prioritizes open source. The software is free to use under its applicable licenses; consulting, implementation, migration, customization and support are available as professional services. Customer-specific integrations can be maintained separately while reusable improvements return to the public product.

New independent CloudFile projects prefer Apache 2.0. Existing upstream licenses remain in force, including AGPLv3 for the Server core and Filestash, and MIT for the OIDC plugin. See [licensing and upstream acknowledgements](docs/en/open-source.md). CloudFile is independently maintained and is not an official Seafile edition.

This product-home repository is licensed under [Apache 2.0](LICENSE).
