# Getting Started

[English](../en/getting-started.md) | [简体中文](../zh-CN/getting-started.md)

[Product home](../../README.md) · [Documentation](README.md)

## Install

Choose a published version from [Releases](https://github.com/eaopen/cloudfile-docker/releases), then follow its deployment instructions. The [deployment guide (Chinese)](https://github.com/eaopen/cloudfile-docker/blob/dev/deploy/compose/README.md) explains Compose configuration, domains, persistent data and optional services. The `dev` guide may describe changes beyond your installed version.

## Choose Components

Start with the file platform and add search, enhanced previews, local application access or storage services as needed. Optional services have their own configuration and licenses. See [components](components.md).

Local storage remains a valid choice. RustFS is an optional S3-compatible backend; use only a release that documents support for your deployment. Changing an endpoint does not migrate existing libraries. S3 objects represent Seafile internal data and are not a directly browsable copy of your original files.

## Upgrade Or Migrate

Read the target release notes, back up both databases and file data, and verify restoration before changing an existing installation. Migration from Seafile and imports from historical file stores require a plan suited to the source version, permissions and data volume. [Professional services](services.md) can help with that work.

## Use And Get Help

Begin with a team library, assign library access, and then configure directory restrictions or share individual resources. Search, previews and integrations must respect the same resource permissions. Report questions through [Issues](https://github.com/eaopen/cloudfile/issues) with your installed version and sanitized reproduction steps.
