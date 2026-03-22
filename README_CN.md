# Awesome 医疗 AI Skills 🏥🤖

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![License: CC0-1.0](https://img.shields.io/badge/License-CC0_1.0-lightgrey.svg)](http://creativecommons.org/publicdomain/zero/1.0/)
[![最后更新](https://img.shields.io/badge/最后更新-2026--03--22-blue.svg)](#)
[![Skills 数量](https://img.shields.io/badge/Skills-100%2B-green.svg)](#)

> 精选医疗 & 健康领域 AI Agent Skills、MCP 服务器和工具合集。
> 覆盖 Claude Code、OpenClaw、Cursor、Codex 等 AI 编程助手平台。

**[English](README.md)** | **[中文说明](#目录)**

---

## 为什么需要这个列表？

医疗 AI Agent Skills 分散在数十个注册表中（ClawHub、awesome-claude-skills、awesome-openclaw-skills 等），缺乏统一的医疗领域集合。本仓库旨在：

- 📦 **聚合** 所有医疗/健康 AI Skills
- ⭐ **评估** 每个 Skill 的质量等级、维护状态和功能
- 🏷️ **分类** 按临床领域组织，方便检索
- 🔄 **持续更新** 通过社区贡献保持最新

---

## 评分体系

| 等级 | 含义 |
|------|------|
| ⭐⭐⭐ **A** | 优秀 — 生产级就绪，维护良好，文档完善 |
| ⭐⭐ **B** | 良好 — 功能可用，积极开发中 |
| ⭐ **C** | 一般 — 早期阶段，范围有限 |
| **D** | 较差 — 已弃用或严重受限 |

| 维护状态 | 含义 |
|---------|------|
| 🟢 活跃 | 30 天内有更新 |
| 🟡 一般 | 90 天内有更新 |
| 🔴 停滞 | 超过 90 天未更新 |

---

## 目录

- [🏥 临床技能与知识库](#-临床技能与知识库)
- [🔌 医疗 MCP 服务器](#-医疗-mcp-服务器)
- [🧬 生物医学研究与基因组学](#-生物医学研究与基因组学)
- [📷 医学影像与放射学](#-医学影像与放射学)
- [💊 药物与药理学](#-药物与药理学)
- [⌚ 健康数据与可穿戴设备](#-健康数据与可穿戴设备)
- [🧠 心理健康与治疗](#-心理健康与治疗)
- [🥗 营养与饮食](#-营养与饮食)
- [🏋️ 健身与训练](#️-健身与训练)
- [🏭 医疗器械合规](#-医疗器械合规)
- [🤖 多智能体医疗系统](#-多智能体医疗系统)
- [📚 技能合集](#-技能合集)

---

## 🏥 临床技能与知识库

| Skill | 平台 | 等级 | 说明 |
|-------|------|------|------|
| [medical-guidelines-suite](https://github.com/fshaan/medical-guidelines-suite) | Claude Code | ⭐⭐ B | 临床指南知识库构建 + 跨指南 RAG 检索 + 批量患者报告生成。支持 NCCN、ESMO、CSCO 指南。中文输出。 |
| [Claude-Ally-Health](https://github.com/huifer/Claude-Ally-Health) | Claude Code | ⭐ C+ | 基于文件的个人健康档案管理。13 个专科咨询模拟、药物相互作用检测、辐射剂量追踪。中英双语。 |
| [therapy-mode](https://clawskills.sh/skills/therapy-mode) | OpenClaw | ⭐⭐ B | AI 辅助治疗支持：CBT、ACT、DBT、动机性访谈。会话记录和危机协议。 |

---

## 🔌 医疗 MCP 服务器

| 服务器 | 等级 | 说明 |
|--------|------|------|
| [BioMCP](https://github.com/genomoncology/biomcp) | ⭐⭐⭐ A | 15+ 生物医学 API 统一接口：PubMed、ClinicalTrials.gov、ClinVar、gnomAD、ChEMBL 等。Rust CLI + MCP 服务器。 |
| [medical-mcp](https://github.com/JamesANZ/medical-mcp) | ⭐⭐ B | 零配置本地 MCP：FDA 药物、WHO 统计、PubMed、RxNorm、Google Scholar。无需 API 密钥。 |
| [WSO2 FHIR MCP](https://github.com/wso2/fhir-mcp-server) | ⭐⭐⭐ A- | 企业级 FHIR 桥接，支持 SMART-on-FHIR OAuth。已测试 Epic EHR。 |
| [DICOM MCP](https://github.com/ChristianHinge/dicom-mcp) | ⭐⭐ B+ | 从 PACS 查询和移动医学影像/报告。唯一面向 DICOM 的 MCP 服务器。 |
| [OMOP MCP](https://github.com/OHNLP/omop_mcp) | ⭐⭐ B | 使用 LLM 将临床术语映射到 OMOP 概念。 |
| [mcp-simple-pubmed](https://github.com/andybrandt/mcp-simple-pubmed) | ⭐⭐ B | PubMed 医学文献搜索与阅读。 |

---

## 🧬 生物医学研究与基因组学

| Skill | 平台 | 等级 | 说明 |
|-------|------|------|------|
| [claude-scientific-skills](https://github.com/K-Dense-AI/claude-scientific-skills) | 多平台 | ⭐⭐⭐ A | 170+ 科学技能：生物信息学、化学信息学、蛋白组学、临床研究、医学影像。15.8K⭐ |
| [OpenClaw-Medical-Skills](https://github.com/FreedomIntelligence/OpenClaw-Medical-Skills) | OpenClaw | ⭐⭐ B+ | 869 个医疗 AI 技能：临床工作流、基因组学、药物发现、法规合规。 |
| [dna-claude-analysis](https://github.com/shmlkv/dna-claude-analysis) | Claude Code | ⭐⭐ B- | 个人基因组分析（23andMe/AncestryDNA）。17 个分析脚本，交互式 HTML 仪表盘。 |
| [admet-prediction](https://clawskills.sh/skills/huifer-admet-prediction) | OpenClaw | ⭐⭐ B | 药物候选物 ADMET（吸收、分布、代谢、排泄、毒性）预测。 |

---

## 📷 医学影像与放射学

| Skill | 等级 | 说明 |
|-------|------|------|
| [MedRAX](https://github.com/bowang-lab/MedRAX) | ⭐⭐⭐ A- | **ICML 2025**。胸部 X 光 AI 解读：集成 CheXagent、LLaVA-Med、MedSAM 等 7+ 专业模型。 |
| [radiology-swarm](https://github.com/The-Swarm-Corporation/radiology-swarm) | ⭐ C+ | 企业级多智能体放射学分析系统。 |
| [DICOM MCP](https://github.com/ChristianHinge/dicom-mcp) | ⭐⭐ B+ | PACS/DICOM 医学影像查询与传输。 |

---

## 💊 药物与药理学

| Skill | 说明 |
|-------|------|
| [maccabi-pharm-search](https://clawskills.sh/skills/alexpolonsky-maccabi-pharm-search) | 以色列 Maccabi 药房药物库存查询 |
| [admet-prediction](https://clawskills.sh/skills/huifer-admet-prediction) | 药物候选物 ADMET 预测 |

> 另见：[BioMCP](#-医疗-mcp-服务器)（ChEMBL、药物-基因交互）、[medical-mcp](#-医疗-mcp-服务器)（FDA 药物、RxNorm）

---

## ⌚ 健康数据与可穿戴设备

**20+ 个技能**覆盖以下设备和平台：

| 设备/平台 | 技能数 | 代表技能 |
|----------|--------|---------|
| 🍎 Apple Health | 2 | apple-health-skill, healthkit-sync |
| ⌚ Garmin | 5 | garmin-health, garmin-cli, garmin-connect |
| 📱 Fitbit | 3 | fitbit, fitbit-analytics, fitbit-health |
| 💚 WHOOP | 7 | whoop-health-analysis, whoop-tracker, whoop-morning |
| 💍 Oura Ring | 4 | oura-analytics, oura-ring-skill, ouracli |
| ⚖️ Withings | 2 | withings-health, withings-family |
| 🛏️ Eight Sleep | 1 | eightctl |
| 📊 综合 | 3 | health-sync, health-summary, gevety |

详见 [完整英文列表](README.md#health-data--wearables)

---

## 🧠 心理健康与治疗

包含 12 个技能：therapy-mode、anxiety-relief、depression-support、ADHD 系列（4个）、jungian-psychologist、mens-mental-health、social-media-detox 等。

---

## 🥗 营养与饮食

包含 11 个技能：calorie-counter、diet-tracker、opencal、fasting-tracker、feast、recipe-finder 等。

---

## 🏋️ 健身与训练

包含 8 个技能：endurance-coach、muscle-gain、hevy、workout、strava-cycling-coach 等。

---

## 🏭 医疗器械合规

| Skill | 说明 |
|-------|------|
| [capa-officer](https://clawskills.sh/skills/alirezarezvani-capa-officer) | 医疗器械 QMS 的 CAPA 系统管理 |

---

## 🤖 多智能体医疗系统

包含 11 个系统：MedRAX（ICML 2025）、Multi-Agent-Medical-Assistant、medgraph-ai 等。

详见 [完整英文列表](README.md#multi-agent-medical-systems)

---

## 📚 技能合集

| 合集 | ⭐ Stars | 医疗技能数 | 说明 |
|------|---------|-----------|------|
| [claude-scientific-skills](https://github.com/K-Dense-AI/claude-scientific-skills) | 15.8K | 30+ | 170 科学技能合集 |
| [OpenClaw-Medical-Skills](https://github.com/FreedomIntelligence/OpenClaw-Medical-Skills) | 1.5K | 869 | 最大医疗专属技能库 |
| [awesome-openclaw-skills](https://github.com/VoltAgent/awesome-openclaw-skills) | 40.5K | 84 | 5,400+ 技能中的健康分类 |
| [awesome-openclaw-skills-zh](https://github.com/clawdbot-ai/awesome-openclaw-skills-zh) | 3.5K | 30+ | OpenClaw 中文技能库 |

---

## ⚠️ 免责声明

> 本列表中的所有技能仅供**信息参考和研究目的**。它们**不是**经过验证的临床工具，**不应**用于实际的医疗诊断或治疗决策。请始终咨询合格的医疗专业人员。AI 生成的医疗信息可能不准确或有害。

---

## 参与贡献

欢迎贡献！请查看 [CONTRIBUTING.md](CONTRIBUTING.md) 了解指南。

## 许可证

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

本列表以 [CC0 1.0 通用](LICENSE) 发布。
