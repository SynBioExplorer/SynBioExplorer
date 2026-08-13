# Hi, I'm Felix

**Data Scientist & Automation Engineer** at the [Australian Genome Foundry](https://www.mq.edu.au/research/research-centres-groups-and-facilities/secure-planet/facilities/australian-genome-foundry), Macquarie University, Sydney.

Ph.D. in Synthetic Biology | Building software at the intersection of biology, data, and automation.

[![Email](https://img.shields.io/badge/Email-felix.meier%40mq.edu.au-blue)](mailto:felix.meier@mq.edu.au) [![LinkedIn](https://img.shields.io/badge/LinkedIn-Felix%20Meier-0A66C2?logo=linkedin)](https://www.linkedin.com/in/felixjonathanmeier/) [![ORCID](https://img.shields.io/badge/ORCID-0009--0000--2858--6259-A6CE39?logo=orcid)](https://orcid.org/0009-0000-2858-6259)


---

## Published Research

| Project | Description | Language |
|---------|-------------|----------|
| [Welly](https://github.com/SynBioExplorer/Welly) | Web-based tool for high-throughput microbial growth curve analysis from 96- and 384-well microplate data. Computes maximum growth rate and area under the curve per well, aggregates across replicates, and generates interactive heatmaps and line graphs. Flask app with CSV/Excel upload and downloadable reports. Published in [*Bioinformatics Advances*, 2025](https://doi.org/10.1093/bioadv/vbaf038). | Python |
| [SynBio NLP Analysis](https://github.com/SynBioExplorer/Navigating-the-frontier-of-Synthetic-Biology-An-AI-driven-platform-for-exploring-research-trends-an) | AI-driven analytics platform mapping the synthetic biology research landscape using NLP on publication corpora. Identifies emerging themes (metabolic engineering, CRISPR, genetic circuits, optogenetics), tracks temporal shifts over two decades, maps co-authorship collaboration networks across institutions and countries, and analyzes journal impact and geographic publication trends. Published in [*ACS Synthetic Biology*, 2023](https://doi.org/10.1021/acssynbio.3c00192). | Python |
| [BackUpYourYeast](https://github.com/SynBioExplorer/BackUpYourYeast) | Addresses a critical limitation in SCRaMbLE (Synthetic Chromosome Rearrangement and Modification by loxP-mediated Evolution): loss of cell viability from essential gene deletions during genome rearrangements. Designed, synthesised, and validated a 181 kb linear essential neochromosome carrying backup copies of 75 essential genes from *S. cerevisiae* synXIV (Sc2.0 project) with telomerator linearization, CEN6 segregation, and orthogonal roxP recombination. Post-SCRaMbLE viability analysis, genomic analysis of 28 SCRaMbLEd strains revealing a consistent 29.7 kb *TOP2* deletion, and nucleosome occupancy modeling demonstrating an inverse relationship between nucleosome positioning and recombination frequency at loxP sites. Submitted to *Nucleic Acids Research* (under peer review). | Python |
| PulseALE | *(private)* Investigates whether oscillating selection regimes in Adaptive Laboratory Evolution can help populations escape local fitness maxima on rugged landscapes. Evolved *S. cerevisiae* for growth on ethanol as sole carbon source over 63 days (~190 generations) under four regimes: continuous positive (ethanol), neutral (glucose pulses), alternative (glycerol pulses), and negative (5-FOA pulses). Neutral regime accumulated highest mutational burden (44.0 +/- 9.5) with 1.49-fold growth rate enhancement; positive correlation between mutation frequency and growth rate across all conditions (r = 0.834, p = 0.0007). Growth curve analysis, WGS variant calling (GATK/Delly), mutation sharing networks, and Wright-Fisher stochastic simulations. Under peer review. | Python |
| RAIN | *(private)* Simplifying multiplex genome engineering in *S. cerevisiae* with intron-mediated Random Assembly and INtegration (RAIN). Nanopore long-read pipeline for mapping synthetic cassette insertions at Ty1 retrotransposon loci. De novo Flye assembly, split-alignment breakpoint detection, tandem daisy-chain resolution, confidence-scored Ty1 locus annotation (>6 kb unique flank requirement), and junction validation with read coverage. Submitted to *FEMS Yeast Research* (under peer review). | Python |
| AI Protein Design Review | *(private)* Co-authored review of AI and machine-learning methods for protein design, framed through chemically induced dimerization (CID) as the application lens: generative backbone generation, inverse-folding sequence design, and structure prediction. Backed by a curated literature corpus with a SQLite index, JSON schema, and audit trail. In preparation. | LaTeX |

## AI & Multi-Agent Systems

| Project | Description | Language |
|---------|-------------|----------|
| [AGF Co-Scientist](https://github.com/SynBioExplorer/AGF_Co-Scientist) | Implementation of Google's AI Co-Scientist - a multi-agent framework with 10 specialized agents for scientific hypothesis generation, debate-based evaluation, and iterative refinement. ~20k lines, FastAPI + React. | Python |
| [Claude Code Agentic Coding](https://github.com/SynBioExplorer/Claude_Code_agentic_coding) | Multi-agent orchestration system using git worktrees, DAG-based scheduling, and tmux-coordinated parallel execution for complex software engineering tasks. | Python |
| NeoFlex | *(private)* End-to-end synthetic chromosome design platform built for the Australian Genome Foundry "Built with Claude: Life Science" 2026 hackathon. Takes neochromosome design from part selection through assembly planning, bundling a vendored AutoSci toolkit and reference literature. | HTML |
| ComfyUI MCP Server | *(private)* Model Context Protocol server that drives a GPU-shared ComfyUI backend to generate image, video, 3D-mesh, and PBR-texture assets for Unity, running co-tenant with a structural-prediction pipeline on the same GPU. | Python |

## Bioinformatics Pipelines

| Project | Description | Language |
|---------|-------------|----------|
| [Synechococcus Transcriptomics](https://github.com/SynBioExplorer/Synechococcus_PCC_11901_transcriptomics) | RNA-seq analysis of *Picosynechococcus sp.* PCC 11901 under 20 stress conditions across nutrient, environmental, and circadian experiments (60 samples, 240 FASTQ files). | Python |
| [Psilocybe Proteomics](https://github.com/SynBioExplorer/magic-mushroom-proteomics) | Extraction and analysis of psilocybin biosynthesis genes from 71 *Psilocybe* species genomes using exonerate protein-to-genome alignment for AlphaFold and phylogenetics. | Python |
| [Basejumper](https://github.com/SynBioExplorer/basejumper) | Desktop GUI pipeline for Oxford Nanopore sequencing: basecalling, demultiplexing, QC, de novo Flye assembly, and reference-based evaluation. | JavaScript |
| [Pulsed Selection](https://github.com/SynBioExplorer/pulsed_selection) | Genomic analysis pipeline for yeast samples - QC, alignment, variant calling, and annotation using fastp, BWA, bcftools, and snpEff. | Shell |
| Automated NGS Pipeline | *(private)* End-to-end Nanopore sequencing analysis: GenBank-to-FASTA conversion, Minimap2 indexing and alignment, per-contig coverage statistics with pysam, SVIM-ASM structural variant detection (haploid mode), loxP site extraction and proximity analysis, gene overlap annotation, rearrangement classification, and Plotly visualization of coverage and SV metrics. | Python |
| [Gene Retrieval from NCBI](https://github.com/SynBioExplorer/Gene-retrieval-from-NCBI) | Automated gene data retrieval from NCBI Entrez and integration with existing datasets. | Python |
| [NCBI BankIt Feature Table Generator](https://github.com/SynBioExplorer/NCBI_Bankit_Featuretable_generator) | Converts GFF annotations into NCBI BankIt-compatible feature tables (.tbl) for genome submission, with paired FASTA and TSV outputs. | Python |
| [Ribo-seq / RNA-seq Analysis](https://github.com/SynBioExplorer/ribo-rnaseq-analysis) | Integrated ribosome-profiling and RNA-seq analysis computing per-gene translational efficiency and 3'UTR coverage, rendered as interactive heatmaps. | Python |
| Metabolic Modelling Toolkit | *(private)* Yeast9 genome-scale metabolic model (GEM) browser for the Australian Genome Foundry: a cobrapy backend exposed through a FastAPI service for flux balance analysis and pathway exploration. | Python |
| Platelet Image Classification | *(private)* Deep-learning classification of platelet microscopy (.czi) images across oxygen levels and solvent conditions (control, thrombin, zinc), using a custom CNN, ResNet50, and ViT with Grad-CAM and SHAP explainability. | Python |

## Computational Structural Biology / Protein Engineering

| Project | Description | Language |
|---------|-------------|----------|
| EnzymeForge | *(private)* GPU-accelerated computational enzyme engineering pipeline (14 stages) for metabolic pathway optimization in *S. cerevisiae*. FBA-guided bottleneck identification, RFdiffusion3 backbone diversification, LigandMPNN sequence design with ligand conditioning, zero-shot fitness ensemble (TranceptEVE + ESM-2 + GEMME + ThermoMPNN), solubility pre-screening, Boltz-2 holo docking with product inhibition modeling, optional GaMD enhanced sampling, Protenix-v1 cross-validation, Pareto-front ranking, glycosylation risk screening, and yeast codon optimization with Golden Gate-compatible plate maps. Progressive funnel: ~2,000 backbones to 48-96 synthesis-ready DNA sequences per enzyme in ~2-3 days on a single GPU. | Python |
| Psilocybin Enzyme Structure Prediction | *(private)* ColabFold (AlphaFold2) structure predictions of psilocybin biosynthesis enzymes (PsiD, PsiK, PsiM, PsiH) from ~50 *Psilocybe* species and ASR nodes. US-align TM-score/RMSD benchmarking, pairwise structural distance matrices, structure-annotated phylogenetic trees, active site geometry comparison, per-residue pLDDT profiles, consensus mutation analysis, cross-species positional variance mapping, interactive 3Dmol.js viewers, and PyMOL session export. | Python |
| CID Protein Complex Structure Prediction | *(private)* Structure prediction and binding affinity analysis for chemically-induced dimerization (CID) split-enzyme complexes using AlphaFold2 Multimer (ColabFold) and Boltz-2 with ligand docking, plus PyMOL alignment and interactive 3D viewers. | Python |
| Ligand Screening Library | *(private)* Curated ligand library for Boltz-2 holo-docking, assembling Biolog Phenotype MicroArray (PM1-10) substrates and Hampton Silver Bullets additives into docking-ready inputs for the enzyme-engineering pipeline. | Python |
| Rubisco Structure Prediction | *(private)* OpenFold3 structure prediction of Type I Rubisco (P2A) for the Australian Genome Foundry, with per-residue confidence assessment and downstream structural analysis. | Python |

## Australian Genome Foundry Platform

| Project | Description | Stack |
|---------|-------------|-------|
| AGF AWS Infrastructure | *(private)* Serverless data pipeline ingesting metadata from 31 laboratory instruments via Lambda, DynamoDB, S3, EventBridge, Cognito, and Amplify. Infrastructure-as-code with CloudFormation. | AWS, Python |
| AGF Data Sync CLI | *(private)* Automated sync engine running on instrument PCs - file discovery, SHA-256 deduplication, metadata extraction, and upload to S3 with retry logic, staff attribution, and experiment detection. | Python |
| [AGF Website](https://agflive.com) | *(private)* Public website and internal data dashboard for the Australian Genome Foundry. Cognito auth with role-based access, GitHub-based CMS, and equipment catalog for 30+ instruments. | TypeScript, Next.js |
| AGF Finance Dashboard | *(private)* Automated finance reporting with interactive HTML dashboards, 8+ visualization types, forecasting, duplicate detection, and a GUI for non-technical users. | Python |
| OpenTronMIC | *(private)* OT-2 liquid handling robot protocol for automated MIC (Minimum Inhibitory Concentration) plate preparation with serial dilutions across 7 plates. | Python |
| LabSync | *(private)* Generic lab data platform: Electron desktop app for AWS deployment and instrument onboarding, Python sync engine, CloudFormation infrastructure, and Next.js dashboard. | TypeScript, Python |

## Lab & Utility Tools

| Project | Description | Language |
|---------|-------------|----------|
| [ColonyClicker](https://github.com/SynBioExplorer/ColonyClicker) | Cross-platform app for manually counting Colony Forming Units from bacterial colony images with annotation and export. | JavaScript |
| [Freezer Format Migration](https://github.com/SynBioExplorer/Macquarie_-80_Freezer_Format_migration) | Automated migration of 67,420 rows across 51 legacy freezer log files to standardized format for the Macquarie PC2 Facility. | Python |
| [Australian Income Calculator](https://github.com/SynBioExplorer/Australian-Income-Distribution-Calculator) | Interactive tool visualizing how your income compares to the Australian income distribution. | TypeScript |
| [SoundScapeAnalyzer](https://github.com/SynBioExplorer/SoundScapeAnalyzer) | Audio analysis tool with BPM detection, key detection, and metadata extraction with a GUI for batch processing. | Python |
| [Claude Usage Widget](https://github.com/SynBioExplorer/claude-usage-widget) | Native macOS SwiftUI desktop widget showing Claude Code usage metrics and subscription limits at a glance. | Swift |
| [PDF Token Counter](https://github.com/SynBioExplorer/PDF_token_counter) | Notebook utility that counts LLM tokens across PDF documents for context-budget estimation. | Python |

---

## Tech Stack

### Languages
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![R](https://img.shields.io/badge/R-276DC3?style=flat&logo=r&logoColor=white)
![Shell](https://img.shields.io/badge/Shell-4EAA25?style=flat&logo=gnubash&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=postgresql&logoColor=white)
![Swift](https://img.shields.io/badge/Swift-F05138?style=flat&logo=swift&logoColor=white)

### Cloud & DevOps
![AWS Lambda](https://img.shields.io/badge/Lambda-FF9900?style=flat&logo=awslambda&logoColor=white)
![DynamoDB](https://img.shields.io/badge/DynamoDB-4053D6?style=flat&logo=amazondynamodb&logoColor=white)
![S3](https://img.shields.io/badge/S3-569A31?style=flat&logo=amazons3&logoColor=white)
![Cognito](https://img.shields.io/badge/Cognito-DD344C?style=flat&logo=amazonaws&logoColor=white)
![CloudFormation](https://img.shields.io/badge/CloudFormation-FF4F8B?style=flat&logo=amazonaws&logoColor=white)
![Amplify](https://img.shields.io/badge/Amplify-FF9900?style=flat&logo=awsamplify&logoColor=white)
![API Gateway](https://img.shields.io/badge/API_Gateway-FF4F8B?style=flat&logo=amazonapigateway&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=githubactions&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)

### AI / ML
![Claude Code](https://img.shields.io/badge/Claude_Code-D97757?style=flat&logo=anthropic&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat&logo=langchain&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat&logo=langchain&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6F61?style=flat)
![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=flat&logo=googlegemini&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat&logo=openai&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-1C1C1C?style=flat)

### Frontend & Backend
![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white)
![Electron](https://img.shields.io/badge/Electron-47848F?style=flat&logo=electron&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?style=flat&logo=tailwindcss&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat&logo=vite&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat&logo=flask&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white)

### Bioinformatics
![Dorado](https://img.shields.io/badge/Dorado-00828C?style=flat) ![Flye](https://img.shields.io/badge/Flye-6B8E23?style=flat) ![Minimap2](https://img.shields.io/badge/Minimap2-6B8E23?style=flat) ![NanoPlot](https://img.shields.io/badge/NanoPlot-00828C?style=flat) ![Porechop](https://img.shields.io/badge/Porechop-00828C?style=flat) ![QUAST](https://img.shields.io/badge/QUAST-6B8E23?style=flat) ![Salmon](https://img.shields.io/badge/Salmon-FA8072?style=flat) ![fastp](https://img.shields.io/badge/fastp-4B8BBE?style=flat) ![SortMeRNA](https://img.shields.io/badge/SortMeRNA-4B8BBE?style=flat) ![Bowtie2](https://img.shields.io/badge/Bowtie2-4B8BBE?style=flat) ![BWA](https://img.shields.io/badge/BWA-4B8BBE?style=flat) ![samtools](https://img.shields.io/badge/samtools-4B8BBE?style=flat) ![deepTools](https://img.shields.io/badge/deepTools-4B8BBE?style=flat) ![FastQC](https://img.shields.io/badge/FastQC-4B8BBE?style=flat) ![MultiQC](https://img.shields.io/badge/MultiQC-4B8BBE?style=flat) ![bcftools](https://img.shields.io/badge/bcftools-8B4513?style=flat) ![snpEff](https://img.shields.io/badge/snpEff-8B4513?style=flat) ![Bedtools](https://img.shields.io/badge/Bedtools-4B8BBE?style=flat) ![exonerate](https://img.shields.io/badge/exonerate-8B6914?style=flat) ![MAFFT](https://img.shields.io/badge/MAFFT-8B6914?style=flat) ![BioPython](https://img.shields.io/badge/BioPython-3776AB?style=flat) ![pysam](https://img.shields.io/badge/pysam-3776AB?style=flat) ![AlphaFold](https://img.shields.io/badge/AlphaFold-4285F4?style=flat&logo=google&logoColor=white) ![ColabFold](https://img.shields.io/badge/ColabFold-F9AB00?style=flat&logo=googlecolab&logoColor=white) ![Boltz--2](https://img.shields.io/badge/Boltz--2-FF6F00?style=flat) ![OpenFold3](https://img.shields.io/badge/OpenFold3-4285F4?style=flat) ![PyMOL](https://img.shields.io/badge/PyMOL-2E86C1?style=flat) ![DESeq2](https://img.shields.io/badge/DESeq2-276DC3?style=flat) ![edgeR](https://img.shields.io/badge/edgeR-276DC3?style=flat) ![tximport](https://img.shields.io/badge/tximport-276DC3?style=flat) ![clusterProfiler](https://img.shields.io/badge/clusterProfiler-276DC3?style=flat) ![complexHeatmap](https://img.shields.io/badge/complexHeatmap-276DC3?style=flat) ![EnhancedVolcano](https://img.shields.io/badge/EnhancedVolcano-276DC3?style=flat) ![goseq](https://img.shields.io/badge/goseq-276DC3?style=flat) ![gseapy](https://img.shields.io/badge/gseapy-3776AB?style=flat) ![COBRA](https://img.shields.io/badge/COBRA-3776AB?style=flat) ![Opentrons](https://img.shields.io/badge/Opentrons_API-00C2A0?style=flat)

### Data & Visualization
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=flat&logo=plotly&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=jupyter&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat)
![Seaborn](https://img.shields.io/badge/Seaborn-444876?style=flat)
![Dash](https://img.shields.io/badge/Dash-008DE4?style=flat&logo=plotly&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)

---

*Open to collaborations in synthetic biology, bioinformatics, and AI-driven scientific discovery.*
