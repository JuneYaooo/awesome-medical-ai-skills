# Awesome Medical AI Skills 🏥🤖🌍

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![License: CC0-1.0](https://img.shields.io/badge/License-CC0_1.0-lightgrey.svg)](http://creativecommons.org/publicdomain/zero/1.0/)
[![Last Updated](https://img.shields.io/badge/Last%20Updated-2026--03--22-blue.svg)](#)
[![Skills Count](https://img.shields.io/badge/Skills-100%2B-green.svg)](#)

> 🇨🇳 **Looking for China-accessible skills?** See [awesome-medical-ai-skills-cn](https://github.com/yyj/awesome-medical-ai-skills-cn) — 国内版：关注网络可达性、中文支持、国内平台生态

> A curated list of AI agent skills, MCP servers, and tools for **medical & healthcare** use cases — **International Edition**.
> Covering Claude Code, OpenClaw, Cursor, Codex, and other AI coding agents.

---

## Why This List?

Medical AI agent skills are scattered across dozens of registries (ClawHub, awesome-claude-skills, awesome-openclaw-skills, etc.) with no unified collection. This repo aims to:

> 🌍 **International Edition**: This list focuses on globally accessible platforms and tools. For skills optimized for the China ecosystem (domestic APIs, Chinese-language models, local compliance), see the [CN version](https://github.com/yyj/awesome-medical-ai-skills-cn).

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
- [Medical Imaging & Radiology](#medical-imaging--radiology)
- [Drug & Pharmacology](#drug--pharmacology)
- [Health Data & Wearables](#health-data--wearables)
- [Mental Health & Therapy](#mental-health--therapy)
- [Nutrition & Diet](#nutrition--diet)
- [Fitness & Training](#fitness--training)
- [Medical Device Compliance](#medical-device-compliance)
- [Multi-Agent Medical Systems](#multi-agent-medical-systems)
- [Curated Skill Collections](#curated-skill-collections)
- [Related Resources](#related-resources)
- [Contributing](#contributing)

---

## Clinical Skills & Knowledge Bases

> Skills for clinical decision support, guideline retrieval, and patient report generation.

| Skill | Platform | Grade | Maintenance | Stars | Description |
|-------|----------|-------|-------------|-------|-------------|
| [medical-guidelines-suite](https://github.com/fshaan/medical-guidelines-suite) | Claude Code | ⭐⭐ B | 🟢 Active | ![](https://img.shields.io/github/stars/fshaan/medical-guidelines-suite?style=flat-square) | Clinical guidelines knowledge base builder with cross-guideline RAG retrieval and batch patient report generation (xlsx/docx/pptx). Supports NCCN, ESMO, CSCO guidelines. Chinese output. |
| [Claude-Ally-Health](https://github.com/huifer/Claude-Ally-Health) | Claude Code | ⭐ C+ | 🟡 Moderate | — | File-based personal health record management. 13 specialist consultation simulations, drug interaction detection, radiation dose tracking. Bilingual CN/EN. |
| [therapy-mode](https://clawskills.sh/skills/therapy-mode) | OpenClaw | ⭐⭐ B | 🟢 Active | — | AI-assisted therapy support framework — CBT, ACT, DBT, Motivational Interviewing. Session notes CLI and crisis protocols. |
| [jungian-psychologist](https://clawskills.sh/skills/jungian-psychologist) | OpenClaw | ⭐ C | 🟡 Moderate | — | Jungian analytical psychology: shadow work, archetype analysis, dream interpretation. |
| [personas (Dr. Med)](https://clawskills.sh/skills/personas) | OpenClaw | ⭐ C | 🟡 Moderate | — | 31 AI personas including Dr. Med role for medical domain consultation. |

**[→ More clinical skills](categories/clinical.md)**

---

## Medical MCP Servers

> Model Context Protocol servers providing structured access to medical databases and healthcare APIs.

| Server | Grade | Maintenance | Stars | Description |
|--------|-------|-------------|-------|-------------|
| [BioMCP](https://github.com/genomoncology/biomcp) | ⭐⭐⭐ A | 🟢 Active | ![](https://img.shields.io/github/stars/genomoncology/biomcp?style=flat-square) | Unified grammar across 15+ biomedical APIs: PubMed, ClinicalTrials.gov, ClinVar, gnomAD, ChEMBL, UniProt, etc. 12 entity types with cross-entity pivots. Rust CLI + MCP server. Also installs as Claude Code skill. |
| [medical-mcp](https://github.com/JamesANZ/medical-mcp) | ⭐⭐ B | 🟢 Active | ![](https://img.shields.io/github/stars/JamesANZ/medical-mcp?style=flat-square) | Zero-config local MCP server for FDA drugs, WHO stats, PubMed, RxNorm, Google Scholar, clinical guidelines. Strong pediatric focus. No API keys needed. `npm install -g medical-mcp` |
| [WSO2 FHIR MCP](https://github.com/wso2/fhir-mcp-server) | ⭐⭐⭐ A- | 🟢 Active | ![](https://img.shields.io/github/stars/wso2/fhir-mcp-server?style=flat-square) | Enterprise FHIR bridge for AI agents with SMART-on-FHIR OAuth. Tested with Epic EHR. Multiple transports (stdio, SSE, HTTP). Docker + PyPI. Apache 2.0. |
| [FHIR MCP Server (Momentum)](https://github.com/the-momentum/fhir-mcp-server) | ⭐⭐ B | 🟡 Moderate | — | Connects AI agents to FHIR servers; query patient history in natural language. |
| [DICOM MCP](https://github.com/ChristianHinge/dicom-mcp) | ⭐⭐ B+ | 🟡 Moderate | ![](https://img.shields.io/github/stars/ChristianHinge/dicom-mcp?style=flat-square) | Query, read, and move medical images/reports from PACS. Only MCP server targeting DICOM infrastructure. PyPI: `dicom-mcp`. |
| [OMOP MCP](https://github.com/OHNLP/omop_mcp) | ⭐⭐ B | 🟡 Moderate | — | Map clinical terminology to OMOP concepts using LLMs for healthcare data standardization. |
| [mcp-simple-pubmed](https://github.com/andybrandt/mcp-simple-pubmed) | ⭐⭐ B | 🟢 Active | ![](https://img.shields.io/github/stars/andybrandt/mcp-simple-pubmed?style=flat-square) | Search and read medical/life sciences papers from PubMed. Simple and focused. |
| [ncbi-mcp-server](https://github.com/vitorpavinato/ncbi-mcp-server) | ⭐ C | 🟡 Moderate | — | Advanced PubMed search with MeSH integration, related articles, batch processing. |
| [apple-health-mcp-server](https://github.com/the-momentum/apple-health-mcp-server) | ⭐⭐ B | 🟡 Moderate | — | Access exported Apple Health data with built-in analytics. |
| [fulcra-context-mcp](https://github.com/fulcradynamics/fulcra-context-mcp) | ⭐⭐ B | 🟡 Moderate | — | Personal biometric data: sleep, heart rate, HRV, glucose, workouts via Fulcra Life API. |
| [verilexdata-mcp](https://github.com/carrierone/verilexdata-mcp) | ⭐ C | 🟡 Moderate | — | 20 structured datasets including NPI healthcare provider registry. Pay-per-query. |

**[→ More MCP servers](categories/mcp-servers.md)**

---

## Biomedical Research & Genomics

> Skills for bioinformatics, genomics, drug discovery, and scientific research.

| Skill | Platform | Grade | Maintenance | Stars | Description |
|-------|----------|-------|-------------|-------|-------------|
| [claude-scientific-skills](https://github.com/K-Dense-AI/claude-scientific-skills) | Claude Code / Multi | ⭐⭐⭐ A | 🟢 Active | ![](https://img.shields.io/github/stars/K-Dense-AI/claude-scientific-skills?style=flat-square) | 170+ scientific skills covering bioinformatics, cheminformatics, proteomics, clinical research, medical imaging. 250+ databases. Cross-platform (Claude Code, Cursor, Codex, Gemini CLI). |
| [OpenClaw-Medical-Skills](https://github.com/FreedomIntelligence/OpenClaw-Medical-Skills) | OpenClaw | ⭐⭐ B+ | 🟢 Active | ![](https://img.shields.io/github/stars/FreedomIntelligence/OpenClaw-Medical-Skills?style=flat-square) | 869 medical AI agent skills: clinical workflows, genomics, drug discovery, bioinformatics, regulatory compliance. |
| [dna-claude-analysis](https://github.com/shmlkv/dna-claude-analysis) | Claude Code | ⭐⭐ B- | 🟡 Moderate | ![](https://img.shields.io/github/stars/shmlkv/dna-claude-analysis?style=flat-square) | Personal genome analysis from 23andMe/AncestryDNA/MyHeritage/Nebula. 17 analysis scripts (health, ancestry, nutrition, carrier status, longevity). Interactive HTML dashboard. |
| [biothings-mcp](https://github.com/longevity-genie/biothings-mcp) | MCP Server | ⭐⭐ B | 🟡 Moderate | — | BioThings API for genes, genetic variants, drugs, and taxonomic information. |
| [gget-mcp](https://github.com/longevity-genie/gget-mcp) | MCP Server | ⭐⭐ B | 🟡 Moderate | — | Bioinformatics toolkit for genomics queries wrapping the gget library. |
| [encode-toolkit](https://github.com/ammawla/encode-toolkit) | MCP Server | ⭐ C | 🟡 Moderate | — | ENCODE Project functional genomics data: search, download, track, and analyze experiments. |
| [paramus-chemistry](https://clawskills.sh/skills/gressling-paramus-chemistry) | OpenClaw | ⭐⭐ B | 🟡 Moderate | — | Hundreds of chemistry and scientific computing tools. |
| [admet-prediction](https://clawskills.sh/skills/huifer-admet-prediction) | OpenClaw | ⭐⭐ B | 🟡 Moderate | — | ADMET (Absorption, Distribution, Metabolism, Excretion, Toxicity) prediction for drug candidates. |

**[→ More research skills](categories/research.md)**

---

## Medical Imaging & Radiology

> AI agents for medical image analysis, radiology, and pathology.

| Skill | Platform | Grade | Maintenance | Stars | Description |
|-------|----------|-------|-------------|-------|-------------|
| [MedRAX](https://github.com/bowang-lab/MedRAX) | LangChain Agent | ⭐⭐⭐ A- | 🟢 Active | ![](https://img.shields.io/github/stars/bowang-lab/MedRAX?style=flat-square) | ICML 2025. First versatile AI agent for chest X-ray interpretation. Integrates CheXagent, LLaVA-Med, MedSAM, Maira-2, DenseNet-121. ChestAgentBench (2,500 queries). |
| [radiology-swarm](https://github.com/The-Swarm-Corporation/radiology-swarm) | Swarms Agent | ⭐ C+ | 🟡 Moderate | ![](https://img.shields.io/github/stars/The-Swarm-Corporation/radiology-swarm?style=flat-square) | Enterprise multi-agent system for radiological analysis, diagnosis, and treatment planning. |
| [DICOM MCP](https://github.com/ChristianHinge/dicom-mcp) | MCP Server | ⭐⭐ B+ | 🟡 Moderate | ![](https://img.shields.io/github/stars/ChristianHinge/dicom-mcp?style=flat-square) | Query and move medical images from PACS/DICOM servers. |
| [wiseocr](https://clawskills.sh/skills/wiseocr) | OpenClaw | ⭐ C | 🟡 Moderate | — | PDF to Markdown with medical document OCR support. |

---

## Drug & Pharmacology

> Skills for drug information, pharmacogenomics, and medication management.

| Skill | Platform | Grade | Maintenance | Stars | Description |
|-------|----------|-------|-------------|-------|-------------|
| [maccabi-pharm-search](https://clawskills.sh/skills/alexpolonsky-maccabi-pharm-search) | OpenClaw | ⭐⭐ B | 🟡 Moderate | — | Check medication stock at Maccabi pharmacies in Israel. |
| [admet-prediction](https://clawskills.sh/skills/huifer-admet-prediction) | OpenClaw | ⭐⭐ B | 🟡 Moderate | — | ADMET prediction for drug candidates. |

> Also see: [BioMCP](#medical-mcp-servers) (ChEMBL, drug-gene interactions), [medical-mcp](#medical-mcp-servers) (FDA drugs, RxNorm)

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
| [healthkit-sync](https://clawskills.sh/skills/mneves75-healthkit-sync) | OpenClaw | ⭐⭐ B | 🟡 Moderate | iOS HealthKit data sync CLI commands. |
| **Garmin** | | | | |
| [garmin-health](https://clawskills.sh/skills/eversonl-garmin-health-analysis) | OpenClaw | ⭐⭐ B | 🟢 Active | Natural language Garmin data — 20+ metrics: sleep, HRV, VO2max, body battery, SPO2. |
| [garmin-cli](https://clawskills.sh/skills/voydz-garmin-cli) | OpenClaw | ⭐⭐ B | 🟡 Moderate | Garmin Connect health/activity data via CLI. |
| [garmin-connect](https://clawskills.sh/skills/garmin-connect) | OpenClaw | ⭐ C | 🟡 Moderate | Garmin Connect auto-sync every 5 minutes. |
| **Fitbit** | | | | |
| [fitbit](https://clawskills.sh/skills/mjrussell-fitbit) | OpenClaw | ⭐⭐ B | 🟢 Active | Query Fitbit sleep, heart rate, activity, SpO2. |
| [fitbit-analytics](https://clawskills.sh/skills/kesslerio-fitbit-analytics) | OpenClaw | ⭐⭐ B | 🟡 Moderate | Fitbit health data integration and analytics. |
| **WHOOP** | | | | |
| [whoop-health-analysis](https://clawskills.sh/skills/whoop-health-analysis) | OpenClaw | ⭐⭐ B | 🟢 Active | WHOOP data (sleep, recovery, HRV, strain) with interactive charts. |
| [whoop-tracker](https://clawskills.sh/skills/whoop-tracker) | OpenClaw | ⭐⭐ B | 🟡 Moderate | WHOOP recovery scores, sleep metrics, workout stats. |
| [whoop-morning](https://clawskills.sh/skills/whoop-morning) | OpenClaw | ⭐ C | 🟡 Moderate | Daily WHOOP morning check-in and recommendations. |
| **Oura Ring** | | | | |
| [oura-analytics](https://clawskills.sh/skills/kesslerio-oura-analytics) | OpenClaw | ⭐⭐ B | 🟡 Moderate | Oura Ring data integration and analytics. |
| [oura-ring-skill](https://clawskills.sh/skills/oura-ring-skill) | OpenClaw | ⭐ C | 🟡 Moderate | Oura readiness/sleep + 7-day trends, morning briefing. |
| **Withings** | | | | |
| [withings-health](https://clawskills.sh/skills/withings-health) | OpenClaw | ⭐⭐ B | 🟡 Moderate | Weight, body composition, activity, and sleep from Withings. |
| [withings-family](https://clawskills.sh/skills/withings-family) | OpenClaw | ⭐ C | 🟡 Moderate | Multi-family member Withings data. |
| **Other** | | | | |
| [soft-pillow](https://clawskills.sh/skills/kivs-soft-pillow) | OpenClaw | ⭐ C | 🟡 Moderate | Sleep data and dream history queries. |
| [eightctl](https://clawskills.sh/skills/steipete-eightctl) | OpenClaw | ⭐⭐ B | 🟡 Moderate | Control Eight Sleep pods — temperature, alarms, schedules. |
| [anthrovision-telegram-body-scan](https://clawskills.sh/skills/dr2101-anthrovision-telegram-body-scan) | OpenClaw | ⭐ C | 🟡 Moderate | Body measurement scan via Telegram. |
| [huckleberry](https://clawskills.sh/skills/jayhickey-huckleberry) | OpenClaw | ⭐⭐ B | 🟢 Active | Baby sleep, feeding, diapers, and growth tracking. |

**[→ Full wearables list](categories/wearables.md)**

---

## Mental Health & Therapy

> Skills for mental health support, therapy frameworks, and psychological well-being.

| Skill | Platform | Grade | Description |
|-------|----------|-------|-------------|
| [therapy-mode](https://clawskills.sh/skills/therapy-mode) | OpenClaw | ⭐⭐ B | CBT, ACT, DBT, Motivational Interviewing. Session notes and crisis protocols. |
| [anxiety-relief](https://clawskills.sh/skills/jhillin8-anxiety-relief) | OpenClaw | ⭐ C | Grounding exercises and breathing techniques for anxiety. |
| [depression-support](https://clawskills.sh/skills/jhillin8-depression-support) | OpenClaw | ⭐ C | Daily mood tracking and depression support tools. |
| [jungian-psychologist](https://clawskills.sh/skills/jungian-psychologist) | OpenClaw | ⭐ C | Shadow work, archetype analysis, dream interpretation. |
| [mens-mental-health](https://clawskills.sh/skills/mens-mental-health) | OpenClaw | ⭐ C | Mood checks, stress tools, and judgment-free space for men. |
| [adhd-assistant](https://clawskills.sh/skills/thinktankmachine-adhd-assistant) | OpenClaw | ⭐ C | ADHD-friendly life management assistant. |
| [adhd-daily-planner](https://clawskills.sh/skills/mikecourt-adhd-daily-planner) | OpenClaw | ⭐ C | Time-blind friendly planning, executive function support. |
| [adhd-founder-planner](https://clawskills.sh/skills/jankutschera-adhd-founder-planner) | OpenClaw | ⭐ C | ADHD-focused planning for founders. |
| [adhd-body-doubling](https://clawskills.sh/skills/jankutschera-adhd-body-doubling) | OpenClaw | ⭐ C | Punk-style ADHD body doubling for founders. |
| [social-media-detox](https://clawskills.sh/skills/social-media-detox) | OpenClaw | ⭐ C | Break social media addiction with digital wellness tools. |
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
| [healthy-eating](https://clawskills.sh/skills/healthy-eating) | OpenClaw | ⭐ C | Build healthy eating habits with meal logging. |
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
| [workout](https://clawskills.sh/skills/workout) | OpenClaw | ⭐ C | Workout CLI: log sets, manage templates. Multi-user support. |
| [ranked-gym](https://clawskills.sh/skills/ranked-gym) | OpenClaw | ⭐ C | Gamified gym tracking with XP, levels, and achievements. |
| [strava-cycling-coach](https://clawskills.sh/skills/strava-cycling-coach) | OpenClaw | ⭐⭐ B | Strava cycling performance tracking and analysis. |
| [intervals-icu](https://clawskills.sh/skills/pseuss-intervals-icu-api) | OpenClaw | ⭐⭐ B | Access and manage training data via Intervals.icu API. |
| [testosterone-optimization](https://clawskills.sh/skills/testosterone-optimization) | OpenClaw | ⭐ C | Natural testosterone optimization via sleep, exercise, nutrition tracking. |

---

## Medical Device Compliance

> Skills for regulatory compliance, quality management, and medical device standards.

| Skill | Platform | Grade | Description |
|-------|----------|-------|-------------|
| [capa-officer](https://clawskills.sh/skills/alirezarezvani-capa-officer) | OpenClaw | ⭐⭐ B | CAPA system management for medical device QMS (Quality Management System). |

> Also see: [OpenClaw-Medical-Skills](#biomedical-research--genomics) includes FDA, CE mark, IEC 62304, ISO 14971 compliance skills.

---

## Maternal & Baby Health

> Skills for pregnancy tracking and infant care.

| Skill | Platform | Grade | Description |
|-------|----------|-------|-------------|
| [pregnancy-tracker](https://clawskills.sh/skills/pregnancy-tracker) | OpenClaw | ⭐⭐ B | Weekly pregnancy updates, symptom logging, milestone countdowns. |
| [huckleberry](https://clawskills.sh/skills/jayhickey-huckleberry) | OpenClaw | ⭐⭐ B | Track baby sleep, feeding, diapers, and growth via Huckleberry. |

---

## Addiction & Habit Recovery

> Skills for quitting addictive substances and building healthy habits.

| Skill | Platform | Grade | Description |
|-------|----------|-------|-------------|
| [quit-smoking](https://clawskills.sh/skills/quit-smoking) | OpenClaw | ⭐ C | Smoke-free streak tracking, craving support, health recovery timeline. |
| [quit-vaping](https://clawskills.sh/skills/quit-vaping) | OpenClaw | ⭐ C | Nicotine-free streak tracking with craving tools and milestones. |

---

## Traditional & Alternative Medicine

> Skills for TCM, integrative medicine, and wellness practices.

| Skill | Platform | Grade | Description |
|-------|----------|-------|-------------|
| [tcm-video-factory](https://clawskills.sh/skills/tcm-video-factory) | OpenClaw | ⭐ C | Automated Traditional Chinese Medicine health video production. |

---

## Multi-Agent Medical Systems

> Multi-agent frameworks and research systems for medical AI.

| System | Stars | Grade | Description |
|--------|-------|-------|-------------|
| [MedRAX](https://github.com/bowang-lab/MedRAX) | ![](https://img.shields.io/github/stars/bowang-lab/MedRAX?style=flat-square) | ⭐⭐⭐ A- | ICML 2025. Chest X-ray AI agent with 7+ specialized models. |
| [Multi-Agent-Medical-Assistant](https://github.com/souvikmajumder26/Multi-Agent-Medical-Assistant) | ![](https://img.shields.io/github/stars/souvikmajumder26/Multi-Agent-Medical-Assistant?style=flat-square) | ⭐⭐ B | Multi-agent diagnostics and healthcare research chatbot. |
| [Awesome-LLM-Healthcare](https://github.com/mingze-yuan/Awesome-LLM-Healthcare) | ![](https://img.shields.io/github/stars/mingze-yuan/Awesome-LLM-Healthcare?style=flat-square) | ⭐⭐ B | Curated paper list: LLMs in medicine. |
| [medgraph-ai](https://github.com/asanmateu/medgraph-ai) | ![](https://img.shields.io/github/stars/asanmateu/medgraph-ai?style=flat-square) | ⭐⭐ B | Healthcare RAG with Neo4j knowledge graphs. LangChain + FastAPI. |
| [Isaree-Platform](https://github.com/Isaree-ai/Isaree-Platform) | — | ⭐ C | Open-source medical-compliant AI assistant and orchestration engine. |
| [Multi_Agent_Medical_System](https://github.com/joyceannie/Multi_Agent_Medical_System) | — | ⭐ C | ICD-10 extractor, SOAP docs, medical image reports. Uses MedGemma. |
| [SOLVE-Med](https://github.com/PRAISELab-PicusLab/SOLVE-Med) | — | ⭐ C | Multi-agent SLM for medical Q&A — private-by-design, cloud-free. |
| [Doctor_Agent](https://github.com/Ho3seinTork/Doctor_Agent) | — | ⭐ C | AI medical assistant: symptom analysis, health data management. |
| [Prescriptly-AI](https://github.com/warshit/Prescriptly-AI) | — | ⭐ C | Autonomous agent for prescription interpretation. |
| [crewai-health-advisor](https://github.com/AjayKuchhadiya/crewai-health-advisor) | — | ⭐ C | CrewAI for medical report summarization and health recommendations. |
| [MediCARE](https://github.com/giuseppericcio/MediCARE) | — | ⭐ C | Medical collaborative agents reasoning over heterogeneous graphs. |

---

## Curated Skill Collections

> Large repositories that include medical skills among broader collections.

| Collection | Stars | Medical Skills Count | Description |
|-----------|-------|---------------------|-------------|
| [claude-scientific-skills](https://github.com/K-Dense-AI/claude-scientific-skills) | ![](https://img.shields.io/github/stars/K-Dense-AI/claude-scientific-skills?style=flat-square) | 30+ | 170 scientific skills — includes bioinformatics, clinical research, medical imaging. |
| [OpenClaw-Medical-Skills](https://github.com/FreedomIntelligence/OpenClaw-Medical-Skills) | ![](https://img.shields.io/github/stars/FreedomIntelligence/OpenClaw-Medical-Skills?style=flat-square) | 869 | Largest medical-only skill library. OpenClaw/NanoClaw platform. |
| [awesome-openclaw-skills](https://github.com/VoltAgent/awesome-openclaw-skills) | ![](https://img.shields.io/github/stars/VoltAgent/awesome-openclaw-skills?style=flat-square) | 84 (Health) | 5,400+ skills total; 84 in Health & Fitness category. |
| [awesome-openclaw-skills-zh](https://github.com/clawdbot-ai/awesome-openclaw-skills-zh) | ![](https://img.shields.io/github/stars/clawdbot-ai/awesome-openclaw-skills-zh?style=flat-square) | 30+ | Chinese translations of OpenClaw skills. |
| [awesome-claude-skills](https://github.com/ComposioHQ/awesome-claude-skills) | ![](https://img.shields.io/github/stars/ComposioHQ/awesome-claude-skills?style=flat-square) | Few | Curated Claude skills; limited medical content. |
| [antigravity-awesome-skills](https://github.com/sickn33/antigravity-awesome-skills) | ![](https://img.shields.io/github/stars/sickn33/antigravity-awesome-skills?style=flat-square) | Some | 1,304+ agentic skills for multiple platforms. |

---

## Related Resources

### Papers & Research
- [Awesome-LLM-Healthcare](https://github.com/mingze-yuan/Awesome-LLM-Healthcare) — Comprehensive paper list on LLMs in medicine
- [MedRAX (ICML 2025)](https://arxiv.org/abs/2502.02673) — First versatile AI agent for chest X-ray interpretation

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
