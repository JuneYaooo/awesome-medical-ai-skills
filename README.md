# Awesome Medical AI Skills 🏥🤖🌍

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![License: CC0-1.0](https://img.shields.io/badge/License-CC0_1.0-lightgrey.svg)](http://creativecommons.org/publicdomain/zero/1.0/)
[![Last Updated](https://img.shields.io/badge/Last%20Updated-2026--04--19-blue.svg)](#)
[![Skills Count](https://img.shields.io/badge/Skills-100%2B-green.svg)](#)

> 🇨🇳 **Looking for China-accessible skills?** See [awesome-medical-ai-skills-cn](https://github.com/JuneYaooo/awesome-medical-ai-skills-cn) — 国内版：关注网络可达性、中文支持、国内平台生态

> 🏥 **Looking for medical AI projects (LLMs, imaging, multi-agent systems)?** See [awesome-medical-ai](https://github.com/JuneYaooo/awesome-medical-ai) — broader medical AI project collection

> A curated list of **installable** AI agent skills, MCP servers, and tools for **medical & healthcare** use cases — **International Edition**.
> Only includes skills you can install into Claude Code, OpenClaw, Cursor, Codex, and other AI coding agents.

---

## Why This List?

Medical AI agent skills are scattered across dozens of registries (ClawHub, awesome-claude-skills, awesome-openclaw-skills, etc.) with no unified collection. This repo aims to:

> 🌍 **International Edition**: This list focuses on globally accessible platforms and tools. For skills optimized for the China ecosystem (domestic APIs, Chinese-language models, local compliance), see the [CN version](https://github.com/JuneYaooo/awesome-medical-ai-skills-cn).

- **Aggregate** all medical/healthcare AI skills in one place
- **Evaluate** each skill with quality grades, maintenance status, and feature reviews
- **Categorize** by clinical domain for easy discovery
- **Stay Updated** through community contributions

---

## Rating System

Each skill is rated on three dimensions:

| Grade | Meaning |
|-------|---------|
| ⭐⭐⭐ **A** | Excellent — production-ready, well-maintained, comprehensive docs |
| ⭐⭐ **B** | Good — functional, active development, some limitations |
| ⭐ **C** | Fair — early stage, limited scope, or stale maintenance |
| **D** | Poor — abandoned, broken, or severely limited |

| Maintenance | Meaning |
|-------------|---------|
| 🟢 Active | Updated within last 30 days |
| 🟡 Moderate | Updated within last 90 days |
| 🔴 Stale | Not updated in 90+ days |

---

## Table of Contents

- [Clinical Skills & Knowledge Bases](#clinical-skills--knowledge-bases)
- [Medical MCP Servers](#medical-mcp-servers)
- [Biomedical Research & Genomics](#biomedical-research--genomics)
- [Medical Imaging Skills](#medical-imaging-skills)
- [Drug & Pharmacology](#drug--pharmacology)
- [Health Data & Wearables](#health-data--wearables)
- [Mental Health & Therapy](#mental-health--therapy)
- [Nutrition & Diet](#nutrition--diet)
- [Fitness & Training](#fitness--training)
- [Medical Device Compliance](#medical-device-compliance)
- [Curated Skill Collections](#curated-skill-collections)
- [Related Resources](#related-resources)
- [Contributing](#contributing)

---

## Clinical Skills & Knowledge Bases

> Skills for clinical decision support, guideline retrieval, and patient report generation.

| Skill | Platform | Grade | Maintenance | Stars | Description |
|-------|----------|-------|-------------|-------|-------------|
| [medical-guidelines-suite](https://github.com/fshaan/medical-guidelines-suite) | Claude Code | ⭐⭐ B | 🟢 Active | ![](https://img.shields.io/github/stars/fshaan/medical-guidelines-suite?style=flat-square) | Clinical guidelines knowledge base builder with cross-guideline RAG retrieval and batch patient report generation (xlsx/docx/pptx). Supports NCCN, ESMO, CSCO guidelines. Chinese output. |
| [NCCN Monitor](https://github.com/fshaan/nccn-monitor) | MCP Server | ⭐⭐ B | 🟢 Active | ![](https://img.shields.io/github/stars/fshaan/nccn-monitor?style=flat-square) | MCP server for monitoring all 92 NCCN professional guidelines. Detects version changes, downloads updated PDFs, extracts update notes, and generates structured change summaries with Chinese/English search support. |
| [Herald](https://github.com/myceldigital/herald) | CLI / Python | ⭐⭐ B- | 🟢 Active | ![](https://img.shields.io/github/stars/myceldigital/herald?style=flat-square) | Clinical-guideline engine that converts guideline PDFs into deterministic, auditable decision trees with citation-backed query results. Ships as a PyPI package with tests and local demo cases. |
| [mediwise-health-suite](https://github.com/JuneYaooo/mediwise-health-suite) | OpenClaw | ⭐⭐ B | 🟢 Active | ![](https://img.shields.io/github/stars/JuneYaooo/mediwise-health-suite?style=flat-square) | Family health management suite — health records, diet tracking, weight management, medication reminders, pre-visit summaries. Multi-member support with data isolation. Local SQLite storage. Bilingual CN/EN. |
| [ICD-10-CM Auto-Coding Skill](https://github.com/EricFu1120/icd10cm-codes-skill) | Claude Code / Multi | ⭐⭐ B | 🟢 Active | ![](https://img.shields.io/github/stars/EricFu1120/icd10cm-codes-skill?style=flat-square) | Agentic medical coding skill built around the full FY2025 ICD-10-CM index, tabular list, and official guidelines. Includes Python search/validation scripts, deterministic workflow, audit trail, and 12 worked examples. |
| [Tula](https://github.com/pswider/tula) | OpenClaw | ⭐⭐ B- | 🟢 Active | ![](https://img.shields.io/github/stars/pswider/tula?style=flat-square) | OpenClaw health-agent layer for labs, DICOM/image interpretation, genomics, FHIR portal access, wearables, journaling, de-identification, and research synthesis. Self-hosted and Telegram-accessible. |
| [ebmt-handbook-skill](https://github.com/htlin222/ebmt-handbook-skill) | Claude Code / Multi | ⭐ C+ | 🟢 Active | ![](https://img.shields.io/github/stars/htlin222/ebmt-handbook-skill?style=flat-square) | Open-access EBMT Handbook 8th-edition skill for transplant/cellular-therapy guidance, chapter routing, source citations, and calculators for BSA, CrCl, HCT-CI, GVHD, and dosing workflows. |
| [ABA Clinical Agent](https://github.com/open-behavior-analysis/aba-clinical-agent) | Claude Code | ⭐ C+ | 🟢 Active | ![](https://img.shields.io/github/stars/open-behavior-analysis/aba-clinical-agent?style=flat-square) | Applied Behavior Analysis clinical-supervision automation suite with 29 Claude Code skills and an Obsidian knowledge base covering intake, assessment, planning, de-identification, supervision, and reporting. |
| [health-skill](https://github.com/googlarz/health-skill) | Claude Code / Cowork | ⭐ C+ | 🟢 Active | ![](https://img.shields.io/github/stars/googlarz/health-skill?style=flat-square) | Local-first health workspace for record organization, lab/context review, appointment prep, caregiver workflows, review queues, and continuity across sessions. Ships scripts and tests. |
| [informed-patient](https://github.com/DrCatHicks/informed-patient) | Claude Code | ⭐ C+ | 🟢 Active | ![](https://img.shields.io/github/stars/DrCatHicks/informed-patient?style=flat-square) | Claude Code plugin that guides a structured symptom interview, literature search, evidence-red-flag review, and appointment-ready health evidence report with transparent search terms and source checks. |
| [audit-oe-skill](https://github.com/htlin222/audit-oe-skill) | Claude Code / Skills | ⭐ C+ | 🟢 Active | ![](https://img.shields.io/github/stars/htlin222/audit-oe-skill?style=flat-square) | Claude Code skill for auditing OpenEvidence responses by mapping claims to citations, verifying papers via PubMed/bioRxiv, and generating structured evidence-strength reports. |
| [samurai-skills](https://github.com/HealthSamurai/samurai-skills) | Claude Code | ⭐ C+ | 🟢 Active | ![](https://img.shields.io/github/stars/HealthSamurai/samurai-skills?style=flat-square) | Claude Code plugin for healthcare development on Health Samurai products: Aidbox FHIR platform workflows, SQL on FHIR, FHIR type generation, and health-samurai.io docs search. |
| [openEHR Assistant Plugin](https://github.com/Cadasto/openehr-assistant-plugin) | Claude Code / Cursor | ⭐ C+ | 🟡 Moderate | ![](https://img.shields.io/github/stars/Cadasto/openehr-assistant-plugin?style=flat-square) | AI plugin suite for openEHR clinical-workflow integration. Adds guide-first skills and commands for CKM discovery, archetype/template authoring, composition building, and AQL workflows; pairs with a companion MCP server. |
| [WellAlly-health](https://github.com/huifer/WellAlly-health) | Claude Code | ⭐ C+ | 🟡 Moderate | — | File-based personal health record management. 13 specialist consultation simulations, drug interaction detection, radiation dose tracking. Bilingual CN/EN. *(Formerly Claude-Ally-Health)* |
| [personas (Dr. Med)](https://clawskills.sh/skills/personas) | OpenClaw | ⭐ C | 🟡 Moderate | — | 31 AI personas including Dr. Med role for medical domain consultation. *(Link may be broken)* |
| [claude-health](https://github.com/tw93/claude-health) | Claude Code | ⭐ C | 🟢 Active | ![](https://img.shields.io/github/stars/tw93/claude-health?style=flat-square) | 🤫 Claude Code skill: audit your Claude Code config health across all layers |
| [healthy-lifestyle-claude-skills](https://github.com/olena-filatova/healthy-lifestyle-claude-skills) | Claude Code | ⭐ C | 🟢 Active | ![](https://img.shields.io/github/stars/olena-filatova/healthy-lifestyle-claude-skills?style=flat-square) | *(no description)* |
| [bOS](https://github.com/zmrlk/bOS) | Claude Code | ⭐ C | 🟢 Active | ![](https://img.shields.io/github/stars/zmrlk/bOS?style=flat-square) | Your personal operating system — 16 AI agents, 22 skills, one Claude Code folder. Business, life, health, learning. |
| [vibe-code-health-check](https://github.com/FuzulsFriend/vibe-code-health-check) | Claude Code | ⭐ C | 🟢 Active | ![](https://img.shields.io/github/stars/FuzulsFriend/vibe-code-health-check?style=flat-square) | Claude Code skill: grades your codebase A through F across 6 health dimensions with plain-English fixes — built for vibe coders and solo founders |
| [health-skillz](https://github.com/jmandel/health-skillz) | Claude Code | ⭐ C | 🟢 Active | ![](https://img.shields.io/github/stars/jmandel/health-skillz?style=flat-square) | A Claude Skill for connecting to and analyzing personal health records via SMART on FHIR |
| [Academic_writing_c_claudecode](https://github.com/grotyx/Academic_writing_c_claudecode) | Claude Code | ⭐ C | 🟢 Active | ![](https://img.shields.io/github/stars/grotyx/Academic_writing_c_claudecode?style=flat-square) | Medical Academic Writing with Claude Code |
| [soanai-xbio](https://clawskills.sh/skills/soanai-xbio) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [johnyquest7-medical-specialty-briefs](https://clawskills.sh/skills/johnyquest7-medical-specialty-briefs) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [sieershafilone-media-orchestrator](https://clawskills.sh/skills/sieershafilone-media-orchestrator) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [mohdalhashemi98-hue-mh-healthcheck](https://clawskills.sh/skills/mohdalhashemi98-hue-mh-healthcheck) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [aaronn-apple-media](https://clawskills.sh/skills/aaronn-apple-media) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [dylntrnr-mediator](https://clawskills.sh/skills/dylntrnr-mediator) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [felipetruman-heartbeat-checklist](https://clawskills.sh/skills/felipetruman-heartbeat-checklist) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [ollieparsley-zenplus-health](https://clawskills.sh/skills/ollieparsley-zenplus-health) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [kleberbaum-pharmaziegasse](https://clawskills.sh/skills/kleberbaum-pharmaziegasse) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [muhammedalibalci-ozel-yetenek](https://clawskills.sh/skills/muhammedalibalci-ozel-yetenek) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [mehediahamed-travel-destination-brochure](https://clawskills.sh/skills/mehediahamed-travel-destination-brochure) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [minduploadedcrab-platform-healthcheck](https://clawskills.sh/skills/minduploadedcrab-platform-healthcheck) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [nikhilp1234567-biodiversity-corridor-calculator](https://clawskills.sh/skills/nikhilp1234567-biodiversity-corridor-calculator) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [iisweetheartii-agent-social](https://clawskills.sh/skills/iisweetheartii-agent-social) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [biohackerrrrrr-paper-fetcher](https://clawskills.sh/skills/biohackerrrrrr-paper-fetcher) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [gekacross-personal-sleep](https://clawskills.sh/skills/gekacross-personal-sleep) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [asleep123-bitwarden](https://clawskills.sh/skills/asleep123-bitwarden) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [reighlan-social-media-autopilot](https://clawskills.sh/skills/reighlan-social-media-autopilot) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [mohammedfarish-al-khanjry-bus](https://clawskills.sh/skills/mohammedfarish-al-khanjry-bus) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [jacksimplified-simplified-social-media](https://clawskills.sh/skills/jacksimplified-simplified-social-media) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [muslimalfatih-server-health](https://clawskills.sh/skills/muslimalfatih-server-health) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [tkuehnl-kube-medic](https://clawskills.sh/skills/tkuehnl-kube-medic) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [jaschadub-symbiont](https://clawskills.sh/skills/jaschadub-symbiont) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [iisweetheartii-agentgram-openclaw](https://clawskills.sh/skills/iisweetheartii-agentgram-openclaw) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [tomquist-mupibox-media-db](https://clawskills.sh/skills/tomquist-mupibox-media-db) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [nevo-david-agent-media](https://clawskills.sh/skills/nevo-david-agent-media) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [pascalwhoop-medical-clinicaltrials](https://clawskills.sh/skills/pascalwhoop-medical-clinicaltrials) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [zbreda-bio-reabilita-z](https://clawskills.sh/skills/zbreda-bio-reabilita-z) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [xsir0-google-gemini-media](https://clawskills.sh/skills/xsir0-google-gemini-media) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [duncandobbins-med-info](https://clawskills.sh/skills/duncandobbins-med-info) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [assistantheinrich-prog-session-health-monitor](https://clawskills.sh/skills/assistantheinrich-prog-session-health-monitor) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [psyb0t-mediaproc](https://clawskills.sh/skills/psyb0t-mediaproc) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [divine-comedian-myosin-hivemind](https://clawskills.sh/skills/divine-comedian-myosin-hivemind) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [clarityprotocol-clarity-clinical](https://clawskills.sh/skills/clarityprotocol-clarity-clinical) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [tryan310-social-media-manager](https://clawskills.sh/skills/tryan310-social-media-manager) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [devhoangkien-medium-writer](https://clawskills.sh/skills/devhoangkien-medium-writer) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [pharmacist9527-best-image](https://clawskills.sh/skills/pharmacist9527-best-image) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [fmdmm-wisediag-medocr](https://clawskills.sh/skills/fmdmm-wisediag-medocr) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [kiaraho-sys-guard-linux-remediator](https://clawskills.sh/skills/kiaraho-sys-guard-linux-remediator) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [satoshistackalotto-system-health-check](https://clawskills.sh/skills/satoshistackalotto-system-health-check) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [iisweetheartii-agent-selfie](https://clawskills.sh/skills/iisweetheartii-agent-selfie) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [callmedas69-credential-manager](https://clawskills.sh/skills/callmedas69-credential-manager) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [cocoblood9527-para-proactive-workspace](https://clawskills.sh/skills/cocoblood9527-para-proactive-workspace) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [ctsolutionsdev-ct-health-guardian](https://clawskills.sh/skills/ctsolutionsdev-ct-health-guardian) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [trypto1019-arc-skill-health-monitor](https://clawskills.sh/skills/trypto1019-arc-skill-health-monitor) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [ryandeangraves-telegram-media](https://clawskills.sh/skills/ryandeangraves-telegram-media) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [asleep123-caldav-calendar](https://clawskills.sh/skills/asleep123-caldav-calendar) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [kanakamedalasumanth-get-kalshi-live-games](https://clawskills.sh/skills/kanakamedalasumanth-get-kalshi-live-games) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [kurinzo-tg-media-resolve](https://clawskills.sh/skills/kurinzo-tg-media-resolve) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [claudiodrusus-shelly-social-media-scheduler](https://clawskills.sh/skills/claudiodrusus-shelly-social-media-scheduler) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [danmurphy1217-nori-health](https://clawskills.sh/skills/danmurphy1217-nori-health) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [gblockchainnetwork-vps-health-auditor](https://clawskills.sh/skills/gblockchainnetwork-vps-health-auditor) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [cewinharhar-lobster-bio-dev](https://clawskills.sh/skills/cewinharhar-lobster-bio-dev) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [fabiolr-duffel](https://clawskills.sh/skills/fabiolr-duffel) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [ctsolutionsdev-egvert-health-guardian](https://clawskills.sh/skills/ctsolutionsdev-egvert-health-guardian) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [underbench2-gif-ub2-api-health-checker](https://clawskills.sh/skills/underbench2-gif-ub2-api-health-checker) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [kuan0808-social-media-ops](https://clawskills.sh/skills/kuan0808-social-media-ops) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [bowen31337-ai-media](https://clawskills.sh/skills/bowen31337-ai-media) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [cewinharhar-lobster-bio-use](https://clawskills.sh/skills/cewinharhar-lobster-bio-use) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [drug-discovery-skills](https://github.com/huifer/drug-discovery-skills) | Claude Code | ⭐ C | 🟢 Active | ![](https://img.shields.io/github/stars/huifer/drug-discovery-skills?style=flat-square) | Drug Discovery Intelligence plugin for Claude Code. AI-powered target validation,  competitive intelligence, literature analysis & clinical trials insights.  Integrates Open Targets, ChEMBL, PubMed... |
| [cheminem-pharma-pharmacology-agent](https://clawskills.sh/skills/cheminem-pharma-pharmacology-agent) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [brandonwadepackard-cell-social-media-platform](https://clawskills.sh/skills/brandonwadepackard-cell-social-media-platform) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [iisweetheartii-opencode-omo](https://clawskills.sh/skills/iisweetheartii-opencode-omo) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [g4dr-social-media-extractor](https://clawskills.sh/skills/g4dr-social-media-extractor) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [xanderrey-youtube-media-downloader](https://clawskills.sh/skills/xanderrey-youtube-media-downloader) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [yujesyoga-brevo](https://clawskills.sh/skills/yujesyoga-brevo) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [alvinecarn-media-writing](https://clawskills.sh/skills/alvinecarn-media-writing) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [bamontejano-skill-doctorbot-healthcheck-free](https://clawskills.sh/skills/bamontejano-skill-doctorbot-healthcheck-free) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [iisweetheartii-agentgram-social](https://clawskills.sh/skills/iisweetheartii-agentgram-social) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [nagellack5c-lan-media-server](https://clawskills.sh/skills/nagellack5c-lan-media-server) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [evolinkai-evolink-media](https://clawskills.sh/skills/evolinkai-evolink-media) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [iisweetheartii-agentgram](https://clawskills.sh/skills/iisweetheartii-agentgram) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [pharmacist9527-cheapest-image](https://clawskills.sh/skills/pharmacist9527-cheapest-image) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [ahmedthegeek-moltysmind](https://clawskills.sh/skills/ahmedthegeek-moltysmind) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [psmamm-social-media-agent](https://clawskills.sh/skills/psmamm-social-media-agent) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [sanjay-gthb-server-health-agent](https://clawskills.sh/skills/sanjay-gthb-server-health-agent) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [jhillin8-mindfulness-meditation](https://clawskills.sh/skills/jhillin8-mindfulness-meditation) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [lyoungblood-morpho-earn](https://clawskills.sh/skills/lyoungblood-morpho-earn) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [xejrax-media-player](https://clawskills.sh/skills/xejrax-media-player) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [bilalmohamed187-cpu-gcal-pro](https://clawskills.sh/skills/bilalmohamed187-cpu-gcal-pro) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [mrummler17-repomedic](https://clawskills.sh/skills/mrummler17-repomedic) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [dinstein-media-news-digest](https://clawskills.sh/skills/dinstein-media-news-digest) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [cgtreadw-health-guardian](https://clawskills.sh/skills/cgtreadw-health-guardian) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [engahmedsalah358-lgtm-ahmed](https://clawskills.sh/skills/engahmedsalah358-lgtm-ahmed) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [seanwyngaard-social-media-content-calendar](https://clawskills.sh/skills/seanwyngaard-social-media-content-calendar) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [mudgesbot-samsung-health](https://clawskills.sh/skills/mudgesbot-samsung-health) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [djemec-bioskills](https://clawskills.sh/skills/djemec-bioskills) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [oblivisheee-wol-sleep-pc](https://clawskills.sh/skills/oblivisheee-wol-sleep-pc) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [agent-skill-bus](https://github.com/ShunsukeHayashi/agent-skill-bus) | — | ⭐ C | 🟢 Active | ![](https://img.shields.io/github/stars/ShunsukeHayashi/agent-skill-bus?style=flat-square) | The missing runtime for Agent Skills — health monitoring, self-improvement, and dependency management for any AI agent framework. Zero dependencies. |
| [openclaw-dashboard](https://github.com/ChristianAlmurr/openclaw-dashboard) | OpenClaw | ⭐ C | 🟢 Active | ![](https://img.shields.io/github/stars/ChristianAlmurr/openclaw-dashboard?style=flat-square) | Mission Control dashboard for monitoring and managing AI agent fleets. Track costs, performance, context health, security posture, and market intelligence. |
| [nullhub](https://github.com/nullclaw/nullhub) | OpenClaw | ⭐ C | 🟢 Active | ![](https://img.shields.io/github/stars/nullclaw/nullhub?style=flat-square) | Management console for the Null ecosystem — install, configure, and monitor AI agents, orchestration workflows, task pipelines, and system health |
| [openclaw-team-builder](https://github.com/eggyrooch-blip/openclaw-team-builder) | OpenClaw | ⭐ C | 🟢 Active | ![](https://img.shields.io/github/stars/eggyrooch-blip/openclaw-team-builder?style=flat-square) | AI agent team management for OpenClaw — org tree, templates, health check, auto-fix, rollback. ClawhHub Skill. |

**[→ More clinical skills](categories/clinical.md)**

---

| [ricardotrevisan-garmin-tracker](https://clawskills.sh/skills/ricardotrevisan-garmin-tracker) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [freakyflow-garmin-pulse](https://clawskills.sh/skills/freakyflow-garmin-pulse) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [nftechie-garmin-skill](https://clawskills.sh/skills/nftechie-garmin-skill) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [clinicalmem](https://github.com/star-ga/clinicalmem) | MCP Server | ⭐ C | 🟢 Active | ![](https://img.shields.io/github/stars/star-ga/clinicalmem?style=flat-square) | Persistent, auditable clinical memory for healthcare AI agents. MCP + A2A. Powered by mind-mem and MIND Lang scoring kernels. Built for Agents Assemble Healthcare AI Hackathon. |
## Medical MCP Servers

> Model Context Protocol servers providing structured access to medical databases and healthcare APIs.

| Server | Grade | Maintenance | Stars | Description |
|--------|-------|-------------|-------|-------------|
| [BioMCP](https://github.com/genomoncology/biomcp) | ⭐⭐⭐ A | 🟢 Active | ![](https://img.shields.io/github/stars/genomoncology/biomcp?style=flat-square) | Unified grammar across 15+ biomedical APIs: PubMed, ClinicalTrials.gov, ClinVar, gnomAD, ChEMBL, UniProt, etc. 12 entity types with cross-entity pivots. Python CLI + MCP server (`pip install biomcp-cli`). Also installs as Claude Code skill. |
| [m3](https://github.com/rafiattrach/m3) | ⭐⭐ B+ | 🟢 Active | ![](https://img.shields.io/github/stars/rafiattrach/m3?style=flat-square) | MCP server for natural-language querying of MIMIC-IV clinical data via local SQLite demos or BigQuery backends. Includes docs, benchmarks, Docker, and Python packaging for healthcare research workflows. |
| [medical-mcp](https://github.com/JamesANZ/medical-mcp) | ⭐⭐ B | 🟢 Active | ![](https://img.shields.io/github/stars/JamesANZ/medical-mcp?style=flat-square) | Zero-config local MCP server for FDA drugs, WHO stats, PubMed, RxNorm, Google Scholar, clinical guidelines. Strong pediatric focus. No API keys needed. `npm install -g medical-mcp` |
| [medical-mcps](https://github.com/pascalwhoop/medical-mcps) | ⭐⭐ B | 🟢 Active | ![](https://img.shields.io/github/stars/pascalwhoop/medical-mcps?style=flat-square) | Unified biomedical APIs MCP server with 100+ tools across 14 medical and biological databases. Hosted endpoint, PyPI package, and ready-to-paste MCP client config. |
| [precision-medicine-mcp](https://github.com/lynnlangit/precision-medicine-mcp) | ⭐⭐ B- | 🟢 Active | ![](https://img.shields.io/github/stars/lynnlangit/precision-medicine-mcp?style=flat-square) | Precision-medicine MCP platform for genomics, transcriptomics, spatial biology, and imaging synthesis with clinician-in-the-loop review workflows. |
| [Nexonco MCP](https://github.com/Nexgene-Research/nexonco-mcp) | ⭐⭐ B- | 🔴 Stale | ![](https://img.shields.io/github/stars/Nexgene-Research/nexonco-mcp?style=flat-square) | CIViC-backed precision-oncology MCP server for structured evidence search across genes, variants, diseases, drugs, and phenotypes. PyPI and Docker setup, citation-rich reports, and clear Claude Desktop docs. |
| [WSO2 FHIR MCP](https://github.com/wso2/fhir-mcp-server) | ⭐⭐⭐ A- | 🟢 Active | ![](https://img.shields.io/github/stars/wso2/fhir-mcp-server?style=flat-square) | Enterprise FHIR bridge for AI agents with SMART-on-FHIR OAuth. Tested with Epic EHR. Multiple transports (stdio, SSE, HTTP). Docker + PyPI. Apache 2.0. |
| [fhir-terminology-server-mcp-wrapper](https://github.com/viniciusfinger/fhir-terminology-server-mcp-wrapper) | ⭐⭐ B- | 🟢 Active | ![](https://img.shields.io/github/stars/viniciusfinger/fhir-terminology-server-mcp-wrapper?style=flat-square) | FastMCP wrapper for FHIR terminology operations: code lookup, validation, ValueSet expansion, translation, and subsumption checks against any external terminology server. Includes pytest coverage. |
| [FHIR MCP Server (Momentum)](https://github.com/the-momentum/fhir-mcp-server) | ⭐⭐ B | 🟡 Moderate | — | Connects AI agents to FHIR servers; query patient history in natural language. |
| [DICOM MCP](https://github.com/ChristianHinge/dicom-mcp) | ⭐⭐ B+ | 🟡 Moderate | ![](https://img.shields.io/github/stars/ChristianHinge/dicom-mcp?style=flat-square) | Query, read, and move medical images/reports from PACS. Only MCP server targeting DICOM infrastructure. PyPI: `dicom-mcp`. |
| [MOSAICX](https://github.com/DIGIT-X-Lab/MOSAICX) | ⭐⭐ B+ | 🟢 Active | ![](https://img.shields.io/github/stars/DIGIT-X-Lab/MOSAICX?style=flat-square) | Local-first clinical-document extraction toolkit with radiology/pathology JSON pipelines, de-identification, patient timeline summarization, and optional MCP server integration. Ships with Docker, PyPI install, and extensive tests/docs. |
| [ab-health-mcp](https://github.com/JCrossman/ab-health-mcp) | ⭐⭐ B- | 🟢 Active | ![](https://img.shields.io/github/stars/JCrossman/ab-health-mcp?style=flat-square) | Read-only Alberta health-records MCP for My Health Records and AHS MyChart. Exposes 44 tools for labs, meds, imaging, vitals, visits, and documents with local or remote auth plus demo mode. |
| [MedCP](https://github.com/BaranziniLab/MedCP) | ⭐ C+ | 🟢 Active | ![](https://img.shields.io/github/stars/BaranziniLab/MedCP?style=flat-square) | Local-first medical MCP that links EHR databases and biomedical knowledge graphs for natural-language clinical queries. Ships as a Claude Desktop `.mcpb` extension or `uvx` server with encrypted credential storage and benchmark assets. |
| [OMOP MCP](https://github.com/OHNLP/omop_mcp) | ⭐⭐ B | 🟡 Moderate | — | Map clinical terminology to OMOP concepts using LLMs for healthcare data standardization. |
| [OMOPHub MCP](https://github.com/OMOPHub/omophub-mcp) | ⭐⭐ B | 🟢 Active | ![](https://img.shields.io/github/stars/OMOPHub/omophub-mcp?style=flat-square) | Production-ready MCP server for OHDSI vocabularies. Search and map SNOMED CT, ICD-10, RxNorm, LOINC, and other OMOP concepts from any MCP client via the hosted OMOPHub API. |
| [Snowstorm MCP Server](https://github.com/IHTSDO/snowstorm-mcp-server) | ⭐⭐ B- | 🟢 Active | ![](https://img.shields.io/github/stars/IHTSDO/snowstorm-mcp-server?style=flat-square) | Official SNOMED CT MCP server from IHTSDO. Supports terminology search, lookup, validation, hierarchy navigation, and ValueSet expansion against Snowstorm or Snowstorm Lite, with CI tests and hosted/local deployment docs. |
| [sct](https://github.com/pacharanero/sct) | ⭐⭐ B- | 🟢 Active | ![](https://img.shields.io/github/stars/pacharanero/sct?style=flat-square) | Local-first SNOMED CT toolchain that converts RF2 into NDJSON, SQLite, Parquet, Markdown, and a stdio MCP server for terminology search, refset queries, hierarchy navigation, and semantic lookup. |
| [mcp-simple-pubmed](https://github.com/andybrandt/mcp-simple-pubmed) | ⭐⭐ B | 🟢 Active | ![](https://img.shields.io/github/stars/andybrandt/mcp-simple-pubmed?style=flat-square) | Search and read medical/life sciences papers from PubMed. Simple and focused. |
| [ncbi-mcp-server](https://github.com/vitorpavinato/ncbi-mcp-server) | ⭐ C | 🟡 Moderate | — | Advanced PubMed search with MeSH integration, related articles, batch processing. |
| [apple-health-mcp-server](https://github.com/the-momentum/apple-health-mcp-server) | ⭐⭐ B | 🟡 Moderate | — | Access exported Apple Health data with analytics. *(Note: project has evolved into "Open Wearables" — broader multi-source health data platform)* |
| [VytalLink](https://github.com/xmartlabs/vytalLink) | ⭐ C+ | 🟢 Active | ![](https://img.shields.io/github/stars/xmartlabs/vytalLink?style=flat-square) | Privacy-focused digital-health platform with a Node.js MCP server and Flutter app. Connects Apple Health, Google Health Connect, and wearable data for agent queries and on-device sync. |
| [fulcra-context-mcp](https://github.com/fulcradynamics/fulcra-context-mcp) | ⭐ C+ | 🟡 Moderate | — | Personal biometric data: sleep, heart rate, HRV, glucose, workouts via Fulcra Life API. *(Note: sparse docs; requires Fulcra account and OAuth setup)* |
| [verilexdata-mcp](https://github.com/carrierone/verilexdata-mcp) | ⭐ C | 🟡 Moderate | — | 20 structured datasets including NPI healthcare provider registry. Pay-per-query. *(Note: general-purpose data tool, not purely medical)* |
| [healthcare-data-mcp](https://github.com/ajhcs/healthcare-data-mcp) | ⭐ C+ | 🟢 Active | ![](https://img.shields.io/github/stars/ajhcs/healthcare-data-mcp?style=flat-square) | Healthcare analytics MCP suite with 13 servers and 69 tools across CMS facilities, quality metrics, service areas, workforce, price transparency, and market intelligence. Strong docs, Docker setup, and public-data safeguards. |
| [medical-calc-mcp](https://github.com/u9401066/medical-calc-mcp) | MCP Server | ⭐ C | 🟢 Active | ![](https://img.shields.io/github/stars/u9401066/medical-calc-mcp?style=flat-square) | 🏥 MCP Server with 121 validated medical calculators for AI agents. DDD architecture, evidence-based formulas with PMID citations. Supports Claude, GPT, and other LLM integrations. |
| [openevidence-mcp](https://github.com/bakhtiersizhaev/openevidence-mcp) | MCP Server | ⭐ C | 🟢 Active | ![](https://img.shields.io/github/stars/bakhtiersizhaev/openevidence-mcp?style=flat-square) | OpenEvidence MCP: open-source browser-session MCP server for human and AI-agent medical workflows |
| [nucleus-apple-mcp](https://github.com/zish-rob-crur/nucleus-apple-mcp) | MCP Server | ⭐ C | 🟢 Active | ![](https://img.shields.io/github/stars/zish-rob-crur/nucleus-apple-mcp?style=flat-square) | A macOS Model Context Protocol (MCP) server that acts as the central nervous system for your AI agent. Bridges Calendar, Reminders, Notes, and Health data using a hybrid Python + Swift architecture. |
| [thinktankmachine-adhd-ssistant](https://clawskills.sh/skills/thinktankmachine-adhd-ssistant) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [mcp-hangar](https://github.com/mcp-hangar/mcp-hangar) | MCP Server | ⭐ C | 🟢 Active | ![](https://img.shields.io/github/stars/mcp-hangar/mcp-hangar?style=flat-square) | Efficient lifecycle management for MCP servers. Hot-loading, health checks, and container orchestration for the Model Context Protocol. |
| [jarvis](https://github.com/isair/jarvis) | MCP Server | ⭐ C | 🟢 Active | ![](https://img.shields.io/github/stars/isair/jarvis?style=flat-square) | Your AI assistant that never forgets and runs 100% privately on your computer. Leave it on 24/7 - it learns your preferences, helps with code, manages your health goals, searches the web, and conne... |
| [helixir](https://github.com/bookedsolidtech/helixir) | MCP Server | ⭐ C | 🟢 Active | ![](https://img.shields.io/github/stars/bookedsolidtech/helixir?style=flat-square) | MCP server that gives AI coding agents deep knowledge of any web component library — properties, events, slots, CSS parts, design tokens, accessibility, health scoring, and more. Works with Claude,... |
| [mcp-ssh-manager](https://github.com/bvisible/mcp-ssh-manager) | MCP Server | ⭐ C | 🟢 Active | ![](https://img.shields.io/github/stars/bvisible/mcp-ssh-manager?style=flat-square) | MCP SSH Server: 37 tools for remote SSH management | Claude Code & OpenAI Codex | DevOps automation, backups, database operations, health monitoring |
| [codescene-mcp-server](https://github.com/codescene-oss/codescene-mcp-server) | MCP Server | ⭐ C | 🟢 Active | ![](https://img.shields.io/github/stars/codescene-oss/codescene-mcp-server?style=flat-square) | The CodeScene MCP Server exposes CodeScene’s Code Health analysis as local AI-friendly tools. |
| [clinicaltrialsgov-mcp-server](https://github.com/cyanheads/clinicaltrialsgov-mcp-server) | MCP Server | ⭐ C | 🟢 Active | ![](https://img.shields.io/github/stars/cyanheads/clinicaltrialsgov-mcp-server?style=flat-square) | MCP server for the ClinicalTrials.gov v2 API. Allow LLMs to search trials, retrieve study details, compare studies, analyze trends, and match patients to eligible trials. |
| [ClinicalTrials.gov Explorer (BLEN)](https://github.com/blencorp/clinicaltrial-mcp-server) | ⭐ C+ | 🟢 Active | ![](https://img.shields.io/github/stars/blencorp/clinicaltrial-mcp-server?style=flat-square) | TypeScript MCP server for the ClinicalTrials.gov v2 API using a typed SDK plus sandboxed "code mode" execution. Strong quickstart, architecture docs, tests, and local/hosted deployment paths. |
| [pyomop](https://github.com/dermatologist/pyomop) | MCP Server | ⭐ C | 🟢 Active | ![](https://img.shields.io/github/stars/dermatologist/pyomop?style=flat-square) | Python package for managing OHDSI clinical data models. Includes support for LLM based plain text queries, MCP server and FHIR import. |
| [national-mcp-pai-oncology-trials](https://github.com/kevinkawchak/national-mcp-pai-oncology-trials) | MCP Server | ⭐ C | 🟢 Active | ![](https://img.shields.io/github/stars/kevinkawchak/national-mcp-pai-oncology-trials?style=flat-square) | National MCP servers for Physical AI oncology clinical trial systems |
| [langcare-mcp-fhir](https://github.com/langcare/langcare-mcp-fhir) | MCP Server | ⭐ C | 🟢 Active | ![](https://img.shields.io/github/stars/langcare/langcare-mcp-fhir?style=flat-square) | Enterprise-grade MCP Server for FHIR-based EMRs, designed for robust deployments in agentic AI platforms. |
| [healsens-fhirmcp](https://github.com/healsens/healsens-fhirmcp) | MCP Server | ⭐⭐ B- | 🟢 Active | ![](https://img.shields.io/github/stars/healsens/healsens-fhirmcp?style=flat-square) | Open-source, conformance-aware FHIR R4/R5 MCP server with embedded structure/operation registries plus live `CapabilityStatement` grounding. Read-only by design; supports stdio and SSE for safer healthcare agent integrations. |
| [mcp-fhir-patient-index](https://github.com/Shaumik-Ashraf/mcp-fhir-patient-index) | MCP Server | ⭐ C | 🟢 Active | ![](https://img.shields.io/github/stars/Shaumik-Ashraf/mcp-fhir-patient-index?style=flat-square) | Rails 8 master patient index with built-in FHIR R4 API, MCP server, web UI, CI, and Inferno test instructions. Early-stage but technically solid reference stack for patient lookup workflows. |
| [clinical-decision-support-mcp](https://github.com/avadh-pro/clinical-decision-support-mcp) | MCP Server | ⭐ C+ | 🟢 Active | ![](https://img.shields.io/github/stars/avadh-pro/clinical-decision-support-mcp?style=flat-square) | FHIR-backed clinical decision support MCP with patient lookup, risk-factor summarization, drug-allergy checking, Docker setup, tests, and demo patient data for local evaluation. |
| [EPIC-Style EHR MCP Server](https://github.com/pcjx8/epic-ehr-mcp-server) | MCP Server | ⭐ C+ | 🟢 Active | ![](https://img.shields.io/github/stars/pcjx8/epic-ehr-mcp-server?style=flat-square) | EPIC-style EHR simulator MCP with JWT auth, 20+ healthcare tools, Docker/quickstart docs, mock patient workflows, and FHIR/HL7 prototyping support for healthcare agent development. |
| [medrecon](https://github.com/astraedus/medrecon) | MCP Server | ⭐ C+ | 🟢 Active | ![](https://img.shields.io/github/stars/astraedus/medrecon?style=flat-square) | Medication-reconciliation MCP/A2A system built on FHIR. Includes clinician and patient agent flows, TypeScript services, local demo setup, and reconciliation artifacts for care-transition workflows. |
| [oncofiles](https://github.com/peter-fusek/oncofiles) | ⭐⭐ B- | 🟢 Active | ![](https://img.shields.io/github/stars/peter-fusek/oncofiles?style=flat-square) | Cancer-care MCP server that organizes Gmail, Google Drive, and Calendar medical records for patients and caregivers. Multi-patient isolation, OAuth setup, demo dashboard, and 600+ passing tests. |
| [mcp-snomed-ct](https://github.com/eigenbau/mcp-snomed-ct) | MCP Server | ⭐ C | 🟢 Active | ![](https://img.shields.io/github/stars/eigenbau/mcp-snomed-ct?style=flat-square) | MCP server for SNOMED CT concept lookup via any FHIR R4 terminology server |
| [healthcare-mcp-public](https://github.com/Cicatriiz/healthcare-mcp-public) | MCP Server | ⭐ C | 🟢 Active | ![](https://img.shields.io/github/stars/Cicatriiz/healthcare-mcp-public?style=flat-square) | A Model Context Protocol (MCP) server providing AI assistants with access to healthcare data and medical information tools, including FDA drug info, PubMed, medRxiv, NCBI Bookshelf, clinical trials... |
| [dicom-mcp-server](https://github.com/fluxinc/dicom-mcp-server) | MCP Server | ⭐ C | 🔴 Stale | ![](https://img.shields.io/github/stars/fluxinc/dicom-mcp-server?style=flat-square) | A server for managing contextual data in DICOM tools, supporting medical imaging and machine learning workflows. |
| [pubmed-mcp-server](https://github.com/cyanheads/pubmed-mcp-server) | MCP Server | ⭐ C | 🟢 Active | ![](https://img.shields.io/github/stars/cyanheads/pubmed-mcp-server?style=flat-square) | MCP server for the NCBI E-utilities API. Search PubMed, fetch article metadata, generate citations, explore MeSH terms, and discover related research. Runs over stdio or HTTP. Deployable to Cloudfl... |
| [pubmed-search-mcp](https://github.com/u9401066/pubmed-search-mcp) | MCP Server | ⭐ C | 🟢 Active | ![](https://img.shields.io/github/stars/u9401066/pubmed-search-mcp?style=flat-square) | 🔬 Professional MCP server for biomedical literature research — 40 tools, multi-source search (PubMed, Europe PMC, CORE, OpenAlex), full-text access, citation networks, PICO analysis, and more |
| [paper-search-mcp](https://github.com/openags/paper-search-mcp) | MCP Server | ⭐ C | 🟢 Active | ![](https://img.shields.io/github/stars/openags/paper-search-mcp?style=flat-square) | A MCP for searching and downloading academic papers from multiple sources like arXiv, PubMed, bioRxiv, etc. |
| [pm-skills](https://github.com/cookjohn/pm-skills) | MCP Server | ⭐ C | 🟢 Active | ![](https://img.shields.io/github/stars/cookjohn/pm-skills?style=flat-square) | PubMed skills for Claude Code — literature search, citation export, and Zotero integration via Chrome DevTools MCP |
| [claude-scholar](https://github.com/jessevanwyk1/claude-scholar) | Claude Code | ⭐ C | 🟢 Active | ![](https://img.shields.io/github/stars/jessevanwyk1/claude-scholar?style=flat-square) | 🚀 Simplify your research workflow with Claude Scholar, the complete configuration for Claude Code in data science, AI, and academic writing. |
| [research-workflow-assistant](https://github.com/andre-inter-collab-llc/research-workflow-assistant) | MCP Server | ⭐ C | 🟢 Active | ![](https://img.shields.io/github/stars/andre-inter-collab-llc/research-workflow-assistant?style=flat-square) | Open-source AI research assistant for VS Code + GitHub Copilot. Connects to PubMed, OpenAlex, Semantic Scholar, Europe PMC, CrossRef, and Zotero via MCP servers. Custom agents guide systematic revi... |
| [med-paper-assistant](https://github.com/u9401066/med-paper-assistant) | — | ⭐ C | 🟢 Active | ![](https://img.shields.io/github/stars/u9401066/med-paper-assistant?style=flat-square) | 🔬 AI-powered medical paper writing toolkit — from PubMed search to Word export, all inside VS Code |
| [ScienceClaw](https://github.com/beita6969/ScienceClaw) | OpenClaw | ⭐ C | 🟢 Active | ![](https://img.shields.io/github/stars/beita6969/ScienceClaw?style=flat-square) | 🔬🦞 A self-evolving AI research colleague for scientists. 285 skills, zero hallucination, persistent memory. |
| [ai-writing-skills](https://github.com/HeartWise-AI/ai-writing-skills) | — | ⭐ C | 🟢 Active | ![](https://img.shields.io/github/stars/HeartWise-AI/ai-writing-skills?style=flat-square) | AI-assisted academic writing skills for medical AI research |
| [humanizer_academic](https://github.com/matsuikentaro1/humanizer_academic) | Claude Code | ⭐ C | 🟢 Active | ![](https://img.shields.io/github/stars/matsuikentaro1/humanizer_academic?style=flat-square) | A Claude Code skill that removes signs of AI-generated writing from academic medical papers, making them sound more natural and professionally written. |
| [ai-research-army](https://github.com/TerryFYL/ai-research-army) | Claude Code | ⭐ C | 🟢 Active | ![](https://img.shields.io/github/stars/TerryFYL/ai-research-army?style=flat-square) | AI Research Army: 10 AI specialists collaborate autonomously in Claude Code — from raw clinical data to submission-ready medical manuscripts. |
| [gitgoodordietrying-emergency-rescue](https://clawskills.sh/skills/gitgoodordietrying-emergency-rescue) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [gitgoodordietrying-cron-scheduling](https://clawskills.sh/skills/gitgoodordietrying-cron-scheduling) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [gitgoodordietrying-data-validation](https://clawskills.sh/skills/gitgoodordietrying-data-validation) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [gitgoodordietrying-csv-pipeline](https://clawskills.sh/skills/gitgoodordietrying-csv-pipeline) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [gitgoodordietrying-git-workflows](https://clawskills.sh/skills/gitgoodordietrying-git-workflows) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [gitgoodordietrying-infra-as-code](https://clawskills.sh/skills/gitgoodordietrying-infra-as-code) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [gekacross-personal-nutrition](https://clawskills.sh/skills/gekacross-personal-nutrition) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [gitgoodordietrying-api-dev](https://clawskills.sh/skills/gitgoodordietrying-api-dev) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [tkuehnl-feed-diet](https://clawskills.sh/skills/tkuehnl-feed-diet) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [yoavfael-intermittent-fasting-skill](https://clawskills.sh/skills/yoavfael-intermittent-fasting-skill) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [gitgoodordietrying-makefile-build](https://clawskills.sh/skills/gitgoodordietrying-makefile-build) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [gitgoodordietrying-cicd-pipeline](https://clawskills.sh/skills/gitgoodordietrying-cicd-pipeline) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [gitgoodordietrying-encoding-formats](https://clawskills.sh/skills/gitgoodordietrying-encoding-formats) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [personal-health-template](https://github.com/mslavov/personal-health-template) | Claude Code | ⭐ C | 🟡 Moderate | ![](https://img.shields.io/github/stars/mslavov/personal-health-template?style=flat-square) | Personal health knowledge base template for Claude Code - track biomarkers, Apple Health data, medical documents, and research |
| [james-southendsolutions-camino-fitness-finder](https://clawskills.sh/skills/james-southendsolutions-camino-fitness-finder) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [harrey401-lofy-fitness](https://clawskills.sh/skills/harrey401-lofy-fitness) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [dr-ralph](https://github.com/blencorp/dr-ralph) | Claude Code | ⭐ C | 🟢 Active | ![](https://img.shields.io/github/stars/blencorp/dr-ralph?style=flat-square) | A Claude Code plugin for AI-assisted medical diagnostics with comprehensive symptom analysis and research-backed treatment plans. |
| [eftalyurtseven-business-card-generation](https://clawskills.sh/skills/eftalyurtseven-business-card-generation) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [eftalyurtseven-youtube-thumbnail-generation](https://clawskills.sh/skills/eftalyurtseven-youtube-thumbnail-generation) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [autogame-17-qr-generator](https://clawskills.sh/skills/autogame-17-qr-generator) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [eftalyurtseven-depth-map-generation](https://clawskills.sh/skills/eftalyurtseven-depth-map-generation) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [foscomputerservices-fosmvvm-react-view-generator](https://clawskills.sh/skills/foscomputerservices-fosmvvm-react-view-generator) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [wells1137-sfx-generator](https://clawskills.sh/skills/wells1137-sfx-generator) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [martinforsulu-neo-github-readme-generator](https://clawskills.sh/skills/martinforsulu-neo-github-readme-generator) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [vokaplok-generect-api](https://clawskills.sh/skills/vokaplok-generect-api) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [thortheai1-hash-thor-generator](https://clawskills.sh/skills/thortheai1-hash-thor-generator) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [shoafsystems-image-and-video-generation-vydra](https://clawskills.sh/skills/shoafsystems-image-and-video-generation-vydra) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [warm-wm-volcengine-image-generate](https://clawskills.sh/skills/warm-wm-volcengine-image-generate) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [ustc-yxw-ascii-art-generator](https://clawskills.sh/skills/ustc-yxw-ascii-art-generator) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [akhmittra-ctf-writeup-generator](https://clawskills.sh/skills/akhmittra-ctf-writeup-generator) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [ryudi84-sovereign-api-docs-generator](https://clawskills.sh/skills/ryudi84-sovereign-api-docs-generator) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [svkozak-sfsymbol-generator](https://clawskills.sh/skills/svkozak-sfsymbol-generator) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [dadaniya99-zenmux-image-generation](https://clawskills.sh/skills/dadaniya99-zenmux-image-generation) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [eftalyurtseven-brochure-design-generation](https://clawskills.sh/skills/eftalyurtseven-brochure-design-generation) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [eftalyurtseven-eachlabs-image-generation](https://clawskills.sh/skills/eftalyurtseven-eachlabs-image-generation) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [evolinkai-cheapest-image-generation](https://clawskills.sh/skills/evolinkai-cheapest-image-generation) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [atyachin-lead-generation](https://clawskills.sh/skills/atyachin-lead-generation) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [generaljerel-copilotkit-react](https://clawskills.sh/skills/generaljerel-copilotkit-react) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [jackycser-seedance-video-generation](https://clawskills.sh/skills/jackycser-seedance-video-generation) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [parasharnagle-mindmap-generator](https://clawskills.sh/skills/parasharnagle-mindmap-generator) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [eftalyurtseven-ai-headshot-generation](https://clawskills.sh/skills/eftalyurtseven-ai-headshot-generation) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [wanng-ide-folder-tree-generator](https://clawskills.sh/skills/wanng-ide-folder-tree-generator) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [calbabyjr-visa-business-planner](https://clawskills.sh/skills/calbabyjr-visa-business-planner) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [kesslerio-babyconnect](https://clawskills.sh/skills/kesslerio-babyconnect) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [deepseekoracle-recursive-generosity-protocol](https://clawskills.sh/skills/deepseekoracle-recursive-generosity-protocol) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [seanwyngaard-technical-doc-generator](https://clawskills.sh/skills/seanwyngaard-technical-doc-generator) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [mkpareek0315-social-media-planner](https://clawskills.sh/skills/mkpareek0315-social-media-planner) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [openclaw-never-die](https://github.com/kennyzheng-builds/openclaw-never-die) | OpenClaw | ⭐ C | 🟢 Active | ![](https://img.shields.io/github/stars/kennyzheng-builds/openclaw-never-die?style=flat-square) | Production-ready auto-recovery system for OpenClaw Gateway. Makes AI agents as reliable as they are brilliant. 24/7 operation with automatic health monitoring, crash recovery, and smart restart logic. |
| [underbench2-gif-ub2-markdown-report-generator](https://clawskills.sh/skills/underbench2-gif-ub2-markdown-report-generator) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [foscomputerservices-fosmvvm-ui-tests-generator](https://clawskills.sh/skills/foscomputerservices-fosmvvm-ui-tests-generator) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [eftalyurtseven-ar-filter-generation](https://clawskills.sh/skills/eftalyurtseven-ar-filter-generation) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [evolinkai-best-image-generation](https://clawskills.sh/skills/evolinkai-best-image-generation) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [eftalyurtseven-digital-twin-generation](https://clawskills.sh/skills/eftalyurtseven-digital-twin-generation) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [cerbug45-sql-query-generator](https://clawskills.sh/skills/cerbug45-sql-query-generator) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [shahbaz02197ali-cmd-social-media-lead-generation](https://clawskills.sh/skills/shahbaz02197ali-cmd-social-media-lead-generation) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [cameron-jovan-email-capture-generator](https://clawskills.sh/skills/cameron-jovan-email-capture-generator) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [eftalyurtseven-book-cover-generation](https://clawskills.sh/skills/eftalyurtseven-book-cover-generation) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [olisim02-smart-meme-generator](https://clawskills.sh/skills/olisim02-smart-meme-generator) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [eftalyurtseven-certificate-generation](https://clawskills.sh/skills/eftalyurtseven-certificate-generation) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [wells1137-music-generator](https://clawskills.sh/skills/wells1137-music-generator) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [fratua-readme-generator](https://clawskills.sh/skills/fratua-readme-generator) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [autogame-17-auto-test-generator](https://clawskills.sh/skills/autogame-17-auto-test-generator) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [tobisamaa-content-generation](https://clawskills.sh/skills/tobisamaa-content-generation) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [foscomputerservices-fosmvvm-fluent-datamodel-generator](https://clawskills.sh/skills/foscomputerservices-fosmvvm-fluent-datamodel-generator) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [holic101-pubmed2blog](https://clawskills.sh/skills/holic101-pubmed2blog) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [vonzellu-ai-3d-generator](https://clawskills.sh/skills/vonzellu-ai-3d-generator) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [seanwyngaard-contract-generator](https://clawskills.sh/skills/seanwyngaard-contract-generator) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [nbf819-web-pr-generator](https://clawskills.sh/skills/nbf819-web-pr-generator) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [killgfat-pubmed-edirect](https://clawskills.sh/skills/killgfat-pubmed-edirect) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [foscomputerservices-fosmvvm-serverrequest-test-generator](https://clawskills.sh/skills/foscomputerservices-fosmvvm-serverrequest-test-generator) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [foscomputerservices-fosmvvm-serverrequest-generator](https://clawskills.sh/skills/foscomputerservices-fosmvvm-serverrequest-generator) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [eftalyurtseven-3d-model-generation](https://clawskills.sh/skills/eftalyurtseven-3d-model-generation) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [foscomputerservices-fosmvvm-leaf-view-generator](https://clawskills.sh/skills/foscomputerservices-fosmvvm-leaf-view-generator) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [generaljerel-copilotkit-runtime-patterns](https://clawskills.sh/skills/generaljerel-copilotkit-runtime-patterns) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [tarasinghrajput-curriculum-generator](https://clawskills.sh/skills/tarasinghrajput-curriculum-generator) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [directivecreator-sideload-avatar-generator](https://clawskills.sh/skills/directivecreator-sideload-avatar-generator) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [martinforsulu-neo-graphql-ts-generator](https://clawskills.sh/skills/martinforsulu-neo-graphql-ts-generator) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [eftalyurtseven-app-store-screenshot-generation](https://clawskills.sh/skills/eftalyurtseven-app-store-screenshot-generation) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [near2sea-generate-news-article](https://clawskills.sh/skills/near2sea-generate-news-article) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [jackycser-seedance-video-generation-byteplus](https://clawskills.sh/skills/jackycser-seedance-video-generation-byteplus) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [sophiaashi-general-writing](https://clawskills.sh/skills/sophiaashi-general-writing) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [clowreed-website-generator](https://clawskills.sh/skills/clowreed-website-generator) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [xuyuan0805-xy-pubmed-pdf-downloader](https://clawskills.sh/skills/xuyuan0805-xy-pubmed-pdf-downloader) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [josunlp-pi-health](https://clawskills.sh/skills/josunlp-pi-health) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [eftalyurtseven-ai-influencer-generation](https://clawskills.sh/skills/eftalyurtseven-ai-influencer-generation) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [ryudi84-sovereign-test-generator](https://clawskills.sh/skills/ryudi84-sovereign-test-generator) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [darshanochandak-heartbeat-scanner](https://clawskills.sh/skills/darshanochandak-heartbeat-scanner) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [ryudi84-sovereign-api-mock-generator](https://clawskills.sh/skills/ryudi84-sovereign-api-mock-generator) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [nhype-generate-presentation](https://clawskills.sh/skills/nhype-generate-presentation) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [eftalyurtseven-album-cover-generation](https://clawskills.sh/skills/eftalyurtseven-album-cover-generation) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [martinforsulu-neo-tf-module-generator](https://clawskills.sh/skills/martinforsulu-neo-tf-module-generator) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [warm-wm-volcengine-video-generate](https://clawskills.sh/skills/warm-wm-volcengine-video-generate) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [foscomputerservices-fosmvvm-fields-generator](https://clawskills.sh/skills/foscomputerservices-fosmvvm-fields-generator) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [foscomputerservices-fosmvvm-swiftui-view-generator](https://clawskills.sh/skills/foscomputerservices-fosmvvm-swiftui-view-generator) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [eftalyurtseven-ai-avatar-generation](https://clawskills.sh/skills/eftalyurtseven-ai-avatar-generation) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [claudiodrusus-shelly-brand-name-generator](https://clawskills.sh/skills/claudiodrusus-shelly-brand-name-generator) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [foscomputerservices-fosmvvm-viewmodel-generator](https://clawskills.sh/skills/foscomputerservices-fosmvvm-viewmodel-generator) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [juguangyuan520-dotcom-report-generator](https://clawskills.sh/skills/juguangyuan520-dotcom-report-generator) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [jirispilka-apify-lead-generation](https://clawskills.sh/skills/jirispilka-apify-lead-generation) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [brianrwagner-brw-content-idea-generator](https://clawskills.sh/skills/brianrwagner-brw-content-idea-generator) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [tmigone-invoice-generator](https://clawskills.sh/skills/tmigone-invoice-generator) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [vokaplok-generect](https://clawskills.sh/skills/vokaplok-generect) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [kakazhang50-tpt-generate-cover](https://clawskills.sh/skills/kakazhang50-tpt-generate-cover) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [generaljerel-copilotkit-agent-patterns](https://clawskills.sh/skills/generaljerel-copilotkit-agent-patterns) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [ide-rea-ai-ppt-generator](https://clawskills.sh/skills/ide-rea-ai-ppt-generator) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [highlander89-ai-lead-generator-skill](https://clawskills.sh/skills/highlander89-ai-lead-generator-skill) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [elihuvillaraus-excalidraw-diagram-generator](https://clawskills.sh/skills/elihuvillaraus-excalidraw-diagram-generator) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [foscomputerservices-fosmvvm-viewmodel-test-generator](https://clawskills.sh/skills/foscomputerservices-fosmvvm-viewmodel-test-generator) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [luruibu-beauty-generation-api](https://clawskills.sh/skills/luruibu-beauty-generation-api) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [eftalyurtseven-youtube-video-generation](https://clawskills.sh/skills/eftalyurtseven-youtube-video-generation) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [kenera-subskill-generation-rule](https://clawskills.sh/skills/kenera-subskill-generation-rule) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [luv005-renderful-generation](https://clawskills.sh/skills/luv005-renderful-generation) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [eftalyurtseven-eachlabs-video-generation](https://clawskills.sh/skills/eftalyurtseven-eachlabs-video-generation) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [pascalwhoop-medical-research-toolkit](https://clawskills.sh/skills/pascalwhoop-medical-research-toolkit) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [longevity-os](https://github.com/albert-ying/longevity-os) | OpenClaw | ⭐ C | 🟢 Active | ![](https://img.shields.io/github/stars/albert-ying/longevity-os?style=flat-square) | 太医院 — Agentic Longevity OS with 10 AI physicians. N-of-1 trials, cross-module pattern detection, PubMed-grounded insights, Bayesian causal inference. Works with Claude Code & OpenClaw. |
| [pubcrawl](https://github.com/nickjlamb/pubcrawl) | MCP Server | ⭐ C | 🟢 Active | ![](https://img.shields.io/github/stars/nickjlamb/pubcrawl?style=flat-square) | A peer-reviewed pub crawl through the literature — MCP server for PubMed & biomedical literature search |
| [mcp-for-research](https://github.com/aringadre76/mcp-for-research) | MCP Server | ⭐ C | 🟢 Active | ![](https://img.shields.io/github/stars/aringadre76/mcp-for-research?style=flat-square) | An MCP server that consolidates academic research across PubMed, Google Scholar, ArXiv, and JSTOR. Published on NPM with 5 tools. |
| [bgpt-mcp](https://github.com/connerlambden/bgpt-mcp) | MCP Server | ⭐ C | 🟢 Active | ![](https://img.shields.io/github/stars/connerlambden/bgpt-mcp?style=flat-square) | Search Paper Data from Any AI Tool |
| [chia-mcp](https://github.com/chia-health/chia-mcp) | MCP Server | ⭐ C | 🟢 Active | ![](https://img.shields.io/github/stars/chia-health/chia-mcp?style=flat-square) | Chia Health MCP Server — Patient workflow integration for a licensed US telehealth platform. Browse GLP-1 medications (semaglutide, tirzepatide), peptide therapies (sermorelin, NAD+, glutathione), ... |
| [octo-vista-api-x-mcp-server-example](https://github.com/department-of-veterans-affairs/octo-vista-api-x-mcp-server-example) | MCP Server | ⭐ C | 🟢 Active | ![](https://img.shields.io/github/stars/department-of-veterans-affairs/octo-vista-api-x-mcp-server-example?style=flat-square) | This example repository contains documentation about a Model Context Protocol (MCP) server that provides secure access to VA's VistA electronic health record (EHR) system, enabling AI applications ... |
| [health-record-mcp](https://github.com/jmandel/health-record-mcp) | MCP Server | ⭐ C | 🟢 Active | ![](https://img.shields.io/github/stars/jmandel/health-record-mcp?style=flat-square) | Connect to an EHR and make clinical data available via MCP |
| [hana-compass-api](https://github.com/mhaihq/hana-compass-api) | MCP Server | ⭐ C | 🔴 Stale | ![](https://img.shields.io/github/stars/mhaihq/hana-compass-api?style=flat-square) | API and MCP server for all EHR integration,Med Research via a single unified API |
| [hm_editor](https://github.com/huimeicloud/hm_editor) | — | ⭐ C | 🟢 Active | ![](https://img.shields.io/github/stars/huimeicloud/hm_editor?style=flat-square) | 一款轻量级、可扩展的、跨平台的、专为医疗信息化设计的电子病历编辑器内核，为EMR（电子病历系统）提供专业的结构化病历编辑与AI接入解决方案。 |
| [aguynextdoor-golemedin-mcp](https://clawskills.sh/skills/aguynextdoor-golemedin-mcp) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [openclaw-superpowers](https://github.com/ArchieIndian/openclaw-superpowers) | MCP Server | ⭐ C | 🟢 Active | ![](https://img.shields.io/github/stars/ArchieIndian/openclaw-superpowers?style=flat-square) | 44 plug-and-play skills for OpenClaw — self-modifying AI agent with cron scheduling, security guardrails, persistent memory, knowledge graphs, and MCP health monitoring. Your agent teaches itself n... |
| [3dslicer-claude-bridge](https://github.com/brainbloodbarrier/3dslicer-claude-bridge) | MCP Server | ⭐ C | 🟢 Active | ![](https://img.shields.io/github/stars/brainbloodbarrier/3dslicer-claude-bridge?style=flat-square) | MCP server bridging 3D Slicer with Claude Code for medical image analysis |
| [drug-interaction-mcp](https://github.com/MOB-sys/drug-interaction-mcp) | MCP Server | ⭐ C | 🟢 Active | ![](https://img.shields.io/github/stars/MOB-sys/drug-interaction-mcp?style=flat-square) | MCP server for drug-drug interaction checking. 176 evidence-based interactions from FDA/NIH. Works with Claude, ChatGPT, and any MCP-compatible AI. |
| [mcp-icd10](https://github.com/stabgan/mcp-icd10) | MCP Server | ⭐ C | 🟢 Active | ![](https://img.shields.io/github/stars/stabgan/mcp-icd10?style=flat-square) | Offline MCP server for ICD-10-CM, ICD-9-CM, ICD-10 WHO code lookup with GEMs crosswalk. 124K codes, 102K mappings. Zero API keys, zero network calls. |
| [nexonco-mcp](https://github.com/1sustgmboab/nexonco-mcp) | MCP Server | ⭐ C | 🟢 Active | ![](https://img.shields.io/github/stars/1sustgmboab/nexonco-mcp?style=flat-square) | An advanced MCP Server for accessing and analyzing clinical evidence data, with flexible search options to support precision medicine and oncology research. |
| [apple-health-mcp](https://github.com/smarzola/apple-health-mcp) | MCP Server | ⭐ C | 🟢 Active | ![](https://img.shields.io/github/stars/smarzola/apple-health-mcp?style=flat-square) | MCP server for Apple Health data — query your export with Claude |
| [dicom_download_mcp](https://github.com/PancrePal-xiaoyibao/dicom_download_mcp) | MCP Server | ⭐ C | 🟡 Moderate | ![](https://img.shields.io/github/stars/PancrePal-xiaoyibao/dicom_download_mcp?style=flat-square) | 社区志愿者贡献的dicom CT报告下载MCP工具，协议禁止商用禁止收费使用。 |
| [claw-ea](https://github.com/fshaan/claw-ea) | MCP Server | ⭐ C | 🟢 Active | ![](https://img.shields.io/github/stars/fshaan/claw-ea?style=flat-square) | MCP server for medical office automation — archives messages into Obsidian notes, Apple Calendar, and Reminders |
| [clinical-research-mcp](https://github.com/wjddusrb03/clinical-research-mcp) | MCP Server | ⭐ C | 🟢 Active | ![](https://img.shields.io/github/stars/wjddusrb03/clinical-research-mcp?style=flat-square) | MCP server for clinical research — PubMed papers, clinical trials, medical concepts. No API key needed. |
| [health-mcp-server](https://github.com/AiAgentKarl/health-mcp-server) | MCP Server | ⭐ C | 🟢 Active | ![](https://img.shields.io/github/stars/AiAgentKarl/health-mcp-server?style=flat-square) | Health and medical data for AI agents |
| [mesh-mcp](https://github.com/msuicaut/mesh-mcp) | MCP Server | ⭐ C | 🟢 Active | ![](https://img.shields.io/github/stars/msuicaut/mesh-mcp?style=flat-square) | An experimental MCP (Model Context Protocol) server connecting Claude to the U.S. National Library of Medicine (NLM) Medical Subject Headings (MeSH) linked data APIs, built to investigate the poten... |
| [amed-research-db](https://github.com/inutano/amed-research-db) | MCP Server | ⭐ C | 🟢 Active | ![](https://img.shields.io/github/stars/inutano/amed-research-db?style=flat-square) | AMED (Japan Agency for Medical Research and Development) research project database with REST API, MCP server, and analytics. ~3,800 projects from 2015-2025. |
| [dicom-mcp](https://github.com/sscotti/dicom-mcp) | MCP Server | ⭐ C+ | 🟢 Active | ![](https://img.shields.io/github/stars/sscotti/dicom-mcp?style=flat-square) | DICOM + FHIR MCP server and local dev stack for Orthanc/PACS workflows. Query studies, read encapsulated PDF reports, move images, manage mini-RIS orders, and test against bundled Docker services. |
| [HealthBridge MCP Server](https://github.com/Fulcria-Labs/healthbridge) | MCP Server | ⭐ C+ | 🟢 Active | ![](https://img.shields.io/github/stars/Fulcria-Labs/healthbridge?style=flat-square) | Clinical decision support MCP with 29 validated tools for drug interactions, risk scores, lab interpretation, renal/pediatric dosing, IV compatibility, pregnancy safety, opioid MEDD, and FHIR patient summaries. |
| [CzechMedMCP](https://github.com/petrsovadina/CzechMedMCP) | MCP Server | ⭐ C+ | 🟢 Active | ![](https://img.shields.io/github/stars/petrsovadina/CzechMedMCP?style=flat-square) | 60-tool MCP server bridging Czech and global healthcare sources: SUKL, ICD-10, provider registries, PubMed, ClinicalTrials.gov, OpenFDA, and genomics APIs. Includes tests, Docker, and hosted docs. |

**[→ More MCP servers](categories/mcp-servers.md)**

---

## Biomedical Research & Genomics

> Skills for bioinformatics, genomics, drug discovery, and scientific research.

| Skill | Platform | Grade | Maintenance | Stars | Description |
|-------|----------|-------|-------------|-------|-------------|
| [claude-scientific-skills](https://github.com/K-Dense-AI/claude-scientific-skills) | Claude Code / Multi | ⭐⭐⭐ A | 🟢 Active | ![](https://img.shields.io/github/stars/K-Dense-AI/claude-scientific-skills?style=flat-square) | 170+ scientific skill definitions (SKILL.md format) covering bioinformatics, cheminformatics, proteomics, clinical research, medical imaging. Install via agent platform (Claude Code, Cursor, Codex, Gemini CLI) — not standalone executables. 250+ database references. |
| [OpenBioMed Skills](https://github.com/PharMolix/OpenBioMed) | Claude Code / Multi | ⭐⭐ B+ | 🟢 Active | ![](https://img.shields.io/github/stars/PharMolix/OpenBioMed?style=flat-square) | Biomedical agent platform from PharMolix + AIR, Tsinghua with 45 installable skills for drug discovery, protein engineering, and single-cell omics. Repo includes `skills/` definitions, Python package, workflows, and docs. |
| [M4](https://github.com/hannesill/m4) | MCP / Python | ⭐⭐ B+ | 🟢 Active | ![](https://img.shields.io/github/stars/hannesill/m4?style=flat-square) | AI-assisted clinical research infrastructure for MIMIC-IV, eICU, and custom datasets. Exposes agent tools via MCP and Python APIs, with docs, tests, and clinician-reviewed analysis skills. |
| [OpenClaw-Medical-Skills](https://github.com/FreedomIntelligence/OpenClaw-Medical-Skills) | OpenClaw | ⭐⭐ B+ | 🟢 Active | ![](https://img.shields.io/github/stars/FreedomIntelligence/OpenClaw-Medical-Skills?style=flat-square) | 869 medical AI agent skill definitions (SKILL.md format): clinical workflows, genomics, drug discovery, bioinformatics, regulatory compliance. Install via OpenClaw/NanoClaw platform. |
| [ClawBio](https://github.com/ClawBio/ClawBio) | OpenClaw | ⭐⭐ B+ | 🟢 Active | ![](https://img.shields.io/github/stars/ClawBio/ClawBio?style=flat-square) | Bioinformatics-native OpenClaw skill library with 39 local-first skills plus Galaxy tool integration for genomics, pharmacogenomics, polygenic risk scoring, and UK Biobank workflows. |
| [SciAgent-Skills](https://github.com/jaechang-hits/SciAgent-Skills) | Claude Code / Multi | ⭐⭐ B | 🟢 Active | ![](https://img.shields.io/github/stars/jaechang-hits/SciAgent-Skills?style=flat-square) | 196 scientific skills for AI coding agents across genomics, proteomics, drug discovery, biostatistics, and scientific writing. Includes plugin packaging, registry metadata, validation scripts, templates, and tests. |
| [MedSci Skills](https://github.com/Aperivue/medsci-skills) | Claude Code | ⭐⭐ B- | 🟢 Active | ![](https://img.shields.io/github/stars/Aperivue/medsci-skills?style=flat-square) | Physician-built Claude Code skill suite for literature search, reporting-guideline audits, statistics, meta-analysis, figures, manuscript writing, revision, and grant drafting. |
| [medical-research-skills](https://github.com/aipoch/medical-research-skills) | Claude Code / OpenClaw / Multi | ⭐⭐ B+ | 🟢 Active | ![](https://img.shields.io/github/stars/aipoch/medical-research-skills?style=flat-square) | 500+ medical-research agent skills for evidence synthesis, protocol design, data analysis, and academic writing. Ships reusable skill directories, install docs, scripts, and a public catalog site. |
| [noah-skills](https://github.com/NOAH-AI-CO/noah-skills) | Claude Code / Multi | ⭐ C | 🟢 Active | ![](https://img.shields.io/github/stars/NOAH-AI-CO/noah-skills?style=flat-square) | Official medical/biotech skill collection for Noah APIs. Includes installable skills for clinical-trial search, drug pipeline intelligence, and medical-conference discovery, each with `SKILL.md` specs plus CLI wrappers. |
| [Bioclaw Skills Hub](https://github.com/zongtingwei/Bioclaw_Skills_Hub) | BioClaw / Multi | ⭐⭐ B- | 🟢 Active | ![](https://img.shields.io/github/stars/zongtingwei/Bioclaw_Skills_Hub?style=flat-square) | Official BioClaw skill library for bioinformatics and omics workflows. Includes reusable skill definitions, catalog metadata, bilingual docs, and a structured `skills/` directory. |
| [bioSkills](https://github.com/GPTomics/bioSkills) | Claude Code / Multi | ⭐⭐ B | 🟢 Active | ![](https://img.shields.io/github/stars/GPTomics/bioSkills?style=flat-square) | SKILLS.md collection for common bioinformatics workflows across Claude Code, Codex, Gemini, and OpenClaw. Covers sequence analysis, single-cell RNA-seq, population genetics, and more. |
| [BioContextAI Knowledgebase MCP](https://github.com/biocontext-ai/knowledgebase-mcp) | MCP Server | ⭐⭐ B+ | 🟡 Moderate | ![](https://img.shields.io/github/stars/biocontext-ai/knowledgebase-mcp?style=flat-square) | Biomedical research MCP server with local and hosted modes. Unifies 14+ resources including Europe PMC, OpenTargets, Reactome, Protein Atlas, AlphaFold DB, and configurable OpenAPI-based extensions. |
| [SPOKEAgent](https://github.com/BaranziniLab/SPOKEAgent) | MCP Server | ⭐ C+ | 🟡 Moderate | ![](https://img.shields.io/github/stars/BaranziniLab/SPOKEAgent?style=flat-square) | Read-only MCP server for UCSF's SPOKE biomedical knowledge graph. Supports Cypher querying and schema retrieval for precision-medicine and translational-research workflows. *(UCSF-affiliate passcode required)* |
| [Agentic BTE](https://github.com/mastorga589/agentic-bte) | MCP / LangGraph | ⭐ C+ | 🟡 Moderate | ![](https://img.shields.io/github/stars/mastorga589/agentic-bte?style=flat-square) | Biomedical research platform built on BioThings Explorer. Combines entity extraction, query decomposition, MCP exposure, and LangGraph agents for drug-discovery and biomedical question-answering workflows. |
| [Heuris-BioMCP](https://github.com/SachinGawande2003/Heuris-BioMCP) | MCP Server | ⭐⭐ B- | 🟢 Active | ![](https://img.shields.io/github/stars/SachinGawande2003/Heuris-BioMCP?style=flat-square) | Life-science MCP server with 31 curated tools across PubMed, UniProt, ChEMBL, OpenTargets, ClinicalTrials.gov, cBioPortal, GWAS, OMIM, PharmGKB, and related translational workflows. Includes hosted demo and tests. |
| [BioBTree v2](https://github.com/tamerh/biobtree) | MCP Server | ⭐⭐ B+ | 🟢 Active | ![](https://img.shields.io/github/stars/tamerh/biobtree?style=flat-square) | Mature biomedical graph database spanning 50+ primary data sources with native MCP support. Strong for identifier mapping and cross-database traversal across genes, proteins, compounds, diseases, pathways, and clinical data. |
| [bioinformatics-agent-skills](https://github.com/variomeanalytics/bioinformatics-agent-skills) | MCP Server | ⭐ C+ | 🟢 Active | ![](https://img.shields.io/github/stars/variomeanalytics/bioinformatics-agent-skills?style=flat-square) | Hosted MCP server from Pipette.bio exposing a knowledge graph of 78 bioinformatics workflows and ~300 tools for single-cell, RNA-seq, variant calling, metagenomics, and drug-discovery pipeline navigation. |
| [GrEBI](https://github.com/EBISPOT/GrEBI) | MCP Server | ⭐⭐ B | 🟢 Active | ![](https://img.shields.io/github/stars/EBISPOT/GrEBI?style=flat-square) | EMBL-EBI knowledge graph aggregation pipeline with a public MCP endpoint for integrative biomedical queries across EBI resources, Monarch, IMPC, ROBOKOP, and related datasets. |
| [dna-claude-analysis](https://github.com/shmlkv/dna-claude-analysis) | Claude Code | ⭐⭐ B- | 🟡 Moderate | ![](https://img.shields.io/github/stars/shmlkv/dna-claude-analysis?style=flat-square) | Personal genome analysis from 23andMe/AncestryDNA/MyHeritage/Nebula. 17 analysis scripts (health, ancestry, nutrition, carrier status, longevity). Interactive HTML dashboard. |
| [biothings-mcp](https://github.com/longevity-genie/biothings-mcp) | MCP Server | ⭐⭐ B | 🟡 Moderate | — | BioThings API for genes, genetic variants, drugs, and taxonomic information. |
| [gget-mcp](https://github.com/longevity-genie/gget-mcp) | MCP Server | ⭐⭐ B | 🟡 Moderate | — | Bioinformatics toolkit for genomics queries wrapping the gget library. |
| [encode-toolkit](https://github.com/ammawla/encode-toolkit) | MCP Server | ⭐⭐ B | 🟡 Moderate | — | ENCODE Project functional genomics data: 47 skills, 20 MCP tools, 7 pipelines, 14 databases. 98% test coverage. PyPI + npm. |
| [paramus-chemistry](https://clawskills.sh/skills/gressling-paramus-chemistry) | OpenClaw | ⭐⭐ B | 🟡 Moderate | — | Hundreds of chemistry and scientific computing tools. |
| [meddev-agent-skills](https://github.com/AminAlam/meddev-agent-skills) | — | ⭐ C | 🟢 Active | ![](https://img.shields.io/github/stars/AminAlam/meddev-agent-skills?style=flat-square) | Modular “skill” files for AI coding agents working on medical device software |
| [wanng-ide-arxiv-gamedevbench-evaluating-agentic-capabili](https://clawskills.sh/skills/wanng-ide-arxiv-gamedevbench-evaluating-agentic-capabili) | OpenClaw | ⭐ C | 🟡 Moderate | — | *(no description)* |
| [admet-prediction](https://clawskills.sh/skills/huifer-admet-prediction) | OpenClaw | ⭐⭐ B | 🟡 Moderate | — | ADMET (Absorption, Distribution, Metabolism, Excretion, Toxicity) prediction for drug candidates. |
| [pubmed-gemini-extension](https://github.com/avivlyweb/pubmed-gemini-extension) | MCP Server | ⭐ C | 🟢 Active | ![](https://img.shields.io/github/stars/avivlyweb/pubmed-gemini-extension?style=flat-square) | PubMed MCP server for Gemini CLI - PhD-level medical research analysis |

**[→ More research skills](categories/research.md)**

---

## Medical Imaging Skills

> Installable skills and MCP servers for medical imaging workflows.

| Skill | Platform | Grade | Maintenance | Stars | Description |
|-------|----------|-------|-------------|-------|-------------|
| [wiseocr](https://clawskills.sh/skills/wiseocr) | OpenClaw | ⭐ C | 🟡 Moderate | — | PDF to Markdown with medical document OCR support. *(Link may be broken)* |
| [medical-image-analysis-skills](https://github.com/HenryLau7/medical-image-analysis-skills) | OpenClaw / Multi | ⭐ C+ | 🟢 Active | ![](https://img.shields.io/github/stars/HenryLau7/medical-image-analysis-skills?style=flat-square) | Portable medical imaging skill bundles for DICOM/NIfTI inspection, orientation normalization, resampling, intensity normalization, and segmentation-mask QC. Includes `SKILL.md` contracts, scripts, docs, and bilingual README. |
| [clinical-skills](https://github.com/aizech/clinical-skills) | Claude Code / Multi | ⭐ C+ | 🟢 Active | ![](https://img.shields.io/github/stars/aizech/clinical-skills?style=flat-square) | 26 installable healthcare agent skills for radiology workflows, clinical documentation, AI integration, and medical research. Includes multi-platform packaging, docs, Docker setup, and 85 tests. |
| [med-guide](https://github.com/burakcanpolat/med-guide) | Claude Code / Multi | ⭐ C+ | 🟢 Active | ![](https://img.shields.io/github/stars/burakcanpolat/med-guide?style=flat-square) | MedGemma-powered AI-editor workflow for X-ray/CT/MRI/DICOM review, lab-result interpretation, and drug-interaction checks. Ships setup guides, scripts, CI, and local report generation. |

> 💡 For standalone medical imaging AI projects (MedRAX, EasyLung, etc.), see [awesome-medical-ai](https://github.com/JuneYaooo/awesome-medical-ai#medical-imaging--radiology). Also see: [DICOM MCP](#medical-mcp-servers) for PACS integration.

---

## Drug & Pharmacology

> Skills for drug information, pharmacogenomics, and medication management.

| Skill | Platform | Grade | Maintenance | Stars | Description |
|-------|----------|-------|-------------|-------|-------------|
| [maccabi-pharm-search](https://clawskills.sh/skills/alexpolonsky-maccabi-pharm-search) | OpenClaw | ⭐⭐ B | 🟡 Moderate | — | Check medication stock at Maccabi pharmacies in Israel. |
| [PharmacyMCP](https://github.com/wkurzatz/PharmacyMCP) | MCP Server | ⭐ C+ | 🟢 Active | ![](https://img.shields.io/github/stars/wkurzatz/PharmacyMCP?style=flat-square) | Health Canada Drug Product Database MCP with 15 tools, 4 resources, and 4 prompts for drug lookup by DIN, brand, ingredient, therapeutic class, status, packaging, route, and veterinary species. |
| [kpic-mcp](https://github.com/antegral/kpic-mcp) | MCP Server | ⭐ C+ | 🟡 Moderate | ![](https://img.shields.io/github/stars/antegral/kpic-mcp?style=flat-square) | TypeScript MCP server for Korea Pharmaceutical Information Center drug lookup. Supports name search, detailed medication records, tests, CI, and Claude Desktop config. |
| [hypokrates](https://github.com/bruno-portfolio/hypokrates) | Python / MCP Server | ⭐ C+ | 🟢 Active | ![](https://img.shields.io/github/stars/bruno-portfolio/hypokrates?style=flat-square) | Public-health and pharmacovigilance toolkit that normalizes WHO/GHO, Our World in Data, and FDA adverse-event datasets, with MCP exposure for agentic analysis and cross-dataset lookups. |
| [DrugClaw](https://github.com/DrugClaw/DrugClaw) | CLI / Web UI | ⭐⭐ B- | 🟢 Active | ![](https://img.shields.io/github/stars/DrugClaw/DrugClaw?style=flat-square) | Local drug-discovery research assistant with tool use, memory, scheduler, web UI, and domain skills for docking, QSAR, ADMET, and prioritization workflows. |

> Also see: [BioMCP](#medical-mcp-servers) (ChEMBL, drug-gene interactions), [medical-mcp](#medical-mcp-servers) (FDA drugs, RxNorm), [admet-prediction](#biomedical-research--genomics) (ADMET prediction)

---

## Health Data & Wearables

> Skills for health device data integration, biometrics, and personal health tracking.

| Skill | Platform | Grade | Maintenance | Description |
|-------|----------|-------|-------------|-------------|
| [health-sync](https://clawskills.sh/skills/filipe-m-almeida-health-sync) | OpenClaw | ⭐⭐ B | 🟢 Active | Analyze synced data across Oura, Withings, Hevy, Strava, WHOOP, and Eight Sleep. |
| [health-summary](https://clawskills.sh/skills/yusaku-0426-health-summary) | OpenClaw | ⭐⭐ B | 🟢 Active | Generate daily/weekly/monthly health summaries with nutrition totals and trends. |
| [gevety](https://clawskills.sh/skills/moclippa-gevety) | OpenClaw | ⭐⭐ B | 🟡 Moderate | Biomarkers, healthspan scores, biological age data. |
| **Apple Health** | | | | |
| [apple-health-skill](https://clawskills.sh/skills/nftechie-apple-health-skill) | OpenClaw | ⭐⭐ B | 🟢 Active | Query Apple Health data — workouts, heart rate, activity rings, fitness trends. |
| [apple-health-analyst](https://github.com/RuochenLyu/apple-health-analyst) | Claude Code / Multi | ⭐⭐ B | 🟢 Active | ![](https://img.shields.io/github/stars/RuochenLyu/apple-health-analyst?style=flat-square) Local Apple Health export analyzer that generates bilingual HTML reports with correlation analysis, behavior-pattern detection, and explainable recovery/activity scoring. |
| [apple-health-analysis](https://github.com/labrinyang/apple-health-analysis) | Claude Code / Multi | ⭐⭐ B | 🟢 Active | ![](https://img.shields.io/github/stars/labrinyang/apple-health-analysis?style=flat-square) Local Apple Health export analyzer with 21 statistical methods, 30 disease-risk screenings, 35+ SVG charts, cited literature, and zero-dependency Python scripts for agent workflows. |
| [healthkit-sync](https://clawskills.sh/skills/mneves75-healthkit-sync) | OpenClaw | ⭐⭐ B | 🟡 Moderate | iOS HealthKit data sync CLI commands. |
| **Garmin** | | | | |
| [garmin-health](https://clawskills.sh/skills/eversonl-garmin-health-analysis) | OpenClaw | ⭐⭐ B | 🟢 Active | Natural language Garmin data — 20+ metrics: sleep, HRV, VO2max, body battery, SPO2. |
| [garmin-cli](https://clawskills.sh/skills/voydz-garmin-cli) | OpenClaw | ⭐⭐ B | 🟡 Moderate | Garmin Connect health/activity data via CLI. |
| [garmin-givemydata](https://github.com/nrvim/garmin-givemydata) | MCP Server | ⭐⭐ B- | 🟢 Active | ![](https://img.shields.io/github/stars/nrvim/garmin-givemydata?style=flat-square) Local Garmin Connect extractor that writes health and activity data into SQLite and exposes it through an MCP server for Claude Code. Ships with CI, PyPI packaging, and cross-platform setup scripts. |
| [garmin-connect-health](https://github.com/dw1161/garmin-connect-health) | OpenClaw | ⭐⭐ B- | 🟢 Active | ![](https://img.shields.io/github/stars/dw1161/garmin-connect-health?style=flat-square) Cross-platform OpenClaw skill for 40+ Garmin Connect metrics including sleep, HRV, stress, Body Battery, SpO2, and VO2 Max. Caching plus multiple auth methods. |
| [Garmin MCP App](https://github.com/chenhunghan/garmin-mcp-app) | MCP App | ⭐⭐ B- | 🟢 Active | ![](https://img.shields.io/github/stars/chenhunghan/garmin-mcp-app?style=flat-square) Claude Desktop `.mcpb` app for Garmin Connect data with interactive charts, workout/training-readiness analysis, calendar-based workout planning, and local sign-in flow. |
| [garmin-connect](https://clawskills.sh/skills/garmin-connect) | OpenClaw | ⭐ C | 🟡 Moderate | Garmin Connect auto-sync every 5 minutes. *(Link may be broken)* |
| **Fitbit** | | | | |
| [fitbit](https://clawskills.sh/skills/mjrussell-fitbit) | OpenClaw | ⭐⭐ B | 🟢 Active | Query Fitbit sleep, heart rate, activity, SpO2. |
| [fitbit-analytics](https://clawskills.sh/skills/kesslerio-fitbit-analytics) | OpenClaw | ⭐⭐ B | 🟡 Moderate | Fitbit health data integration and analytics. |
| [personal-health-fitbit](https://github.com/somz22/personal-health-fitbit) | Claude Code / Multi | ⭐ C+ | 🟢 Active | ![](https://img.shields.io/github/stars/somz22/personal-health-fitbit?style=flat-square) Local-first Fitbit analytics stack that syncs cloud exports into DuckDB and ships agent skills for SQL-based sleep, HRV, activity, anomaly, and lab-data analysis. |
| **WHOOP** | | | | |
| [whoop-health-analysis](https://clawskills.sh/skills/whoop-health-analysis) | OpenClaw | ⭐⭐ B | 🟢 Active | WHOOP data (sleep, recovery, HRV, strain) with interactive charts. *(Link may be broken)* |
| [whoop-tracker](https://clawskills.sh/skills/whoop-tracker) | OpenClaw | ⭐⭐ B | 🟡 Moderate | WHOOP recovery scores, sleep metrics, workout stats. *(Link may be broken)* |
| [whoop-morning](https://clawskills.sh/skills/whoop-morning) | OpenClaw | ⭐ C | 🟡 Moderate | Daily WHOOP morning check-in and recommendations. *(Link may be broken)* |
| **Oura Ring** | | | | |
| [oura-analytics](https://clawskills.sh/skills/kesslerio-oura-analytics) | OpenClaw | ⭐⭐ B | 🟡 Moderate | Oura Ring data integration and analytics. |
| [oura-ring-skill](https://clawskills.sh/skills/oura-ring-skill) | OpenClaw | ⭐ C | 🟡 Moderate | Oura readiness/sleep + 7-day trends, morning briefing. *(Link may be broken)* |
| **Withings** | | | | |
| [withings-mcp](https://github.com/akutishevsky/withings-mcp) | MCP Server | ⭐⭐ B- | 🟢 Active | ![](https://img.shields.io/github/stars/akutishevsky/withings-mcp?style=flat-square) Remote/self-hosted MCP server for Withings sleep, body composition, blood pressure, workouts, ECG, and goals. OAuth setup, TypeScript codebase, and privacy-focused token handling. |
| [withings-health](https://clawskills.sh/skills/withings-health) | OpenClaw | ⭐⭐ B | 🟡 Moderate | Weight, body composition, activity, and sleep from Withings. *(Link may be broken)* |
| [withings-family](https://clawskills.sh/skills/withings-family) | OpenClaw | ⭐ C | 🟡 Moderate | Multi-family member Withings data. *(Link may be broken)* |
| **Other** | | | | |
| [soft-pillow](https://clawskills.sh/skills/kivs-soft-pillow) | OpenClaw | ⭐ C | 🟡 Moderate | Sleep data and dream history queries. |
| [eightctl](https://clawskills.sh/skills/steipete-eightctl) | OpenClaw | ⭐⭐ B | 🟡 Moderate | Control Eight Sleep pods — temperature, alarms, schedules. |
| [anthrovision-telegram-body-scan](https://clawskills.sh/skills/dr2101-anthrovision-telegram-body-scan) | OpenClaw | ⭐ C | 🟡 Moderate | Body measurement scan via Telegram. |

**[→ Full wearables list](categories/wearables.md)**

---

## Mental Health & Therapy

> Skills for mental health support, therapy frameworks, and psychological well-being.

| Skill | Platform | Grade | Description |
|-------|----------|-------|-------------|
| [therapy-mode](https://clawskills.sh/skills/therapy-mode) | OpenClaw | ⭐⭐ B | CBT, ACT, DBT, Motivational Interviewing. Session notes and crisis protocols. *(Link may be broken)* |
| [anxiety-relief](https://clawskills.sh/skills/jhillin8-anxiety-relief) | OpenClaw | ⭐ C | Grounding exercises and breathing techniques for anxiety. |
| [depression-support](https://clawskills.sh/skills/jhillin8-depression-support) | OpenClaw | ⭐ C | Daily mood tracking and depression support tools. |
| [jungian-psychologist](https://clawskills.sh/skills/jungian-psychologist) | OpenClaw | ⭐ C | Shadow work, archetype analysis, dream interpretation. *(Link may be broken)* |
| [mens-mental-health](https://clawskills.sh/skills/mens-mental-health) | OpenClaw | ⭐ C | Mood checks, stress tools, and judgment-free space for men. *(Link may be broken)* |
| [adhd-assistant](https://clawskills.sh/skills/thinktankmachine-adhd-assistant) | OpenClaw | ⭐ C | ADHD-friendly life management assistant. |
| [adhd-daily-planner](https://clawskills.sh/skills/mikecourt-adhd-daily-planner) | OpenClaw | ⭐ C | Time-blind friendly planning, executive function support. |
| [adhd-founder-planner](https://clawskills.sh/skills/jankutschera-adhd-founder-planner) | OpenClaw | ⭐ C | ADHD-focused planning for founders. |
| [adhd-body-doubling](https://clawskills.sh/skills/jankutschera-adhd-body-doubling) | OpenClaw | ⭐ C | Punk-style ADHD body doubling for founders. |
| [social-media-detox](https://clawskills.sh/skills/social-media-detox) | OpenClaw | ⭐ C | Break social media addiction with digital wellness tools. *(Link may be broken)* |
| [sauna-calm](https://clawskills.sh/skills/grx21-sauna-calm) | OpenClaw | ⭐ C | Breathing exercises and calm-down protocols. |
| [clawtopia](https://clawskills.sh/skills/alfrescian-clawtopia) | OpenClaw | ⭐ C | Peaceful wellness sanctuary for AI agents. |

---

## Nutrition & Diet

> Skills for meal planning, calorie tracking, and nutritional analysis.

| Skill | Platform | Grade | Description |
|-------|----------|-------|-------------|
| [calorie-counter](https://clawskills.sh/skills/cnqso-calorie-counter) | OpenClaw | ⭐⭐ B | Track daily calorie and protein intake, set goals. |
| [calorie-visualizer](https://clawskills.sh/skills/vintlin-calorie-visualizer) | OpenClaw | ⭐⭐ B | Local calorie logging with visual reports and chart images. |
| [diet-tracker](https://clawskills.sh/skills/yonghaozhao722-diet-tracker) | OpenClaw | ⭐⭐ B | Track daily diet and calculate nutrition information. |
| [opencal](https://clawskills.sh/skills/neikfu-opencal) | OpenClaw | ⭐⭐ B | Log meals and manage calorie goals hands-free via AI agent. |
| [healthy-eating](https://clawskills.sh/skills/healthy-eating) | OpenClaw | ⭐ C | Build healthy eating habits with meal logging. *(Link may be broken)* |
| [fasting-tracker](https://clawskills.sh/skills/jhillin8-fasting-tracker) | OpenClaw | ⭐⭐ B | Track intermittent fasting windows and extended fasts. |
| [detox-counter](https://clawskills.sh/skills/jhillin8-detox-counter) | OpenClaw | ⭐ C | Track detox with counters and symptom logging. |
| [feast](https://clawskills.sh/skills/smadgerano-feast) | OpenClaw | ⭐⭐ B | Comprehensive meal planning with cultural themes and authentic recipes. |
| [recipe-finder](https://clawskills.sh/skills/harshasic-recipe-finder) | OpenClaw | ⭐ C | Find recipes by ingredients, cuisine, or dietary preferences. |
| [mealie-api](https://clawskills.sh/skills/angusthefuzz-mealie-api) | OpenClaw | ⭐⭐ B | Interact with Mealie recipe manager. |
| [cookidoo](https://clawskills.sh/skills/thekie-cookidoo) | OpenClaw | ⭐ C | Access Thermomix recipes, shopping lists, meal planning. |

---

## Fitness & Training

> Skills for workout tracking, training plans, and athletic performance.

| Skill | Platform | Grade | Description |
|-------|----------|-------|-------------|
| [endurance-coach](https://clawskills.sh/skills/shiv19-endurance-coach) | OpenClaw | ⭐⭐ B | Personalized triathlon, marathon, ultra-endurance training plans. |
| [muscle-gain](https://clawskills.sh/skills/jhillin8-muscle-gain) | OpenClaw | ⭐ C | Track muscle building with weight progression and protein tracking. |
| [hevy](https://clawskills.sh/skills/mjrussell-hevy) | OpenClaw | ⭐⭐ B | Query workout data — routines, exercises, history. |
| [workout](https://clawskills.sh/skills/workout) | OpenClaw | ⭐ C | Workout CLI: log sets, manage templates. Multi-user support. *(Link may be broken)* |
| [ranked-gym](https://clawskills.sh/skills/ranked-gym) | OpenClaw | ⭐ C | Gamified gym tracking with XP, levels, and achievements. *(Link may be broken)* |
| [strava-cycling-coach](https://clawskills.sh/skills/strava-cycling-coach) | OpenClaw | ⭐⭐ B | Strava cycling performance tracking and analysis. *(Link may be broken)* |
| [intervals-icu](https://clawskills.sh/skills/pseuss-intervals-icu-api) | OpenClaw | ⭐⭐ B | Access and manage training data via Intervals.icu API. |
| [testosterone-optimization](https://clawskills.sh/skills/testosterone-optimization) | OpenClaw | ⭐ C | Natural testosterone optimization via sleep, exercise, nutrition tracking. *(Link may be broken)* |

---

## Medical Device Compliance

> Skills for regulatory compliance, quality management, and medical device standards.

| Skill | Platform | Grade | Description |
|-------|----------|-------|-------------|
| [capa-officer](https://clawskills.sh/skills/alirezarezvani-capa-officer) | OpenClaw | ⭐⭐ B | CAPA system management for medical device QMS (Quality Management System). |
| [samd-qms-workflow](https://github.com/jcafazzo/samd-qms-workflow) | Claude Code | ⭐ C+ | ISO 13485 / IEC 62304 / ISO 14971 workflow skill for SaMD teams, with stage-gated prompts, compliance artifacts, and AI/GenAI change-control guidance. ![](https://img.shields.io/github/stars/jcafazzo/samd-qms-workflow?style=flat-square) |
| [iec62366-usability-skill](https://github.com/sven-jungmann/iec62366-usability-skill) | Claude Code | ⭐ C+ | Claude Code skill for IEC 62366-1/2 usability-engineering workflows in SaMD and health software. Generates audit-ready artifacts, use-related risk analysis, and usability-test protocols for EU MDR and FDA-aligned teams. ![](https://img.shields.io/github/stars/sven-jungmann/iec62366-usability-skill?style=flat-square) |
| [International Health Law MCP](https://github.com/Ansvar-Systems/international-health-law-mcp) | MCP Server | ⭐ C+ | Structured MCP database for WHO, ICH, IMDRF, Declaration of Helsinki, and Codex provisions for regulatory, pharma, and medical-device compliance workflows. ![](https://img.shields.io/github/stars/Ansvar-Systems/international-health-law-mcp?style=flat-square) |

> Also see: [OpenClaw-Medical-Skills](#biomedical-research--genomics) includes FDA, CE mark, IEC 62304, ISO 14971 compliance skills.

---

## Maternal & Baby Health

> Skills for pregnancy tracking and infant care.

| Skill | Platform | Grade | Description |
|-------|----------|-------|-------------|
| [pregnancy-tracker](https://clawskills.sh/skills/pregnancy-tracker) | OpenClaw | ⭐⭐ B | Weekly pregnancy updates, symptom logging, milestone countdowns. *(Link may be broken)* |
| [huckleberry](https://clawskills.sh/skills/jayhickey-huckleberry) | OpenClaw | ⭐⭐ B | Track baby sleep, feeding, diapers, and growth via Huckleberry. |

---

## Addiction & Habit Recovery

> Skills for quitting addictive substances and building healthy habits.

| Skill | Platform | Grade | Description |
|-------|----------|-------|-------------|
| [quit-smoking](https://clawskills.sh/skills/quit-smoking) | OpenClaw | ⭐ C | Smoke-free streak tracking, craving support, health recovery timeline. *(Link may be broken)* |
| [quit-vaping](https://clawskills.sh/skills/quit-vaping) | OpenClaw | ⭐ C | Nicotine-free streak tracking with craving tools and milestones. *(Link may be broken)* |

---

## Traditional & Alternative Medicine

> Skills for TCM, integrative medicine, and wellness practices.

| Skill | Platform | Grade | Description |
|-------|----------|-------|-------------|
| [tcm-video-factory](https://clawskills.sh/skills/tcm-video-factory) | OpenClaw | ⭐ C | Automated Traditional Chinese Medicine health video production. *(Link may be broken)* |

---

## Curated Skill Collections

> Large repositories that include medical skills among broader collections.

| Collection | Stars | Medical Skills Count | Description |
|-----------|-------|---------------------|-------------|
| [claude-scientific-skills](https://github.com/K-Dense-AI/claude-scientific-skills) | ![](https://img.shields.io/github/stars/K-Dense-AI/claude-scientific-skills?style=flat-square) | 30+ | 170 scientific skill definitions (SKILL.md) — includes bioinformatics, clinical research, medical imaging. Install via Claude Code/Cursor. |
| [OpenClaw-Medical-Skills](https://github.com/FreedomIntelligence/OpenClaw-Medical-Skills) | ![](https://img.shields.io/github/stars/FreedomIntelligence/OpenClaw-Medical-Skills?style=flat-square) | 869 | Largest medical skill definition library (SKILL.md). Install via OpenClaw/NanoClaw. |
| [HealthSim Workspace](https://github.com/mark64oswald/healthsim-workspace) | ![](https://img.shields.io/github/stars/mark64oswald/healthsim-workspace?style=flat-square) | 6 | Installable healthcare data-generation workspace with six core skills for synthetic EMR, claims, pharmacy, clinical-trial, population, and provider-network data across FHIR, HL7v2, X12, NCPDP, and CDISC formats. |
| [Reason: Healthcare Tech Skills](https://github.com/reason-healthcare/health-skills) | ![](https://img.shields.io/github/stars/reason-healthcare/health-skills?style=flat-square) | 8 | Curated installable skill set for healthcare software teams: project bootstrap, product discovery, FHIR API/modeling, documentation, compliance review, and human-factors audits for digital-health and EHR systems. |
| [SpeziVibe](https://github.com/StanfordSpezi/SpeziVibe) | ![](https://img.shields.io/github/stars/StanfordSpezi/SpeziVibe?style=flat-square) | 8 | Stanford's installable digital-health skill suite for biodesign, health-data modeling, FHIR design, UX, study planning, and compliance workflows. Distributed via `npx skills` with releases and reusable reference guides. |
| [BioContextAI Registry](https://github.com/biocontext-ai/registry) | ![](https://img.shields.io/github/stars/biocontext-ai/registry?style=flat-square) | 56 | Registry codebase and curation workflow for 56 biomedical MCP servers published on biocontext.ai, with schema validation, JSON export, and submission guidelines backed by the BioContextAI project. |
| [awesome-openclaw-skills](https://github.com/VoltAgent/awesome-openclaw-skills) | ![](https://img.shields.io/github/stars/VoltAgent/awesome-openclaw-skills?style=flat-square) | 84 (Health) | 5,400+ skills total; 84 in Health & Fitness category. |
| [awesome-openclaw-skills-zh](https://github.com/clawdbot-ai/awesome-openclaw-skills-zh) | ![](https://img.shields.io/github/stars/clawdbot-ai/awesome-openclaw-skills-zh?style=flat-square) | 30+ | Chinese translations of OpenClaw skills. |
| [awesome-claude-skills](https://github.com/ComposioHQ/awesome-claude-skills) | ![](https://img.shields.io/github/stars/ComposioHQ/awesome-claude-skills?style=flat-square) | Few | Curated Claude skills; limited medical content. |
| [antigravity-awesome-skills](https://github.com/sickn33/antigravity-awesome-skills) | ![](https://img.shields.io/github/stars/sickn33/antigravity-awesome-skills?style=flat-square) | Some | 1,304+ agentic skills for multiple platforms. |

---

## Related Resources

### Sibling Repos

| Repo | Description |
|------|-------------|
| [awesome-medical-ai-skills-cn](https://github.com/JuneYaooo/awesome-medical-ai-skills-cn) | 🇨🇳 Medical AI Skills（国内版） |
| [awesome-medical-ai](https://github.com/JuneYaooo/awesome-medical-ai) | 🏥 Medical AI Projects — LLMs, imaging, multi-agent systems |
| [awesome-medical-ai-cn](https://github.com/JuneYaooo/awesome-medical-ai-cn) | 🇨🇳 医疗 AI 项目合集（国内版） |

### Standards & Protocols
- [HL7 FHIR](https://www.hl7.org/fhir/) — Fast Healthcare Interoperability Resources
- [DICOM](https://www.dicomstandard.org/) — Digital Imaging and Communications in Medicine
- [OMOP CDM](https://ohdsi.github.io/CommonDataModel/) — Observational Medical Outcomes Partnership Common Data Model

### Platforms
- [OpenClaw / ClawHub](https://clawskills.sh) — Largest AI skill registry (5,400+ skills)
- [Agent Skills Standard](https://agentskills.io/) — Open standard for agent skill definitions

---

## Contributing

We welcome contributions! Please see [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

### 💡 Used a Great Medical Skill? Recommend It!

If you've actually used a medical AI skill and found it genuinely helpful, **we'd love to hear about it!** Real-world usage feedback is the most valuable signal for this list.

**How to recommend:**
1. [Open an Issue](../../issues/new?template=recommend.md&title=Recommend:+SKILL_NAME) with the title `Recommend: <Skill Name>`
2. Tell us: **what you used it for**, **what worked well**, and **any gotchas**
3. We'll add a `👍 Community Recommended` badge to the listing

> Skills validated by real users carry more weight than star counts. Your experience helps others make better choices.

### How to Add a Skill

1. Fork this repository
2. Add your skill to the appropriate category in `README.md`
3. Include: name, platform, link, grade, maintenance status, and description
4. Submit a Pull Request

### Evaluation Criteria

Skills are evaluated on:
- **Documentation Quality** — clear README, usage examples, API docs
- **Maintenance** — commit frequency, issue responsiveness
- **Feature Completeness** — scope coverage, edge case handling
- **Community** — stars, forks, real-world usage reports
- **Safety** — appropriate disclaimers for clinical use, data privacy

---

## Disclaimer

> ⚠️ **Important**: The skills listed here are for **informational and research purposes only**. They are NOT validated clinical tools and should NOT be used for actual medical diagnosis or treatment decisions. Always consult qualified healthcare professionals for medical advice. AI-generated medical information may be inaccurate or harmful.

---

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

This list is released under [CC0 1.0 Universal](LICENSE). You can copy, modify, distribute, and use the work, even for commercial purposes, all without asking permission.
