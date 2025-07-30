# GoodBench

This repository collects useful benchmarks for evaluating AI models. The list below groups them by domain and provides links to the corresponding papers, projects and datasets.

## Vision–Language

1. **Saliency-Bench: A Comprehensive Benchmark for Evaluating Visual Explanations**  
   Paper: <https://arxiv.org/abs/2310.08537>  
   Project: <https://github.com/yifeizhangcs/XAIdataset.github.io>  
   Data: <https://xaidataset.github.io/dataset/>  
   Features:
   - Covers eight datasets spanning tasks such as gender classification, environment recognition, cancer diagnosis and action recognition.
   - Provides a unified evaluation pipeline with reproducible metrics.
   - Includes benchmark results for ResNet-18, VGG-19 and ViT architectures.
   - Offers a user-friendly Python toolkit for data loading and evaluation.
   - Dataset publicly accessible via the project website.

2. **OCRBench v2: An Improved Benchmark for Evaluating Large Multimodal Models on Visual Text Localization and Reasoning**
   Paper: <https://arxiv.org/pdf/2501.00321>
   Leaderboard: <https://99franklin.github.io/ocrbench_v2/>
   Code: <https://github.com/Yuliang-Liu/MultimodalOCR>
   Data: <https://huggingface.co/datasets/ling99/OCRBench_v2>
   Features:
   - Focuses on text localization and reasoning tasks in complex documents.
   - Provides a public leaderboard for standardized comparison.
   - Dataset openly available on HuggingFace.

3. **Lmgame Bench**
   Developed by UCSD, this framework combines classic games to evaluate perception, memory and reasoning abilities.
   <https://lmgame.org/#/blog/pokemon_red>
   Features:
   - Uses classic game environments to probe agent capabilities.
   - Emphasizes perception, memory and strategic reasoning.
   - No standalone dataset; tasks derive from open-source game logs.

4. **OCR-Reasoning Benchmark**
   Paper: <https://arxiv.org/pdf/2505.17163>
   Code: <https://github.com/SCUT-DLVCLab/OCR-Reasoning>
   Project page: <https://ocr-reasoning.github.io/>
   Features:
   - Combines optical character recognition with downstream reasoning tasks.
   - Provides open-source implementations and datasets.
   - Data freely available through the project page.

5. **VSI-Bench**
   Evaluates a model's ability to reason about space from video sequences.
   Paper: <https://arxiv.org/abs/2412.14171>
   Data: <https://huggingface.co/datasets/nyu-visionx/VSI-Bench>
   Features:
   - Tests spatial reasoning from dynamic video input.
   - Provides annotated video sequences with spatial questions.
   - Dataset publicly hosted on HuggingFace.

6. **WildDoc**
   OCR benchmark by ByteDance.
   Code: <https://github.com/bytedance/WildDoc>
   Data: <https://huggingface.co/datasets/ByteDance/WildDoc>
   Features:
   - Targets challenging real-world document images.
   - Provides training and evaluation splits for OCR tasks.
   - Dataset freely accessible on HuggingFace.

7. **ViewSpatial-Bench**
   Paper: <https://arxiv.org/abs/2505.21500>
   Project: <https://zju-real.github.io/ViewSpatial-Page>
   GitHub: <https://github.com/ZJU-REAL/ViewSpatial-Bench>
   Features:
   - Tests viewpoint reasoning and spatial awareness.
   - Provides code for dataset generation and evaluation.
   - Dataset availability currently limited to project contributors.

8. **MME-Reasoning**
   Comprehensive evaluation of reasoning capabilities in multimodal models.
   Paper: <https://arxiv.org/pdf/2505.21327>
   Code: <https://github.com/Alpha-Innovator/MME-Reasoning>
   Data: <https://huggingface.co/datasets/U4R/MME-Reasoning>
   Features:
   - Covers visual and textual reasoning tasks with unified metrics.
   - Open-source evaluation toolkit with baseline results.
   - Dataset freely available on HuggingFace.

## Industry Benchmarks

1. **DrafterBench**
   First engineering automation benchmark for evaluating LLMs on civil engineering drawing modifications.
   Paper: <https://arxiv.org/abs/2507.11527>
   Code: <https://github.com/Eason-Li-AIS/DrafterBench>
   Data: <https://huggingface.co/datasets/Eason666/DrafterBench>
   Features:
   - Focuses on practical CAD editing scenarios.
   - Provides annotated drawing modification tasks.
   - Dataset openly available via HuggingFace.

2. **ChemTable**
   Large-scale benchmark containing over 1,300 real chemistry tables.
   Dataset: <https://huggingface.co/datasets/ustc-zyt/ChemTable>
   Code: <https://github.com/lqzxt/ChemTable>
   Features:
   - Focuses on chemical table understanding and extraction tasks.
   - Includes diverse layouts from published chemistry literature.
   - Dataset freely accessible on HuggingFace.

