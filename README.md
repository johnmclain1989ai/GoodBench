# GoodBench
collection of some good benchmarks

Vision Language:
1. Saliency-Bench: A Comprehensive Benchmark for Evaluating Visual Explanations

埃默里大学团队推出首个覆盖8个真实任务、带有人类解释真值的视觉解释基准Saliency-Bench

论文链接: https://arxiv.org/abs/2310.08537
项目主页: 
https://github.com/yifeizhangcs/XAIdataset.github.io
数据主页：https://xaidataset.github.io/dataset/
特点：
* 全面的数据集集合：精心构建并标注了8个数据集，覆盖了从性别分类、环境识别到癌症诊断和行为分类等多种任务，并且包含了二分类和多分类问题。
* 标准化的评估流程：开发了一套统一的评估流水线，能够对不同显著性方法生成的视觉解释进行标准化处理，并使用统一的指标进行衡量，确保了实验的可复现性。
* 广泛的基准测试和分析：对6种主流的显著性方法（如GradCAM, RISE等）在不同模型架构（ResNet-18, VGG-19, ViT）上进行了大规模的基准测试，并提供了深入的性能分析。
* 用户友好的评估工具包：提供了一个易于使用的Python工具包，封装了数据加载、模型评估等功能，极大地简化了研究人员的评估过程。

2. 论文标题：OCRBench v2: An Improved Benchmark for Evaluating Large Multimodal Models on Visual Text Localization and Reasoning

论文地址：https://arxiv.org/pdf/2501.00321

榜单地址：https://99franklin.github.io/ocrbench_v2/

代码地址：https://github.com/Yuliang-Liu/MultimodalOCR

公开数据链接：https://huggingface.co/datasets/ling99/OCRBench_v2

3. Lmgame Bench
UCSD等推出Lmgame Bench标准框架，结合多款经典游戏，分模块测评模型的感知、记忆与推理表现。
结果显示，不同模型在各游戏中表现迥异，凸显游戏作为AI评估工具的独特价值。
https://lmgame.org/#/blog/pokemon_red
https://x.com/haoailab/status/1939777711502946544

4. ocr-reasoning
论文标题：OCR-Reasoning Benchmark: Unveiling the True Capabilities of MLLMs in Complex Text-Rich Image Reasoning
论文链接：https://arxiv.org/pdf/2505.17163
代码链接：https://github.com/SCUT-DLVCLab/OCR-Reasoning
项目主页：https://ocr-reasoning.github.io/

5. VSI-Bench
test ability to think in space
Humans possess the visual-spatial intelligence to remember spaces from sequential visual observations. However, can Multimodal Large Language Models (MLLMs) trained on million-scale video datasets also ``think in space'' from videos? We present a novel video-based visual-spatial intelligence benchmark (VSI-Bench) of over 5,000 question-answer pairs, and find that MLLMs exhibit competitive - though subhuman - visual-spatial intelligence. We probe models to express how they think in space both linguistically and visually and find that while spatial reasoning capabilities remain the primary bottleneck for MLLMs to reach higher benchmark performance, local world models and spatial awareness do emerge within these models. Notably, prevailing linguistic reasoning techniques (e.g., chain-of-thought, self-consistency, tree-of-thoughts) fail to improve performance, whereas explicitly generating cognitive maps during question-answering enhances MLLMs' spatial distance ability.

https://huggingface.co/datasets/nyu-visionx/VSI-Bench

https://arxiv.org/abs/2412.14171

6. WildDoc
字节跳动提出的，ocr bench
https://github.com/bytedance/WildDoc

https://huggingface.co/datasets/ByteDance/WildDoc

7.  ViewSpatial-Bench
论文链接：
https://arxiv.org/abs/2505.21500
项目主页：
https://zju-real.github.io/ViewSpatial-Page
GitHub仓库：
https://github.com/ZJU-REAL/ViewSpatial-Bench


8. MME-reasoning
多模态大语言模型 (MLLMs) 的关键能力。随着DeepSeek-R1等具备强大推理能力的LLM的出现，研究人员开始探索如何将推理能力引入多模态大模型(MLLMs)。

然而，现有的benchmark大多缺乏对逻辑推理类型的明确分类，以及对逻辑推理的理解不够清晰，常将感知能力或知识广度与推理能力混淆。

在此背景下，复旦大学及香港中文大学MMLab联合上海人工智能实验室等多家单位，提出了MME-Reasoning，旨在全面的评估多模态大模型的推理能力。

