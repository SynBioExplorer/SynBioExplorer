# Hi, I'm Felix

**Data Scientist & Automation Engineer** at the [Australian Genome Foundry](https://www.mq.edu.au/research/research-centres-groups-and-facilities/secure-planet/facilities/australian-genome-foundry), Macquarie University, Sydney.

Ph.D. in Synthetic Biology | Building software at the intersection of biology, data, and automation.

[![Email](https://img.shields.io/badge/Email-felix.meier%40mq.edu.au-blue)](mailto:felix.meier@mq.edu.au) [![LinkedIn](https://img.shields.io/badge/LinkedIn-Felix%20Meier-0A66C2?logo=linkedin)](https://www.linkedin.com/in/felixjonathanmeier/) [![ORCID](https://img.shields.io/badge/ORCID-0009--0000--2858--6259-A6CE39?logo=orcid)](https://orcid.org/0009-0000-2858-6259)


---

## Published Research Tools

| Project | Description | Language |
|---------|-------------|----------|
| [Welly](https://github.com/SynBioExplorer/Welly) | High-throughput microbial growth curve analysis from microplate data. Published in [*Bioinformatics Advances*, 2025](https://doi.org/10.1093/bioadv/vbaf038). | Python |
| [SynBio NLP Analysis](https://github.com/SynBioExplorer/Navigating-the-frontier-of-Synthetic-Biology-An-AI-driven-platform-for-exploring-research-trends-an) | NLP platform mapping synthetic biology research trends, collaboration networks, and emerging themes. Published in [*ACS Synthetic Biology*, 2023](https://github.com/SynBioExplorer/SynBio_NLP_analysis). | Python |

## AI & Multi-Agent Systems

| Project | Description | Language |
|---------|-------------|----------|
| [AGF Co-Scientist](https://github.com/SynBioExplorer/AGF_Co-Scientist) | Implementation of Google's AI Co-Scientist - a multi-agent framework with 10 specialized agents for scientific hypothesis generation, debate-based evaluation, and iterative refinement. ~20k lines, FastAPI + React. | Python |
| [Claude Code Agentic Coding](https://github.com/SynBioExplorer/Claude_Code_agentic_coding) | Multi-agent orchestration system using git worktrees, DAG-based scheduling, and tmux-coordinated parallel execution for complex software engineering tasks. | Python |

## Bioinformatics Pipelines

| Project | Description | Language |
|---------|-------------|----------|
| [Synechococcus Transcriptomics](https://github.com/SynBioExplorer/Synechococcus_PCC_11901_transcriptomics) | RNA-seq analysis of *Picosynechococcus sp.* PCC 11901 under 20 stress conditions across nutrient, environmental, and circadian experiments (60 samples, 240 FASTQ files). | Python |
| [Psilocybe Proteomics](https://github.com/SynBioExplorer/magic-mushroom-proteomics) | Extraction and analysis of psilocybin biosynthesis genes from 71 *Psilocybe* species genomes using exonerate protein-to-genome alignment for AlphaFold and phylogenetics. | Python |
| [Basejumper](https://github.com/SynBioExplorer/basejumper) | Desktop GUI pipeline for Oxford Nanopore sequencing: basecalling, demultiplexing, QC, de novo Flye assembly, and reference-based evaluation. | JavaScript |
| [Pulsed Selection](https://github.com/SynBioExplorer/pulsed_selection) | Genomic analysis pipeline for yeast samples - QC, alignment, variant calling, and annotation using fastp, BWA, bcftools, and snpEff. | Shell |
| RAIN *(private)* | Cassette insertion mapping pipeline for Oxford Nanopore long-read sequencing using Minimap2 and pysam. | Python |
| [Gene Retrieval from NCBI](https://github.com/SynBioExplorer/Gene-retrieval-from-NCBI) | Automated gene data retrieval from NCBI Entrez and integration with existing datasets. | Python |

## Australian Genome Foundry Platform

| Project | Description | Stack |
|---------|-------------|-------|
| AGF AWS Infrastructure *(private)* | Serverless data pipeline ingesting metadata from 31 laboratory instruments via Lambda, DynamoDB, S3, EventBridge, Cognito, and Amplify. Infrastructure-as-code with CloudFormation. | AWS, Python |
| AGF Data Sync CLI *(private)* | Automated sync engine running on instrument PCs - file discovery, SHA-256 deduplication, metadata extraction, and upload to S3 with retry logic, staff attribution, and experiment detection. | Python |
| [AGF Website](https://agflive.com) *(private)* | Public website and internal data dashboard for the Australian Genome Foundry. Cognito auth with role-based access, GitHub-based CMS, and equipment catalog for 30+ instruments. | TypeScript, Next.js |
| AGF Finance Dashboard *(private)* | Automated finance reporting with interactive HTML dashboards, 8+ visualization types, forecasting, duplicate detection, and a GUI for non-technical users. | Python |
| OpenTronMIC *(private)* | OT-2 liquid handling robot protocol for automated MIC (Minimum Inhibitory Concentration) plate preparation with serial dilutions across 7 plates. | Python |
| LabSync *(private)* | Generic lab data platform: Electron desktop app for AWS deployment and instrument onboarding, Python sync engine, CloudFormation infrastructure, and Next.js dashboard. | TypeScript, Python |

## Lab & Utility Tools

| Project | Description | Language |
|---------|-------------|----------|
| [ColonyClicker](https://github.com/SynBioExplorer/ColonyClicker) | Cross-platform app for manually counting Colony Forming Units from bacterial colony images with annotation and export. | JavaScript |
| [Freezer Format Migration](https://github.com/SynBioExplorer/Macquarie_-80_Freezer_Format_migration) | Automated migration of 67,420 rows across 51 legacy freezer log files to standardized format for the Macquarie PC2 Facility. | Python |
| [BackUpYourYeast](https://github.com/SynBioExplorer/BackUpYourYeast) | Chromatin accessibility modeling and visualization code for yeast synthetic biology research. | Python |
| [Australian Income Calculator](https://github.com/SynBioExplorer/Australian-Income-Distribution-Calculator) | Interactive tool visualizing how your income compares to the Australian income distribution. | TypeScript |
| [SoundScapeAnalyzer](https://github.com/SynBioExplorer/SoundScapeAnalyzer) | Audio analysis tool with BPM detection, key detection, and metadata extraction with a GUI for batch processing. | Python |

---

## Tech Stack

**Languages:** Python, TypeScript, JavaScript, R, Shell, Swift, SQL
**Cloud:** AWS (Lambda, DynamoDB, S3, Cognito, EventBridge, API Gateway, Amplify, CloudFormation), GitHub Actions CI/CD
**AI/ML:** Claude Code (hooks, MCP servers, custom agents, skills), LangGraph, LangChain, ChromaDB, Google Gemini, OpenAI, multi-agent systems, NLP
**Frontend:** React, Next.js, Electron, Tailwind CSS, Vite
**Backend:** FastAPI, PostgreSQL, Redis, Node.js
**Bioinformatics:** Dorado, Flye, Minimap2, NanoPlot, Porechop, QUAST | Salmon, fastp, SortMeRNA, Bowtie2, BWA, samtools, deepTools, gffread, FastQC, MultiQC, bcftools, snpEff, Bedtools | exonerate, MAFFT, BioPython, pysam, AlphaFold | DESeq2, edgeR, tximport, clusterProfiler, complexHeatmap, EnhancedVolcano, goseq, gseapy, COBRA | Opentrons API
**Data & Viz:** Plotly, Jupyter, Seaborn, Matplotlib, Dash, Flask
**DevOps:** Docker, tmux, git worktrees

---

*Open to collaborations in synthetic biology, bioinformatics, and AI-driven scientific discovery.*