3. **CovDocker: Benchmarking Covalent Drug Design with Tasks, Datasets and Solutions**
   Paper: <https://arxiv.org/pdf/2506.21085v1>
   Project: <https://github.com/PoloWitty/CovDocker>
   Data: <https://doi.org/10.5281/zenodo.12805810>
   Features:
   - Provides docking tasks focused on covalent drug design.
   - Includes solution scripts for reproducible baselines.
   - Dataset downloadable via Zenodo.

4. **MATP-BENCH**
   A multimodal theorem proving benchmark for geometry problems.
   Paper: <https://arxiv.org/pdf/2506.06034>
   Project: <https://matpbench.github.io/>
   Features:
   - Poses geometry theorems requiring diagram understanding.
   - Includes automated theorem proving baselines.
   - Dataset availability pending through the project website.

5. **SeePhys**
   Multilevel physics benchmark covering problems from middle school to PhD.
   Competition: <https://www.codabench.org/competitions/7925/>
   Paper: <https://arxiv.org/pdf/2505.19099>
   Project: <https://github.com/SeePhys/seephys-project>
   Features:
   - Organized as an open competition with diverse physics tasks.
   - Includes problems ranging from conceptual questions to simulations.
   - Data and baselines publicly released on GitHub.

6. **PhyX (Physical Reasoning Benchmark)**
   Evaluates multimodal physical reasoning.
   Project: <https://phyx-bench.github.io/>
   Paper: <https://arxiv.org/abs/2505.15929>
   GitHub: <https://github.com/NastyMarcus/PhyX>
   Data: <https://huggingface.co/datasets/Cloudriver/PhyX>
   Features:
   - Contains physics scenarios requiring visual and textual reasoning.
   - Offers a reproducible evaluation pipeline with baseline agents.
   - Dataset openly available on HuggingFace.

7. **VCBench**
   Visual-dependent math reasoning benchmark aimed at elementary level problems.
   Paper: <http://arxiv.org/abs/2504.18589>
   Data: <https://huggingface.co/datasets/cloudcatcher2/VCBench>
   Code: <https://github.com/alibaba-damo-academy/VCBench>
   Website: <https://alibaba-damo-academy.github.io/VCBench/>
   Features:
   - Combines basic arithmetic questions with supporting images.
   - Provides standardized evaluation scripts and baseline scores.
   - Dataset publicly hosted on HuggingFace.

8. **ML Space Benchmark**
   Apple’s benchmark for spatial cognition.
   Paper: <https://arxiv.org/pdf/2410.06468>
   Project: <https://github.com/apple/ml-space-benchmark>
   Features:
   - Tests navigation and spatial reasoning abilities.
   - Includes simulator environments and evaluation tools.
   - Dataset availability not publicly disclosed.

9. **OmnixR**
   Evaluates reasoning across modalities.
   Features:
   - Focuses on integrating language, vision and audio understanding.
   - Dataset availability not specified.

10. **LogicGame**
    Benchmarks rule understanding and planning in large language models.
    Paper: <https://arxiv.org/abs/2408.15778>
    Data: <https://github.com/Hypatiaalegra/LogicGame-Data>
    Features:
    - Uses game-based tasks to assess logical planning skills.
    - Dataset publicly available on GitHub.

## Language

1. **REST: Stress Testing Large Reasoning Models by Asking Multiple Problems at Once**
   Paper: <https://arxiv.org/abs/2507.10541>
   Features:
   - Presents multiple problems in a single prompt to test model compositionality.
   - Focuses on robust reasoning under increased cognitive load.
   - Dataset availability not specified.

2. **MMLU-CF**
   Contamination-free evaluation with 20,000 questions across 14 subjects.
   Paper: <https://arxiv.org/pdf/2412.15194>
   Code: <https://github.com/microsoft/MMLU-CF>
   Data: <https://huggingface.co/datasets/microsoft/MMLU-CF>
   Features:
   - Designed to avoid training data contamination.
   - Covers undergraduate-level questions across many fields.
   - Dataset openly accessible on HuggingFace.

3. **HistBench**
   Focuses on historical research questions.
   Paper: <http://arxiv.org/abs/2505.20246>
   Code: <https://github.com/CharlesQ9/HistAgent>
   Features:
   - Includes diverse historical topics spanning multiple eras.
   - Provides evaluation scripts for open-domain question answering.
   - Dataset availability through GitHub.

4. **RBench**
   Multi-disciplinary, multilingual reasoning benchmark.
   Paper: <https://arxiv.org/pdf/2505.02018>
   Data: <https://huggingface.co/datasets/R-Bench/R-Bench>
   Website: <https://evalmodels.github.io/rbench/>
   Features:
   - Covers twelve subjects across multiple languages.
   - Provides standardized prompts for reasoning evaluation.
   - Dataset openly available on HuggingFace.