论文链接：https://arxiv.org/pdf/2505.21327
代码链接：https://github.com/Alpha-Innovator/MME-Reasoning
数据集链接：https://huggingface.co/datasets/U4R/MME-Reasoning




行业测试集：
1. DrafterBench
首个工程自动化任务评估基准DrafterBench，可用于测试大语言模型在土木工程图纸修改任务中的表现。通过模拟真实工程命令，全面考察模型的结构化数据理解、工具调用、指令跟随和批判性推理能力，研究结果发现当前主流大模型虽有一定能力，但整体水平仍不足以满足工程一线需求。

论文链接：https://arxiv.org/abs/2507.11527
代码链接：https://github.com/Eason-Li-AIS/DrafterBench
数据链接：https://huggingface.co/datasets/Eason666/DrafterBench


2. ChemTable

https://huggingface.co/datasets/ustc-zyt/ChemTable

https://github.com/lqzxt/ChemTable
1️⃣ 首个化学表格综合基准ChemTable：构建并发布了一个包含超过1300个真实化学表格的大规模基准，专门用于评估MLLM在化学表格识别和理解方面的综合能力。

2️⃣ 深度多模态与领域特定设计：ChemTable的标注极其详尽，包含了单元格多边形、逻辑布局、领域特定标签（试剂、催化剂、产率等）和嵌入的分子图形，并设计了从基础描述到复杂推理的超过9000个问答实例。
3️⃣ 系统性揭示当前MLLM的局限性：通过对一系列主流开源和闭源MLLM的评估，论文清晰地揭示了它们在处理化学表格时的显著性能差距——不仅与人类专家相比存在巨大鸿沟，开源与闭源模型之间也差异明显。


3. CovDocker: Benchmarking Covalent Drug Design with Tasks, Datasets, and Solutions

📎论文链接：arxiv.org/pdf/2506.21085v1
🧠项目地址：github.com/PoloWitty/CovDocker
📦数据集：doi.org/10.5281/zenodo.12805810

4.  MATP-BENCH
一个新推出的多模态自动定理证明基准，旨在评估多模态大模型（MLLMs）在处理包含图像和文本的几何定理证明中的能力。实验表明，尽管模型在将图文信息转化为形式化定理方面有一定能力，但在构建完整证明时面临重大挑战，尤其是复杂逻辑推理和辅助线构造方面。

论文地址：https://arxiv.org/pdf/2506.06034

项目主页：https://matpbench.github.io/

5. 新基准名为SeePhys，强调了图形感知对于模型认识和理解物理世界的重要性。

内容涵盖经典与现代物理的各个知识等级和领域，包括从初中到博士资格考试的全谱系多模态物理问题。

参赛链接：https://www.codabench.org/competitions/7925/
挑战赛详细信息：https://sites.google.com/view/ai4mathworkshopicml2025/challenge
ICML workshop 主页：https://sites.google.com/view/ai4mathworkshopicml2025/home

论文：https://arxiv.org/pdf/2505.19099
项目主页：https://github.com/SeePhys/seephys-project

6. PhyX（Physical Reasoning Benchmark）
物理基准，多模态

研究人员构建了PhyX（Physical Reasoning Benchmark），首个专门面向多模态大模型物理推理能力的大规模基准测试。

PhyX包含3000道题目，涵盖6大物理学科（力学、电磁、热学、光学、波动、现代物理），25个细分子类与6类推理方式（如空间理解、物理建模、公式联立、预测性推理等），每道题目都结合教材级图像与真实物理设定，并由STEM专业研究生精心审核。

Project Page: https://phyx-bench.github.io/

Arxiv: https://arxiv.org/abs/2505.15929

Github: https://github.com/NastyMarcus/PhyX

Huggingface Dataset: https://huggingface.co/datasets/Cloudriver/PhyX

7. VCBench

上述结论来自达摩院推出的新基准VCBench——这是一个专为评估具备显式视觉依赖性的多模态数学推理任务而设计的综合基准。

该基准主要面向小学 1-6 年级的数学问题，即并不涉及复杂的数学或几何推理，但高度依赖于显式的视觉依赖性的问题。

解决这种问题，需要模型识别和整合图像中的视觉特征，并理解不同视觉元素之间的关系。

