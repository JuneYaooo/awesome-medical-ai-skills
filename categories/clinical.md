# Awesome Medical AI Skills — Category: Clinical Skills & Knowledge Bases

[← Back to main list](../README.md#clinical-skills--knowledge-bases)

## Clinical Decision Support

### [medical-guidelines-suite](https://github.com/fshaan/medical-guidelines-suite)

- **Platform**: Claude Code
- **Grade**: ⭐⭐ B
- **Maintenance**: 🟢 Active
- **Install**: `npx skills add fshaan/medical-guidelines-suite -g -y`
- **Description**: A three-phase clinical guidelines knowledge suite:
  1. **BUILD** — Convert PDF/DOCX guidelines → extracted text + search indices
  2. **QUERY (RAG)** — Search indices → Generate clinical recommendations
  3. **BATCH** — Excel patient list → RAG retrieval → xlsx/docx/pptx reports
- **Supported Guidelines**: NCCN, ESMO, CSCO (configurable)
- **Output Language**: Simplified Chinese (简体中文)
- **Requirements**: Python 3, openpyxl, python-docx, python-pptx, pdfplumber
- **Key Features**:
  - Cross-guideline retrieval for the same clinical question
  - Batch patient processing from Excel spreadsheets
  - Multi-format output: summary table (.xlsx), per-patient reports (.docx), presentation slides (.pptx)
  - Multi-version guideline handling with configurable knowledge base paths
- **Limitations**:
  - Output is Chinese-only
  - Requires manual guideline PDF procurement (no built-in download)
  - RAG quality depends on guideline text extraction quality

### [Claude-Ally-Health](https://github.com/huifer/Claude-Ally-Health)

- **Platform**: Claude Code
- **Grade**: ⭐ C+
- **Maintenance**: 🟡 Moderate
- **Description**: File-based personal health record management system using Claude Code CLI tools.
- **Key Features**:
  - Manages medical reports, medications, surgeries, discharge summaries
  - 13 medical specialist consultation simulations (MDT)
  - Drug interaction detection with 5-level severity (A/B/C/D/X)
  - Radiation dose tracking
  - Bilingual (Chinese/English)
- **Limitations**:
  - All data stored as local JSON files (not a clinical database)
  - Specialist "consultations" are LLM-generated, not clinically validated
  - Depends on external image recognition API
  - No FHIR/HL7 integration

## Therapy & Counseling

### [therapy-mode](https://clawskills.sh/skills/therapy-mode)

- **Platform**: OpenClaw
- **Grade**: ⭐⭐ B
- **Maintenance**: 🟢 Active
- **Description**: AI-assisted therapy support framework with evidence-based approaches.
- **Key Features**:
  - CBT (Cognitive Behavioral Therapy)
  - ACT (Acceptance and Commitment Therapy)
  - DBT (Dialectical Behavior Therapy)
  - Motivational Interviewing
  - Session notes CLI and crisis protocols
- **Limitations**:
  - NOT a substitute for professional therapy
  - No integration with clinical EHR systems

### [jungian-psychologist](https://clawskills.sh/skills/jungian-psychologist)

- **Platform**: OpenClaw
- **Grade**: ⭐ C
- **Maintenance**: 🟡 Moderate
- **Description**: Jungian analytical psychology framework — shadow work, archetype analysis, dream interpretation.