5. **OlympicArena**
   Multi-disciplinary cognitive reasoning benchmark from SJTU GAIR Lab.
   Paper: <https://arxiv.org/pdf/2406.12753>
   Project: <https://gair-nlp.github.io/OlympicArena/>
   Code: <https://github.com/GAIR-NLP/OlympicArena>
   Data: <https://huggingface.co/datasets/GAIR/OlympicArena>
   Features:
   - Contains tasks covering math, language, vision and strategy games.
   - Includes a leaderboard with evaluation scripts.
   - Dataset publicly available on HuggingFace.

6. **TextGames**
   Benchmarks logical reasoning through text-based games.
   Paper: <https://arxiv.org/abs/2502.18431>
   Code: <https://github.com/fhudi/textgames>
   Features:
   - Provides interactive environments for text adventure games.
   - Evaluates planning and memory through long-horizon tasks.
   - Dataset and game scripts available on GitHub.

7. **Operations Research Question Answering (ORQA)**
   Dataset: <https://github.com/nl4opt/ORQA>
   Paper: <https://arxiv.org/pdf/2412.17874>
   Features:
   - Focuses on operations research and optimization topics.
   - Provides question answering tasks with detailed solutions.
   - Dataset openly available on GitHub.

8. **DAIL-SQL**
   Text-to-SQL benchmark for large language models.
   Paper: <https://arxiv.org/pdf/2308.15363>
   Code: <https://github.com/BeachWang/DAIL-SQL>
   Features:
   - Provides complex database schemas for SQL generation tasks.
   - Includes evaluation scripts for logical form accuracy.
   - Dataset publicly hosted on GitHub.

Original link: <https://www.yuque.com/u21774036/qnmlr1/ilxxsoh26grbafe4>

## Code Benchmarks

1. **LiveCodeBench Pro**
   Challenging competitive programming benchmark containing 584 high-quality problems from Codeforces, ICPC and IOI events.
   Paper: <https://arxiv.org/pdf/2506.11928>
   Website: <https://livecodebenchpro.com/GitHub>
   Code: <https://github.com/GavinZhengOI/LiveCodeBench-Pro>
   Features:
   - Provides strict runtime and memory constraints similar to contests.
   - Includes a public leaderboard with test cases.
   - Dataset and evaluation harness available on GitHub.

2. **Aider LLM Leaderboards**
   Evaluates models in realistic workflows that involve editing existing code, debugging and feature additions.
   Uses Exercism problems covering C++, Go, Java, JavaScript, Python and Rust.
   <https://github.com/Aider-AI/polyglot-benchmark>
   Features:
   - Measures iterative code editing capabilities of LLMs.
   - Supports multiple programming languages and tooling setups.
   - Datasets and leaderboards hosted openly on GitHub.

## Agentic Benchmarks

1. **Scientists’ First Exam (SFE)**
   Evaluates MLLM capabilities in difficult scientific domains.
   Report: <https://arxiv.org/abs/2506.10521>
   Data: <https://huggingface.co/datasets/PrismaX/SFE>
   Features:
   - Includes tasks from physics, chemistry and biology articles.
   - Provides multimodal questions combining text and figures.
   - Dataset openly available on HuggingFace.

2. **BrowseComp**
   <https://openai.com/index/browsecomp/>
   Features:
   - Tasks require web navigation and information extraction.
   - Dataset not publicly released.

3. **MLA-Trust** – a trustworthy evaluation framework for GUI-based multimodal agents.
   Paper: <https://arxiv.org/pdf/2506.01616>
   Website: <https://mla-trust.github.io>
   Code: <https://github.com/thu-ml/MLA-Trust>
   Features:
   - Provides GUI tasks to evaluate agent reliability and safety.
   - Offers standardized scoring metrics and baselines.
   - Dataset availability unspecified.

4. **CRMArena-Pro**
   Holistic assessment of LLM agents in business scenarios.
   Data: <https://huggingface.co/datasets/Salesforce/CRMArenaPro>
   Code: <https://github.com/SalesforceAIResearch/CRMArena>
   Features:
   - Contains customer relationship management cases with multi-turn dialogues.
   - Provides evaluation scripts and baseline agent implementations.
   - Dataset freely accessible on HuggingFace.

## Generation Control

1. **XVerseBench**
   Benchmark for evaluating multi-agent control in image generation.
   Paper: <https://arxiv.org/abs/2506.21416>
   Website: <https://bytedance.github.io/XVerse/>
   Features:
   - Focuses on collaborative generation with multiple controllable agents.
   - Provides tasks for text-to-image refinement and scene composition.
   - Dataset availability not explicitly stated.

Additional resources
- <https://www.codabench.org/>
- <https://opencompass.org.cn/large-model>
