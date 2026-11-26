# PixoTap Releases

PixoTap 各平台安装包的公开发布仓库。本仓库**只**包含 [Releases](https://github.com/PixoTap/pixo-tap-releases/releases)，不包含任何源码或网站产物。

- 官网与下载页：<https://pixotap.com/download/>
- 每个 Release 附带 `SHA256SUMS.txt` 与分离签名 `SHA256SUMS.txt.sig`（ECDSA P-256），应用内更新只安装签名校验通过的文件。
- macOS 与 Linux 一行安装：`curl -fsSL https://pixotap.com/install | bash`；Windows：`irm https://pixotap.com/install.ps1 | iex`。

2026-11-26 之前的仓库历史（含旧的网站构建产物）保存在已归档的 `PixoTap/pixo-tap-releases-legacy`，其中的 Release 已按原标签、原文件迁移到这里。

PixoTap 是私有软件，本仓库的文件不附带开源许可；安装包内附第三方组件的许可声明。

---

Public release repository for PixoTap desktop installers. It contains only Releases — no source code and no website build output.
