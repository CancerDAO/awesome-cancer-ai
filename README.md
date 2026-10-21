<div align="center">

# 开源抗癌 AI 资源大全 — 250+ 项目 [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

精选 250+ 个用于癌症研究和患者关怀的开源 AI 工具、数据集与资源。

[English](README_EN.md) · [贡献指南](#contributing)

</div>

---

## 目录

- [患者导航与决策支持](#患者导航与决策支持)
- [临床试验匹配](#临床试验匹配)
- [基因组学与变异解读](#基因组学与变异解读)
- [新抗原预测与疫苗设计](#新抗原预测与疫苗设计)
- [计算病理学](#计算病理学)
- [放射学与医学影像](#放射学与医学影像)
- [放射治疗规划](#放射治疗规划)
- [药物发现与重定位](#药物发现与重定位)
- [单细胞与空间组学](#单细胞与空间组学)
- [RNA 调控网络](#rna-调控网络)
- [蛋白质组与代谢组](#蛋白质组与代谢组)
- [突变特征](#突变特征)
- [液体活检与 ctDNA](#液体活检与-ctdna)
- [生存预测与预后](#生存预测与预后)
- [医学大语言模型与智能体](#医学大语言模型与智能体)
- [肿瘤数据标准](#肿瘤数据标准)
- [数据集与数据平台](#数据集与数据平台)
- [知识库](#知识库)
- [药物审批与靶点查询](#药物审批与靶点查询)
- [临床指南](#临床指南)
- [患者社区](#患者社区)
- [患者财务援助](#患者财务援助)
- [中国特色项目](#中国特色项目)
- [相关 Awesome 列表](#相关-awesome-列表)

---

## 患者导航与决策支持

帮助患者了解诊断、探索治疗方案、管理就医旅程的工具。

| 项目 | 描述 | Stars |
|------|------|-------|
| [CancerDAO/cancer-buddy-skill](https://github.com/CancerDAO/cancer-buddy-skill) | 抗癌搭子 — AI 抗癌伙伴。病历解读、临床试验匹配、扩展准入导航、并行治疗管理、患者数据保险箱 | ![Stars](https://img.shields.io/github/stars/CancerDAO/cancer-buddy-skill) |
| [PancrePal-xiaoyibao/PancrePal](https://github.com/PancrePal-xiaoyibao) | 小胰宝 — 胰腺癌患者 AI 助手，国内首个癌种专属患者 AI 工具 | — |

## 临床试验匹配

帮助患者和临床医生找到最适合的临床试验的工具。

| 项目 | 描述 | Stars |
|------|------|-------|
| [ncbi-nlp/TrialGPT](https://github.com/ncbi-nlp/TrialGPT) | NIH/NLM 出品。零样本 LLM 患者-试验匹配，支持逐条标准评估 | ![Stars](https://img.shields.io/github/stars/ncbi-nlp/TrialGPT) |
| [dfci/matchminer](https://github.com/dfci/matchminer) | Dana-Farber 癌症研究所。基因组特征到精准医疗试验匹配 | ![Stars](https://img.shields.io/github/stars/dfci/matchminer) |
| [dfci/matchengine-V2](https://github.com/dfci/matchengine-V2) | MatchMiner 核心匹配引擎 V2 | ![Stars](https://img.shields.io/github/stars/dfci/matchengine-V2) |
| [chncwang/ClinTrialFinder](https://github.com/chncwang/ClinTrialFinder) | 基于 GPT-4 入排标准评分的 AI 临床试验匹配 | ![Stars](https://img.shields.io/github/stars/chncwang/ClinTrialFinder) |
| [RyanWangZf/PyTrial](https://github.com/RyanWangZf/PyTrial) | 综合 AI 药物研发平台，支持试验模拟与匹配 | ![Stars](https://img.shields.io/github/stars/RyanWangZf/PyTrial) |
| [PancrePal-xiaoyibao/chictr-mcp-server](https://github.com/PancrePal-xiaoyibao/chictr-mcp-server) | 中国临床试验注册中心（ChiCTR）MCP Server，让 AI 可检索中国临床试验 | ![Stars](https://img.shields.io/github/stars/PancrePal-xiaoyibao/chictr-mcp-server) |
| [cbib/TrialMatchAI](https://github.com/cbib/TrialMatchAI) | 基于 RAG 的临床试验匹配，Nature Communications 2026 | ![Stars](https://img.shields.io/github/stars/cbib/TrialMatchAI) |

## 基因组学与变异解读

癌症基因组测序分析、变异检测与突变解读。

| 项目 | 描述 | Stars |
|------|------|-------|
| [google/deepsomatic](https://github.com/google/deepsomatic) | 深度学习体细胞变异检测，Nature Biotechnology 2025 | ![Stars](https://img.shields.io/github/stars/google/deepsomatic) |
| [broadinstitute/gatk](https://github.com/broadinstitute/gatk) | Broad 研究所基因组分析工具包，行业标准 | ![Stars](https://img.shields.io/github/stars/broadinstitute/gatk) |
| [google/deepvariant](https://github.com/google/deepvariant) | Google 出品。基于深度学习的变异检测 | ![Stars](https://img.shields.io/github/stars/google/deepvariant) |
| [sigven/pcgr](https://github.com/sigven/pcgr) | 个人癌症基因组报告器 — 体细胞变异临床解读 | ![Stars](https://img.shields.io/github/stars/sigven/pcgr) |
| [sigven/cpsr](https://github.com/sigven/cpsr) | 癌症易感性测序报告器 — 胚系变异解读 | ![Stars](https://img.shields.io/github/stars/sigven/cpsr) |
| [KarchinLab/open-cravat](https://github.com/KarchinLab/open-cravat) | 模块化变异注释与可视化平台 | ![Stars](https://img.shields.io/github/stars/KarchinLab/open-cravat) |
| [griffithlab/civic-v2](https://github.com/griffithlab/civic-v2) | 癌症变异临床解读，社区协作标注 | ![Stars](https://img.shields.io/github/stars/griffithlab/civic-v2) |
| [cBioPortal/cbioportal](https://github.com/cBioPortal/cbioportal) | MSK 出品。癌症基因组数据可视化与分析平台 | ![Stars](https://img.shields.io/github/stars/cBioPortal/cbioportal) |
| [xjtu-omics/msisensor-pro](https://github.com/xjtu-omics/msisensor-pro) | 基于肿瘤测序的微卫星不稳定性（MSI）检测 | ![Stars](https://img.shields.io/github/stars/xjtu-omics/msisensor-pro) |
| [sztup/scarHRD](https://github.com/sztup/scarHRD) | 同源重组缺陷（HRD）评分，用于 PARP 抑制剂敏感性预测 | ![Stars](https://img.shields.io/github/stars/sztup/scarHRD) |
| [suhrig/arriba](https://github.com/suhrig/arriba) | 基于 RNA-seq 的快速准确融合基因检测 | ![Stars](https://img.shields.io/github/stars/suhrig/arriba) |
| [STAR-Fusion/STAR-Fusion](https://github.com/STAR-Fusion/STAR-Fusion) | 基于 STAR 比对器的融合转录本检测 | ![Stars](https://img.shields.io/github/stars/STAR-Fusion/STAR-Fusion) |
| [nf-core/sarek](https://github.com/nf-core/sarek) | WGS/WES 变异检测 Nextflow 流水线 | ![Stars](https://img.shields.io/github/stars/nf-core/sarek) |
| [nf-core/rnafusion](https://github.com/nf-core/rnafusion) | RNA 融合检测 Nextflow 流水线 | ![Stars](https://img.shields.io/github/stars/nf-core/rnafusion) |
| [genome/analysis-workflows](https://github.com/genome/analysis-workflows) | 华盛顿大学标准化分析流水线（WGS/WES/RNA-seq） | ![Stars](https://img.shields.io/github/stars/genome/analysis-workflows) |

## 新抗原预测与疫苗设计

个性化癌症疫苗计算流水线。

### OpenVax 套件（Mount Sinai 医学院）

| 项目 | 描述 | Stars |
|------|------|-------|
| [openvax/neoantigen-vaccine-pipeline](https://github.com/openvax/neoantigen-vaccine-pipeline) | 完整疫苗流水线：从 DNA/RNA 测序到个性化疫苗肽段。已用于两项 I 期临床试验 | ![Stars](https://img.shields.io/github/stars/openvax/neoantigen-vaccine-pipeline) |
| [openvax/vaxrank](https://github.com/openvax/vaxrank) | 基于体细胞突变 + RNA-seq 的疫苗肽段排序选择 | ![Stars](https://img.shields.io/github/stars/openvax/vaxrank) |
| [openvax/mhcflurry](https://github.com/openvax/mhcflurry) | MHC I 类分子结合亲和力预测，泛等位基因 | ![Stars](https://img.shields.io/github/stars/openvax/mhcflurry) |
| [openvax/isovar](https://github.com/openvax/isovar) | 体细胞变异位点 RNA 序列组装 | ![Stars](https://img.shields.io/github/stars/openvax/isovar) |
| [openvax/pyensembl](https://github.com/openvax/pyensembl) | Ensembl 基因组注释 Python 接口 | ![Stars](https://img.shields.io/github/stars/openvax/pyensembl) |
| [openvax/varcode](https://github.com/openvax/varcode) | 编码序列变异效果预测 | ![Stars](https://img.shields.io/github/stars/openvax/varcode) |
| [openvax/mhctools](https://github.com/openvax/mhctools) | MHC 结合预测工具统一接口 | ![Stars](https://img.shields.io/github/stars/openvax/mhctools) |

### 其他新抗原工具

| 项目 | 描述 | Stars |
|------|------|-------|
| [griffithlab/pVACtools](https://github.com/griffithlab/pVACtools) | 完整的新抗原表征与优先级排序套件 | ![Stars](https://img.shields.io/github/stars/griffithlab/pVACtools) |
| [GfellerLab/MixMHCpred](https://github.com/GfellerLab/MixMHCpred) | HLA I 类配体预测 | ![Stars](https://img.shields.io/github/stars/GfellerLab/MixMHCpred) |
| [GfellerLab/PRIME](https://github.com/GfellerLab/PRIME) | MHC 呈递表位免疫原性预测 | ![Stars](https://img.shields.io/github/stars/GfellerLab/PRIME) |
| [GfellerLab/MixMHC2pred](https://github.com/GfellerLab/MixMHC2pred) | HLA II 类配体预测 | ![Stars](https://img.shields.io/github/stars/GfellerLab/MixMHC2pred) |
| [TRON-Bioinformatics/neofox](https://github.com/TRON-Bioinformatics/neofox) | NEOantigen Feature toolbOX — 新抗原候选注释 | ![Stars](https://img.shields.io/github/stars/TRON-Bioinformatics/neofox) |
| [MathOnco/NeoPredPipe](https://github.com/MathOnco/NeoPredPipe) | 多区域新抗原预测流水线 | ![Stars](https://img.shields.io/github/stars/MathOnco/NeoPredPipe) |
| [sidhomj/DeepTCR](https://github.com/sidhomj/DeepTCR) | TCR 库分析深度学习框架 | ![Stars](https://img.shields.io/github/stars/sidhomj/DeepTCR) |
| [tianshilu/pMTnet](https://github.com/tianshilu/pMTnet) | 基于深度学习的 TCR-pMHC 结合预测 | ![Stars](https://img.shields.io/github/stars/tianshilu/pMTnet) |

## 计算病理学

AI 分析病理切片（H&E、IHC 等），用于诊断、预后及生物标志物发现。

| 项目 | 描述 | Stars |
|------|------|-------|
| [qupath/qupath](https://github.com/qupath/qupath) | 开源数字病理学标准平台 | ![Stars](https://img.shields.io/github/stars/qupath/qupath) |
| [mahmoodlab/UNI](https://github.com/mahmoodlab/UNI) | 病理学基础模型，Nature Medicine 2024 | ![Stars](https://img.shields.io/github/stars/mahmoodlab/UNI) |
| [mahmoodlab/CONCH](https://github.com/mahmoodlab/CONCH) | 病理学视觉-语言基础模型 | ![Stars](https://img.shields.io/github/stars/mahmoodlab/CONCH) |
| [mahmoodlab/TITAN](https://github.com/mahmoodlab/TITAN) | 多模态全切片图像模型 | ![Stars](https://img.shields.io/github/stars/mahmoodlab/TITAN) |
| [mahmoodlab/CLAM](https://github.com/mahmoodlab/CLAM) | 基于注意力机制的弱监督全切片图像分析 | ![Stars](https://img.shields.io/github/stars/mahmoodlab/CLAM) |
| [mahmoodlab/TRIDENT](https://github.com/mahmoodlab/TRIDENT) | 大规模全切片图像处理 | ![Stars](https://img.shields.io/github/stars/mahmoodlab/TRIDENT) |
| [mahmoodlab/PORPOISE](https://github.com/mahmoodlab/PORPOISE) | 组织学-基因组多模态生存预测 | ![Stars](https://img.shields.io/github/stars/mahmoodlab/PORPOISE) |
| [vqdang/hover_net](https://github.com/vqdang/hover_net) | 同步细胞核分割与分类 | ![Stars](https://img.shields.io/github/stars/vqdang/hover_net) |
| [slideflow/slideflow](https://github.com/slideflow/slideflow) | 数字病理学深度学习库 | ![Stars](https://img.shields.io/github/stars/slideflow/slideflow) |
| [PathAI/pathml](https://github.com/PathAI/pathml) | 端到端病理学机器学习工具包 | ![Stars](https://img.shields.io/github/stars/PathAI/pathml) |
| [prov-gigapath/prov-gigapath](https://github.com/prov-gigapath/prov-gigapath) | 微软/Providence 全切片病理基础模型 | ![Stars](https://img.shields.io/github/stars/prov-gigapath/prov-gigapath) |
| [PathologyFoundation/plip](https://github.com/PathologyFoundation/plip) | 病理学语言-图像预训练（病理 CLIP） | ![Stars](https://img.shields.io/github/stars/PathologyFoundation/plip) |
| [Xiyue-Wang/TransPath](https://github.com/Xiyue-Wang/TransPath) | CNN + Swin Transformer 计算病理学 | ![Stars](https://img.shields.io/github/stars/Xiyue-Wang/TransPath) |
| [owkin/HistoSSLscaling](https://github.com/owkin/HistoSSLscaling) | Phikon — 大规模自监督病理模型 | ![Stars](https://img.shields.io/github/stars/owkin/HistoSSLscaling) |
| [georg-wolflein/pathology-foundation-models](https://github.com/georg-wolflein/pathology-foundation-models) | 病理学基础模型目录与基准测试 | ![Stars](https://img.shields.io/github/stars/georg-wolflein/pathology-foundation-models) |
| [kaiko-ai/eva](https://github.com/kaiko-ai/eva) | 肿瘤学基础模型评估框架 | ![Stars](https://img.shields.io/github/stars/kaiko-ai/eva) |
| [SBU-BMI/wsinfer](https://github.com/SBU-BMI/wsinfer) | 全切片推理模型共享生态系统 | ![Stars](https://img.shields.io/github/stars/SBU-BMI/wsinfer) |
| [openslide/openslide](https://github.com/openslide/openslide) | 全切片图像格式读取器 — 病理 AI 基础设施 | ![Stars](https://img.shields.io/github/stars/openslide/openslide) |
| [omnideconv/immunedeconv](https://github.com/omnideconv/immunedeconv) | 免疫细胞反卷积方法统一接口 | ![Stars](https://img.shields.io/github/stars/omnideconv/immunedeconv) |
| [scverse/squidpy](https://github.com/scverse/squidpy) | 空间转录组学分析框架 | ![Stars](https://img.shields.io/github/stars/scverse/squidpy) |
| [BayraktarLab/cell2location](https://github.com/BayraktarLab/cell2location) | 基于转录组学的空间细胞类型定位 | ![Stars](https://img.shields.io/github/stars/BayraktarLab/cell2location) |

## 放射学与医学影像

面向 CT、MRI、PET-CT 等医学影像模态的 AI 工具。

| 项目 | 描述 | Stars |
|------|------|-------|
| [Project-MONAI/MONAI](https://github.com/Project-MONAI/MONAI) | NVIDIA + 伦敦国王学院。医学影像 PyTorch 框架 | ![Stars](https://img.shields.io/github/stars/Project-MONAI/MONAI) |
| [Project-MONAI/MONAILabel](https://github.com/Project-MONAI/MONAILabel) | AI 辅助交互式医学图像标注 | ![Stars](https://img.shields.io/github/stars/Project-MONAI/MONAILabel) |
| [MIC-DKFZ/nnUNet](https://github.com/MIC-DKFZ/nnUNet) | 德国癌症研究中心。自配置分割网络，多项比赛冠军 | ![Stars](https://img.shields.io/github/stars/MIC-DKFZ/nnUNet) |
| [MIC-DKFZ/nnDetection](https://github.com/MIC-DKFZ/nnDetection) | 自配置 3D 医学目标检测 | ![Stars](https://img.shields.io/github/stars/MIC-DKFZ/nnDetection) |
| [wasserth/TotalSegmentator](https://github.com/wasserth/TotalSegmentator) | CT 图像 100+ 结构自动分割 | ![Stars](https://img.shields.io/github/stars/wasserth/TotalSegmentator) |
| [bowang-lab/MedSAM](https://github.com/bowang-lab/MedSAM) | Segment Anything Model 医学图像适配版 | ![Stars](https://img.shields.io/github/stars/bowang-lab/MedSAM) |
| [bowang-lab/MedSAM2](https://github.com/bowang-lab/MedSAM2) | MedSAM 3D 体积与医学视频版 | ![Stars](https://img.shields.io/github/stars/bowang-lab/MedSAM2) |
| [mlcommons/GaNDLF](https://github.com/mlcommons/GaNDLF) | 通用细粒度深度学习医学影像框架 | ![Stars](https://img.shields.io/github/stars/mlcommons/GaNDLF) |
| [AIM-Harvard/pyradiomics](https://github.com/AIM-Harvard/pyradiomics) | 医学图像影像组学特征提取 | ![Stars](https://img.shields.io/github/stars/AIM-Harvard/pyradiomics) |
| [nyukat/breast_cancer_classifier](https://github.com/nyukat/breast_cancer_classifier) | 深度学习乳腺钼靶筛查分类器 | ![Stars](https://img.shields.io/github/stars/nyukat/breast_cancer_classifier) |
| [nyukat/GMIC](https://github.com/nyukat/GMIC) | 可解释乳腺钼靶全局感知多实例分类器 | ![Stars](https://img.shields.io/github/stars/nyukat/GMIC) |
| [raidionics/Raidionics](https://github.com/raidionics/Raidionics) | 术前脑肿瘤分割与标准化报告 | ![Stars](https://img.shields.io/github/stars/raidionics/Raidionics) |

## 放射治疗规划

| 项目 | 描述 | Stars |
|------|------|-------|
| [matRad](https://e0404.github.io/matRad/) | 开源 MATLAB 放射治疗计划（光子/质子/碳离子） | — |
| [OpenTPS](https://opentps.org/) | Python 质子治疗计划系统 | — |
| [SlicerRT](https://slicerrt.github.io/) | 3D Slicer 放射治疗工具包 | — |
| [dicompyler/dicompyler-core](https://github.com/dicompyler/dicompyler-core) | DICOM-RT 解析和 DVH 计算 Python 库 | ![Stars](https://img.shields.io/github/stars/dicompyler/dicompyler-core) |
| [didymo/OnkoDICOM](https://github.com/didymo/OnkoDICOM) | 开源放射肿瘤学 DICOM-RT 查看器 | ![Stars](https://img.shields.io/github/stars/didymo/OnkoDICOM) |

## 药物发现与重定位

面向抗癌药物发现、老药新用和药物敏感性预测的 AI 工具。

| 项目 | 描述 | Stars |
|------|------|-------|
| [deepchem/deepchem](https://github.com/deepchem/deepchem) | 分子机器学习 Python 库，用于药物发现 | ![Stars](https://img.shields.io/github/stars/deepchem/deepchem) |
| [mims-harvard/TDC](https://github.com/mims-harvard/TDC) | Therapeutics Data Commons — 药物发现 ML 基准测试 | ![Stars](https://img.shields.io/github/stars/mims-harvard/TDC) |
| [kexinhuang12345/DeepPurpose](https://github.com/kexinhuang12345/DeepPurpose) | 药物-靶点相互作用预测深度学习工具包 | ![Stars](https://img.shields.io/github/stars/kexinhuang12345/DeepPurpose) |
| [idekerlab/DrugCell](https://github.com/idekerlab/DrugCell) | 可解释神经网络预测药物响应 | ![Stars](https://img.shields.io/github/stars/idekerlab/DrugCell) |
| [kimmo1019/DeepCDR](https://github.com/kimmo1019/DeepCDR) | 癌症药物响应预测（清华大学） | ![Stars](https://img.shields.io/github/stars/kimmo1019/DeepCDR) |

**数据资源：**
- [GDSC](https://www.cancerrxgene.org/) — 癌症药物敏感性基因组学（1000+ 细胞系 x 数百种药物）
- [DepMap](https://depmap.org/) — Broad 癌症依赖图谱（发现每种癌症的脆弱靶点）
- [PRISM](https://depmap.org/repurposing/) — 大规模药物重定位筛选数据

## 单细胞与空间组学

用于肿瘤微环境表征的单细胞和空间转录组学分析工具。

| 项目 | 描述 | Stars |
|------|------|-------|
| [broadinstitute/infercnv](https://github.com/broadinstitute/infercnv) | 从单细胞 RNA-seq 推断拷贝数变异 | ![Stars](https://img.shields.io/github/stars/broadinstitute/infercnv) |
| [navinlabcode/copykat](https://github.com/navinlabcode/copykat) | 贝叶斯 CNV 分类，区分肿瘤与正常细胞 | ![Stars](https://img.shields.io/github/stars/navinlabcode/copykat) |
| [icbi-lab/infercnvpy](https://github.com/icbi-lab/infercnvpy) | scRNA-seq CNV 推断 Python 实现 | ![Stars](https://img.shields.io/github/stars/icbi-lab/infercnvpy) |
| [Teichlab/celltypist](https://github.com/Teichlab/celltypist) | 单细胞数据自动化细胞类型注释 | ![Stars](https://img.shields.io/github/stars/Teichlab/celltypist) |
| [scverse/scvi-tools](https://github.com/scverse/scvi-tools) | 单细胞组学深度生成模型 | ![Stars](https://img.shields.io/github/stars/scverse/scvi-tools) |
| [BorchLab/scRepertoire](https://github.com/BorchLab/scRepertoire) | 单细胞 TCR/BCR 库分析 | ![Stars](https://img.shields.io/github/stars/BorchLab/scRepertoire) |
| [immunomind/immunarch](https://github.com/immunomind/immunarch) | 免疫库分析框架（TCR/BCR 测序） | ![Stars](https://img.shields.io/github/stars/immunomind/immunarch) |
| [scverse/scirpy](https://github.com/scverse/scirpy) | 单细胞免疫库分析 Python 库 | ![Stars](https://img.shields.io/github/stars/scverse/scirpy) |
| [10xgenomics/cellranger](https://github.com/10xgenomics/cellranger) | 10x Genomics 单细胞分析流水线 | ![Stars](https://img.shields.io/github/stars/10xgenomics/cellranger) |
| [bowang-lab/scGPT](https://github.com/bowang-lab/scGPT) | 基于生成式预训练的单细胞基础模型 | ![Stars](https://img.shields.io/github/stars/bowang-lab/scGPT) |
| [BoevaLab/CancerFoundation](https://github.com/BoevaLab/CancerFoundation) | 专为癌症单细胞生物学打造的基础模型 | ![Stars](https://img.shields.io/github/stars/BoevaLab/CancerFoundation) |

## RNA 调控网络

| 资源 | 描述 |
|------|------|
| [miRBase](https://www.mirbase.org/) | miRNA 序列权威数据库 |
| [miRTarBase](https://mirtarbase.cuhk.edu.cn/) | 36 万+ 实验验证的 miRNA-靶基因互作 |
| [ENCORI/starBase](https://rnasysu.com/encori/) | 泛癌 RNA 互作平台（32 种癌症） |
| [LNCipedia](https://lncipedia.org/) | 人类 lncRNA 注释与功能数据库 |
| [NONCODE](https://www.noncode.org/) | 综合 lncRNA 数据库，含癌症关联 |

## 蛋白质组与代谢组

| 资源 | 描述 |
|------|------|
| [MaxQuant](https://maxquant.org/) | 定量蛋白质组学金标准软件 |
| [Perseus](https://maxquant.net/perseus/) | 蛋白质组学统计分析平台 |
| [CPTAC/蛋白质组数据共享](https://proteomic.datacommons.cancer.gov/) | NCI 癌症蛋白质组：1,000+ 肿瘤，10 种癌症 |
| [HMDB](https://www.hmdb.ca/) | 人类代谢组数据库：22 万代谢物 |
| [MetaboAnalyst](https://www.metaboanalyst.ca/) | 综合代谢组学分析网页平台 |

## 突变特征

用于提取和分析癌症基因组突变特征的工具。

### SigProfiler 套件（Alexandrov 实验室，UCSD）

| 项目 | 描述 | Stars |
|------|------|-------|
| [AlexandrovLab/SigProfilerExtractor](https://github.com/AlexandrovLab/SigProfilerExtractor) | 突变特征从头提取 | ![Stars](https://img.shields.io/github/stars/AlexandrovLab/SigProfilerExtractor) |
| [AlexandrovLab/SigProfilerAssignment](https://github.com/AlexandrovLab/SigProfilerAssignment) | 已知特征到样本的分配 | ![Stars](https://img.shields.io/github/stars/AlexandrovLab/SigProfilerAssignment) |
| [AlexandrovLab/SigProfilerMatrixGenerator](https://github.com/AlexandrovLab/SigProfilerMatrixGenerator) | 从 VCF 文件生成突变矩阵 | ![Stars](https://img.shields.io/github/stars/AlexandrovLab/SigProfilerMatrixGenerator) |
| [AlexandrovLab/SigProfilerPlotting](https://github.com/AlexandrovLab/SigProfilerPlotting) | 突变特征可视化 | ![Stars](https://img.shields.io/github/stars/AlexandrovLab/SigProfilerPlotting) |

### 其他特征工具

| 项目 | 描述 | Stars |
|------|------|-------|
| [ShixiangWang/sigminer](https://github.com/ShixiangWang/sigminer) | R 语言综合突变特征分析 | ![Stars](https://img.shields.io/github/stars/ShixiangWang/sigminer) |
| [raerose01/deconstructSigs](https://github.com/raerose01/deconstructSigs) | 确定单个肿瘤中的特征贡献 | ![Stars](https://img.shields.io/github/stars/raerose01/deconstructSigs) |
| [UMCUGenetics/MutationalPatterns](https://github.com/UMCUGenetics/MutationalPatterns) | R/Bioconductor 综合突变模式分析 | ![Stars](https://img.shields.io/github/stars/UMCUGenetics/MutationalPatterns) |
| [Nik-Zainal-Group/signature.tools.lib](https://github.com/Nik-Zainal-Group/signature.tools.lib) | Nik-Zainal 实验室特征分析工具 | ![Stars](https://img.shields.io/github/stars/Nik-Zainal-Group/signature.tools.lib) |
| [parklab/SigMA](https://github.com/parklab/SigMA) | 面向靶向 Panel 的特征多变量分析 | ![Stars](https://img.shields.io/github/stars/parklab/SigMA) |
| [mskcc/mutation-signatures](https://github.com/mskcc/mutation-signatures) | MSK 突变特征分析工具 | ![Stars](https://img.shields.io/github/stars/mskcc/mutation-signatures) |
| [morrislab/TrackSig](https://github.com/morrislab/TrackSig) | 追踪肿瘤演化中的特征活性变化 | ![Stars](https://img.shields.io/github/stars/morrislab/TrackSig) |

## 液体活检与 ctDNA

用于循环肿瘤 DNA 分析、微小残留病灶检测和片段组学的工具。

| 项目 | 描述 | Stars |
|------|------|-------|
| [broadinstitute/ichorCNA](https://github.com/broadinstitute/ichorCNA) | 从游离 DNA 低深度 WGS 估计肿瘤占比 | ![Stars](https://img.shields.io/github/stars/broadinstitute/ichorCNA) |
| [cancer-genomics/delfi3](https://github.com/cancer-genomics/delfi3) | DNA 片段化分析用于癌症检测 | ![Stars](https://img.shields.io/github/stars/cancer-genomics/delfi3) |
| [XWangLabTHU/cfDNApipe](https://github.com/XWangLabTHU/cfDNApipe) | 综合 cfDNA 分析流水线（清华大学） | ![Stars](https://img.shields.io/github/stars/XWangLabTHU/cfDNApipe) |
| [epifluidlab/FinaleToolkit](https://github.com/epifluidlab/FinaleToolkit) | 高速 DNA 片段化分析工具包 | ![Stars](https://img.shields.io/github/stars/epifluidlab/FinaleToolkit) |
| [alkodsi/ctDNAtools](https://github.com/alkodsi/ctDNAtools) | R 包，用于从 ctDNA 检测微小残留病灶 | ![Stars](https://img.shields.io/github/stars/alkodsi/ctDNAtools) |
| [OpenGene/ctdna-pipeline](https://github.com/OpenGene/ctdna-pipeline) | ctDNA 分析流水线 | ![Stars](https://img.shields.io/github/stars/OpenGene/ctdna-pipeline) |

## 生存预测与预后

用于癌症生存分析的统计和深度学习工具。

| 项目 | 描述 | Stars |
|------|------|-------|
| [CamDavidsonPilon/lifelines](https://github.com/CamDavidsonPilon/lifelines) | 纯 Python 生存分析 | ![Stars](https://img.shields.io/github/stars/CamDavidsonPilon/lifelines) |
| [sebp/scikit-survival](https://github.com/sebp/scikit-survival) | 兼容 Scikit-learn 的生存分析 | ![Stars](https://img.shields.io/github/stars/sebp/scikit-survival) |
| [havakv/pycox](https://github.com/havakv/pycox) | 基于 PyTorch 的深度学习生存分析 | ![Stars](https://img.shields.io/github/stars/havakv/pycox) |
| [jaredleekatzman/DeepSurv](https://github.com/jaredleekatzman/DeepSurv) | 深度 Cox 比例风险网络 | ![Stars](https://img.shields.io/github/stars/jaredleekatzman/DeepSurv) |
| [autonlab/auton-survival](https://github.com/autonlab/auton-survival) | CMU Auton Lab 生存分析工具包 | ![Stars](https://img.shields.io/github/stars/autonlab/auton-survival) |
| [mahmoodlab/PORPOISE](https://github.com/mahmoodlab/PORPOISE) | 多模态组织学-基因组生存预测 | ![Stars](https://img.shields.io/github/stars/mahmoodlab/PORPOISE) |
| [Novartis/torchsurv](https://github.com/Novartis/torchsurv) | 基于 PyTorch 的生存损失函数与评估指标 | ![Stars](https://img.shields.io/github/stars/Novartis/torchsurv) |

## 医学大语言模型与智能体

面向医学和肿瘤学的大语言模型与 AI 智能体。

| 项目 | 描述 | Stars |
|------|------|-------|
| [romeo111/OpenOnco](https://github.com/romeo111/OpenOnco) | 通过 MCP 工具向 AI 助手提供基于确定性规则、附有来源引用的肿瘤治疗方案草案和诊断摘要；项目处于早期阶段，须由临床医生审核 | ![Stars](https://img.shields.io/github/stars/romeo111/OpenOnco) |
| [shibing624/MedicalGPT](https://github.com/shibing624/MedicalGPT) | 训练你自己的医疗 GPT，提供完整训练流水线 | ![Stars](https://img.shields.io/github/stars/shibing624/MedicalGPT) |
| [SCIR-HI/Huatuo-Llama-Med-Chinese](https://github.com/SCIR-HI/Huatuo-Llama-Med-Chinese) | 基于 LLaMA 的中文医学大模型 | ![Stars](https://img.shields.io/github/stars/SCIR-HI/Huatuo-Llama-Med-Chinese) |
| [microsoft/BioGPT](https://github.com/microsoft/BioGPT) | 微软出品。面向生物医学文本的生成式预训练 Transformer | ![Stars](https://img.shields.io/github/stars/microsoft/BioGPT) |
| [epfLLM/meditron](https://github.com/epfLLM/meditron) | EPFL 出品。开源医学大语言模型 | ![Stars](https://img.shields.io/github/stars/epfLLM/meditron) |
| [dmis-lab/biobert](https://github.com/dmis-lab/biobert) | 在 PubMed/PMC 上预训练的生物医学 BERT | ![Stars](https://img.shields.io/github/stars/dmis-lab/biobert) |
| [FreedomIntelligence/HuatuoGPT](https://github.com/FreedomIntelligence/HuatuoGPT) | 华佗GPT — 中文医疗对话模型 | ![Stars](https://img.shields.io/github/stars/FreedomIntelligence/HuatuoGPT) |
| [chaoyi-wu/PMC-LLaMA](https://github.com/chaoyi-wu/PMC-LLaMA) | 基于 PubMed Central 文献微调的 LLaMA | ![Stars](https://img.shields.io/github/stars/chaoyi-wu/PMC-LLaMA) |
| [michael-wzhu/ChatMed](https://github.com/michael-wzhu/ChatMed) | 中文医疗对话大模型 | ![Stars](https://img.shields.io/github/stars/michael-wzhu/ChatMed) |
| [kbressem/medAlpaca](https://github.com/kbressem/medAlpaca) | 基于 Alpaca 的医学对话 AI | ![Stars](https://img.shields.io/github/stars/kbressem/medAlpaca) |
| [msk-mph/woollie](https://github.com/msk-mph/woollie) | MSK 肿瘤学大语言模型 | ![Stars](https://img.shields.io/github/stars/msk-mph/woollie) |
| [KatherLab/LLMAIx](https://github.com/KatherLab/LLMAIx) | 隐私保护型肿瘤学 NLP 框架 | ![Stars](https://img.shields.io/github/stars/KatherLab/LLMAIx) |
| [facebookresearch/esm](https://github.com/facebookresearch/esm) | Evolutionary Scale Modeling — 蛋白质语言模型 | ![Stars](https://img.shields.io/github/stars/facebookresearch/esm) |

## 肿瘤数据标准

用于互操作癌症数据交换的标准与平台。

| 项目 | 描述 | Stars |
|------|------|-------|
| [cBioPortal/cbioportal](https://github.com/cBioPortal/cbioportal) | MSK 出品。癌症基因组数据可视化与分析平台 | ![Stars](https://img.shields.io/github/stars/cBioPortal/cbioportal) |
| [HL7/fhir-mCODE-ig](https://github.com/HL7/fhir-mCODE-ig) | mCODE — 肿瘤学最小通用数据元素 FHIR 标准 | ![Stars](https://img.shields.io/github/stars/HL7/fhir-mCODE-ig) |
| [ga4gh/phenopacket-schema](https://github.com/ga4gh/phenopacket-schema) | GA4GH Phenopackets — 标准化患者表型交换 | ![Stars](https://img.shields.io/github/stars/ga4gh/phenopacket-schema) |
| [monarch-initiative/oncopacket](https://github.com/monarch-initiative/oncopacket) | 肿瘤学特化 Phenopacket 生成 | ![Stars](https://img.shields.io/github/stars/monarch-initiative/oncopacket) |
| [OHDSI/CommonDataModel](https://github.com/OHDSI/CommonDataModel) | OMOP 通用数据模型，用于观察性健康数据 | ![Stars](https://img.shields.io/github/stars/OHDSI/CommonDataModel) |
| [OHDSI/OncologyWG](https://github.com/OHDSI/OncologyWG) | OHDSI 肿瘤学工作组 — 癌症 OMOP 扩展 | ![Stars](https://img.shields.io/github/stars/OHDSI/OncologyWG) |
| [opencb/opencga](https://github.com/opencb/opencga) | 临床基因组学分析开放平台 | ![Stars](https://img.shields.io/github/stars/opencb/opencga) |

## 数据集与数据平台

| 平台 | 描述 | 类型 |
|------|------|------|
| [GDC Data Portal](https://portal.gdc.cancer.gov/) | NCI 基因组数据共享平台（TCGA、TARGET 等） | 基因组 |
| [TCGA](https://www.cancer.gov/tcga) | 癌症基因组图谱 — 覆盖 33 种癌症类型的多组学数据 | 多组学 |
| [TCIA](https://www.cancerimagingarchive.net/) | 癌症影像档案 — 开放获取的医学影像 | 影像 |
| [SEER](https://seer.cancer.gov/) | NCI 监测、流行病学和最终结果项目 | 流行病学 |
| [Reactome](https://reactome.org/) | 开源生物通路数据库 | 通路 |
| [osteosarc.com](https://osteosarc.com/) | Sid Sijbrandij 的 25 TB 骨肉瘤数据集 — N=1 数据共享 | N=1 |
| [AACR Project GENIE](https://www.aacr.org/professionals/research/aacr-project-genie/) | 27 万样本真实世界临床基因组数据 | 临床基因组 |
| [GLOBOCAN/GCO](https://gco.iarc.who.int/) | IARC 全球癌症发病率/死亡率/生存率（185 国） | 流行病学 |
| [CCLE/DepMap](https://depmap.org/portal/) | 癌细胞系百科 + 依赖性图谱：1,000+ 细胞系 | 细胞系 |
| [PCAWG](https://dcc.icgc.org/pcawg) | 2,658 个癌症全基因组（38 种肿瘤） | 全基因组 |
| [TARGET](https://www.cancer.gov/ccg/research/genome-sequencing/target/about) | NCI 儿童癌症基因组项目 | 儿童肿瘤 |
| [UCSC Xena](https://xenabrowser.net/) | 1,500+ 癌症数据集可视化浏览器 | 多组学 |
| [CellMiner](https://discover.nci.nih.gov/cellminer/) | NCI-60 细胞系探索器 | 细胞系 |
| [METABRIC](https://www.cbioportal.org/study?id=brca_metabric) | 2,000 例乳腺癌多组学数据 | 乳腺癌 |

## 知识库

| 数据库 | 描述 | 类型 |
|--------|------|------|
| [OncoKB](https://www.oncokb.org/) | MSK 精准肿瘤学知识库（变异可操作性分级） | 变异解读 |
| [CIViC](https://civicdb.org/) | 社区协作标注的癌症变异临床解读 | 变异解读 |
| [COSMIC](https://cancer.sanger.ac.uk/cosmic) | 癌症体细胞突变目录 | 突变 |
| [ClinVar](https://www.ncbi.nlm.nih.gov/clinvar/) | 基因组变异与临床意义数据库 | 变异 |
| [DrugBank](https://go.drugbank.com/) | 综合药物数据资源 | 药物 |
| [PharmGKB](https://www.pharmgkb.org/) | 药物基因组学知识库 | 药物基因组学 |
| [FAERS](https://open.fda.gov/data/faers/) | FDA 不良事件报告系统 | 药物安全 |
| [IEDB](https://www.iedb.org/) | 免疫表位数据库 | 免疫学 |

## 药物审批与靶点查询

| 资源 | 描述 | 类型 |
|------|------|------|
| [Drugs@FDA](https://www.accessdata.fda.gov/scripts/cder/daf/) | FDA 官方药品审批数据库，含标签和审评报告 | 监管 |
| [openFDA](https://open.fda.gov/) | FDA 开放 API：不良事件、药品标签、召回 | API |
| [DailyMed](https://dailymed.nlm.nih.gov/) | NLM 药品标签结构化数据库 | 药品标签 |
| [NCI 癌症药物词典](https://www.cancer.gov/publications/dictionaries/cancer-drug) | 癌症专用药物百科，含作用机制 | 癌症药物 |
| [My Cancer Genome](https://www.mycancergenome.org/) | Vanderbilt 出品。突变→已批准疗法映射，覆盖 957 种癌症 | 精准医学 |
| [Cancer Genome Interpreter](https://www.cancergenomeinterpreter.org/) | 上传变异，自动识别驱动突变并匹配药物 | 变异-药物 |
| [Genome Nexus](https://www.genomenexus.org/) | MSK 变异注释 API，聚合 12+ 数据源 | 变异注释 |
| [Cancer Hotspots](https://www.cancerhotspots.org/) | MSK 癌症热点突变数据库 | 热点突变 |
| [FDA 伴随诊断列表](https://www.fda.gov/medical-devices/in-vitro-diagnostics/list-cleared-or-approved-companion-diagnostic-devices-in-vitro-and-imaging-tools) | 生物标志物→伴随诊断→对应药物 | 诊断 |
| [Therapeutic Target Database](https://idrblab.org/ttd/) | 3,798 靶点 × 40,398 药物 | 靶点-药物 |
| [EMA 药品数据库](https://www.ema.europa.eu/en/medicines) | 欧洲药品审批及完整评估报告 | 监管 |
| [CPIC 药物基因组指南](https://cpicpgx.org/guidelines/) | 基于基因型的化疗剂量指南（如 DPYD/氟尿嘧啶） | 药物基因组 |
| [FDALabel](https://www.fda.gov/science-research/bioinformatics-tools/fdalabel-full-text-search-drug-product-labeling) | 15 万+ FDA 药品标签全文搜索 | 标签搜索 |

## 临床指南

| 资源 | 描述 | 地区 |
|------|------|------|
| [NCCN Guidelines](https://www.nccn.org/guidelines/) | 美国国家综合癌症网络指南 | 美国 |
| [ESMO Guidelines](https://www.esmo.org/guidelines) | 欧洲肿瘤内科学会指南 | 欧洲 |
| [CSCO Guidelines](https://www.csco.org.cn/) | 中国临床肿瘤学会指南 | 中国 |
| [ASCO 指南](https://www.asco.org/guidelines) | 美国临床肿瘤学会循证指南 | 美国 |
| [NICE 癌症路径](https://www.nice.org.uk/guidance/conditions-and-diseases/cancer) | 英国癌症治疗路径（含成本效益分析） | 英国 |
| [CACA 指南](http://www.caca.org.cn/) | 中国抗癌协会整合诊疗指南，覆盖 53 种癌症 | 中国 |

## 患者社区

| 资源 | 描述 |
|------|------|
| [osteosarc.com](https://osteosarc.com/) | Sid Sijbrandij 骨肉瘤开放数据项目 — N=1 数据共享典范 |
| [Even One Ventures](https://evenone.ventures/) | "患者优先"生物科技投资基金，由 Sid Sijbrandij 创立 |
| [Cancer.Net](https://www.cancer.net/) | ASCO 患者信息网站：癌症类型、治疗、应对指南 |
| [CancerCare](https://www.cancercare.org/) | 免费心理咨询、支持小组、财务援助 |
| [美国癌症协会](https://www.cancer.org/) | 24/7 热线、住宿、交通、财务指导 |
| [Macmillan Cancer Support](https://www.macmillan.org.uk/) | 英国最大癌症慈善机构 |
| [NCI 指定癌症中心](https://www.cancer.gov/research/infrastructure/cancer-centers/find) | 73 家美国顶级癌症中心目录 |
| [中国抗癌协会 (CACA)](http://www.caca.org.cn/) | 中国最大抗癌学术组织，患者科普与筛查 |

## 患者财务援助

| 资源 | 描述 |
|------|------|
| [NeedyMeds](https://www.needymeds.org/) | 患者援助计划、免费诊所数据库 |
| [RxAssist](https://www.rxassist.org/) | 按药品名搜索患者援助计划 |
| [PAN Foundation](https://www.panfoundation.org/) | 欠保癌症患者共付额援助 |
| [CancerCare 财务援助](https://www.cancercare.org/copayfoundation) | 癌症治疗专项共付额援助 |
| [Cancer Financial Assistance Coalition](https://www.cancerfac.org/) | 可搜索的癌症财务帮助组织数据库 |
| [GoodRx](https://www.goodrx.com/) | 美国 7 万+ 药房药品价格比较 |
| [中国医保药品目录 (NRDL)](https://www.nhsa.gov.cn/) | 中国国家医保局药品目录，年度更新 |

## 中国特色项目

以下项目由中国团队主导开发或与中国研究机构密切相关，在本列表各分类中均有收录，此处集中展示。

| 项目 | 分类 | 描述 |
|------|------|------|
| [shibing624/MedicalGPT](https://github.com/shibing624/MedicalGPT) | 医学大模型 | 训练你自己的医疗 GPT，提供完整训练流水线 |
| [SCIR-HI/Huatuo-Llama-Med-Chinese](https://github.com/SCIR-HI/Huatuo-Llama-Med-Chinese) | 医学大模型 | 华佗系列 — 基于 LLaMA 的中文医学大模型（哈工大 SCIR） |
| [FreedomIntelligence/HuatuoGPT](https://github.com/FreedomIntelligence/HuatuoGPT) | 医学大模型 | 华佗GPT — 中文医疗对话模型（香港中文大学深圳） |
| [chaoyi-wu/PMC-LLaMA](https://github.com/chaoyi-wu/PMC-LLaMA) | 医学大模型 | 基于 PubMed Central 文献微调的 LLaMA |
| [michael-wzhu/ChatMed](https://github.com/michael-wzhu/ChatMed) | 医学大模型 | 中文医疗对话大模型 |
| [XWangLabTHU/cfDNApipe](https://github.com/XWangLabTHU/cfDNApipe) | 液体活检 | 综合 cfDNA 分析流水线（清华大学） |
| [ShixiangWang/sigminer](https://github.com/ShixiangWang/sigminer) | 突变特征 | R 语言综合突变特征分析 |
| [xjtu-omics/msisensor-pro](https://github.com/xjtu-omics/msisensor-pro) | 基因组学 | 微卫星不稳定性检测（西安交通大学） |
| [kimmo1019/DeepCDR](https://github.com/kimmo1019/DeepCDR) | 药物发现 | 癌症药物响应预测（清华大学） |
| [PancrePal-xiaoyibao/chictr-mcp-server](https://github.com/PancrePal-xiaoyibao/chictr-mcp-server) | 临床试验 | 中国临床试验注册中心 MCP Server |
| [PancrePal-xiaoyibao/PancrePal](https://github.com/PancrePal-xiaoyibao) | 患者导航 | 小胰宝 — 胰腺癌患者 AI 助手 |
| [OpenMEDLab](https://github.com/OpenMEDLab) | 医学大模型 | 上海 AI 实验室医学多模态开源项目群 |
| [中国医保药品目录 (NRDL)](https://www.nhsa.gov.cn/) | 患者财务援助 | 中国国家医保局药品目录，年度更新 |

## 相关 Awesome 列表

| 项目 | 描述 |
|------|------|
| [cbailes/awesome-ai-cancer](https://github.com/cbailes/awesome-ai-cancer) | 癌症诊断与肿瘤学中的 AI |
| [medtorch/awesome-healthcare-ai](https://github.com/medtorch/awesome-healthcare-ai) | 开源医疗 AI 工具与数据集 |
| [broadinstitute/AwesomeGenomics](https://github.com/broadinstitute/AwesomeGenomics) | Broad 研究所基因组学工具 |
| [FreedomIntelligence/Awesome-Specialized-Medical-LLMs](https://github.com/FreedomIntelligence/Awesome-Specialized-Medical-LLMs) | 专科医学大模型合集 |
| [AgenticHealthAI/Awesome-AI-Agents-for-Healthcare](https://github.com/AgenticHealthAI/Awesome-AI-Agents-for-Healthcare) | 医疗 AI 智能体 — 论文与项目 |

---

## Contributing

欢迎贡献！请提交 PR 添加项目。格式：

```markdown
| [org/project](GitHub-URL) | 一句话描述 | ![Stars](https://img.shields.io/github/stars/org/project) |
```

提交前请确认：项目与癌症 + AI 直接相关，且为开源项目。

---

<div align="center">

由 [CancerDAO](https://github.com/CancerDAO) 维护

**好工具不应只被少数人知道。Star 本仓库，帮助更多人发现它们。**

</div>
