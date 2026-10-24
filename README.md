# Agnovexa

**让 AI 对话、项目资料与工具连接汇聚于一个桌面工作台。**

[![Latest Release](https://img.shields.io/github/v/release/kllin8154-arch/Agnovexa-Releases?label=Latest%20Release)](https://github.com/kllin8154-arch/Agnovexa-Releases/releases/latest)
![Platform](https://img.shields.io/badge/Platform-Windows%20x64-4B5563)

**[下载最新正式版](https://github.com/kllin8154-arch/Agnovexa-Releases/releases/latest)** · [查看所有版本](https://github.com/kllin8154-arch/Agnovexa-Releases/releases) · [问题反馈与建议](https://github.com/kllin8154-arch/Agnovexa-Releases/issues)

> **关于本仓库：** 这里是 Agnovexa 的 **Windows 桌面版发行仓库**，用于提供安装包、发行说明和更新元数据；**不包含应用开发源码**。具体功能、修复内容与已知限制，请查看对应版本的 Release Notes。

## Agnovexa 是什么？

Agnovexa 是面向 AI 与 Agent 工作流的桌面工作台，尝试将日常对话、项目组织、资料上下文、模型连接与扩展工具集中在统一界面中，减少在多个应用和配置页面之间切换。

主要使用场景包括：

- **AI 对话与工作空间**：组织会话，在统一工作台中开展不同任务。
- **项目与资料管理**：围绕项目整理会话、文件与知识库相关资源。
- **灵活的模型接入**：配置模型服务商、自定义 API 或中转站连接，按连接管理相应模型与参数。
- **Agent 与扩展生态**：探索和配置助理、技能（Skills）、MCP 及其他工具资源。
- **桌面应用管理**：在应用中查看设置、版本与可用的更新入口。

Agnovexa 持续迭代中。以上是产品的主要能力方向，**具体功能的可用范围、连接方式和限制以所下载版本的发行说明及实际界面为准**；展示了入口不代表所有第三方服务均已完成接入或验证。

## 下载与快速开始

**当前公开发布平台：Windows x64。**

1. 前往 **[最新正式版](https://github.com/kllin8154-arch/Agnovexa-Releases/releases/latest)**。
2. 在该版本的 **Assets** 中下载 Windows 安装程序（通常以 `-setup.exe` 结尾）；请勿将更新清单当作安装程序。
3. 运行安装程序，按提示完成安装并启动 Agnovexa。
4. 如需使用在线模型，在应用内配置你有权使用的模型服务商或中转站地址、密钥与模型；然后开始使用对话和项目工作台。

Agnovexa 安装包**不附带第三方模型的 API 密钥、付费额度或中转服务**。相关服务可能需要单独申请、授权和计费。

## 版本发布与升级

| 入口 | 说明 |
| --- | --- |
| [最新正式版](https://github.com/kllin8154-arch/Agnovexa-Releases/releases/latest) | 始终指向 GitHub 标记的最新正式 Release，无须手工修改版本号 |
| [全部发行记录](https://github.com/kllin8154-arch/Agnovexa-Releases/releases) | 查看历史版本、更新内容、修复项与已知限制 |
| Release Assets | 获取对应版本的安装程序及可能附带的更新元数据 |
| `stable.yml` | 供应用更新机制读取的发行清单，**不是供用户运行的安装包** |

**升级前建议：**

- 先阅读目标版本的 Release Notes，尤其是安装方式、数据迁移与兼容性说明。
- 升级前备份重要的本地项目、会话、知识库及配置资料。
- 如果当前版本提供应用内“检查更新”入口，可按界面指引操作；**下载、自动安装和跨版本迁移是否已验收，以对应版本说明为准**。
- 通过复制文件夹使用的旧版或免安装目录，可能仍需**手动更新**，不要假定其与正式安装版具有相同的升级流程。

**README 只介绍长期有效的产品信息和下载方式，不记录某个版本的完整更新日志。** 每次发布新版，请把新增功能、修复、已知问题、兼容性和升级注意事项写在该版本的 Release Notes 中。

## 安全与数据说明

- 请仅通过本仓库的 [GitHub Releases](https://github.com/kllin8154-arch/Agnovexa-Releases/releases) 获取发行文件；如发布页提供校验信息，可核对文件完整性。
- 不同版本的代码签名状态可能不同。未签名的安装程序可能触发 Windows 或安全软件提示；请先确认来源和对应发行说明。
- 使用第三方模型或中转站时，请自行确认服务商的隐私政策和数据处理方式；发送给外部模型的内容可能由相应服务处理。
- 不要在公开 Issue、截图或日志中泄露 API Key、访问令牌、密码、私人文档等敏感信息。

## 问题反馈

遇到问题或希望改进功能，可在 [Issues](https://github.com/kllin8154-arch/Agnovexa-Releases/issues) 提交反馈。建议提供**使用的版本、Windows 环境、复现步骤、预期结果与实际现象**；必要时附上已脱敏的截图或日志，便于定位问题。

---

**Agnovexa · Desktop AI & Agent Workspace**

本仓库专注于发布与分发。**最新下载入口保持不变；每个版本的变化以 Release Notes 为准。**