论文链接：http://arxiv.org/abs/2504.18589
数据仓库：https://huggingface.co/datasets/cloudcatcher2/VCBench
代码：https://github.com/alibaba-damo-academy/VCBench
网页：https://alibaba-damo-academy.github.io/VCBench/

8. ml space
苹果推出大模型“空间认知能力”测试基准：SPACE，又给火热的大模型市场浇了盆冷水
paper: https://arxiv.org/pdf/2410.06468
https://github.com/apple/ml-space-benchmark

9. OmnixR: Evaluating Omni-modality Language Models on Reasoning across Modalities

10. LogicGame，旨在全面评估 LLM 在规则理解、执行和规划方面的能力。先看评测结果：

LogicGame: Benchmarking Rule-Based Reasoning Abilities of Large Language Models

论文链接：
https://arxiv.org/abs/2408.15778

https://github.com/Hypatiaalegra/LogicGame-Data


Language:

1. 多任务基准：
论文提出了一个名为REST的新基准框架，用于评估大型推理模型（LRMs）在多问题压力下的鲁棒性。与传统的单问题评估不同，REST通过在单个提示中呈现多个推理问题来测试模型，更好地模拟了真实世界的多任务处理需求。
论文标题：REST: Stress Testing Large Reasoning Models by Asking Multiple Problems at Once 
论文链接：https://arxiv.org/abs/2507.10541

2. MMLU-CF是一个无污染的多任务语言理解基准测试，旨在更公平、准确地评估大语言模型的能力。通过去污染规则和闭源测试集防止数据泄露，确保评估结果可靠。该基准包含20,000道题目，涵盖14个学科，验证集公开透明，测试集闭源防泄露

论文链接：https://arxiv.org/pdf/2412.15194
代码链接：https://github.com/microsoft/MMLU-CF
数据连接：https://huggingface.co/datasets/microsoft/MMLU-CF


3. 聚焦历史研究能力的AI评测基准——HistBench

论文地址：http://arxiv.org/abs/2505.20246
代码链接: https://github.com/CharlesQ9/HistAgent


4.  Reasoning Bench(RBench)[1], 

一个多学科、多语言的高质量复杂推理评估基准和数据集，兼顾语言模型与多模态模型的评估需求，旨在系统性地衡量大模型的推理能力，并推动其持续演进与优化。

目前，该项目中所有使用的数据已经在huggingface 上开源，地址为：

https://huggingface.co/datasets/R-Bench/R-Bench

关于项目的更多信息，请访问项目官网：

https://evalmodels.github.io/rbench/

论文链接：

https://arxiv.org/pdf/2505.02018

5. OlympicArena

上海交通大学生成式人工智能实验室 (GAIR Lab) 的研究团队推出多学科认知推理基准OlympicArena，即使是GPT-4o 也只达到了 34.01% 的整体准确率，而其他开源模型的整体准确率也难以达到20%。

论文地址： https://arxiv.org/pdf/2406.12753

项目地址： https://gair-nlp.github.io/OlympicArena/

代码地址： https://github.com/GAIR-NLP/OlympicArena

数据地址：https://huggingface.co/datasets/GAIR/OlympicArena

6. 
来自研究团队的一项最新研究引入了一个全新的TEXTGAMES基准，该基准通过文本推理游戏来系统评估LLMs的逻辑推理能力。研究发现，即便是最先进的大模型，在某些复杂任务上依然存在显著短板，尤其是在序列推理、计数、复杂规则遵循等方面表现不佳。

论文标题：TextGames: Learning to Self-Play Text-Based Puzzle Games via Language Model Reasoning

论文链接：https://arxiv.org/abs/2502.18431    

https://github.com/fhudi/textgames

7. Operations Research Question Answering（ORQA）

