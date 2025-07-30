# GoodBench

A curated collection of high-quality AI benchmarks for evaluating machine learning models across various domains and tasks.

## Table of Contents

- [Vision-Language Benchmarks](#vision-language-benchmarks)
- [Industry-Specific Benchmarks](#industry-specific-benchmarks)
- [Language Understanding Benchmarks](#language-understanding-benchmarks)
- [Code Generation Benchmarks](#code-generation-benchmarks)
- [Agentic AI Benchmarks](#agentic-ai-benchmarks)
- [Image Generation Benchmarks](#image-generation-benchmarks)
- [Additional Resources](#additional-resources)

## Vision-Language Benchmarks

### 1. Saliency-Bench: A Comprehensive Benchmark for Evaluating Visual Explanations

The first comprehensive visual explanation benchmark from Emory University, covering 8 real-world tasks with human-annotated ground truth explanations.

- **Paper**: [arXiv:2310.08537](https://arxiv.org/abs/2310.08537)
- **Project**: [GitHub Repository](https://github.com/yifeizhangcs/XAIdataset.github.io)
- **Dataset**: [XAI Dataset](https://xaidataset.github.io/dataset/)

**Key Features:**
- Comprehensive dataset collection with 8 carefully constructed and annotated datasets
- Covers diverse tasks from gender classification and environment recognition to cancer diagnosis and behavior classification
- Includes both binary and multi-class classification problems
- Standardized evaluation pipeline for consistent assessment of saliency methods
- Extensive benchmarking of 6 mainstream saliency methods (GradCAM, RISE, etc.) across different architectures (ResNet-18, VGG-19, ViT)
- User-friendly Python evaluation toolkit for simplified research workflows

### 2. OCRBench v2: An Improved Benchmark for Evaluating Large Multimodal Models on Visual Text

An enhanced benchmark for evaluating large multimodal models on visual text localization and reasoning tasks.

- **Paper**: [arXiv:2501.00321](https://arxiv.org/pdf/2501.00321)
- **Leaderboard**: [OCRBench v2 Results](https://99franklin.github.io/ocrbench_v2/)
- **Code**: [MultimodalOCR Repository](https://github.com/Yuliang-Liu/MultimodalOCR)
- **Dataset**: [Hugging Face Dataset](https://huggingface.co/datasets/ling99/OCRBench_v2)

### 3. LMGame Bench

A modular evaluation framework from UCSD combining classic games to assess model perception, memory, and reasoning capabilities across different gaming scenarios.

- **Project**: [LMGame Organization](https://lmgame.org/#/blog/pokemon_red)
- **Announcement**: [Twitter/X Post](https://x.com/haoailab/status/1939777711502946544)

**Features:**
- Tests perception, memory, and reasoning through classic games
- Modular assessment framework
- Reveals distinct model performance patterns across different games

### 4. OCR-Reasoning Benchmark

A benchmark designed to unveil the true capabilities of Multimodal Large Language Models (MLLMs) in complex text-rich image reasoning tasks.

- **Paper**: [arXiv:2505.17163](https://arxiv.org/pdf/2505.17163)
- **Code**: [GitHub Repository](https://github.com/SCUT-DLVCLab/OCR-Reasoning)
- **Project**: [Homepage](https://ocr-reasoning.github.io/)

### 5. VSI-Bench: Visual-Spatial Intelligence Benchmark

A novel video-based benchmark testing spatial thinking abilities with over 5,000 question-answer pairs, evaluating how well multimodal models can "think in space" from sequential visual observations.

- **Paper**: [arXiv:2412.14171](https://arxiv.org/abs/2412.14171)
- **Dataset**: [Hugging Face](https://huggingface.co/datasets/nyu-visionx/VSI-Bench)

**Key Findings:**
- MLLMs exhibit competitive but subhuman visual-spatial intelligence
- Spatial reasoning remains the primary bottleneck for higher performance
- Generating cognitive maps during question-answering enhances spatial distance ability
- Traditional linguistic reasoning techniques (chain-of-thought, self-consistency) fail to improve performance

### 6. WildDoc: OCR Benchmark

A comprehensive OCR benchmark developed by ByteDance for evaluating document understanding capabilities in wild scenarios.

- **Code**: [GitHub Repository](https://github.com/bytedance/WildDoc)
- **Dataset**: [Hugging Face](https://huggingface.co/datasets/ByteDance/WildDoc)

### 7. ViewSpatial-Bench

A benchmark for evaluating spatial understanding capabilities in multimodal models from multiple viewpoints.

- **Paper**: [arXiv:2505.21500](https://arxiv.org/abs/2505.21500)
- **Homepage**: [Project Page](https://zju-real.github.io/ViewSpatial-Page)
- **Code**: [GitHub Repository](https://github.com/ZJU-REAL/ViewSpatial-Bench)

### 8. MME-Reasoning

A comprehensive benchmark from Fudan University, CUHK MMLab, and Shanghai AI Laboratory for evaluating reasoning capabilities in multimodal large language models, with clear categorization of logical reasoning types.

- **Paper**: [arXiv:2505.21327](https://arxiv.org/pdf/2505.21327)
- **Code**: [GitHub Repository](https://github.com/Alpha-Innovator/MME-Reasoning)
- **Dataset**: [Hugging Face](https://huggingface.co/datasets/U4R/MME-Reasoning)

**Focus Areas:**
- Clear logical reasoning type classification
- Distinguishes reasoning from perception and knowledge breadth
- Comprehensive evaluation of multimodal reasoning capabilities

## Industry-Specific Benchmarks

### 1. DrafterBench: Engineering Automation Assessment

The first benchmark for evaluating large language models on civil engineering drawing modification tasks, simulating real engineering commands to assess structured data understanding, tool usage, instruction following, and critical reasoning.

- **Paper**: [arXiv:2507.11527](https://arxiv.org/abs/2507.11527)
- **Code**: [GitHub Repository](https://github.com/Eason-Li-AIS/DrafterBench)
- **Dataset**: [Hugging Face](https://huggingface.co/datasets/Eason666/DrafterBench)

**Findings:**
- Current mainstream models show limited capability for real-world engineering tasks
- Comprehensive evaluation of engineering-specific AI capabilities

### 2. ChemTable: Chemical Table Understanding

The first comprehensive chemical table benchmark with over 1,300 real chemical tables for evaluating MLLM capabilities in chemical table recognition and understanding.

- **Dataset**: [Hugging Face](https://huggingface.co/datasets/ustc-zyt/ChemTable)
- **Code**: [GitHub Repository](https://github.com/lqzxt/ChemTable)

**Key Features:**
- Detailed annotations including cell polygons, logical layouts, and domain-specific labels
- Over 9,000 question-answer instances ranging from basic description to complex reasoning
- Embedded molecular graphics and specialized chemical content
- Reveals significant performance gaps between current MLLMs and human experts

### 3. CovDocker: Covalent Drug Design Benchmark

A comprehensive benchmark for covalent drug design with tasks, datasets, and solutions.

- **Paper**: [arXiv:2506.21085](https://arxiv.org/pdf/2506.21085v1)
- **Code**: [GitHub Repository](https://github.com/PoloWitty/CovDocker)
- **Dataset**: [Zenodo](https://doi.org/10.5281/zenodo.12805810)

### 4. MATP-BENCH: Multimodal Automatic Theorem Proving

A benchmark for evaluating multimodal large language models in geometric theorem proving tasks that combine images and text.

- **Paper**: [arXiv:2506.06034](https://arxiv.org/pdf/2506.06034)
- **Homepage**: [Project Page](https://matpbench.github.io/)

**Focus:**
- Tests ability to convert image-text information into formal theorems
- Evaluates complex logical reasoning and auxiliary line construction
- Identifies challenges in complete proof construction

### 5. SeePhys: Physics Understanding Benchmark

A comprehensive physics benchmark emphasizing graphic perception for understanding the physical world, covering classical and modern physics across all educational levels from middle school to doctoral qualifying exams.

- **Paper**: [arXiv:2505.19099](https://arxiv.org/pdf/2505.19099)
- **Code**: [GitHub Repository](https://github.com/SeePhys/seephys-project)
- **Competition**: [CodaBench](https://www.codabench.org/competitions/7925/)
- **Workshop**: [ICML 2025 AI4Math](https://sites.google.com/view/ai4mathworkshopicml2025/home)

### 6. PhyX: Physical Reasoning Benchmark

The first large-scale benchmark specifically designed for evaluating physical reasoning capabilities in multimodal large language models.

- **Paper**: [arXiv:2505.15929](https://arxiv.org/abs/2505.15929)
- **Homepage**: [Project Page](https://phyx-bench.github.io/)
- **Code**: [GitHub Repository](https://github.com/NastyMarcus/PhyX)
- **Dataset**: [Hugging Face](https://huggingface.co/datasets/Cloudriver/PhyX)

**Features:**
- 3,000 problems covering 6 physics disciplines (mechanics, electromagnetics, thermodynamics, optics, waves, modern physics)
- 25 subcategories and 6 reasoning types (spatial understanding, physical modeling, formula integration, predictive reasoning)
- Textbook-level images with realistic physical settings
- Reviewed by STEM graduate students

### 7. VCBench: Visual-Dependent Mathematical Reasoning

A comprehensive benchmark from Alibaba DAMO Academy for evaluating multimodal mathematical reasoning tasks with explicit visual dependencies, focused on elementary school mathematics (grades 1-6).

- **Paper**: [arXiv:2504.18589](http://arxiv.org/abs/2504.18589)
- **Dataset**: [Hugging Face](https://huggingface.co/datasets/cloudcatcher2/VCBench)
- **Code**: [GitHub Repository](https://github.com/alibaba-damo-academy/VCBench)
- **Homepage**: [Project Page](https://alibaba-damo-academy.github.io/VCBench/)

**Focus:**
- Problems requiring identification and integration of visual features
- Understanding relationships between different visual elements
- High visual dependency without complex mathematical reasoning

### 8. SPACE: Spatial Cognition Assessment

Apple's benchmark for testing large language models' spatial cognition abilities, providing comprehensive evaluation of spatial reasoning capabilities.

- **Paper**: [arXiv:2410.06468](https://arxiv.org/pdf/2410.06468)
- **Code**: [GitHub Repository](https://github.com/apple/ml-space-benchmark)

## Language Understanding Benchmarks

### 1. REST: Multi-Problem Stress Testing

A benchmark framework for evaluating Large Reasoning Models (LRMs) under multi-problem pressure, testing robustness when handling multiple reasoning problems simultaneously.

- **Paper**: [REST: Stress Testing Large Reasoning Models by Asking Multiple Problems at Once](https://arxiv.org/abs/2507.10541)

**Key Innovation:**
- Tests multi-task processing capabilities rather than single-problem evaluation
- Better simulates real-world multi-task processing demands
- Evaluates model robustness under cognitive load

### 2. MMLU-CF: Contamination-Free Multi-Task Language Understanding

A contamination-free multi-task language understanding benchmark ensuring fair and accurate evaluation of large language models through decontamination rules and closed-source test sets.

- **Paper**: [arXiv:2412.15194](https://arxiv.org/pdf/2412.15194)
- **Code**: [GitHub Repository](https://github.com/microsoft/MMLU-CF)
- **Dataset**: [Hugging Face](https://huggingface.co/datasets/microsoft/MMLU-CF)

**Features:**
- 20,000 questions across 14 disciplines
- Transparent validation set with closed-source test set
- Prevents data leakage for reliable evaluation

### 3. HistBench: Historical Research Capabilities

An AI evaluation benchmark focused on historical research capabilities, testing models' ability to understand and reason about historical information.

- **Paper**: [arXiv:2505.20246](http://arxiv.org/abs/2505.20246)
- **Code**: [GitHub Repository](https://github.com/CharlesQ9/HistAgent)

### 4. R-Bench: Multi-Disciplinary Complex Reasoning

A multi-disciplinary, multi-language high-quality complex reasoning evaluation benchmark supporting both language models and multimodal models.

- **Paper**: [arXiv:2505.02018](https://arxiv.org/pdf/2505.02018)
- **Dataset**: [Hugging Face](https://huggingface.co/datasets/R-Bench/R-Bench)
- **Homepage**: [Project Website](https://evalmodels.github.io/rbench/)

**Scope:**
- Multi-disciplinary reasoning evaluation
- Multi-language support
- Both text and multimodal model assessment

### 5. OlympicArena: Multi-Disciplinary Cognitive Reasoning

A challenging multi-disciplinary cognitive reasoning benchmark from Shanghai Jiao Tong University GAIR Lab, where even GPT-4o achieves only 34.01% overall accuracy.

- **Paper**: [arXiv:2406.12753](https://arxiv.org/pdf/2406.12753)
- **Homepage**: [Project Page](https://gair-nlp.github.io/OlympicArena/)
- **Code**: [GitHub Repository](https://github.com/GAIR-NLP/OlympicArena)
- **Dataset**: [Hugging Face](https://huggingface.co/datasets/GAIR/OlympicArena)

**Performance:**
- GPT-4o: 34.01% accuracy
- Other open-source models: <20% accuracy

### 6. TextGames: Text-Based Puzzle Game Reasoning

A benchmark using text-based reasoning games to systematically evaluate LLMs' logical reasoning capabilities, revealing significant limitations in complex tasks.

- **Paper**: [TextGames: Learning to Self-Play Text-Based Puzzle Games via Language Model Reasoning](https://arxiv.org/abs/2502.18431)
- **Code**: [GitHub Repository](https://github.com/fhudi/textgames)

**Identified Weaknesses:**
- Sequential reasoning challenges
- Counting difficulties
- Complex rule following limitations

### 7. ORQA: Operations Research Question Answering

A dataset for evaluating LLMs' generalization capabilities in operations research, focusing on understanding OR problems rather than just solving them.

- **Paper**: [arXiv:2412.17874](https://arxiv.org/pdf/2412.17874)
- **Code**: [GitHub Repository](https://github.com/nl4opt/ORQA)

### 8. DAIL-SQL: Text-to-SQL Benchmark

A comprehensive benchmark evaluation for text-to-SQL capabilities empowered by large language models.

- **Paper**: [arXiv:2308.15363](https://arxiv.org/pdf/2308.15363)
- **Code**: [GitHub Repository](https://github.com/BeachWang/DAIL-SQL)

### 9. LogicGame: Rule-Based Reasoning

A comprehensive benchmark for evaluating LLMs' capabilities in rule understanding, execution, and planning through game-based scenarios.

- **Paper**: [LogicGame: Benchmarking Rule-Based Reasoning Abilities of Large Language Models](https://arxiv.org/abs/2408.15778)
- **Dataset**: [GitHub Repository](https://github.com/Hypatiaalegra/LogicGame-Data)

## Code Generation Benchmarks

### 1. LiveCodeBench Pro: Competitive Programming Assessment

A highly challenging competitive programming benchmark from NYU, Princeton, and other institutions, featuring problems from top-tier programming competitions.

- **Paper**: [LiveCodeBench Pro: How Do Olympiad Medalists Judge LLMs in Competitive Programming?](https://arxiv.org/pdf/2506.11928)
- **Homepage**: [LiveCodeBench Pro](https://livecodebenchpro.com/)
- **Code**: [GitHub Repository](https://github.com/GavinZhengOI/LiveCodeBench-Pro)

**Features:**
- 584 high-quality problems from Codeforces, ICPC, and IOI competitions
- Problems updated continuously to reduce data contamination
- Evaluated by competitive programming medalists
- Updated through April 25, 2025

### 2. Aider LLM Leaderboards: Real-World Code Editing

A benchmark focusing on real-world coding workflows, testing models' ability to edit existing code, fix bugs, and add new features across multiple files.

**Key Characteristics:**
- **Real-world Workflow**: Unlike HumanEval, tests iterative code editing and debugging
- **System Evaluation**: Measures Aider + LLM combination performance
- **Multi-file Operations**: Tests complex, multi-file modifications
- **Based on Exercism**: Uses practical programming exercises as benchmarks

**Polyglot Benchmark Features:**
- **Languages**: C++, Go, Java, JavaScript, Python, Rust
- **Difficulty**: 225 most challenging exercises out of 697 available
- **Repository**: [GitHub](https://github.com/Aider-AI/polyglot-benchmark)

## Agentic AI Benchmarks

### 1. Scientists' First Exam (SFE)

A comprehensive benchmark from Shanghai AI Laboratory for systematically evaluating multimodal large language models' cognitive abilities across multiple scientific disciplines at high difficulty levels.

- **Paper**: [arXiv:2506.10521](https://arxiv.org/abs/2506.10521)
- **Dataset**: [Hugging Face](https://huggingface.co/datasets/PrismaX/SFE)
- **Evaluation Platform**: [OpenCompass](https://hub.opencompass.org.cn/dataset-detail/SFE)

### 2. BrowseComp: Web Browsing Competency

OpenAI's benchmark for evaluating AI agents' web browsing and interaction capabilities.

- **Homepage**: [OpenAI BrowseComp](https://openai.com/index/browsecomp/)

### 3. MLA-Trust: GUI Multimodal Agent Trustworthiness

The first trustworthy evaluation framework and benchmark for GUI multimodal large language model agents.

- **Paper**: [arXiv:2506.01616](https://arxiv.org/pdf/2506.01616)
- **Homepage**: [Project Page](https://mla-trust.github.io)
- **Code**: [GitHub Repository](https://github.com/thu-ml/MLA-Trust)

### 4. CRMArena-Pro: Business Scenario Assessment

A holistic assessment framework for LLM agents across diverse business scenarios and interactions.

- **Paper**: [CRMArena-Pro: Holistic Assessment of LLM Agents Across Diverse Business Scenarios and Interactions](https://huggingface.co/datasets/Salesforce/CRMArenaPro)
- **Dataset**: [Hugging Face](https://huggingface.co/datasets/Salesforce/CRMArenaPro)
- **Code**: [GitHub Repository](https://github.com/SalesforceAIResearch/CRMArena)

### 5. OmnixR: Omni-modality Language Model Reasoning

A benchmark for evaluating omni-modality language models on reasoning across different modalities.

*Note: Additional details and links to be added as they become available.*

## Image Generation Benchmarks

### 1. XVerseBench: Multi-Subject Control Image Generation

A comprehensive benchmark from ByteDance for evaluating multi-subject control in image generation, featuring a diverse dataset and multi-dimensional evaluation metrics.

- **Paper**: [arXiv:2506.21416](https://arxiv.org/abs/2506.21416)
- **Homepage**: [Project Page](https://bytedance.github.io/XVerse/)

**Dataset Features:**
- **Subjects**: 20 human identities, 74 unique objects, 45 animal species/individuals
- **Test Prompts**: 300 unique test scenarios

**Evaluation Metrics:**
- **DPG Score**: Evaluates model editing functionality
- **Face ID Similarity**: Assesses human identity preservation
- **DINOv2 Similarity**: Evaluates object feature maintenance
- **Aesthetic Score**: Measures generated image aesthetic quality

## Additional Resources

### Evaluation Platforms
- **CodaBench**: [https://www.codabench.org/](https://www.codabench.org/)
- **OpenCompass**: [https://opencompass.org.cn/large-model](https://opencompass.org.cn/large-model)

---

*This collection is continuously updated to include the latest benchmarks and evaluation frameworks in AI research. For contributions or suggestions, please refer to the repository's contribution guidelines.*