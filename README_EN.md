<div align="center">

# Awesome Cancer AI [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of 250+ open-source AI tools, datasets, and resources for cancer research and patient care.

[中文](README.md) · [Contributing](#contributing)

</div>

---

## Table of Contents

- [Patient Navigation & Decision Support](#patient-navigation--decision-support)
- [Clinical Trial Matching](#clinical-trial-matching)
- [Genomics & Variant Interpretation](#genomics--variant-interpretation)
- [Neoantigen Prediction & Vaccine Design](#neoantigen-prediction--vaccine-design)
- [Computational Pathology](#computational-pathology)
- [Radiology & Medical Imaging](#radiology--medical-imaging)
- [Radiation Therapy Planning](#radiation-therapy-planning)
- [Drug Discovery & Repositioning](#drug-discovery--repositioning)
- [Single-cell & Spatial Omics](#single-cell--spatial-omics)
- [RNA Regulatory Networks](#rna-regulatory-networks)
- [Proteomics & Metabolomics](#proteomics--metabolomics)
- [Mutational Signatures](#mutational-signatures)
- [Liquid Biopsy & ctDNA](#liquid-biopsy--ctdna)
- [Survival Prediction & Prognosis](#survival-prediction--prognosis)
- [Medical LLMs & Agents](#medical-llms--agents)
- [Cancer Data Standards](#cancer-data-standards)
- [Datasets & Data Portals](#datasets--data-portals)
- [Knowledge Bases](#knowledge-bases)
- [Drug Approvals & Target-Drug Lookup](#drug-approvals--target-drug-lookup)
- [Financial Assistance & Drug Pricing](#financial-assistance--drug-pricing)
- [Clinical Guidelines](#clinical-guidelines)
- [Patient Communities](#patient-communities)
- [Related Awesome Lists](#related-awesome-lists)

---

## Patient Navigation & Decision Support

Tools that help patients understand their diagnosis, explore treatment options, and manage their care journey.

| Project | Description | Stars |
|---------|-------------|-------|
| [CancerDAO/cancer-buddy-skill](https://github.com/CancerDAO/cancer-buddy-skill) | Cancer Buddy — AI cancer companion. Medical record interpretation, clinical trial matching, expanded access navigation, parallel therapy management, patient data vault | ![Stars](https://img.shields.io/github/stars/CancerDAO/cancer-buddy-skill) |
| [PancrePal-xiaoyibao/PancrePal](https://github.com/PancrePal-xiaoyibao) | PancrePal — Pancreatic cancer patient AI assistant, the first cancer-specific patient AI tool in China | — |

## Clinical Trial Matching

Tools that help patients and clinicians find the most suitable clinical trials.

| Project | Description | Stars |
|---------|-------------|-------|
| [ncbi-nlp/TrialGPT](https://github.com/ncbi-nlp/TrialGPT) | NIH/NLM. Zero-shot LLM patient-trial matching with criterion-level eligibility assessment | ![Stars](https://img.shields.io/github/stars/ncbi-nlp/TrialGPT) |
| [dfci/matchminer](https://github.com/dfci/matchminer) | Dana-Farber Cancer Institute. Genomic profile to precision medicine trial matching | ![Stars](https://img.shields.io/github/stars/dfci/matchminer) |
| [dfci/matchengine-V2](https://github.com/dfci/matchengine-V2) | MatchMiner core matching engine V2 | ![Stars](https://img.shields.io/github/stars/dfci/matchengine-V2) |
| [chncwang/ClinTrialFinder](https://github.com/chncwang/ClinTrialFinder) | AI-driven clinical trial matching with GPT-4 eligibility scoring | ![Stars](https://img.shields.io/github/stars/chncwang/ClinTrialFinder) |
| [RyanWangZf/PyTrial](https://github.com/RyanWangZf/PyTrial) | Comprehensive AI drug development platform with trial simulation and matching | ![Stars](https://img.shields.io/github/stars/RyanWangZf/PyTrial) |
| [PancrePal-xiaoyibao/chictr-mcp-server](https://github.com/PancrePal-xiaoyibao/chictr-mcp-server) | China Clinical Trial Registry (ChiCTR) MCP Server, enabling AI search of Chinese clinical trials | ![Stars](https://img.shields.io/github/stars/PancrePal-xiaoyibao/chictr-mcp-server) |
| [cbib/TrialMatchAI](https://github.com/cbib/TrialMatchAI) | RAG-based clinical trial matching, Nature Communications 2026 | ![Stars](https://img.shields.io/github/stars/cbib/TrialMatchAI) |

## Genomics & Variant Interpretation

Cancer genome sequencing analysis, variant calling, and mutation interpretation.

| Project | Description | Stars |
|---------|-------------|-------|
| [google/deepsomatic](https://github.com/google/deepsomatic) | Deep learning somatic variant caller, Nature Biotechnology 2025 | ![Stars](https://img.shields.io/github/stars/google/deepsomatic) |
| [broadinstitute/gatk](https://github.com/broadinstitute/gatk) | Broad Institute Genome Analysis Toolkit, the industry standard | ![Stars](https://img.shields.io/github/stars/broadinstitute/gatk) |
| [google/deepvariant](https://github.com/google/deepvariant) | Google. Deep learning-based variant calling | ![Stars](https://img.shields.io/github/stars/google/deepvariant) |
| [sigven/pcgr](https://github.com/sigven/pcgr) | Personal Cancer Genome Reporter — clinical interpretation of somatic variants | ![Stars](https://img.shields.io/github/stars/sigven/pcgr) |
| [sigven/cpsr](https://github.com/sigven/cpsr) | Cancer Predisposition Sequencing Reporter — germline variant interpretation | ![Stars](https://img.shields.io/github/stars/sigven/cpsr) |
| [KarchinLab/open-cravat](https://github.com/KarchinLab/open-cravat) | Modular variant annotation and visualization platform | ![Stars](https://img.shields.io/github/stars/KarchinLab/open-cravat) |
| [griffithlab/civic-v2](https://github.com/griffithlab/civic-v2) | Clinical Interpretation of Variants in Cancer, community-curated | ![Stars](https://img.shields.io/github/stars/griffithlab/civic-v2) |
| [cBioPortal/cbioportal](https://github.com/cBioPortal/cbioportal) | MSK. Cancer genomics data visualization and analysis platform | ![Stars](https://img.shields.io/github/stars/cBioPortal/cbioportal) |
| [xjtu-omics/msisensor-pro](https://github.com/xjtu-omics/msisensor-pro) | Microsatellite instability (MSI) detection from tumor sequencing | ![Stars](https://img.shields.io/github/stars/xjtu-omics/msisensor-pro) |
| [sztup/scarHRD](https://github.com/sztup/scarHRD) | Homologous recombination deficiency (HRD) score for PARP inhibitor sensitivity | ![Stars](https://img.shields.io/github/stars/sztup/scarHRD) |
| [suhrig/arriba](https://github.com/suhrig/arriba) | Fast and accurate fusion gene detection from RNA-seq | ![Stars](https://img.shields.io/github/stars/suhrig/arriba) |
| [STAR-Fusion/STAR-Fusion](https://github.com/STAR-Fusion/STAR-Fusion) | Fusion transcript detection using STAR aligner | ![Stars](https://img.shields.io/github/stars/STAR-Fusion/STAR-Fusion) |
| [nf-core/sarek](https://github.com/nf-core/sarek) | WGS/WES variant calling Nextflow pipeline | ![Stars](https://img.shields.io/github/stars/nf-core/sarek) |
| [nf-core/rnafusion](https://github.com/nf-core/rnafusion) | RNA fusion detection Nextflow pipeline | ![Stars](https://img.shields.io/github/stars/nf-core/rnafusion) |
| [genome/analysis-workflows](https://github.com/genome/analysis-workflows) | Washington University standardized analysis pipelines (WGS/WES/RNA-seq) | ![Stars](https://img.shields.io/github/stars/genome/analysis-workflows) |

## Neoantigen Prediction & Vaccine Design

Computational pipelines for personalized cancer vaccines.

### OpenVax Suite (Mount Sinai)

| Project | Description | Stars |
|---------|-------------|-------|
| [openvax/neoantigen-vaccine-pipeline](https://github.com/openvax/neoantigen-vaccine-pipeline) | Full vaccine pipeline: DNA/RNA sequencing to personalized vaccine peptides. Used in two Phase I clinical trials | ![Stars](https://img.shields.io/github/stars/openvax/neoantigen-vaccine-pipeline) |
| [openvax/vaxrank](https://github.com/openvax/vaxrank) | Ranked vaccine peptide selection from somatic mutations + RNA-seq | ![Stars](https://img.shields.io/github/stars/openvax/vaxrank) |
| [openvax/mhcflurry](https://github.com/openvax/mhcflurry) | MHC class I binding affinity prediction, pan-allelic | ![Stars](https://img.shields.io/github/stars/openvax/mhcflurry) |
| [openvax/isovar](https://github.com/openvax/isovar) | RNA read assembly around somatic variants | ![Stars](https://img.shields.io/github/stars/openvax/isovar) |
| [openvax/pyensembl](https://github.com/openvax/pyensembl) | Python interface to Ensembl genome annotations | ![Stars](https://img.shields.io/github/stars/openvax/pyensembl) |
| [openvax/varcode](https://github.com/openvax/varcode) | Variant effect prediction on coding sequences | ![Stars](https://img.shields.io/github/stars/openvax/varcode) |
| [openvax/mhctools](https://github.com/openvax/mhctools) | Unified interface to MHC binding prediction tools | ![Stars](https://img.shields.io/github/stars/openvax/mhctools) |

### Other Neoantigen Tools

| Project | Description | Stars |
|---------|-------------|-------|
| [griffithlab/pVACtools](https://github.com/griffithlab/pVACtools) | Complete neoantigen characterization and prioritization suite | ![Stars](https://img.shields.io/github/stars/griffithlab/pVACtools) |
| [GfellerLab/MixMHCpred](https://github.com/GfellerLab/MixMHCpred) | HLA class I ligand prediction | ![Stars](https://img.shields.io/github/stars/GfellerLab/MixMHCpred) |
| [GfellerLab/PRIME](https://github.com/GfellerLab/PRIME) | Predicted immunogenicity of MHC-presented epitopes | ![Stars](https://img.shields.io/github/stars/GfellerLab/PRIME) |
| [GfellerLab/MixMHC2pred](https://github.com/GfellerLab/MixMHC2pred) | HLA class II ligand prediction | ![Stars](https://img.shields.io/github/stars/GfellerLab/MixMHC2pred) |
| [TRON-Bioinformatics/neofox](https://github.com/TRON-Bioinformatics/neofox) | NEOantigen Feature toolbOX — annotation of neoantigen candidates | ![Stars](https://img.shields.io/github/stars/TRON-Bioinformatics/neofox) |
| [MathOnco/NeoPredPipe](https://github.com/MathOnco/NeoPredPipe) | Multi-region neoantigen prediction pipeline | ![Stars](https://img.shields.io/github/stars/MathOnco/NeoPredPipe) |
| [sidhomj/DeepTCR](https://github.com/sidhomj/DeepTCR) | Deep learning framework for TCR repertoire analysis | ![Stars](https://img.shields.io/github/stars/sidhomj/DeepTCR) |
| [tianshilu/pMTnet](https://github.com/tianshilu/pMTnet) | TCR-pMHC binding prediction with deep learning | ![Stars](https://img.shields.io/github/stars/tianshilu/pMTnet) |

## Computational Pathology

AI analysis of pathology slides (H&E, IHC, etc.) for diagnosis, prognosis, and biomarker discovery.

| Project | Description | Stars |
|---------|-------------|-------|
| [qupath/qupath](https://github.com/qupath/qupath) | THE standard open-source digital pathology platform | ![Stars](https://img.shields.io/github/stars/qupath/qupath) |
| [mahmoodlab/UNI](https://github.com/mahmoodlab/UNI) | Pathology foundation model, Nature Medicine 2024 | ![Stars](https://img.shields.io/github/stars/mahmoodlab/UNI) |
| [mahmoodlab/CONCH](https://github.com/mahmoodlab/CONCH) | Vision-language foundation model for pathology | ![Stars](https://img.shields.io/github/stars/mahmoodlab/CONCH) |
| [mahmoodlab/TITAN](https://github.com/mahmoodlab/TITAN) | Multimodal whole-slide image model | ![Stars](https://img.shields.io/github/stars/mahmoodlab/TITAN) |
| [mahmoodlab/CLAM](https://github.com/mahmoodlab/CLAM) | Attention-based weakly supervised whole-slide image analysis | ![Stars](https://img.shields.io/github/stars/mahmoodlab/CLAM) |
| [mahmoodlab/TRIDENT](https://github.com/mahmoodlab/TRIDENT) | Large-scale whole-slide image processing | ![Stars](https://img.shields.io/github/stars/mahmoodlab/TRIDENT) |
| [mahmoodlab/PORPOISE](https://github.com/mahmoodlab/PORPOISE) | Histology-genomic multimodal survival prediction | ![Stars](https://img.shields.io/github/stars/mahmoodlab/PORPOISE) |
| [vqdang/hover_net](https://github.com/vqdang/hover_net) | Simultaneous nuclear segmentation and classification | ![Stars](https://img.shields.io/github/stars/vqdang/hover_net) |
| [slideflow/slideflow](https://github.com/slideflow/slideflow) | Deep learning library for digital pathology | ![Stars](https://img.shields.io/github/stars/slideflow/slideflow) |
| [PathAI/pathml](https://github.com/PathAI/pathml) | End-to-end pathology machine learning toolkit | ![Stars](https://img.shields.io/github/stars/PathAI/pathml) |
| [prov-gigapath/prov-gigapath](https://github.com/prov-gigapath/prov-gigapath) | Microsoft/Providence whole-slide pathology foundation model | ![Stars](https://img.shields.io/github/stars/prov-gigapath/prov-gigapath) |
| [PathologyFoundation/plip](https://github.com/PathologyFoundation/plip) | Pathology Language-Image Pretraining (pathology CLIP) | ![Stars](https://img.shields.io/github/stars/PathologyFoundation/plip) |
| [Xiyue-Wang/TransPath](https://github.com/Xiyue-Wang/TransPath) | CNN + Swin Transformer for computational pathology | ![Stars](https://img.shields.io/github/stars/Xiyue-Wang/TransPath) |
| [owkin/HistoSSLscaling](https://github.com/owkin/HistoSSLscaling) | Phikon — self-supervised pathology model at scale | ![Stars](https://img.shields.io/github/stars/owkin/HistoSSLscaling) |
| [georg-wolflein/pathology-foundation-models](https://github.com/georg-wolflein/pathology-foundation-models) | Directory and benchmark of pathology foundation models | ![Stars](https://img.shields.io/github/stars/georg-wolflein/pathology-foundation-models) |
| [kaiko-ai/eva](https://github.com/kaiko-ai/eva) | Oncology foundation model evaluation framework | ![Stars](https://img.shields.io/github/stars/kaiko-ai/eva) |
| [SBU-BMI/wsinfer](https://github.com/SBU-BMI/wsinfer) | Whole-slide inference model sharing ecosystem | ![Stars](https://img.shields.io/github/stars/SBU-BMI/wsinfer) |
| [openslide/openslide](https://github.com/openslide/openslide) | Whole-slide image format reader — pathology AI infrastructure | ![Stars](https://img.shields.io/github/stars/openslide/openslide) |
| [omnideconv/immunedeconv](https://github.com/omnideconv/immunedeconv) | Unified interface to immune cell deconvolution methods | ![Stars](https://img.shields.io/github/stars/omnideconv/immunedeconv) |
| [scverse/squidpy](https://github.com/scverse/squidpy) | Spatial transcriptomics analysis framework | ![Stars](https://img.shields.io/github/stars/scverse/squidpy) |
| [BayraktarLab/cell2location](https://github.com/BayraktarLab/cell2location) | Spatial cell type mapping from transcriptomics | ![Stars](https://img.shields.io/github/stars/BayraktarLab/cell2location) |

## Radiology & Medical Imaging

AI for CT, MRI, PET-CT, and other medical imaging modalities.

| Project | Description | Stars |
|---------|-------------|-------|
| [Project-MONAI/MONAI](https://github.com/Project-MONAI/MONAI) | NVIDIA + King's College. Medical imaging PyTorch framework | ![Stars](https://img.shields.io/github/stars/Project-MONAI/MONAI) |
| [Project-MONAI/MONAILabel](https://github.com/Project-MONAI/MONAILabel) | AI-assisted interactive medical image labeling | ![Stars](https://img.shields.io/github/stars/Project-MONAI/MONAILabel) |
| [MIC-DKFZ/nnUNet](https://github.com/MIC-DKFZ/nnUNet) | German Cancer Research Center. Self-configuring segmentation, multi-competition winner | ![Stars](https://img.shields.io/github/stars/MIC-DKFZ/nnUNet) |
| [MIC-DKFZ/nnDetection](https://github.com/MIC-DKFZ/nnDetection) | Self-configuring 3D medical object detection | ![Stars](https://img.shields.io/github/stars/MIC-DKFZ/nnDetection) |
| [wasserth/TotalSegmentator](https://github.com/wasserth/TotalSegmentator) | Automatic segmentation of 100+ structures in CT images | ![Stars](https://img.shields.io/github/stars/wasserth/TotalSegmentator) |
| [bowang-lab/MedSAM](https://github.com/bowang-lab/MedSAM) | Segment Anything Model adapted for medical images | ![Stars](https://img.shields.io/github/stars/bowang-lab/MedSAM) |
| [bowang-lab/MedSAM2](https://github.com/bowang-lab/MedSAM2) | MedSAM for 3D volumes and medical video | ![Stars](https://img.shields.io/github/stars/bowang-lab/MedSAM2) |
| [mlcommons/GaNDLF](https://github.com/mlcommons/GaNDLF) | Generally Nuanced Deep Learning Framework for medical images | ![Stars](https://img.shields.io/github/stars/mlcommons/GaNDLF) |
| [AIM-Harvard/pyradiomics](https://github.com/AIM-Harvard/pyradiomics) | Radiomics feature extraction from medical images | ![Stars](https://img.shields.io/github/stars/AIM-Harvard/pyradiomics) |
| [nyukat/breast_cancer_classifier](https://github.com/nyukat/breast_cancer_classifier) | Deep learning mammography screening classifier | ![Stars](https://img.shields.io/github/stars/nyukat/breast_cancer_classifier) |
| [nyukat/GMIC](https://github.com/nyukat/GMIC) | Globally-aware multiple instance classifier for interpretable mammography | ![Stars](https://img.shields.io/github/stars/nyukat/GMIC) |
| [raidionics/Raidionics](https://github.com/raidionics/Raidionics) | Pre-operative brain tumor segmentation and standardized reporting | ![Stars](https://img.shields.io/github/stars/raidionics/Raidionics) |

## Radiation Therapy Planning

| Project | Description | Stars |
|---------|-------------|-------|
| [e0404/matRad](https://e0404.github.io/matRad/) | Open-source MATLAB treatment planning for photon, proton, and carbon ion therapy | — |
| [opentps](https://opentps.org/) | Python-based open-source TPS for proton therapy research | — |
| [SlicerRT](https://slicerrt.github.io/) | Radiation therapy toolkit for 3D Slicer: DICOM-RT, DVH, dose accumulation | — |
| [dicompyler/dicompyler-core](https://github.com/dicompyler/dicompyler-core) | Python library for DICOM-RT parsing and DVH calculation | ![Stars](https://img.shields.io/github/stars/dicompyler/dicompyler-core) |
| [didymo/OnkoDICOM](https://github.com/didymo/OnkoDICOM) | Open-source DICOM-RT viewer for radiation oncology | ![Stars](https://img.shields.io/github/stars/didymo/OnkoDICOM) |

## Drug Discovery & Repositioning

AI for anticancer drug discovery, repositioning, and drug sensitivity prediction.

| Project | Description | Stars |
|---------|-------------|-------|
| [deepchem/deepchem](https://github.com/deepchem/deepchem) | Molecular machine learning Python library for drug discovery | ![Stars](https://img.shields.io/github/stars/deepchem/deepchem) |
| [mims-harvard/TDC](https://github.com/mims-harvard/TDC) | Therapeutics Data Commons — benchmarks for drug discovery ML | ![Stars](https://img.shields.io/github/stars/mims-harvard/TDC) |
| [kexinhuang12345/DeepPurpose](https://github.com/kexinhuang12345/DeepPurpose) | Deep learning toolkit for drug-target interaction prediction | ![Stars](https://img.shields.io/github/stars/kexinhuang12345/DeepPurpose) |
| [idekerlab/DrugCell](https://github.com/idekerlab/DrugCell) | Interpretable neural network for drug response prediction | ![Stars](https://img.shields.io/github/stars/idekerlab/DrugCell) |
| [kimmo1019/DeepCDR](https://github.com/kimmo1019/DeepCDR) | Cancer drug response prediction (Tsinghua University) | ![Stars](https://img.shields.io/github/stars/kimmo1019/DeepCDR) |

**Data Resources:**
- [GDSC](https://www.cancerrxgene.org/) — Genomics of Drug Sensitivity in Cancer (1000+ cell lines x hundreds of drugs)
- [DepMap](https://depmap.org/) — Broad Cancer Dependency Map (identifying vulnerabilities in every cancer)
- [PRISM](https://depmap.org/repurposing/) — Large-scale drug repurposing screening data

## Single-cell & Spatial Omics

Single-cell and spatial transcriptomics analysis for tumor microenvironment characterization.

| Project | Description | Stars |
|---------|-------------|-------|
| [broadinstitute/infercnv](https://github.com/broadinstitute/infercnv) | Infer copy number variations from single-cell RNA-seq | ![Stars](https://img.shields.io/github/stars/broadinstitute/infercnv) |
| [navinlabcode/copykat](https://github.com/navinlabcode/copykat) | Bayesian CNV classification to distinguish tumor from normal cells | ![Stars](https://img.shields.io/github/stars/navinlabcode/copykat) |
| [icbi-lab/infercnvpy](https://github.com/icbi-lab/infercnvpy) | Python implementation of CNV inference from scRNA-seq | ![Stars](https://img.shields.io/github/stars/icbi-lab/infercnvpy) |
| [Teichlab/celltypist](https://github.com/Teichlab/celltypist) | Automated cell type annotation for single-cell data | ![Stars](https://img.shields.io/github/stars/Teichlab/celltypist) |
| [scverse/scvi-tools](https://github.com/scverse/scvi-tools) | Deep generative models for single-cell omics | ![Stars](https://img.shields.io/github/stars/scverse/scvi-tools) |
| [BorchLab/scRepertoire](https://github.com/BorchLab/scRepertoire) | Single-cell TCR/BCR repertoire analysis | ![Stars](https://img.shields.io/github/stars/BorchLab/scRepertoire) |
| [immunomind/immunarch](https://github.com/immunomind/immunarch) | Immune repertoire analysis framework (TCR/BCR sequencing) | ![Stars](https://img.shields.io/github/stars/immunomind/immunarch) |
| [scverse/scirpy](https://github.com/scverse/scirpy) | Python library for single-cell immune repertoire analysis | ![Stars](https://img.shields.io/github/stars/scverse/scirpy) |
| [10xgenomics/cellranger](https://github.com/10xgenomics/cellranger) | 10x Genomics single-cell analysis pipeline | ![Stars](https://img.shields.io/github/stars/10xgenomics/cellranger) |
| [bowang-lab/scGPT](https://github.com/bowang-lab/scGPT) | Single-cell foundation model built on generative pretraining | ![Stars](https://img.shields.io/github/stars/bowang-lab/scGPT) |
| [BoevaLab/CancerFoundation](https://github.com/BoevaLab/CancerFoundation) | Foundation model specifically for cancer single-cell biology | ![Stars](https://img.shields.io/github/stars/BoevaLab/CancerFoundation) |

## RNA Regulatory Networks

| Resource | Description |
|----------|-------------|
| [miRBase](https://www.mirbase.org/) | Definitive miRNA sequence database |
| [miRTarBase](https://mirtarbase.cuhk.edu.cn/) | 360,000+ experimentally validated miRNA-target interactions |
| [ENCORI/starBase](https://rnasysu.com/encori/) | Pan-cancer RNA interaction platform across 32 cancer types |
| [LNCipedia](https://lncipedia.org/) | Human lncRNA annotations and functional data |
| [NONCODE](https://www.noncode.org/) | Comprehensive lncRNA database with cancer associations |

## Proteomics & Metabolomics

| Resource | Description |
|----------|-------------|
| [MaxQuant](https://maxquant.org/) | Gold-standard quantitative proteomics software |
| [Perseus](https://maxquant.net/perseus/) | Statistical analysis platform for proteomics |
| [CPTAC/Proteomic Data Commons](https://proteomic.datacommons.cancer.gov/) | NCI cancer proteomics repository: 1,000+ tumors, 10 cancer types |
| [HMDB](https://www.hmdb.ca/) | Human Metabolome Database: 220,945 metabolites with disease associations |
| [MetaboAnalyst](https://www.metaboanalyst.ca/) | Comprehensive metabolomics analysis web platform |

## Mutational Signatures

Tools for extracting and analyzing mutational signatures in cancer genomes.

### SigProfiler Suite (Alexandrov Lab, UCSD)

| Project | Description | Stars |
|---------|-------------|-------|
| [AlexandrovLab/SigProfilerExtractor](https://github.com/AlexandrovLab/SigProfilerExtractor) | De novo extraction of mutational signatures | ![Stars](https://img.shields.io/github/stars/AlexandrovLab/SigProfilerExtractor) |
| [AlexandrovLab/SigProfilerAssignment](https://github.com/AlexandrovLab/SigProfilerAssignment) | Assignment of known signatures to samples | ![Stars](https://img.shields.io/github/stars/AlexandrovLab/SigProfilerAssignment) |
| [AlexandrovLab/SigProfilerMatrixGenerator](https://github.com/AlexandrovLab/SigProfilerMatrixGenerator) | Mutational matrix generation from VCF files | ![Stars](https://img.shields.io/github/stars/AlexandrovLab/SigProfilerMatrixGenerator) |
| [AlexandrovLab/SigProfilerPlotting](https://github.com/AlexandrovLab/SigProfilerPlotting) | Visualization of mutational signatures | ![Stars](https://img.shields.io/github/stars/AlexandrovLab/SigProfilerPlotting) |

### Other Signature Tools

| Project | Description | Stars |
|---------|-------------|-------|
| [ShixiangWang/sigminer](https://github.com/ShixiangWang/sigminer) | Comprehensive mutational signature analysis in R | ![Stars](https://img.shields.io/github/stars/ShixiangWang/sigminer) |
| [raerose01/deconstructSigs](https://github.com/raerose01/deconstructSigs) | Determine signature contributions in individual tumors | ![Stars](https://img.shields.io/github/stars/raerose01/deconstructSigs) |
| [UMCUGenetics/MutationalPatterns](https://github.com/UMCUGenetics/MutationalPatterns) | Comprehensive mutational pattern analysis in R/Bioconductor | ![Stars](https://img.shields.io/github/stars/UMCUGenetics/MutationalPatterns) |
| [Nik-Zainal-Group/signature.tools.lib](https://github.com/Nik-Zainal-Group/signature.tools.lib) | Signature analysis tools from the Nik-Zainal Lab | ![Stars](https://img.shields.io/github/stars/Nik-Zainal-Group/signature.tools.lib) |
| [parklab/SigMA](https://github.com/parklab/SigMA) | Signature Multivariate Analysis for targeted panels | ![Stars](https://img.shields.io/github/stars/parklab/SigMA) |
| [mskcc/mutation-signatures](https://github.com/mskcc/mutation-signatures) | MSK mutation signature analysis tools | ![Stars](https://img.shields.io/github/stars/mskcc/mutation-signatures) |
| [morrislab/TrackSig](https://github.com/morrislab/TrackSig) | Track signature activity changes through tumor evolution | ![Stars](https://img.shields.io/github/stars/morrislab/TrackSig) |

## Liquid Biopsy & ctDNA

Tools for circulating tumor DNA analysis, minimal residual disease detection, and fragmentomics.

| Project | Description | Stars |
|---------|-------------|-------|
| [broadinstitute/ichorCNA](https://github.com/broadinstitute/ichorCNA) | Estimate tumor fraction from cell-free DNA shallow WGS | ![Stars](https://img.shields.io/github/stars/broadinstitute/ichorCNA) |
| [cancer-genomics/delfi3](https://github.com/cancer-genomics/delfi3) | DNA fragmentation analysis for cancer detection | ![Stars](https://img.shields.io/github/stars/cancer-genomics/delfi3) |
| [XWangLabTHU/cfDNApipe](https://github.com/XWangLabTHU/cfDNApipe) | Comprehensive cfDNA analysis pipeline (Tsinghua University) | ![Stars](https://img.shields.io/github/stars/XWangLabTHU/cfDNApipe) |
| [epifluidlab/FinaleToolkit](https://github.com/epifluidlab/FinaleToolkit) | High-speed DNA fragmentation analysis toolkit | ![Stars](https://img.shields.io/github/stars/epifluidlab/FinaleToolkit) |
| [alkodsi/ctDNAtools](https://github.com/alkodsi/ctDNAtools) | R package for minimal residual disease detection from ctDNA | ![Stars](https://img.shields.io/github/stars/alkodsi/ctDNAtools) |
| [OpenGene/ctdna-pipeline](https://github.com/OpenGene/ctdna-pipeline) | ctDNA analysis pipeline | ![Stars](https://img.shields.io/github/stars/OpenGene/ctdna-pipeline) |

## Survival Prediction & Prognosis

Statistical and deep learning tools for cancer survival analysis.

| Project | Description | Stars |
|---------|-------------|-------|
| [CamDavidsonPilon/lifelines](https://github.com/CamDavidsonPilon/lifelines) | Survival analysis in pure Python | ![Stars](https://img.shields.io/github/stars/CamDavidsonPilon/lifelines) |
| [sebp/scikit-survival](https://github.com/sebp/scikit-survival) | Scikit-learn compatible survival analysis | ![Stars](https://img.shields.io/github/stars/sebp/scikit-survival) |
| [havakv/pycox](https://github.com/havakv/pycox) | Deep learning survival analysis with PyTorch | ![Stars](https://img.shields.io/github/stars/havakv/pycox) |
| [jaredleekatzman/DeepSurv](https://github.com/jaredleekatzman/DeepSurv) | Deep Cox proportional hazards network | ![Stars](https://img.shields.io/github/stars/jaredleekatzman/DeepSurv) |
| [autonlab/auton-survival](https://github.com/autonlab/auton-survival) | CMU Auton Lab survival analysis toolkit | ![Stars](https://img.shields.io/github/stars/autonlab/auton-survival) |
| [mahmoodlab/PORPOISE](https://github.com/mahmoodlab/PORPOISE) | Multimodal histology-genomic survival prediction | ![Stars](https://img.shields.io/github/stars/mahmoodlab/PORPOISE) |
| [Novartis/torchsurv](https://github.com/Novartis/torchsurv) | PyTorch-based survival loss functions and metrics | ![Stars](https://img.shields.io/github/stars/Novartis/torchsurv) |

## Medical LLMs & Agents

Large language models and AI agents for medicine and oncology.

| Project | Description | Stars |
|---------|-------------|-------|
| [romeo111/OpenOnco](https://github.com/romeo111/OpenOnco) | MCP tools let AI assistants request source-cited oncology plan drafts and diagnostic briefs from a deterministic rules engine; early-stage, clinician review required | ![Stars](https://img.shields.io/github/stars/romeo111/OpenOnco) |
| [shibing624/MedicalGPT](https://github.com/shibing624/MedicalGPT) | Train your own medical GPT with full pipeline | ![Stars](https://img.shields.io/github/stars/shibing624/MedicalGPT) |
| [SCIR-HI/Huatuo-Llama-Med-Chinese](https://github.com/SCIR-HI/Huatuo-Llama-Med-Chinese) | Chinese medical LLM based on LLaMA | ![Stars](https://img.shields.io/github/stars/SCIR-HI/Huatuo-Llama-Med-Chinese) |
| [microsoft/BioGPT](https://github.com/microsoft/BioGPT) | Microsoft. Generative pre-trained transformer for biomedical text | ![Stars](https://img.shields.io/github/stars/microsoft/BioGPT) |
| [epfLLM/meditron](https://github.com/epfLLM/meditron) | EPFL. Open-source medical large language model | ![Stars](https://img.shields.io/github/stars/epfLLM/meditron) |
| [dmis-lab/biobert](https://github.com/dmis-lab/biobert) | Biomedical BERT pre-trained on PubMed/PMC | ![Stars](https://img.shields.io/github/stars/dmis-lab/biobert) |
| [FreedomIntelligence/HuatuoGPT](https://github.com/FreedomIntelligence/HuatuoGPT) | HuatuoGPT — Chinese medical dialogue model | ![Stars](https://img.shields.io/github/stars/FreedomIntelligence/HuatuoGPT) |
| [chaoyi-wu/PMC-LLaMA](https://github.com/chaoyi-wu/PMC-LLaMA) | LLaMA fine-tuned on PubMed Central articles | ![Stars](https://img.shields.io/github/stars/chaoyi-wu/PMC-LLaMA) |
| [michael-wzhu/ChatMed](https://github.com/michael-wzhu/ChatMed) | Chinese medical dialogue LLM | ![Stars](https://img.shields.io/github/stars/michael-wzhu/ChatMed) |
| [kbressem/medAlpaca](https://github.com/kbressem/medAlpaca) | Medical conversational AI based on Alpaca | ![Stars](https://img.shields.io/github/stars/kbressem/medAlpaca) |
| [msk-mph/woollie](https://github.com/msk-mph/woollie) | MSK oncology large language model | ![Stars](https://img.shields.io/github/stars/msk-mph/woollie) |
| [KatherLab/LLMAIx](https://github.com/KatherLab/LLMAIx) | Privacy-preserving oncology NLP framework | ![Stars](https://img.shields.io/github/stars/KatherLab/LLMAIx) |
| [facebookresearch/esm](https://github.com/facebookresearch/esm) | Evolutionary Scale Modeling — protein language models | ![Stars](https://img.shields.io/github/stars/facebookresearch/esm) |

## Cancer Data Standards

Standards and platforms for interoperable cancer data exchange.

| Project | Description | Stars |
|---------|-------------|-------|
| [cBioPortal/cbioportal](https://github.com/cBioPortal/cbioportal) | MSK. Cancer genomics data visualization and analysis platform | ![Stars](https://img.shields.io/github/stars/cBioPortal/cbioportal) |
| [HL7/fhir-mCODE-ig](https://github.com/HL7/fhir-mCODE-ig) | mCODE — Minimal Common Oncology Data Elements FHIR standard | ![Stars](https://img.shields.io/github/stars/HL7/fhir-mCODE-ig) |
| [ga4gh/phenopacket-schema](https://github.com/ga4gh/phenopacket-schema) | GA4GH Phenopackets — standardized patient phenotype exchange | ![Stars](https://img.shields.io/github/stars/ga4gh/phenopacket-schema) |
| [monarch-initiative/oncopacket](https://github.com/monarch-initiative/oncopacket) | Oncology-specific Phenopacket generation | ![Stars](https://img.shields.io/github/stars/monarch-initiative/oncopacket) |
| [OHDSI/CommonDataModel](https://github.com/OHDSI/CommonDataModel) | OMOP Common Data Model for observational health data | ![Stars](https://img.shields.io/github/stars/OHDSI/CommonDataModel) |
| [OHDSI/OncologyWG](https://github.com/OHDSI/OncologyWG) | OHDSI Oncology Working Group — OMOP extensions for cancer | ![Stars](https://img.shields.io/github/stars/OHDSI/OncologyWG) |
| [opencb/opencga](https://github.com/opencb/opencga) | Open platform for clinical genomics analysis | ![Stars](https://img.shields.io/github/stars/opencb/opencga) |

## Datasets & Data Portals

| Platform | Description | Type |
|----------|-------------|------|
| [GDC Data Portal](https://portal.gdc.cancer.gov/) | NCI Genomic Data Commons (TCGA, TARGET, and more) | Genomic |
| [TCGA](https://www.cancer.gov/tcga) | The Cancer Genome Atlas — multi-omic data across 33 cancer types | Multi-omic |
| [TCIA](https://www.cancerimagingarchive.net/) | The Cancer Imaging Archive — open-access medical images | Imaging |
| [SEER](https://seer.cancer.gov/) | NCI Surveillance, Epidemiology, and End Results Program | Epidemiology |
| [Reactome](https://reactome.org/) | Open-source biological pathway database | Pathways |
| [osteosarc.com](https://osteosarc.com/) | Sid Sijbrandij's 25 TB osteosarcoma dataset — N=1 data sharing | N=1 |
| [AACR Project GENIE](https://www.aacr.org/professionals/research/aacr-project-genie/) | 271K samples real-world clinico-genomic data from 20 centers | Clinico-genomic |
| [GLOBOCAN/GCO](https://gco.iarc.who.int/) | IARC global cancer incidence, mortality, survival for 185 countries | Epidemiology |
| [CCLE/DepMap](https://depmap.org/portal/) | Cancer Cell Line Encyclopedia + Dependency Map: 1,000+ cell lines | Cell Lines |
| [PCAWG](https://dcc.icgc.org/pcawg) | 2,658 whole cancer genomes across 38 tumor types | Whole Genome |
| [CPTAC/PDC](https://proteomic.datacommons.cancer.gov/) | NCI cancer proteomics across 10 cancer types | Proteomics |
| [TARGET](https://www.cancer.gov/ccg/research/genome-sequencing/target/about) | NCI pediatric cancer genomics program | Pediatric |
| [UCSC Xena](https://xenabrowser.net/) | Visual browser for 1,500+ cancer datasets across 50 cancer types | Multi-omic |
| [CellMiner](https://discover.nci.nih.gov/cellminer/) | NCI-60 cell line explorer: genes, miRNAs, compounds | Cell Lines |
| [METABRIC](https://www.cbioportal.org/study?id=brca_metabric) | 2,000 breast cancer tumors multi-omic dataset | Breast Cancer |

## Knowledge Bases

| Database | Description | Type |
|----------|-------------|------|
| [OncoKB](https://www.oncokb.org/) | MSK Precision Oncology Knowledge Base (variant actionability tiering) | Variant interpretation |
| [CIViC](https://civicdb.org/) | Community-curated Clinical Interpretation of Variants in Cancer | Variant interpretation |
| [COSMIC](https://cancer.sanger.ac.uk/cosmic) | Catalogue of Somatic Mutations in Cancer | Mutations |
| [ClinVar](https://www.ncbi.nlm.nih.gov/clinvar/) | Genomic variant and clinical significance database | Variants |
| [DrugBank](https://go.drugbank.com/) | Comprehensive drug data resource | Drugs |
| [PharmGKB](https://www.pharmgkb.org/) | Pharmacogenomics Knowledge Base | Pharmacogenomics |
| [FAERS](https://open.fda.gov/data/faers/) | FDA Adverse Event Reporting System | Drug safety |
| [IEDB](https://www.iedb.org/) | Immune Epitope Database | Immunology |

## Drug Approvals & Target-Drug Lookup

| Resource | Description | Type |
|----------|-------------|------|
| [Drugs@FDA](https://www.accessdata.fda.gov/scripts/cder/daf/) | Official FDA drug approval database with labels and reviews | Regulatory |
| [openFDA](https://open.fda.gov/) | API-accessible FDA data: adverse events, drug labels, recalls | API |
| [DailyMed](https://dailymed.nlm.nih.gov/) | NLM database of current drug labeling in structured format | Drug Labels |
| [NCI Drug Dictionary](https://www.cancer.gov/publications/dictionaries/cancer-drug) | Cancer-specific drug encyclopedia with mechanism of action | Cancer Drugs |
| [My Cancer Genome](https://www.mycancergenome.org/) | Vanderbilt. Maps mutations to approved therapies across 957 cancer types | Precision Medicine |
| [Cancer Genome Interpreter](https://www.cancergenomeinterpreter.org/) | Upload variants, get automated driver identification and drug matching | Variant-Drug |
| [Genome Nexus](https://www.genomenexus.org/) | MSK variant annotation API aggregating 12+ sources | Variant Annotation |
| [Cancer Hotspots](https://www.cancerhotspots.org/) | MSK. Statistically significant recurrent mutations in cancer | Hotspot Mutations |
| [FDA Companion Diagnostics](https://www.fda.gov/medical-devices/in-vitro-diagnostics/list-cleared-or-approved-companion-diagnostic-devices-in-vitro-and-imaging-tools) | Biomarker → companion diagnostic → drug mapping | Diagnostics |
| [Therapeutic Target Database](https://idrblab.org/ttd/) | 3,798 targets × 40,398 drugs with clinical profiles | Target-Drug |
| [EMA Medicines](https://www.ema.europa.eu/en/medicines) | European drug approvals with full assessment reports | Regulatory |
| [CPIC Guidelines](https://cpicpgx.org/guidelines/) | Genotype-based dosing guidelines for chemotherapy (e.g., DPYD/fluoropyrimidine) | Pharmacogenomics |
| [FDALabel](https://www.fda.gov/science-research/bioinformatics-tools/fdalabel-full-text-search-drug-product-labeling) | Full-text search across 150,000+ FDA drug labels | Label Search |

## Financial Assistance & Drug Pricing

| Resource | Description |
|----------|-------------|
| [NeedyMeds](https://www.needymeds.org/) | Database of patient assistance programs, copay cards, free clinics |
| [RxAssist](https://www.rxassist.org/) | Patient assistance program database searchable by drug name |
| [PAN Foundation](https://www.panfoundation.org/) | Copay assistance for underinsured cancer patients |
| [CancerCare Financial Assistance](https://www.cancercare.org/copayfoundation) | Copay assistance specifically for cancer treatments |
| [Cancer Financial Assistance Coalition](https://www.cancerfac.org/) | Searchable database of organizations providing financial help |
| [GoodRx](https://www.goodrx.com/) | Drug price comparison across 70,000+ US pharmacies |

## Clinical Guidelines

| Resource | Description | Region |
|----------|-------------|--------|
| [NCCN Guidelines](https://www.nccn.org/guidelines/) | National Comprehensive Cancer Network Guidelines | USA |
| [ESMO Guidelines](https://www.esmo.org/guidelines) | European Society for Medical Oncology Guidelines | Europe |
| [CSCO Guidelines](https://www.csco.org.cn/) | Chinese Society of Clinical Oncology Guidelines | China |
| [ASCO Guidelines](https://www.asco.org/guidelines) | American Society of Clinical Oncology evidence-based guidelines | USA |
| [NICE Cancer Pathways](https://www.nice.org.uk/guidance/conditions-and-diseases/cancer) | UK cancer treatment pathways with cost-effectiveness analysis | UK |
| [CACA Guidelines](http://www.caca.org.cn/) | Chinese Integrated Cancer Guidelines covering 53 cancer types | China |

## Patient Communities

| Resource | Description |
|----------|-------------|
| [osteosarc.com](https://osteosarc.com/) | Sid Sijbrandij's osteosarcoma open data project — N=1 data sharing exemplar |
| [Even One Ventures](https://evenone.ventures/) | "Patient First" biotech investment fund founded by Sid Sijbrandij |
| [Cancer.Net](https://www.cancer.net/) | ASCO patient information: cancer types, treatment, coping guides |
| [CancerCare](https://www.cancercare.org/) | Free counseling, support groups, financial assistance for cancer patients |
| [American Cancer Society](https://www.cancer.org/) | 24/7 helpline, lodging, rides to treatment, financial guidance |
| [Macmillan Cancer Support](https://www.macmillan.org.uk/) | UK's leading cancer charity: nurses, financial help, online community |
| [NCI-Designated Cancer Centers](https://www.cancer.gov/research/infrastructure/cancer-centers/find) | Directory of 73 top US cancer centers for finding specialists |

## Related Awesome Lists

| Project | Description |
|---------|-------------|
| [cbailes/awesome-ai-cancer](https://github.com/cbailes/awesome-ai-cancer) | AI in cancer diagnosis and oncology |
| [medtorch/awesome-healthcare-ai](https://github.com/medtorch/awesome-healthcare-ai) | Open-source healthcare AI tools and datasets |
| [broadinstitute/AwesomeGenomics](https://github.com/broadinstitute/AwesomeGenomics) | Broad Institute genomics tools |
| [FreedomIntelligence/Awesome-Specialized-Medical-LLMs](https://github.com/FreedomIntelligence/Awesome-Specialized-Medical-LLMs) | Specialized medical LLM collection |
| [AgenticHealthAI/Awesome-AI-Agents-for-Healthcare](https://github.com/AgenticHealthAI/Awesome-AI-Agents-for-Healthcare) | AI agents for healthcare — papers and projects |

---

## Contributing

Contributions welcome! Please submit a PR to add a project. Format:

```markdown
| [org/project](GitHub-URL) | One-line description | ![Stars](https://img.shields.io/github/stars/org/project) |
```

Before submitting, please confirm: the project is directly related to cancer + AI, and is open-source.

---

<div align="center">

Maintained by [CancerDAO](https://github.com/CancerDAO)

**Great tools should not be known only to the few. Star this repo to help more people find them.**

</div>