数据集(https://arxiv.org/pdf/2412.17874，测试数据地址：https://github.com/nl4opt/ORQA)，

用于评估LLMs在运筹学领域的泛化能力，重点在于对OR问题的“理解”上。


8. 阿里 DAIL-SQL：

大型语言模型支持的文本到 SQL：基准评估

论文地址：https://arxiv.org/pdf/2308.15363

Text-to-SQL Empowered by Large Language Models: A Benchmark Evaluation

代码地址：https://github.com/BeachWang/DAIL-SQL

原文链接：https://www.yuque.com/u21774036/qnmlr1/ilxxsoh26grbafe4
---

Code:

1. LiveCodeBench Pro

来自纽约大学、普林斯顿大学等 8 家机构的研究者提出了 LiveCodeBench Pro，这是一个极具挑战性的竞技编程基准测试。
值得一提的是，这项研究有多位参加过国际算法竞赛。例如，作者之一、纽约大学本科生 Zihan Zheng 曾代表学校参加 ICPC 世界总决赛。
LiveCodeBench Pro 收录了 584 道截至 2025 年 4 月 25 日的高质量题目，这些题目均来自 Codeforces 、ICPC 系列赛和 IOI 系列赛等顶级赛事。并且这些问题会不断更新以降低可能的数据污染。
论文标题：LiveCodeBench Pro: How Do Olympiad Medalists Judge LLMs in Competitive Programming? 
论文地址：https://arxiv.org/pdf/2506.11928
项目主页：https://livecodebenchpro.com/GitHub
https://github.com/GavinZhengOI/LiveCodeBench-Pro

2. Aider LLM Leaderboards 的核心特点】

注重真实世界的工作流 (Real-world Workflow)与 HumanEval 等评测基准不同（那些通常只测试模型能否一次性生成正确的函数代码），Aider 排行榜模拟的是一个更真实的开发流程。
它测试的是模型编辑现有代码、修复 Bug 和根据需求添加新功能的能力，这通常涉及多个文件的修改和反复调试

评测的是“系统”而非“纯模型”

这个排行榜衡量的不仅仅是 LLM 本身，而是 Aider + LLM 这个组合系统的整体表现。
Aider 的提示工程（Prompt Engineering）、上下文管理能力以及与模型的交互方式，都会直接影响最终结果。因此，它衡量的是模型在特定工具辅助下的实用效能

基于实际编程挑战

Aider 排行榜使用了来自 Exercism 平台的编程练习作为评测基准。这些练习通常包含一个问题描述文件（README.md）、一些起始代码和一套单元测试
模型的任务就是理解需求，然后修改代码，直到所有的单元测试都能成功通过

The polyglot benchmark
Like aider’s original code editing benchmark, the new polyglot benchmark is based on Exercism coding exercises.

The new polyglot benchmark:

Contains coding problems in C++, Go, Java, JavaScript, Python and Rust. The old benchmark was solely based on Python exercises.
Focuses on the most difficult 225 exercises out of the 697 that Exercism provides for those languages. The old benchmark simply included all 133 Python exercises, regardless of difficulty.

https://github.com/Aider-AI/polyglot-benchmark

3. 

Agentic：
1. Scientists’ First Exam

上海人工智能实验室 AI4S 团队推出了 Scientists’ First Exam（以下简称 SFE）—— 系统评估多模态大模型（MLLMs）多学科、高难度的科学专业领域认知能力的评测基准。
SFE 
技术报告链接: https://arxiv.org/abs/2506.10521SFE 
数据集链接：https://huggingface.co/datasets/PrismaX/SFESFE 
评测基准已上架到司南评测集社区，欢迎访问：https://hub.opencompass.org.cn/dataset-detail/SFE

https://huggingface.co/datasets/PrismaX/SFE/tree/main

2. browsecomp
 https://openai.com/index/browsecomp/

3. 首个GUI多模态大模型智能体可信评测框架+基准：MLA-Trust
📄 论文：https://arxiv.org/pdf/2506.01616

🌐 项目主页：https://mla-trust.github.io

💻 代码仓库：https://github.com/thu-ml/MLA-Trust

4. CRMArena-Pro
CRMArena-Pro: Holistic Assessment of LLM Agents Across Diverse Business Scenarios and Interactions

https://huggingface.co/datasets/Salesforce/CRMArenaPro

https://github.com/SalesforceAIResearch/CRMArena

GC:
1. XVerseBench基准测试
为了全面评估多主体控制图像生成能力，字节提出了XVerseBench基准测试。该测试的数据集主题丰富多样，包含20种不同的人类身份、74种独特的物品，以及45种不同的动物物种或个体，共设有300个独特的测试提示。不仅如此，XVerseBench还采用多维评估指标：DPG评分：评估模型的编辑功能；Face ID相似度：评估模型维护人类身份的能力；DINOv2相似度：评估模型保持对象特征的能力；美学评分：评估生成图像的美学质量。
论文地址：https://arxiv.org/abs/2506.21416
参考链接：https://bytedance.github.io/XVerse/



https://www.codabench.org/

https://opencompass.org.cn/large-model
