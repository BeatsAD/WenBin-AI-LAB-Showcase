# Security Policy / 安全政策

## Supported content / 支持范围

Security fixes are maintained for the latest content on `main`. This public repository contains documentation, images, and GitHub collaboration configuration. It does not contain the website application source or deployment credentials. Repository maintenance is handled by [BeatsAD](https://github.com/BeatsAD).

安全修正针对 `main` 分支的最新内容。本公开仓库包含文档、图片及 GitHub 协作配置，不包含网站应用源码或部署凭据。仓库由 [BeatsAD](https://github.com/BeatsAD) 维护。

## Report privately / 私密报告

Use [Report a vulnerability](https://github.com/BeatsAD/WenBin-AI-LAB-Showcase/security/advisories/new) to contact the maintainer privately through GitHub. Do not put secrets, personal information, or unpublished exploit details in public issues, pull requests, or screenshots.

请通过 GitHub 的 [Report a vulnerability](https://github.com/BeatsAD/WenBin-AI-LAB-Showcase/security/advisories/new) 私密联系维护者。不要在公开 Issue、PR 或截图中提交密钥、个人信息或尚未披露的漏洞利用细节。

Include the affected URL or repository path, relevant commit or date, a minimal reproduction, expected and actual behavior, and potential impact. Redact all credentials and personal data. If the private reporting form is unavailable, wait until it is available; do not publish sensitive details as a workaround.

报告请包含受影响的网址或仓库路径、相关提交或日期、最小复现步骤、预期与实际行为及潜在影响，并遮盖凭据和个人数据。如果私密报告入口暂不可用，请等待入口恢复，不要改为公开提交敏感细节。

The maintainer will assess the report and coordinate remediation and disclosure through the private advisory. No fixed response or resolution time is promised.

维护者会在私密报告中评估问题，并协商修复和披露安排。目前不承诺固定响应或修复时间。

## System boundary and trust / 系统边界与信任

Public Markdown, images, links, and proposed contributions can be read or submitted by untrusted parties. Maintainers control changes to `main` and repository settings. The public website and its private source repository are separate surfaces; this policy does not establish their internal implementation or security controls.

公开 Markdown、图片、链接及贡献内容可能由不可信的访问者读取或提交。维护者控制 `main` 分支变更及仓库设置。公开网站及其私有源码仓库是独立的系统，本政策不声明其内部实现或安全控制已得到验证。

## Security properties / 安全要求

- Public files and revision history must not disclose credentials, private configuration, personal data, or confidential source material.
- Documentation must not direct visitors to credential theft, malicious downloads, or commands that expose their data.
- Changes to documentation, assets, and GitHub configuration must be reviewed before integration.
- Reports and reproduction materials must minimize exposure of sensitive information.

- 公开文件和版本历史不得泄露凭据、私有配置、个人数据或保密源码资料。
- 文档不得引导访问者进入凭据窃取页面、恶意下载或执行泄露数据的命令。
- 文档、素材和 GitHub 配置变更应在合入前核查。
- 报告及复现材料应尽量减少敏感信息暴露。

## What to report / 可报告的问题

Report exposed secrets or private data, malicious or compromised links and assets, and configuration problems with a concrete security impact. Describe realistic exposure and impact; severity is assessed from evidence rather than the issue title alone. A suspected issue affecting the linked public website may also be submitted privately for maintainer triage, even though its source is absent here.

可报告密钥或私密数据泄露、恶意或被篡改的链接与素材，以及具有具体安全影响的配置问题。请说明实际暴露范围和影响，严重程度以证据判断。即使网站源码不在本仓库，涉及所链接公开网站的疑似安全问题也可通过私密入口提交，由维护者分流处理。

Ordinary typos, layout problems, and feature requests belong in public issues after sensitive details are removed. Their classification as ordinary issues does not exclude a security report with demonstrated impact.

普通错别字、布局问题和功能建议可以在去除敏感信息后提交公开 Issue；若存在已证实的安全影响，仍可作为安全问题私密报告。

## Limitations / 验证边界

This showcase currently has no application dependency manifest or executable application source. An empty dependency alert list does not verify the private website source, its dependencies, deployment, or live behavior. No additional vulnerability exclusions or accepted risks are declared here.

本展示仓库目前没有应用依赖清单或可执行的应用源码。依赖提醒为空不能证明私有网站源码、其依赖、部署环境或线上行为安全。本政策未另行声明漏洞豁免项或已接受风险。
