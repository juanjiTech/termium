<p align="center">
  <a href="https://juanjitech.github.io/termium/">
    <img src="docs/header.png" alt="Termium — 随时随地，管理您的基础设施" width="100%" />
  </a>
</p>

<p align="center">
  <a href="https://github.com/juanjiTech/termium/releases/latest"><img src="https://img.shields.io/github/v/release/juanjiTech/termium?label=最新版本&style=for-the-badge&color=145af5" alt="Latest release" /></a>
  <a href="https://juanjitech.github.io/termium/"><img src="https://img.shields.io/badge/官网-下载页-0A20CD?style=for-the-badge" alt="Website" /></a>
  <a href="https://github.com/juanjiTech/termium/issues/new/choose"><img src="https://img.shields.io/badge/反馈-Issues-61D4F8?style=for-the-badge" alt="Issues" /></a>
</p>

**Termium** 是一款面向团队的基础设施管理桌面应用：在安全的端到端加密前提下，统一管理 SSH 连接、密钥与密码、端口转发、Kubernetes 集群等资源，并通过团队协作在多设备间同步配置。

- **官网 / 下载页**：[https://juanjitech.github.io/termium/](https://juanjitech.github.io/termium/)
- **最新版本**：[Releases](https://github.com/juanjiTech/termium/releases/latest)
- **问题反馈**：[GitHub Issues](https://github.com/juanjiTech/termium/issues/new/choose)

---

## 下载

前往 **[Releases](https://github.com/juanjiTech/termium/releases/latest)** 获取最新安装包。当前支持的平台与文件命名规则如下：

| 平台 | 架构 | 安装包示例 |
|------|------|------------|
| macOS | Apple Silicon (ARM64) | `termium_*_darwin_arm64.dmg` |
| macOS | Intel (x64) | `termium_*_darwin_amd64.dmg` |
| Windows | x64 | `termium_*_windows_amd64-installer.exe` |

> **提示**：不确定 Mac 芯片类型时，点击左上角  → **关于本机** → **芯片**（Apple M 系列选 ARM64，Intel 选 x64）。

应用内也支持**检查更新**并自动下载安装，更新源即本仓库的 Releases。

---

## 系统要求

| 平台 | 最低要求 |
|------|----------|
| macOS | macOS 12 Monterey 或更高版本 |
| Windows | Windows 10 64 位或更高版本 |

Linux 桌面端尚未提供公开安装包。如有需求，欢迎在 Issues 中反馈。

---

## 安装

### macOS

1. 下载对应架构的 `.dmg` 文件。
2. 打开 DMG，将 **Termium** 拖入 **Applications** 文件夹。
3. 首次打开若提示「无法验证开发者」，请前往 **系统设置 → 隐私与安全性** 选择仍要打开。

### Windows

1. 下载 `*-installer.exe`。
2. 运行安装程序并按向导完成安装。
3. 若 SmartScreen 提示未知发布者，请确认来源为本仓库 Release 后再继续。

---

## 主要能力

- **SSH 终端**：多标签会话、主机链式跳转、端口转发
- **凭据与密钥**：密码、SSH 密钥统一保管，主密码仅在本地派生加密密钥
- **团队协作**：通过团队共享主机、密钥等配置，多设备自动同步
- **Kubernetes**：集群资源浏览、Pod 日志、Shell、端口转发（持续完善中）
- **安全设计**：端到端加密，主密码不上传；详见官网安全说明

---

## 反馈与支持

本仓库是 Termium 的**公开渠道**，用于：

- 发布正式/预发布安装包（Releases）
- 托管产品官网（GitHub Pages）
- 收集 Bug 报告与功能建议（Issues）

提交 Issue 前请先搜索是否已有相同反馈。我们提供结构化模板，请尽量填写完整信息（版本号、操作系统、复现步骤等），以便更快定位问题。

| 类型 | 入口 |
|------|------|
| Bug 报告 | [报告问题](https://github.com/juanjiTech/termium/issues/new?template=bug_report.yml) |
| 功能建议 | [功能建议](https://github.com/juanjiTech/termium/issues/new?template=feature_request.yml) |

---

## 关于本仓库

- **不包含源代码**。桌面端由私有仓库 `termium-wails` 构建，经 CI 自动发布安装包至本仓库 Releases；官网由 `termium-landing` 构建并部署至 `gh-pages` 分支。
- **版本号**遵循 [Semantic Versioning](https://semver.org/lang/zh-CN/)。带 `alpha` / `beta` 后缀的版本为预览版，可能存在不稳定行为。
- **更新日志**：各版本说明见对应 [Release 页面](https://github.com/juanjiTech/termium/releases)。

---

## English

**Termium** is a desktop app for managing infrastructure with team collaboration and end-to-end encryption. Download the latest build from [Releases](https://github.com/juanjiTech/termium/releases/latest), visit the [product site](https://juanjitech.github.io/termium/), or [open an issue](https://github.com/juanjiTech/termium/issues/new/choose) for bugs and feature requests.

This repository hosts **releases and user feedback only** — source code is not published here.

---

<p align="center">
  <sub>© JuanjiTech · <a href="mailto:contact@juanji.tech">contact@juanji.tech</a></sub>
</p>
