# Awesome Medical AI Skills — Category: Medical MCP Servers

[← Back to main list](../README.md#medical-mcp-servers)

## Tier 1: Comprehensive Medical Data Servers

### [BioMCP](https://github.com/genomoncology/biomcp) ⭐⭐⭐ A

One command grammar across 15+ biomedical APIs.

- **Install**: `uv tool install biomcp-cli` or `pip install biomcp-cli`
- **Also installs as Claude Code skill**: `biomcp skill install ~/.claude --force`
- **12 Entity Types**: genes, variants, drugs, diseases, articles, trials, pathways, proteins, adverse events, pharmacogenomics, GWAS, phenotypes
- **Data Sources**: PubMed, PubTator3, Europe PMC, ClinicalTrials.gov, ClinVar, gnomAD, ChEMBL, UniProt, PharmGKB, Reactome, OpenFDA, OpenTargets, g:Profiler, OncoKB, AlphaGenome
- **Key Features**:
  - Cross-entity pivots (e.g., `gene → trials → drugs`)
  - Progressive disclosure via selectable sections
  - Gene-set enrichment analysis
  - Remote HTTP server mode for shared deployments
  - Citation graph traversal
  - Works without API keys (optional keys unlock enrichments)
- **Architecture**: Rust CLI + Python MCP server

### [medical-mcp](https://github.com/JamesANZ/medical-mcp) ⭐⭐ B

Zero-config local MCP server — no API keys needed.

- **Install**: `npm install -g medical-mcp`
- **Tools**:
  - `search-drugs` — FDA database
  - `get-drug-details` — Comprehensive drug info by NDC
  - `search-drug-nomenclature` — RxNorm standardized names
  - `get-health-statistics` — WHO Global Health Observatory
  - `search-medical-literature` — 30M+ PubMed articles
  - `search-google-scholar` — Academic research with citations
  - `search-medical-databases` — Multi-database (PubMed, Cochrane, ClinicalTrials.gov)
  - `search-clinical-guidelines` — Practice recommendations
  - `search-pediatric-guidelines` — AAP, Bright Futures
  - `search-pediatric-drugs` — Pediatric dosing
- **Key Strengths**: Zero config, strong pediatric focus, 100% local

## Tier 2: Healthcare Infrastructure Servers

### [WSO2 FHIR MCP](https://github.com/wso2/fhir-mcp-server) ⭐⭐⭐ A-

Enterprise FHIR bridge for AI agents.

- **Install**: `uvx fhir-mcp-server` or Docker
- **Features**:
  - Full SMART-on-FHIR OAuth 2.0 (tested with Epic EHR)
  - Multiple transports: stdio, SSE, streamable HTTP
  - Docker Compose with HAPI FHIR bundled
  - Apache 2.0 license
- **Limitations**: Generic FHIR bridge — no built-in clinical reasoning

### [FHIR MCP Server (Momentum)](https://github.com/the-momentum/fhir-mcp-server) ⭐⭐ B

Natural language queries against FHIR servers.

### [DICOM MCP](https://github.com/ChristianHinge/dicom-mcp) ⭐⭐ B+

Query, read, and move medical images from PACS.

- **Install**: `pip install dicom-mcp`
- **Features**: Patient/study/series queries, PDF report extraction, DICOM C-MOVE
- **Requires**: Python 3.12+, access to DICOM server

### [OMOP MCP](https://github.com/OHNLP/omop_mcp) ⭐⭐ B

Map clinical terminology to OMOP concepts.

- **Features**: Vocabulary search, batch CSV processing, domain-specific vocabulary prioritization (LOINC, SNOMED, etc.)
- **Demo**: [omapper.org](https://omapper.org)
- **Paper**: [arXiv:2509.03828](https://arxiv.org/abs/2509.03828)

## Tier 3: Literature & Research Servers

### [mcp-simple-pubmed](https://github.com/andybrandt/mcp-simple-pubmed) ⭐⭐ B

Focused PubMed search and paper reading.

### [ncbi-mcp-server](https://github.com/vitorpavinato/ncbi-mcp-server) ⭐ C

Advanced NCBI/PubMed with MeSH integration, related articles, batch processing.

## Tier 4: Personal Health Data Servers

### [apple-health-mcp-server](https://github.com/the-momentum/apple-health-mcp-server) ⭐⭐ B

Access exported Apple Health data with built-in analytics.

### [fulcra-context-mcp](https://github.com/fulcradynamics/fulcra-context-mcp) ⭐⭐ B

Personal biometric data: sleep, HR, HRV, glucose, workouts via Fulcra Life API.

### [verilexdata-mcp](https://github.com/carrierone/verilexdata-mcp) ⭐ C

NPI healthcare provider registry and 20 structured datasets. Pay-per-query.
