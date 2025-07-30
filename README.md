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

2. **OCRBench v2: An Improved Benchmark for Evaluating Large Multimodal Models on Visual Text Localization and Reasoning**  
   Paper: <https://arxiv.org/pdf/2501.00321>  
   Leaderboard: <https://99franklin.github.io/ocrbench_v2/>  
   Code: <https://github.com/Yuliang-Liu/MultimodalOCR>  
   Data: <https://huggingface.co/datasets/ling99/OCRBench_v2>

3. **Lmgame Bench**  
   Developed by UCSD, this framework combines classic games to evaluate perception, memory and reasoning abilities.  
   <https://lmgame.org/#/blog/pokemon_red>

4. **OCR-Reasoning Benchmark**  
   Paper: <https://arxiv.org/pdf/2505.17163>  
   Code: <https://github.com/SCUT-DLVCLab/OCR-Reasoning>  
   Project page: <https://ocr-reasoning.github.io/>

5. **VSI-Bench**  
   Evaluates a model's ability to reason about space from video sequences.  
   Paper: <https://arxiv.org/abs/2412.14171>  
   Data: <https://huggingface.co/datasets/nyu-visionx/VSI-Bench>

6. **WildDoc**  
   OCR benchmark by ByteDance.  
   Code: <https://github.com/bytedance/WildDoc>  
   Data: <https://huggingface.co/datasets/ByteDance/WildDoc>

7. **ViewSpatial-Bench**  
   Paper: <https://arxiv.org/abs/2505.21500>  
   Project: <https://zju-real.github.io/ViewSpatial-Page>  
   GitHub: <https://github.com/ZJU-REAL/ViewSpatial-Bench>

8. **MME-Reasoning**  
   Comprehensive evaluation of reasoning capabilities in multimodal models.  
   Paper: <https://arxiv.org/pdf/2505.21327>  
   Code: <https://github.com/Alpha-Innovator/MME-Reasoning>  
   Data: <https://huggingface.co/datasets/U4R/MME-Reasoning>

## Industry Benchmarks

1. **DrafterBench**  
   First engineering automation benchmark for evaluating LLMs on civil engineering drawing modifications.  
   Paper: <https://arxiv.org/abs/2507.11527>  
   Code: <https://github.com/Eason-Li-AIS/DrafterBench>  
   Data: <https://huggingface.co/datasets/Eason666/DrafterBench>

2. **ChemTable**  
   Large-scale benchmark containing over 1,300 real chemistry tables.  
   Dataset: <https://huggingface.co/datasets/ustc-zyt/ChemTable>  
   Code: <https://github.com/lqzxt/ChemTable>

3. **CovDocker: Benchmarking Covalent Drug Design with Tasks, Datasets and Solutions**  
   Paper: <https://arxiv.org/pdf/2506.21085v1>  
   Project: <https://github.com/PoloWitty/CovDocker>  
   Data: <https://doi.org/10.5281/zenodo.12805810>

4. **MATP-BENCH**  
   A multimodal theorem proving benchmark for geometry problems.  
   Paper: <https://arxiv.org/pdf/2506.06034>  
   Project: <https://matpbench.github.io/>

5. **SeePhys**  
   Multilevel physics benchmark covering problems from middle school to PhD.  
   Competition: <https://www.codabench.org/competitions/7925/>  
   Paper: <https://arxiv.org/pdf/2505.19099>  
   Project: <https://github.com/SeePhys/seephys-project>

6. **PhyX (Physical Reasoning Benchmark)**  
   Evaluates multimodal physical reasoning.  
   Project: <https://phyx-bench.github.io/>  
   Paper: <https://arxiv.org/abs/2505.15929>  
   GitHub: <https://github.com/NastyMarcus/PhyX>  
   Data: <https://huggingface.co/datasets/Cloudriver/PhyX>

7. **VCBench**  
   Visual-dependent math reasoning benchmark aimed at elementary level problems.  
   Paper: <http://arxiv.org/abs/2504.18589>  
   Data: <https://huggingface.co/datasets/cloudcatcher2/VCBench>  
   Code: <https://github.com/alibaba-damo-academy/VCBench>  
   Website: <https://alibaba-damo-academy.github.io/VCBench/>

8. **ML Space Benchmark**  
   Apple’s benchmark for spatial cognition.  
   Paper: <https://arxiv.org/pdf/2410.06468>  
   Project: <https://github.com/apple/ml-space-benchmark>

