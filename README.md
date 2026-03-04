# 🤖 oc-smart-agent-hub

> **💼 开发说明**: 本 SKILL 由 **OpenClaw 的 AI 助手 Leo** 全程独立开发  
> **Developer**: This SKILL was developed entirely by **Leo, the OpenClaw AI Assistant**

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)](https://github.com/msonline1110/oc-smart-agent-hub)
[![OpenClaw](https://img.shields.io/badge/OpenClaw-Skill-green.svg)](https://clawhub.ai)

---

## 📋 简介 | Introduction

**oc-smart-agent-hub** - 智能体多模型路由系统，由使用者 MSonline 提出需求，OpenClaw AI 助手 Leo 独立开发。

本 SKILL 以充分使用阿里云百炼 Coding Plane 提供的 8 种功能性大模型为核心目标，为分工不同的子智能体匹配最适合的大模型，从而提高运行效率和内容完成质量。

支持阿里云、OpenAI、Anthropic 等 5+ 厂商及 Ollama 本地模型，提供智能体专属模型分配、任务类型自动路由、成本优化等功能。纯 YAML 配置，零代码，企业级安全规范。

---

## 🎯 核心功能 | Key Features

- **🌐 多厂商支持** - 支持阿里云百炼 8 种功能性大模型 + OpenAI、Anthropic 等外部厂商
- **🎯 智能体匹配** - 为项目协调、前端开发、智能合约、数据库、测试、运营、安全、数值、美术等子智能体分配专属模型
- **⚡ 效率优化** - 根据任务类型自动选择最优模型，提高运行效率
- **✨ 质量提升** - 为不同子智能体匹配最适合的模型，提高内容完成质量
- **🏠 本地模型** - 支持 Ollama、LM Studio、vLLM 等本地部署，自动发现、完全免费
- **⚙️ 零代码配置** - 纯 YAML 配置，即改即用，无需修改代码
- **🔒 安全规范** - 企业级敏感信息保护，打包前自动检查

---

## 🚀 快速开始 | Quick Start

### 安装 | Install

```bash
# 从 ClawHub 安装
clawhub install oc-smart-agent-hub

# 或从 GitHub 克隆
git clone https://github.com/msonline1110/oc-smart-agent-hub.git
```

### 配置 | Configure

```bash
# 编辑模型配置
编辑 config/models.yaml

# 启动智能体
python scripts/provider_manager.py list-models
```

---

## 📊 百炼 8 模型 | Bailian 8 LLMs

| 模型 | 适用智能体 | 用途 |
|------|----------|------|
| qwen3.5-plus | 项目协调、数据库设计 | 均衡全能，日常任务 |
| qwen3-max | 测试审计、安全审计 | 最强推理，关键任务 |
| qwen3-coder-plus | 前端开发、智能合约 | 代码专家，编程任务 |
| qwen3-coder-next | 前端开发（快速） | 低延迟，快速响应 |
| glm-5 | 项目协调 | Agent 编排，任务调度 |
| kimi-k2.5 | 运营方案、美术设计 | 长文本，创意理解 |
| MiniMax-M2.5 | 运营方案 | Agent 原生，多语言 |
| glm-4.7 | 备用模型 | 备用，基础任务 |

---

## 📁 目录结构 | Structure

```
oc-smart-agent-hub/
├── SKILL.md                      # 技能说明
├── SECURITY_NOTICE.md            # 安全提示
├── INTRODUCTION.md               # 介绍文档
├── config/
│   └── models.yaml               # 模型配置
├── docs/
│   ├── README_zh.md              # 中文文档
│   └── README_en.md              # 英文文档
├── examples/                     # 配置示例
└── scripts/                      # 脚本
```

---

## 📄 许可证 | License

MIT License - See [LICENSE](LICENSE) file for details.

---

## 👨‍💻 开发者 | Developer

**Leo** - OpenClaw AI Assistant

---

## 📅 发布日期 | Release Date

2026-03-04

---

## 🔗 链接 | Links

- [ClawHub](https://clawhub.ai)
- [OpenClaw](https://github.com/openclaw/openclaw)
- [GitHub Repository](https://github.com/msonline1110/oc-smart-agent-hub)

---

**⭐ 如果这个项目对你有帮助，请给一个 Star！**