9. **OmnixR**  
   Evaluates reasoning across modalities.

10. **LogicGame**  
    Benchmarks rule understanding and planning in large language models.  
    Paper: <https://arxiv.org/abs/2408.15778>  
    Data: <https://github.com/Hypatiaalegra/LogicGame-Data>

## Language

1. **REST: Stress Testing Large Reasoning Models by Asking Multiple Problems at Once**  
   Paper: <https://arxiv.org/abs/2507.10541>

2. **MMLU-CF**  
   Contamination-free evaluation with 20,000 questions across 14 subjects.  
   Paper: <https://arxiv.org/pdf/2412.15194>  
   Code: <https://github.com/microsoft/MMLU-CF>  
   Data: <https://huggingface.co/datasets/microsoft/MMLU-CF>

3. **HistBench**  
   Focuses on historical research questions.  
   Paper: <http://arxiv.org/abs/2505.20246>  
   Code: <https://github.com/CharlesQ9/HistAgent>

4. **RBench**  
   Multi-disciplinary, multilingual reasoning benchmark.  
   Paper: <https://arxiv.org/pdf/2505.02018>  
   Data: <https://huggingface.co/datasets/R-Bench/R-Bench>  
   Website: <https://evalmodels.github.io/rbench/>

5. **OlympicArena**  
   Multi-disciplinary cognitive reasoning benchmark from SJTU GAIR Lab.  
   Paper: <https://arxiv.org/pdf/2406.12753>  
   Project: <https://gair-nlp.github.io/OlympicArena/>  
   Code: <https://github.com/GAIR-NLP/OlympicArena>  
   Data: <https://huggingface.co/datasets/GAIR/OlympicArena>

6. **TextGames**  
   Benchmarks logical reasoning through text-based games.  
   Paper: <https://arxiv.org/abs/2502.18431>  
   Code: <https://github.com/fhudi/textgames>

7. **Operations Research Question Answering (ORQA)**  
   Dataset: <https://github.com/nl4opt/ORQA>  
   Paper: <https://arxiv.org/pdf/2412.17874>

8. **DAIL-SQL**  
   Text-to-SQL benchmark for large language models.  
   Paper: <https://arxiv.org/pdf/2308.15363>  
   Code: <https://github.com/BeachWang/DAIL-SQL>

Original link: <https://www.yuque.com/u21774036/qnmlr1/ilxxsoh26grbafe4>

## Code Benchmarks

1. **LiveCodeBench Pro**  
   Challenging competitive programming benchmark containing 584 high-quality problems from Codeforces, ICPC and IOI events.  
   Paper: <https://arxiv.org/pdf/2506.11928>  
   Website: <https://livecodebenchpro.com/GitHub>  
   Code: <https://github.com/GavinZhengOI/LiveCodeBench-Pro>

2. **Aider LLM Leaderboards**  
   Evaluates models in realistic workflows that involve editing existing code, debugging and feature additions.  
   Uses Exercism problems covering C++, Go, Java, JavaScript, Python and Rust.  
   <https://github.com/Aider-AI/polyglot-benchmark>

## Agentic Benchmarks

1. **Scientists’ First Exam (SFE)**  
   Evaluates MLLM capabilities in difficult scientific domains.  
   Report: <https://arxiv.org/abs/2506.10521>  
   Data: <https://huggingface.co/datasets/PrismaX/SFE>

2. **BrowseComp**  
   <https://openai.com/index/browsecomp/>

3. **MLA-Trust** – a trustworthy evaluation framework for GUI-based multimodal agents.  
   Paper: <https://arxiv.org/pdf/2506.01616>  
   Website: <https://mla-trust.github.io>  
   Code: <https://github.com/thu-ml/MLA-Trust>

4. **CRMArena-Pro**  
   Holistic assessment of LLM agents in business scenarios.  
   Data: <https://huggingface.co/datasets/Salesforce/CRMArenaPro>  
   Code: <https://github.com/SalesforceAIResearch/CRMArena>

## Generation Control

1. **XVerseBench**  
   Benchmark for evaluating multi-agent control in image generation.  
   Paper: <https://arxiv.org/abs/2506.21416>  
   Website: <https://bytedance.github.io/XVerse/>

Additional resources
- <https://www.codabench.org/>
- <https://opencompass.org.cn/large-model>
