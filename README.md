# 🚀 AI Researcher Ecosystem: Empowering Scientific Discovery with AI

[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://github.com/[YOUR_USERNAME]/[YOUR_REPO_NAME]/pulls) <!-- Replace placeholders -->
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Last Updated](https://img.shields.io/github/last-commit/[YOUR_USERNAME]/[YOUR_REPO_NAME]?label=Updated&logo=github)](https://github.com/[YOUR_USERNAME]/[YOUR_REPO_NAME]/commits/main) <!-- Replace placeholders -->
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](CONTRIBUTING.md) <!-- Link removed or points to CONTRIBUTING.md -->
[![Contribution Welcome](https://img.shields.io/badge/Contributions-welcome-blue)](CONTRIBUTING.md)

**Dive into the rapidly evolving world of AI-powered research automation!** 💡 This curated repository is your compass to navigate the cutting-edge tools, frameworks, and methodologies that are revolutionizing scientific discovery. We track the latest advancements, focusing on resources that empower researchers and accelerate breakthroughs.

<!-- omit in toc -->
# 👀 Introduction

AI is transforming the scientific landscape, offering powerful tools to assist researchers throughout the entire research lifecycle. This repository provides a structured overview of the AI researcher ecosystem, focusing on key components and advancements.

<p align="center">
  <img src="https://github.com/zhu-minjun/Researcher/blob/main/img/ai-research.png" alt="AI Research Automation Landscape" width="800">
  <!-- Consider replacing placeholder image -->
</p>

We categorize resources 📚 based on the core stages of research automation impacted by AI, drawing heavily from the surveyed literature. For the papers compiled, we provide links to the paper itself 📄, associated code 💻, and available reviews 📝. Crucially, for some publications lacking open reviews, we've utilized our [**DeepReviewer**](https://ai-researcher.net/DeepReviewer) to generate AI-powered review analyses 🤖, also including links to these results. We welcome everyone to use our [**AI-Researcher.net**](https://ai-researcher.net), including **DeepReviewer**, **CycleResearcher**, **AutoSurvey**, and others! ✨

<!-- omit in toc -->
# 📌 Table of Contents

- [⚙️ Core Components](#️-core-components)
    - [Research Automation Stack](#research-automation-stack)
    - [Emerging Capabilities](#emerging-capabilities)
- [📰 Latest Buzz / News](#-latest-buzz--news)
- [🔥 Featured Projects](#-featured-projects)
    - [Open Source Tools](#open-source-tools)
    - [Commercial Platforms](#commercial-platforms)
- [📚 Knowledge Building](#-knowledge-building)
    - [Knowledge Acquisition](#knowledge-acquisition)
        - [Main Acquisition & Recommendation](#main-acquisition--recommendation)
        - [Figure Understanding](#figure-understanding)
        - [Table Understanding](#table-understanding)
    - [Knowledge Utilization](#knowledge-utilization)
- [💡 Idea Generation](#-idea-generation)
    - [Generation](#generation)
    - [Evaluation](#evaluation)
- [🔬 Experiment Execution](#-experiment-execution)
    - [Experiment Design](#experiment-design)
    - [Experiment Conduction](#experiment-conduction)
    - [Internal Evaluation](#internal-evaluation-1)
- [📝 Paper Writing](#-paper-writing)
    - [Main Writing & Summarization](#main-writing--summarization)
    - [Figure Generation](#figure-generation)
    - [Table Generation](#table-generation)
    - [Slides & Poster Generation](#slides--poster-generation)
- [✅ Paper Review](#-paper-review)
- [🏆 Benchmarks](#-benchmarks)
- [🌐 Community](#-community)
    - [📅 Upcoming Events](#upcoming-events)
    - [💬 Discussion Forums](#discussion-forums)
- [👋 Contributing](#-contributing)
- [📜 License](#-license)

# ⚙️ Core Components

<!-- omit in toc -->
## Research Automation Stack

The fundamental layers where AI is impacting the research lifecycle:

| Layer                 | Key Papers Category Alignment | Example Technologies / Concepts                                                                      | Description                                                                                                                                  |
| :-------------------- | :---------------------------- | :--------------------------------------------------------------------------------------------------- | :------------------------------------------------------------------------------------------------------------------------------------------- |
| **Knowledge Building** | Knowledge Building            | [Elicit](https://elicit.org), [Consensus](https://consensus.app), SciSpace, Semantic Scholar, KG Tools | AI tools for literature discovery, summarization, knowledge graph construction, understanding figures/tables, and synthesizing existing work. |
| **Idea Generation**   | Idea Generation               | Hypothesis generators (e.g., based on KGs, LLMs), Agent-based exploration (e.g., [ResearchAgent](https://github.com/JinheonBaek/ResearchAgent)) | AI assisting in formulating novel research questions, hypotheses, identifying gaps, and exploring new research directions.                 |
| **Experimentation**   | Experiment Execution          | Autonomous Labs (e.g., [CoScientist](https://github.com/gomesgroup/coscientist)), [AlphaFold](https://alphafold.ebi.ac.uk), AutoML, Agent-driven simulation | AI aiding in experimental design, automating experiment execution (physical or simulated), data collection, analysis, and interpretation. |
| **Paper Writing**     | Paper Writing                 | [Overleaf AI](https://www.overleaf.com), [PaperRobot](https://github.com/EagleW/PaperRobot), [CycleResearcher](https://github.com/zhu-minjun/Researcher),Citation/Figure generators | AI assistance in drafting sections (abstract, related work), generating figures/tables, citation management, editing, and formatting.     |
| **Paper Review**       | Paper Review                   | Reviewer assignment tools, Argument mining, Review generation aids (e.g., [ReviewRobot](https://github.com/EagleW/ReviewRobot), [CycleResearcher](https://github.com/zhu-minjun/Researcher))            | AI tools supporting reviewer assignment, review quality assessment, argument extraction, and potentially review generation/summarization.      |

<!-- omit in toc -->
## Emerging Capabilities

Exciting frontiers pushing the boundaries of AI in research:

-   **End-to-End Research Agents:** AI systems attempting to automate multiple stages of the research cycle autonomously (e.g., The AI Scientist, AutoSurvey).
-   **Human-AI Collaboration Patterns:** Novel workflows and interfaces integrating AI assistance seamlessly into researcher tasks for enhanced productivity and creativity.
-   **AI for Reproducibility & Validation:** Tools focused on verifying scientific claims, attempting automated replication of results, and ensuring overall scientific rigor.

# 📰 Latest Buzz / News

Recent news, announcements, and noteworthy updates circulating in the AI researcher ecosystem.

*   **Sakana AI Labs Update on AI Scientist**
    *   *Source:* X (Twitter) Post (Mar 2025) <!-- Added potential date/topic for context -->
    *   *Link:* [Tweet](https://x.com/SakanaAILabs/status/1899646987781501181)

*   **Meet CARL: The First AI System To Produce Academically Peer-Reviewed Research**
    *   *Source:* AutoScience AI Blog Post (Mar 2025) <!-- Added potential date for context -->
    *   *Link:* [Blog Post](https://www.autoscience.ai/blog/meet-carl-the-first-ai-system-to-produce-academically-peer-reviewed-research)


# 🔥 Featured Projects

<!-- omit in toc -->
## Open Source Tools

| Project | Description | Stars | Link |
|---------|-------------|-------|------|
| [CycleResearcher&DeepReviewr](https://github.com/zhu-minjun/Researcher) | Improving Automated Research via Automated Review. | ![](https://img.shields.io/github/stars/zhu-minjun/Researcher?style=social) | [GitHub](https://github.com/zhu-minjun/Researcher) |
| [AutoSurvey](https://github.com/AutoSurveys/AutoSurvey) | Large language models automatically writing surveys. | ![](https://img.shields.io/github/stars/AutoSurveys/AutoSurvey?style=social) | [GitHub](https://github.com/AutoSurveys/AutoSurvey) |
| [AI-Scientis](https://github.com/SakanaAI/AI-Scientist) | Towards Fully Automated Open-Ended Scientific Discovery. | ![](https://img.shields.io/github/stars/SakanaAI/AI-Scientist?style=social) | [GitHub](https://github.com/SakanaAI/AI-Scientist) |
| [Galactica](https://github.com/paperswithcode/galai) | Meta's scientific language model for research tasks. | ![](https://img.shields.io/github/stars/paperswithcode/galai?style=social) | [GitHub](https://github.com/paperswithcode/galai) |
| [SciKit-LLM](https://github.com/iryna-kondr/scikit-llm) | Integration of LLMs into scientific workflows. | ![](https://img.shields.io/github/stars/iryna-kondr/scikit-llm?style=social) | [GitHub](https://github.com/iryna-kondr/scikit-llm) |
| [CoScientist](https://github.com/gomesgroup/coscientist) | Autonomous chemical research with LLMs. | ![](https://img.shields.io/github/stars/gomesgroup/coscientist?style=social) | [GitHub](https://github.com/gomesgroup/coscientist) |
| [PaperRobot](https://github.com/EagleW/PaperRobot) | Incremental Draft Generation of Scientific Ideas. | ![](https://img.shields.io/github/stars/EagleW/PaperRobot?style=social) | [GitHub](https://github.com/EagleW/PaperRobot) |


<!-- omit in toc -->
## Commercial Platforms

*   [AI Researcher](https://ai-researcher.net/)
*   [Elicit](https://elicit.org/)
*   [Consensus](https://consensus.app/)
*   [SciSpace](https://scispace.com/)
*   [Wolfram Research Assistant](https://www.wolfram.com/research-assistant/)
*   [IBM Watson Discovery](https://www.ibm.com/cloud/watson-discovery)
*   [Overleaf AI](https://www.overleaf.com)

# 📚 Knowledge Building


<!-- omit in toc -->
## Knowledge Acquisition

<!-- omit in toc -->
### Main Acquisition & Recommendation
*   From Who You Know to What You Read: Augmenting Scientific Recommendations with Implicit Social Networks [[Paper]](https://doi.org/10.1145/3491102.3517470) ![](https://img.shields.io/badge/CHI-2022-blue) [[Review](https://openreview.net/forum?id=7vdeyZVPHL)]
*   Comlittee: Literature discovery with personal elected author committees [[Paper]](https://doi.org/10.1145/3544548.3581371) ![](https://img.shields.io/badge/CHI-2023-blue) [[Review](https://openreview.net/forum?id=NdSOavTTqdC)]
*   An academic recommender system on large citation data based on clustering, graph modeling and deep learning [[Paper]](https://doi.org/10.1007/s10115-024-02094-7) ![](https://img.shields.io/badge/Knowl._Inf._Syst.-2024-green) [No Review]
*   Paperweaver: Enriching topical paper alerts by contextualizing recommended papers with user-collected papers [[Paper]](https://doi.org/10.1145/3613904.3642196) ![](https://img.shields.io/badge/CHI-2024-blue) [No Review]
*   AgentRxiv: Towards Collaborative Autonomous Research [[Paper]](https://arxiv.org/abs/2503.18102) ![](https://img.shields.io/badge/arXiv-2025.03-red?logo=arxiv) [[Code]](https://github.com/SamuelSchmidgall/AgentLaboratory) [[AI Review]](https://ai-researcher.net/abs/2503.18102)
*   ResearchBench: Benchmarking LLMs in Scientific Discovery via Inspiration-Based Task Decomposition [[Paper]](http://arxiv.org/abs/2503.21248) ![](https://img.shields.io/badge/arXiv-2025.03-red?logo=arxiv) [No Code] [[AI Review]](https://ai-researcher.net/abs/2503.21248)
*   CodeScientist: End-to-End Semi-Automated Scientific Discovery with Code-based Experimentation [[Paper]](http://arxiv.org/abs/2503.22708) ![](https://img.shields.io/badge/arXiv-2025.03-red?logo=arxiv) [[Code]](https://github.com/allenai/codescientist) [[AI Review]](https://ai-researcher.net/abs/2503.22708)
*   DORA AI Scientist: Multi-agent Virtual Research Team for Scientific Exploration Discovery and Automated Report Generation [[Paper]](http://biorxiv.org/lookup/doi/10.1101/2025.03.06.641840) ![](https://img.shields.io/badge/bioRxiv-2025.03-orange) [No Code] [No Review] [[Project]](https://pharma.ai/dora)

<!-- omit in toc -->
### Figure Understanding
*   A Diagram is Worth a Dozen Images [[Paper]](https://link.springer.com/chapter/10.1007/978-3-319-46493-0_15) ![](https://img.shields.io/badge/ECCV-2016-blue) [No Code] [No OpenReview]
*   FigureQA: An Annotated Figure Dataset for Visual Reasoning [[Paper]](https://arxiv.org/abs/1710.07300) ![](https://img.shields.io/badge/arXiv-2017.10-red?logo=arxiv) [[Code](https://github.com/Maluuba/FigureQA)] [[Review](https://openreview.net/forum?id=SyunbfbAb)]
*   A simple neural network module for relational reasoning [[Paper]](https://papers.nips.cc/paper_files/paper/2017/hash/e6acf4b0f69f6f6e60e9a815938aa1ff-Abstract.html) ![](https://img.shields.io/badge/NeurIPS-2017-blue) [No Code] [[Review](https://papers.nips.cc/paper_files/paper/2017/file/e6acf4b0f69f6f6e60e9a815938aa1ff-Reviews.html)]
*   ChartQA: A Benchmark for Question Answering about Charts with Visual and Logical Reasoning [[Paper]](https://aclanthology.org/2022.findings-acl.177/) ![](https://img.shields.io/badge/ACL_Findings-2022-blue) [[Code](https://github.com/vis-nlp/chartqa)] [No Review]
*   ChartSumm: A Comprehensive Benchmark for Automatic Chart Summarization of Long and Short Summaries [[Paper]](https://arxiv.org/abs/2304.13620) ![](https://img.shields.io/badge/arXiv-2023.04-red?logo=arxiv) [[Code](https://github.com/pranonrahman/ChartSumm)] [[AI Review]](https://ai-researcher.net/abs/2304.13620)
*   SPIQA: A Dataset for Multimodal Question Answering on Scientific Papers [[Paper]](https://arxiv.org/pdf/2407.09413) ![](https://img.shields.io/badge/arXiv-2024.07-red?logo=arxiv) [[Code](https://github.com/google/spiqa)] [[Review](https://openreview.net/forum?id=h3lddsY5nf#discussion)]
*   Multimodal ArXiv: A Dataset for Improving Scientific Comprehension of Large Vision-Language Models [[Paper]](https://aclanthology.org/2024.acl-long.775/) ![](https://img.shields.io/badge/ACL-2024-blue) [[Code](https://huggingface.co/MMInstruction/Qwen-VL-ArXivQA)] [[Review](https://openreview.net/forum?id=ly4fTqFwHp)] [[Project](https://mm-arxiv.github.io/)]
*   SciMMIR: Benchmarking Scientific Multi-modal Information Retrieval [[Paper]](https://aclanthology.org/2024.findings-acl.746/) ![](https://img.shields.io/badge/ACL_Findings-2024-blue) [[Code](https://github.com/Wusiwei0410/SciMMIR)] [[Review](https://openreview.net/forum?id=8TZ8XlXslu)]
*   CharXiv: Charting Gaps in Realistic Chart Understanding in Multimodal LLMs [[Paper]](https://openreview.net/pdf?id=cy8mq7QYae) ![](https://img.shields.io/badge/NeurIPS-2024-blue) [[Code](https://github.com/princeton-nlp/CharXiv)] [[Review](https://openreview.net/forum?id=lNvE8VOkPK)]
*   ChartAdapter: Large Vision-Language Model for Chart Summarization [[Paper]](https://arxiv.org/abs/2412.20715) ![](https://img.shields.io/badge/arXiv-2024.12-red?logo=arxiv) [No Code] [[AI Review]](https://ai-researcher.net/abs/2412.20715)

<!-- omit in toc -->
### Table Understanding
*   ToTTo: A Controlled Table-To-Text Generation Dataset [[Paper]](https://aclanthology.org/2020.emnlp-main.89/) ![](https://img.shields.io/badge/EMNLP-2020-blue) [[Code](https://github.com/google-research-datasets/ToTTo)] [[Review](https://openreview.net/forum?id=5IFfYuORcC-)]
*   Towards Table-to-Text Generation with Numerical Reasoning [[Paper]](https://aclanthology.org/2021.acl-long.115/) ![](https://img.shields.io/badge/ACL-2021-blue) [[Code](https://github.com/titech-nlp/numeric-nlg)] [No Review]
*   Structure-Aware Pre-Training for Table-to-Text Generation [[Paper]](https://aclanthology.org/2021.findings-acl.200/) ![](https://img.shields.io/badge/ACL_Findings-2021-blue) [No Code] [No Review]
*   SciGen: a Dataset for Reasoning-Aware Text Generation from Scientific Tables [[Paper]](https://openreview.net/forum?id=Jul-uX7EV_I) ![](https://img.shields.io/badge/EMNLP_Findings-2021-blue) [[Code](https://github.com/UKPLab/SciGen)] [[Review](https://openreview.net/forum?id=Jul-uX7EV_I)]
*   SciXGen: A Scientific Paper Dataset for Context-Aware Text Generation [[Paper]](https://aclanthology.org/2021.findings-emnlp.128/) ![](https://img.shields.io/badge/EMNLP_Findings-2021-blue) [No Code] [[Review](https://openreview.net/forum?id=3Nz7NWKuEz)]
*   Robust (Controlled) Table-to-Text Generation with Structure-Aware Equivariance Learning [[Paper]](https://aclanthology.org/2022.naacl-main.371/) ![](https://img.shields.io/badge/NAACL-2022-blue) [[Code](https://github.com/luka-group/Lattice)] [[Review](https://openreview.net/forum?id=BNll4sXfH-c)]
*   Few-shot Table-to-text Generation with Prefix-Controlled Generator [[Paper]](https://aclanthology.org/2022.coling-1.565/) ![](https://img.shields.io/badge/COLING-2022-blue) [No Code] [No Review]
*   Table-To-Text generation and pre-training with TabT5 [[Paper]](https://aclanthology.org/2022.findings-emnlp.503/) ![](https://img.shields.io/badge/EMNLP_Findings-2022-blue) [No Code] [[Review](https://openreview.net/forum?id=xyz6uMggk3H)]
*   LoFT: Enhancing Faithfulness and Diversity for Table-to-Text Generation via Logic Form Control [[Paper]](https://aclanthology.org/2023.eacl-main.40/) ![](https://img.shields.io/badge/EACL-2023-blue) [[Code](https://github.com/Yale-LILY/LoFT)] [No Review]
*   SORTIE: Dependency-Aware Symbolic Reasoning for Logical Data-to-text Generation [[Paper]](https://aclanthology.org/2023.findings-acl.715/) ![](https://img.shields.io/badge/ACL_Findings-2023-blue) [[Code](https://github.com/wenhuchen/LogicNLG)] [[Review](https://openreview.net/forum?id=xnKWybYYCJ)]
*   Arithmetic-Based Pretraining Improving Numeracy of Pretrained Language Models [[Paper]](https://aclanthology.org/2023.starsem-1.42/) ![](https://img.shields.io/badge/STARSEM-2023-blue) [[Code](https://github.com/UKPLab/starsem2023-arithmetic-based-pretraining)] [[Review](https://openreview.net/forum?id=Dm6k8WTERfab)]
*   Structure-aware Table-to-Text Generation with Prefix-tuning [[Paper]](https://dlnext.acm.org/doi/10.1145/3622896.3622919) ![](https://img.shields.io/badge/CIKM-2023-blue) [No Code] [No Review]
*   Unifying Structured Data as Graph for Data-to-Text Pre-Training [[Paper]](https://aclanthology.org/2024.tacl-1.12/) ![](https://img.shields.io/badge/TACL-2024-blue) [[Code](https://github.com/AlibabaResearch/DAMO-ConvAI/tree/main/unid2t)] [[Review](https://openreview.net/forum?id=luuI3Jl7DB)]
*   Table-to-Text Using Pre-trained Large Language Model and LoRA [[Paper]](https://ieeexplore.ieee.org/document/10707812) ![](https://img.shields.io/badge/IEEE_Access-2024-green) [No Code] [No Review]
*   Integrating Table Representations into Large Language Models for Improved Scholarly Document Comprehension [[Paper]](https://aclanthology.org/2024.sdp-1.28/) ![](https://img.shields.io/badge/SDP@ACL-2024-blue) [[Code](https://github.com/buseskorkmaz/Integrating-Table-Representations-into-LLMs)] [No Review]

<!-- omit in toc -->
## Knowledge Utilization
*   Multi-document scientific summarization from a knowledge graph-centric view [[Paper]](https://aclanthology.org/2022.coling-1.543) ![](https://img.shields.io/badge/COLING-2022-blue) [[Code](https://github.com/muguruzawang/kgsum)] [[Review](https://openreview.net/forum?id=hFhnvujND7)]
*   Bio-sieve: exploring instruction tuning large language models for systematic review automation [[Paper]](https://arxiv.org/abs/2308.06610) ![](https://img.shields.io/badge/arXiv-2023.08-red?logo=arxiv) [[Code](https://github.com/ambroser53/Bio-SIEVE)] [[AI Review]](https://ai-researcher.net/abs/2308.06610)
*   Hierarchical catalogue generation for literature review: a benchmark [[Paper]](https://doi.org/10.18653/v1/2023.findings-emnlp.453) ![](https://img.shields.io/badge/EMNLP_Findings-2023-blue) [No Code] [[Review](https://openreview.net/forum?id=aeLyo8GAco¬eId=FLAXCeX7Dj)]
*   Litllm: A toolkit for scientific literature review [[Paper]](https://arxiv.org/abs/2402.01788) ![](https://img.shields.io/badge/arXiv-2024.02-red?logo=arxiv) [[Code](https://github.com/LitLLM/litllms-for-literature-review-tmlr)] [[Review](https://openreview.net/forum?id=heeJqQXKg7)]
*   Automating research synthesis with domain-specific large language model fine-tuning [[Paper]](https://arxiv.org/abs/2404.08680) ![](https://img.shields.io/badge/arXiv-2024.04-red?logo=arxiv) [[Code](https://github.com/peterjhwang/slr-helper)] [[AI Review]](https://ai-researcher.net/abs/2404.08680)
*   Assisting in writing wikipedia-like articles from scratch with large language models [[Paper]](https://doi.org/10.18653/v1/2024.naacl-long.347) ![](https://img.shields.io/badge/NAACL-2024-blue) [[Code](https://github.com/stanford-oval/storm)] [[Review](https://openreview.net/forum?id=XOsAvZL57c)]
*   Chime: Llm-assisted hierarchical organization of scientific studies for literature review support [[Paper]](https://doi.org/10.18653/v1/2024.findings-acl.8) ![](https://img.shields.io/badge/ACL_Findings-2024-blue) [[Code](https://github.com/allenai/chime)] [[Review](https://openreview.net/forum?id=poEi1Qul8IC)]
*   Instruct Large Language Models to Generate Scientific Literature Survey Step by Step [[Paper]](https://arxiv.org/pdf/2408.07884) ![](https://img.shields.io/badge/NLPCC-2024-blue) [No Code] [[AI Review]](https://ai-researcher.net/abs/2408.07884)
*   Language agents achieve superhuman synthesis of scientific knowledge [[Paper]](https://arxiv.org/abs/2409.13740) ![](https://img.shields.io/badge/arXiv-2024.09-red?logo=arxiv) [No Code] [[AI Review]](https://ai-researcher.net/abs/2409.13740)
*   Hireview: Hierarchical taxonomy-driven automatic literature review generation [[Paper]](https://arxiv.org/abs/2410.03761) ![](https://img.shields.io/badge/arXiv-2024.10-red?logo=arxiv) [No Code] [[Review](https://openreview.net/forum?id=Ncx0X8lcN1)]
*   Knowledge Navigator: LLM-guided Browsing Framework for Exploratory Search in Scientific Literature [[Paper]](https://aclanthology.org/2024.findings-emnlp.516) ![](https://img.shields.io/badge/EMNLP_Findings-2024-blue) [[Code](https://github.com/katzurik/Knowledge_Navigator)] [[Review](https://openreview.net/forum?id=cO39ZQvgIv)]
*   Autosurvey: Large language models can automatically write surveys [[Paper]](http://papers.nips.cc/paper_files/paper/2024/hash/d07a9fc7da2e2ec0574c38d5f504d105-Abstract-Conference.html) ![](https://img.shields.io/badge/NeurIPS-2024-blue) [No Code] [[Review](https://openreview.net/forum?id=FExX8pMrdT)]
*   SurveyX: Academic Survey Automation via Large Language Models [[Paper]](https://arxiv.org/abs/2502.14776) ![](https://img.shields.io/badge/arXiv-2025.02-red?logo=arxiv) [No Code] [[AI Review]](https://ai-researcher.net/abs/2502.14776)
*   LimTopic: LLM-based Topic Modeling and Text Summarization for Analyzing Scientific Articles limitations [[Paper]](https://arxiv.org/abs/2503.10658) ![](https://img.shields.io/badge/JCDL-2024-blue) [[Code](https://github.com/IbrahimAlAzhar/LimTopic/tree/master)] [[AI Review]](https://ai-researcher.net/abs/2503.10658)
*   What's In Your Field? Mapping Scientific Research with Knowledge Graphs and Large Language Models [[Paper]](https://arxiv.org/abs/2503.09894) ![](https://img.shields.io/badge/arXiv-2025.03-red?logo=arxiv) [[Code](https://github.com/chiral-carbon/kg-for-science)] [[AI Review]](https://ai-researcher.net/abs/2503.09894)
*   DORA AI Scientist: Multi-agent Virtual Research Team for Scientific Exploration Discovery and Automated Report Generation [[Paper]](http://biorxiv.org/lookup/doi/10.1101/2025.03.06.641840) ![](https://img.shields.io/badge/bioRxiv-2025.03-orange) [No Code] [No Review] [[Project]](https://pharma.ai/dora)

# 💡 Idea Generation

<!-- omit in toc -->
## Generation
*   Literature based discovery: models, methods, and trends [[Paper]](https://doi.org/10.1016/j.jbi.2017.08.011) ![](https://img.shields.io/badge/J._Biomed._Inform.-2017-green) [No Code] [No Review]
*   Predicting the Future of AI with AI: High-quality link prediction in an exponentially growing knowledge network [[Paper]](https://arxiv.org/abs/2210.00881) ![](https://img.shields.io/badge/arXiv-2022.10-red?logo=arxiv) [[Code](https://github.com/artificial-scientist-lab/FutureOfAIviaAI)] [[AI Review]](https://ai-researcher.net/abs/2210.00881)
*   LLM and Simulation as Bilevel Optimizers: A New Paradigm to Advance Physical Scientific Discovery [[Paper]](https://openreview.net/forum?id=hz8cFsdz7P) ![](https://img.shields.io/badge/ICML-2024-blue) [No Code] [[Review]](https://openreview.net/forum?id=hz8cFsdz7P)
*   Chain of ideas: Revolutionizing research via novel idea development with llm agents [[Paper]](https://arxiv.org/abs/2410.13185) ![](https://img.shields.io/badge/arXiv-2024.10-red?logo=arxiv) [[Code](https://github.com/DAMO-NLP-SG/CoI-Agent)] [[AI Review]](https://ai-researcher.net/abs/2410.13185)
*   Nova: An iterative planning and search approach to enhance novelty and diversity of llm generated ideas [[Paper]](https://arxiv.org/abs/2410.14255) ![](https://img.shields.io/badge/arXiv-2024.10-red?logo=arxiv) [No Code] [[Review](https://openreview.net/forum?id=4ytRL3HJrq)]
*   Ideas are dimes a dozen: Large language models for idea generation in innovation [[Paper]](https://christophegirard.com/wp-content/uploads/2023/09/Etude-creation-idees-comparative-ChatGPT-vs-etudiants.pdf) ![](https://img.shields.io/badge/Wharton_School_Paper-2023-brown) [No Code] [No Review]
*   Monte Carlo Thought Search: Large Language Model Querying for Complex Scientific Reasoning in Catalyst Design [[Paper]](https://arxiv.org/abs/2310.14420) ![](https://img.shields.io/badge/arXiv-2023.10-red?logo=arxiv) [[Code](https://github.com/pnnl/chemreasoner)] [[AI Review]](https://ai-researcher.net/abs/2310.14420)
*   Large Language Models are Zero Shot Hypothesis Proposers [[Paper]](https://arxiv.org/abs/2311.05965) ![](https://img.shields.io/badge/arXiv-2023.11-red?logo=arxiv) [No Code] [[AI Review]](https://ai-researcher.net/abs/2311.05965)
*   Mathematical discoveries from program search with large language models [[Paper]](https://www.nature.com/articles/s41586-023-06924-6) ![](https://img.shields.io/badge/Nature-2023-green) [[Code](https://github.com/google-deepmind/funsearch)] [No Review]
*   ChemReasoner: Heuristic Search over a Large Language Model's Knowledge Space using Quantum-Chemical Feedback [[Paper]](https://arxiv.org/abs/2402.10980) ![](https://img.shields.io/badge/arXiv-2024.02-red?logo=arxiv) [[Code](https://github.com/pnnl/chemreasoner)] [[AI Review]](https://ai-researcher.net/abs/2402.10980)
*   Acceleron: A tool to accelerate research ideation [[Paper]](https://arxiv.org/abs/2403.04382) ![](https://img.shields.io/badge/arXiv-2024.03-red?logo=arxiv) [No Code] [[AI Review]](https://ai-researcher.net/abs/2403.04382)
*   Hypothesis generation with large language models [[Paper]](https://arxiv.org/abs/2404.04326) ![](https://img.shields.io/badge/arXiv-2024.04-red?logo=arxiv) [[Code](https://github.com/ChicagoHAI/hypothesis-generation)] [[AI Review]](https://ai-researcher.net/abs/2404.04326)
*   Researchagent: Iterative research idea generation over scientific literature with large language models [[Paper]](https://arxiv.org/abs/2404.07738) ![](https://img.shields.io/badge/arXiv-2024.04-red?logo=arxiv) [[Code](https://github.com/JinheonBaek/ResearchAgent)] [[AI Review]](https://ai-researcher.net/abs/2404.07738)
*   Data-driven discovery with large generative models [[Paper]](https://openreview.net/forum?id=5SpjhZNXtt) ![](https://img.shields.io/badge/ICML-2024-blue) [No Code] [[Review]](https://openreview.net/forum?id=5SpjhZNXtt)
*   Generation and human-expert evaluation of interesting research ideas using knowledge graphs and large language models [[Paper]](https://arxiv.org/abs/2405.17044) ![](https://img.shields.io/badge/arXiv-2024.05-red?logo=arxiv) [[Code](https://github.com/artificial-scientist-lab/SciMuse)] [[AI Review]](https://ai-researcher.net/abs/2405.17044)
*   Large Language Models as Biomedical Hypothesis Generators: A Comprehensive Evaluation [[Paper]](https://openreview.net/forum?id=q36rpGlG9X#discussion) ![](https://img.shields.io/badge/ICML_Workshop-2024-blue) [[Code](https://github.com/TsinghuaC3I/LLM4BioHypoGen/)] [No Review]
*   The AI Scientist: Towards Fully Automated Open-Ended Scientific Discovery [[Paper]](https://arxiv.org/abs/2408.06292) ![](https://img.shields.io/badge/arXiv-2024.08-red?logo=arxiv) [[Code](https://github.com/SakanaAI/AI-Scientist)] [[AI Review]](https://ai-researcher.net/abs/2408.06292) 
*   SciMON: Scientific Inspiration Machines Optimized for Novelty [[Paper]](https://doi.org/10.18653/v1/2024.acl-long.18) ![](https://img.shields.io/badge/ACL-2024-blue) [[Code](https://github.com/EagleW/Scientific-Inspiration-Machines-Optimized-for-Novelty)] [No Review]
*   Large language models for automated open-domain scientific hypotheses discovery [[Paper]](https://doi.org/10.18653/v1/2024.findings-acl.804) ![](https://img.shields.io/badge/ACL_Findings-2024-blue) [[Code](https://github.com/SenticNet/MOOSE)] [No Review]
*   Can LLMs Generate Novel Research Ideas? A Large-Scale Human Study with 100+ NLP Researchers [[Paper]](https://arxiv.org/abs/2409.04109) ![](https://img.shields.io/badge/arXiv-2024.09-red?logo=arxiv) [[Code](https://github.com/NoviScl/AI-Researcher)] [[AI Review]](https://ai-researcher.net/abs/2409.04109)
*   Accelerating scientific discovery with generative knowledge extraction, graph-based representation, and multimodal intelligent graph reasoning [[Paper]](https://doi.org/10.1088/2632-2153/ad7228) ![](https://img.shields.io/badge/Mach._Learn.:_Sci._Technol.-2024-green) [[Code](https://github.com/lamm-mit/GraphReasoning)] [No Review]
*   Can Large Language Models Unlock Novel Scientific Research Ideas? [[Paper]](https://arxiv.org/abs/2409.06185) ![](https://img.shields.io/badge/arXiv-2024.09-red?logo=arxiv) [[Code](https://github.com/sandeep82945/Future-Idea-Generation)] [[AI Review]](https://ai-researcher.net/abs/2409.06185)
*   Sciagents: Automating scientific discovery through multi-agent intelligent graph reasoning [[Paper]](https://arxiv.org/abs/2409.05556) ![](https://img.shields.io/badge/arXiv-2024.09-red?logo=arxiv) [[Code](https://github.com/lamm-mit/SciAgentsDiscovery)] [[AI Review]](https://ai-researcher.net/abs/2409.05556)
*   Scideator: Human-LLM Scientific Idea Generation Grounded in Research-Paper Facet Recombination [[Paper]](https://arxiv.org/abs/2409.14634) ![](https://img.shields.io/badge/arXiv-2024.09-red?logo=arxiv) [No Code] [[AI Review]](https://ai-researcher.net/abs/2409.14634)
*   IdeaSynth: Iterative Research Idea Development Through Evolving and Composing Idea Facets with Literature-Grounded Feedback [[Paper]](https://arxiv.org/abs/2410.04025) ![](https://img.shields.io/badge/arXiv-2024.10-red?logo=arxiv) [No Code] [[AI Review]](https://ai-researcher.net/abs/2410.04025)
*   MOOSE-Chem: Large Language Models for Rediscovering Unseen Chemistry Scientific Hypotheses [[Paper]](https://arxiv.org/abs/2410.07076) ![](https://img.shields.io/badge/arXiv-2024.10-red?logo=arxiv) [[Code](https://github.com/ZonglinY/MOOSE-Chem)] [[Review](https://openreview.net/forum?id=X9OfMNNepI¬eId=6wqTKd3LtF)]
*   Two heads are better than one: A multi-agent system has the potential to improve scientific idea generation [[Paper]](https://arxiv.org/abs/2410.09403) ![](https://img.shields.io/badge/arXiv-2024.10-red?logo=arxiv) [[Code](https://github.com/open-sciencelab/Virtual-Scientists)] [[Review](https://openreview.net/forum?id=yYQLvofQ1k)]
*   Literature meets data: A synergistic approach to hypothesis generation [[Paper]](https://arxiv.org/abs/2410.17309) ![](https://img.shields.io/badge/arXiv-2024.10-red?logo=arxiv) [[Code](https://github.com/ChicagoHAI/hypothesis-generation)] [[Review](https://openreview.net/forum?id=ucGalW3icF)]
*   SciPIP: An LLM-based Scientific Paper Idea Proposer [[Paper]](https://arxiv.org/abs/2410.23166) ![](https://img.shields.io/badge/arXiv-2024.10-red?logo=arxiv) [No Code] [[Review](https://openreview.net/forum?id=RiQRUcjXBD)]
*   Aigs: Generating Science from Ai-Powered Automated Falsification [[Paper]](https://arxiv.org/pdf/2411.11910) ![](https://img.shields.io/badge/arXiv-2024.11-red?logo=arxiv) [No Code] [[AI Review]](https://ai-researcher.net/abs/2411.11910)
*   Exploring Scientific Hypothesis Generation with Mamba [[Paper]](https://aclanthology.org/2024.nlp4science-1.17/) ![](https://img.shields.io/badge/NLP4Science@EMNLP-2024-blue) [[Code](https://github.com/fglx-c/Exploring-Scientific-Hypothesis-Generation-with-Mamba)] [No Review]
*   Improving Scientific Hypothesis Generation with Knowledge Grounded Large Language Models [[Paper]](https://arxiv.org/abs/2411.02382) ![](https://img.shields.io/badge/arXiv-2024.11-red?logo=arxiv) [[Code](https://anonymous.4open.science/r/KG-CoI-C203/README.md)] [[Review](https://openreview.net/forum?id=Y1VtR6uHjf)] 
*   DiscoveryWorld: A Virtual Environment for Developing and Evaluating Automated Scientific Discovery Agents [[Paper]](http://papers.nips.cc/paper_files/paper/2024/hash/13836f251823945316ae067350a5c366-Abstract-Datasets_and_Benchmarks_Track.html) ![](https://img.shields.io/badge/NeurIPS_D&B-2024-blue) [[Code](https://github.com/allenai/discoveryworld)] [[Review](https://openreview.net/forum?id=cDYqckEt6d#discussion)]
*   Learning to Generate Research Idea with Dynamic Control [[Paper]](https://arxiv.org/abs/2412.14626) ![](https://img.shields.io/badge/arXiv-2024.12-red?logo=arxiv) [[Code](https://github.com/du-nlp-lab/Learn2Gen)] [[Review](https://openreview.net/forum?id=zCb0dPvGYN)] 
*   ResearchTown: Simulator of Human Research Community [[Paper]](https://arxiv.org/abs/2412.17767) ![](https://img.shields.io/badge/arXiv-2024.12-red?logo=arxiv) [[Code](https://github.com/ulab-uiuc/research-town)] [[Review](https://openreview.net/forum?id=IwhvaDrL39)] 
*   Dolphin: Closed-loop Open-ended Auto-research through Thinking, Practice, and Feedback [[Paper]](https://arxiv.org/abs/2501.03916) ![](https://img.shields.io/badge/arXiv-2025.01-red?logo=arxiv) [[Code](https://github.com/Alpha-Innovator/Dolphin)] [[Review](https://openreview.net/forum?id=bGTpYaPJqD)]
*   Superintelligent Agents Pose Catastrophic Risks: Can Scientist AI Offer a Safer Path? [[Paper]](http://arxiv.org/abs/2502.15657) ![](https://img.shields.io/badge/arXiv-2025.02-red?logo=arxiv) [No Code] [[AI Review]](https://ai-researcher.net/abs/2502.15657)
*   Towards an AI co-scientist [[Paper]](https://arxiv.org/pdf/2502.18864) ![](https://img.shields.io/badge/arXiv-2025.02-red?logo=arxiv) [No Code] [[AI Review]](https://ai-researcher.net/abs/2502.18864)
*   Graph of AI Ideas: Leveraging Knowledge Graphs and LLMs for AI Research Idea Generation [[Paper]](https://arxiv.org/abs/2503.08549) ![](https://img.shields.io/badge/arXiv-2025.03-red?logo=arxiv) [No Code] [[AI Review]](https://ai-researcher.net/abs/2503.08549)
*   AgentRxiv: Towards Collaborative Autonomous Research [[Paper]](https://arxiv.org/abs/2503.18102) ![](https://img.shields.io/badge/arXiv-2025.03-red?logo=arxiv) [[Code]](https://github.com/SamuelSchmidgall/AgentLaboratory) [[AI Review]](https://ai-researcher.net/abs/2503.18102)
*   ResearchBench: Benchmarking LLMs in Scientific Discovery via Inspiration-Based Task Decomposition [[Paper]](http://arxiv.org/abs/2503.21248) ![](https://img.shields.io/badge/arXiv-2025.03-red?logo=arxiv) [No Code] [[AI Review]](https://ai-researcher.net/abs/2503.21248)
*   CodeScientist: End-to-End Semi-Automated Scientific Discovery with Code-based Experimentation [[Paper]](http://arxiv.org/abs/2503.22708) ![](https://img.shields.io/badge/arXiv-2025.03-red?logo=arxiv) [[Code]](https://github.com/allenai/codescientist) [[AI Review]](https://ai-researcher.net/abs/2503.22708) 
*   DORA AI Scientist: Multi-agent Virtual Research Team for Scientific Exploration Discovery and Automated Report Generation [[Paper]](http://biorxiv.org/lookup/doi/10.1101/2025.03.06.641840) ![](https://img.shields.io/badge/bioRxiv-2025.03-orange) [No Code] [No Review] [[Project]](https://pharma.ai/dora) 

<!-- omit in toc -->
## Evaluation
*   Generating fact checking explanations [[Paper]](https://doi.org/10.18653/v1/2020.acl-main.656) ![](https://img.shields.io/badge/ACL-2020-blue) [No Code] [No Review]
*   Generative language modeling for automated theorem proving [[Paper]](https://arxiv.org/abs/2009.03393) ![](https://img.shields.io/badge/arXiv-2020.09-red?logo=arxiv) [No Code] [[AI Review]](https://ai-researcher.net/abs/2009.03393)
*   Fact or fiction: Verifying scientific claims [[Paper]](https://doi.org/10.18653/v1/2020.emnlp-main.609) ![](https://img.shields.io/badge/EMNLP-2020-blue) [[Code](https://github.com/allenai/scifact)] [[Review](https://openreview.net/forum?id=ghf46B0rQ6)]
*   MultiVerS: Improving scientific claim verification with weak supervision and full-document context [[Paper]](https://doi.org/10.18653/v1/2022.findings-naacl.6) ![](https://img.shields.io/badge/NAACL_Findings-2022-blue) [[Code](https://github.com/dwadden/longchecker)] [No Review] 
*   Proofver: Natural logic theorem proving for fact verification [[Paper]](https://doi.org/10.1162/tacl_a_00503) ![](https://img.shields.io/badge/TACL-2022-blue) [[Code](https://github.com/krishnamrith12/ProoFVer)] [No Review]
*   HyperTree Proof Search for Neural Theorem Proving [[Paper]](http://papers.nips.cc/paper_files/paper/2022/hash/a8901c5e85fb8e1823bbf0f755053672-Abstract-Conference.html) ![](https://img.shields.io/badge/NeurIPS-2022-blue) [No Code] [[Review](https://openreview.net/forum?id=J4pX8Q8cxHH)]
*   Thor: Wielding hammers to integrate language models and automated theorem provers [[Paper]](http://papers.nips.cc/paper_files/paper/2022/hash/377c25312668e48f2e531e2f2c422483-Abstract-Conference.html) ![](https://img.shields.io/badge/NeurIPS-2022-blue) [No Code] [[Review](https://openreview.net/forum?id=fUeOyt-2EOp)]
*   Missing counter-evidence renders NLP fact-checking unrealistic for misinformation [[Paper]](https://doi.org/10.18653/v1/2022.emnlp-main.397) ![](https://img.shields.io/badge/EMNLP-2022-blue) [[Code](https://github.com/UKPLab/emnlp2022-missing-counter-evidence)] [No Review]
*   The state of human-centered NLP technology for fact-checking [[Paper]](https://arxiv.org/pdf/2301.03056) ![](https://img.shields.io/badge/Inf._Process._Manag.-2023-green) [No Code] [[AI Review]](https://ai-researcher.net/abs/2301.03056)
*   Draft, sketch, and prove: Guiding formal theorem provers with informal proofs [[Paper]](https://openreview.net/forum?id=SMa9EAovKMC) ![](https://img.shields.io/badge/ICLR-2023-blue) [[Code](https://github.com/albertqjiang/draft_sketch_prove)] [[Review](https://openreview.net/forum?id=SMa9EAovKMC)]
*   Decomposing the enigma: Subgoal-based demonstration learning for formal theorem proving [[Paper]](https://arxiv.org/abs/2305.16366) ![](https://img.shields.io/badge/arXiv-2023.05-red?logo=arxiv) [[Code](https://github.com/HKUNLP/subgoal-theorem-prover)] [[Review](https://openreview.net/forum?id=xLoxMvO695)]
*   aedFaCT: Scientific Fact-Checking Made Easier via Semi-Automatic Discovery of Relevant Expert Opinions [[Paper]](https://arxiv.org/abs/2305.07796) ![](https://img.shields.io/badge/arXiv-2023.05-red?logo=arxiv) [[Code](https://github.com/altuncu/aedFaCT)] [[AI Review]](https://ai-researcher.net/abs/2305.07796)
*   Fact-checking complex claims with program-guided reasoning [[Paper]](https://doi.org/10.18653/v1/2023.acl-long.386) ![](https://img.shields.io/badge/ACL-2023-blue) [[Code](https://github.com/mbzuai-nlp/ProgramFC)] [No Review]
*   FactKG: Fact verification via reasoning on knowledge graphs [[Paper]](https://doi.org/10.18653/v1/2023.acl-long.895) ![](https://img.shields.io/badge/ACL-2023-blue) [[Code](https://github.com/jiho283/FactKG)] [[Review](https://openreview.net/forum?id=bvZSKS8f7k)]
*   Prompt to be Consistent is Better than Self-Consistent? Few-Shot and Zero-Shot Fact Verification with Pre-trained Language Models [[Paper]](https://doi.org/10.18653/v1/2023.findings-acl.278) ![](https://img.shields.io/badge/ACL_Findings-2023-blue) [[Code](https://github.com/znhy1024/ProToCo)] [No Review]
*   Dt-solver: Automated theorem proving with dynamic-tree sampling guided by proof-level value function [[Paper]](https://doi.org/10.18653/v1/2023.acl-long.706) ![](https://img.shields.io/badge/ACL-2023-blue) [No Code] [No Review]
*   An in-context learning agent for formal theorem-proving [[Paper]](https://arxiv.org/abs/2310.04353) ![](https://img.shields.io/badge/arXiv-2023.10-red?logo=arxiv) [[Code](https://github.com/trishullab/copra)] [[Review](https://openreview.net/forum?id=V7HRrxXUhN#discussion)]
*   Baldur: Whole-proof generation and repair with large language models [[Paper]](https://doi.org/10.1145/3611643.3616243) ![](https://img.shields.io/badge/ESEC/FSE-2023-blue) [No Code] [No Review]
*   Towards LLM-based Fact Verification on News Claims with a Hierarchical Step-by-Step Prompting Method [[Paper]](https://doi.org/10.18653/v1/2023.ijcnlp-main.64) ![](https://img.shields.io/badge/IJCNLP-2023-blue) [[Code](https://github.com/jadeCurl/HiSS)] [[Review](https://openreview.net/forum?id=F315Z6NZeu)]
*   Investigating zero-and few-shot generalization in fact verification [[Paper]](https://doi.org/10.18653/v1/2023.ijcnlp-main.34) ![](https://img.shields.io/badge/IJCNLP-2023-blue) [[Code](https://github.com/teacherpeterpan/Fact-Checking-Generalization)] [[Review](https://openreview.net/forum?id=R_OaHG1juW)]
*   Characterizing and Verifying Scientific Claims: Qualitative Causal Structure is All You Need [[Paper]](https://doi.org/10.18653/v1/2023.emnlp-main.828) ![](https://img.shields.io/badge/EMNLP-2023-blue) [[Code](https://github.com/VulnDetector/VerQCS)] [[Review](https://openreview.net/forum?id=vQQrmp5dbO)]
*   Mustard: Mastering uniform synthesis of theorem and proof data [[Paper]](https://openreview.net/forum?id=8xliOUg9EW) ![](https://img.shields.io/badge/ICLR-2024-blue) [[Code](https://github.com/Eleanor-H/MUSTARD)] [[Review](https://openreview.net/forum?id=8xliOUg9EW)]
*   Unsupervised Pretraining for Fact Verification by Language Model Distillation [[Paper]](https://openreview.net/forum?id=1mjsP8RYAw) ![](https://img.shields.io/badge/ICLR-2024-blue) [[Code](https://github.com/AdrianBZG/SFAVEL)] [[Review](https://openreview.net/forum?id=1mjsP8RYAw)]
*   Lego-prover: Neural theorem proving with growing libraries [[Paper]](https://openreview.net/forum?id=3f5PALef5B) ![](https://img.shields.io/badge/ICLR-2024-blue) [[Code](https://github.com/wiio12/LEGO-Prover)] [[Review](https://openreview.net/forum?id=3f5PALef5B)]
*   Can Large Language Models Detect Misinformation in Scientific News Reporting? [[Paper]](https://arxiv.org/abs/2402.14268) ![](https://img.shields.io/badge/arXiv-2024.02-red?logo=arxiv) [No Code] [[AI Review]](https://ai-researcher.net/abs/2402.14268)
*   What Makes Medical Claims (Un)Verifiable? Analyzing Entity and Relation Properties for Fact Verification [[Paper]](https://aclanthology.org/2024.eacl-long.124) ![](https://img.shields.io/badge/EACL-2024-blue) [No Code] [No Review]
*   Comparing knowledge sources for open-domain scientific claim verification [[Paper]](https://aclanthology.org/2024.eacl-long.128) ![](https://img.shields.io/badge/EACL-2024-blue) [[Code](https://www.github.com/jvladika/comparing-knowledge-sources)] [[Review](https://openreview.net/forum?id=sEyPhLonyD)]
*   Towards large language models as copilots for theorem proving in lean [[Paper]](https://arxiv.org/abs/2404.12534) ![](https://img.shields.io/badge/arXiv-2024.04-red?logo=arxiv) [[Code](https://github.com/lean-dojo/LeanCopilot)] [[Review](https://openreview.net/forum?id=C9X5sXa2k1)]
*   Deepseek-prover: Advancing theorem proving in llms through large-scale synthetic data [[Paper]](https://arxiv.org/abs/2405.14333) ![](https://img.shields.io/badge/arXiv-2024.05-red?logo=arxiv) [No Code] [[Review](https://openreview.net/forum?id=A2UDQ6wt2X)]
*   MAGIC: Multi-Argument Generation with Self-Refinement for Domain Generalization in Automatic Fact-Checking [[Paper]](https://aclanthology.org/2024.lrec-main.951) ![](https://img.shields.io/badge/LREC--COLING-2024-blue) [[Code](https://github.com/NYCU-NLP-Lab/XClaimCheck)] [[Review](https://openreview.net/forum?id=s9ueQmFx30)]
*   Improving health question answering with reliable and time-aware evidence retrieval [[Paper]](https://doi.org/10.18653/v1/2024.findings-naacl.295) ![](https://img.shields.io/badge/NAACL_Findings-2024-blue) [[Code](https://github.com/jvladika/Improving-Health-QA)] [[Review](https://openreview.net/forum?id=7m9Gkgm9B1)]
*   Lean-star: Learning to interleave thinking and proving [[Paper]](https://arxiv.org/abs/2407.10040) ![](https://img.shields.io/badge/arXiv-2024.07-red?logo=arxiv) [[Code](https://github.com/Lagooon/LeanSTaR)] [[Review](https://openreview.net/forum?id=SOWZ59UyNc)]
*   Grounding fallacies misrepresenting scientific publications in evidence [[Paper]](https://arxiv.org/abs/2408.12812) ![](https://img.shields.io/badge/arXiv-2024.08-red?logo=arxiv) [[Code](https://github.com/UKPLab/naacl2025-missciplus)] [[Review](https://openreview.net/forum?id=944ahoVisE)]
*   Understanding Fine-grained Distortions in Reports of Scientific Findings [[Paper]](https://doi.org/10.18653/v1/2024.findings-acl.369) ![](https://img.shields.io/badge/ACL_Findings-2024-blue) [[Project](https://www.uni-bamberg.de/en/nlproc/resources/sciencecommdistortion/)] [[Review](https://openreview.net/forum?id=cQJeu7yIrL)]
*   Enhancing natural language inference performance with knowledge graph for COVID-19 automated fact-checking in Indonesian language [[Paper]](https://arxiv.org/abs/2409.00061) ![](https://img.shields.io/badge/arXiv-2024.09-red?logo=arxiv) [No Code] [[AI Review]](https://ai-researcher.net/abs/2409.00061)
*   Augmenting the Veracity and Explanations of Complex Fact Checking via Iterative Self-Revision with LLMs [[Paper]](https://arxiv.org/abs/2410.15135) ![](https://img.shields.io/badge/arXiv-2024.10-red?logo=arxiv) [No Code] [[Review](https://openreview.net/forum?id=ZTWHMi3jTM)]
*   ClaimVer: Explainable claim-level verification and evidence attribution of text through knowledge graphs [[Paper]](https://aclanthology.org/2024.findings-emnlp.795) ![](https://img.shields.io/badge/EMNLP_Findings-2024-blue) [No Code] [[Review](https://openreview.net/forum?id=IEB3MU0t3j)]
*   Proving theorems recursively [[Paper]](http://papers.nips.cc/paper_files/paper/2024/hash/9de7a49945898da86e062e7029baa284-Abstract-Conference.html) ![](https://img.shields.io/badge/NeurIPS-2024-blue) [No Code] [[Review](https://openreview.net/forum?id=yAa5l92TtQ)]
*   Automating Mathematical Proof Generation Using Large Language Model Agents and Knowledge Graphs [[Paper]](https://arxiv.org/abs/2503.11657) ![](https://img.shields.io/badge/arXiv-2025.03-red?logo=arxiv) [No Code] [[AI Review]](https://ai-researcher.net/abs/2503.11657)
*   Optimizing Decomposition for Optimal Claim Verification [[Paper]](https://arxiv.org/abs/2503.15354) ![](https://img.shields.io/badge/arXiv-2025.03-red?logo=arxiv) [[Code](https://github.com/yining610/dynamic-decomposition)] [[AI Review]](https://ai-researcher.net/abs/2503.15354)
*   Enabling AI Scientists to Recognize Innovation: A Domain-Agnostic Algorithm for Assessing Novelty [[Paper]](https://arxiv.org/abs/2503.01508) ![](https://img.shields.io/badge/arXiv-2025.03-red?logo=arxiv) [No Code] [[AI Review]](https://ai-researcher.net/abs/2503.01508)
*   GraphEval: A Lightweight Graph-Based LLM Framework for Idea Evaluation [[Paper]](https://arxiv.org/abs/2503.12600) ![](https://img.shields.io/badge/arXiv-2025.03-red?logo=arxiv) [[Code]](https://github.com/ulab-uiuc/GraphEval) [[AI Review]](https://ai-researcher.net/abs/2503.12600)

# 🔬 Experiment Execution

<!-- omit in toc -->
## Experiment Design
*   HuggingGPT: Solving AI Tasks with ChatGPT and its Friends in Hugging Face [[Paper]](https://arxiv.org/abs/2303.17580) ![](https://img.shields.io/badge/arXiv-2023.03-red?logo=arxiv) [[Code](https://github.com/microsoft/JARVIS)] [[Review](https://openreview.net/forum?id=yHdTscY6Ci)]
*   AutoGen: Enabling Next-Gen LLM Applications via Multi-Agent Conversation [[Paper]](https://arxiv.org/abs/2308.08155) ![](https://img.shields.io/badge/arXiv-2023.08-red?logo=arxiv) [[Code](https://github.com/microsoft/autogen)] [[Review](https://openreview.net/forum?id=tEAF9LBdgu)]
*   Autonomous chemical research with large language models [[Paper]](https://www.nature.com/articles/s41586-023-06792-0) ![](https://img.shields.io/badge/Nature-2023-green) [[Code](https://github.com/gomesgroup/coscientist)] [No Review] 
*   Navigating Complexity: Orchestrated Problem Solving with Multi-Agent LLMs [[Paper]](https://arxiv.org/abs/2402.16713) ![](https://img.shields.io/badge/arXiv-2024.02-red?logo=arxiv) [No Code] [[AI Review]](https://ai-researcher.net/abs/2402.16713)
*   CRISPR-GPT: An LLM Agent for Automated Design of Gene-Editing Experiments [[Paper]](https://arxiv.org/abs/2404.18021) ![](https://img.shields.io/badge/arXiv-2024.04-red?logo=arxiv) [No Code] [[AI Review]](https://ai-researcher.net/abs/2404.18021)
*   Simulating Expert Discussions with Multi-agent for Enhanced Scientific Problem Solving [[Paper]](https://aclanthology.org/2024.sdp-1.23/) ![](https://img.shields.io/badge/SDP@ACL-2024-blue) [No Code] [[Review](https://openreview.net/forum?id=EHg5GDnyq1)]
*   An automatic end-to-end chemical synthesis development platform powered by large language models [[Paper]](https://www.nature.com/articles/s41467-024-54457-x) ![](https://img.shields.io/badge/Nat._Commun.-2024-green) [[Code](https://github.com/Ruan-Yixiang/LLM-RDF)] [No Review]

<!-- omit in toc -->
## Experiment Conduction
*   Biological structure and function emerge from scaling unsupervised learning to 250 million protein sequences [[Paper]](https://www.pnas.org/doi/full/10.1073/pnas.2016239118) ![](https://img.shields.io/badge/PNAS-2020-green) [[Code](https://github.com/facebookresearch/esm)] [No Review]
*   Controllable Protein Design with Language Models [[Paper]](https://arxiv.org/abs/2201.07338) ![](https://img.shields.io/badge/arXiv-2022.01-red?logo=arxiv) [No Code] [[AI Review]](https://ai-researcher.net/abs/2201.07338)
*   Evolutionary-scale prediction of atomic-level protein structure with a language model [[Paper]](https://www.science.org/doi/10.1126/science.ade2574) ![](https://img.shields.io/badge/Science-2023-green) [No Code] [No Review]
*   Bayesian Optimization of Catalysts With In-context Learning [[Paper]](https://arxiv.org/abs/2304.05341) ![](https://img.shields.io/badge/arXiv-2023.04-red?logo=arxiv) [[Code](https://github.com/ur-whitelab/BO-LIFT)] [[AI Review]](https://ai-researcher.net/abs/2304.05341)
*   Large Language Models for Automated Data Science: Introducing CAAFE for Context-Aware Automated Feature Engineering [[Paper]](https://arxiv.org/abs/2305.03403) ![](https://img.shields.io/badge/arXiv-2023.05-red?logo=arxiv) [[Code](https://github.com/noahho/CAAFE)] [[Review](https://openreview.net/forum?id=9WSxQZ9mG7¬eId=lVsGaf1y4J)]
*   ChatGPT-powered Conversational Drug Editing Using Retrieval and Domain Feedback [[Paper]](https://arxiv.org/abs/2305.18090) ![](https://img.shields.io/badge/arXiv-2023.05-red?logo=arxiv) [[Code](https://github.com/chao1224/ChatDrug)] [[Review](https://openreview.net/forum?id=BsSrjBrSN4)]
*   Training Socially Aligned Language Models on Simulated Social Interactions [[Paper]](https://arxiv.org/abs/2305.16960) ![](https://img.shields.io/badge/arXiv-2023.05-red?logo=arxiv) [No Code] [[Review](https://openreview.net/forum?id=NddKiWtdUm)]
*   Are you in a Masquerade? Exploring the Behavior and Impact of Large Language Model Driven Social Bots in Online Social Networks [[Paper]](https://arxiv.org/abs/2307.10337) ![](https://img.shields.io/badge/arXiv-2023.07-red?logo=arxiv) [[Code - Dataset]](https://github.com/Litsay/Masquerade-23) [[AI Review]](https://ai-researcher.net/abs/2307.10337)
*   AutoML-GPT: Large Language Model for AutoML [[Paper]](https://arxiv.org/abs/2309.01125) ![](https://img.shields.io/badge/arXiv-2023.09-red?logo=arxiv) [No Code] [[Review](https://openreview.net/forum?id=5TameAQcng)]
*   Data-Juicer: A One-Stop Data Processing System for Large Language Models [[Paper]](https://arxiv.org/abs/2309.02033) ![](https://img.shields.io/badge/arXiv-2023.09-red?logo=arxiv) [[Code](https://github.com/modelscope/data-juicer)] [[Review](https://openreview.net/forum?id=iHrtJK9cs4)]
*   Monte Carlo Thought Search: Large Language Model Querying for Complex Scientific Reasoning in Catalyst Design [[Paper]](https://arxiv.org/abs/2310.14420) ![](https://img.shields.io/badge/arXiv-2023.10-red?logo=arxiv) [[Code](https://github.com/pnnl/chemreasoner)] [[Review](https://openreview.net/forum?id=ToMdTqVIb5)]
*   Jellyfish: A Large Language Model for Data Preprocessing [[Paper]](https://arxiv.org/abs/2312.01678) ![](https://img.shields.io/badge/arXiv-2023.12-red?logo=arxiv) [[Code](https://huggingface.co/NECOUDBFM/Jellyfish-8B)] [[AI Review]](https://ai-researcher.net/abs/2312.01678)
*   Autonomous chemical research with large language models [[Paper]](https://www.nature.com/articles/s41586-023-06792-0) ![](https://img.shields.io/badge/Nature-2023-green) [[Code](https://github.com/gomesgroup/coscientist)] [No Review] 
*   DrugAssist: A Large Language Model for Molecule Optimization [[Paper]](https://arxiv.org/abs/2401.10334) ![](https://img.shields.io/badge/arXiv-2024.01-red?logo=arxiv) [[Code](https://github.com/blazerye/DrugAssist)] [[AI Review]](https://ai-researcher.net/abs/2401.10334)
*   ChemReasoner: Heuristic Search over a Large Language Model's Knowledge Space using Quantum-Chemical Feedback [[Paper]](https://arxiv.org/abs/2402.10980) ![](https://img.shields.io/badge/arXiv-2024.02-red?logo=arxiv) [[Code](https://github.com/pnnl/chemreasoner)] [[AI Review]](https://ai-researcher.net/abs/2402.10980) 
*   Augmenting large language models with chemistry tools [[Paper]](https://www.nature.com/articles/s42256-024-00832-8) ![](https://img.shields.io/badge/Nat._Mach._Intell.-2024-green) [[Code](https://github.com/ur-whitelab/chemcrow-public)] [[Review](https://openreview.net/forum?id=wdGIL6lx3l)]
*   Efficient Evolutionary Search Over Chemical Space with Large Language Models [[Paper]](https://arxiv.org/abs/2406.16976) ![](https://img.shields.io/badge/arXiv-2024.06-red?logo=arxiv) [[Code](https://github.com/zoom-wang112358/MOLLEO)] [[Review](https://openreview.net/forum?id=awWiNvQwf3)]
*   Tree Search for Language Model Agents [[Paper]](https://arxiv.org/abs/2407.01476) ![](https://img.shields.io/badge/arXiv-2024.07-red?logo=arxiv) [[Code](https://github.com/kohjingyu/search-agents)] [[Review](https://openreview.net/forum?id=kpL66Mvd2a)]
*   De novo generation of SARS-CoV-2 antibody CDRH3 with a pre-trained generative large language model [[Paper]](https://www.nature.com/articles/s41467-024-50903-y) ![](https://img.shields.io/badge/Nat._Commun.-2024-green) [[Code](https://github.com/TencentAILabHealthcare/PALM)] [No Review]
*   DrugAgent: Automating AI-aided Drug Discovery Programming through LLM Multi-Agent Collaboration [[Paper]](https://arxiv.org/abs/2411.15692) ![](https://img.shields.io/badge/arXiv-2024.11-red?logo=arxiv) [[Code - Anonymous]](https://anonymous.4open.science/r/drugagent-5C42/README.md) [[Review](https://openreview.net/forum?id=YWzIw7yYnR)]
*   PaperBench: Evaluating AI’s Ability to Replicate AI Research [[Paper]](https://cdn.openai.com/papers/22265bac-3191-44e5-b057-7aaacd8e90cd/paperbench.pdf) ![](https://img.shields.io/badge/OpenAI_Report-2025-brown) [[Code](https://github.com/openai/preparedness)] [No Review]
*   Curie: Toward Rigorous and Automated Scientific Experimentation with AI Agents [[Paper]](https://arxiv.org/abs/2502.16069) ![](https://img.shields.io/badge/arXiv-2025.03-red?logo=arxiv) [[Code]](https://github.com/Just-Curieous/Curie) [[AI Review]](https://ai-researcher.net/abs/2502.16069)
*   AgentRxiv: Towards Collaborative Autonomous Research [[Paper]](https://arxiv.org/abs/2503.18102) ![](https://img.shields.io/badge/arXiv-2025.03-red?logo=arxiv) [[Code]](https://github.com/SamuelSchmidgall/AgentLaboratory) [[AI Review]](https://ai-researcher.net/abs/2503.18102)
*   ResearchBench: Benchmarking LLMs in Scientific Discovery via Inspiration-Based Task Decomposition [[Paper]](http://arxiv.org/abs/2503.21248) ![](https://img.shields.io/badge/arXiv-2025.03-red?logo=arxiv) [No Code] [[AI Review]](https://ai-researcher.net/abs/2503.21248) 
*   CodeScientist: End-to-End Semi-Automated Scientific Discovery with Code-based Experimentation [[Paper]](http://arxiv.org/abs/2503.22708) ![](https://img.shields.io/badge/arXiv-2025.03-red?logo=arxiv) [[Code]](https://github.com/allenai/codescientist) [[AI Review]](https://ai-researcher.net/abs/2503.22708) 

<!-- omit in toc -->
## Internal Evaluation
*   Automl-gpt: Automatic machine learning with gpt [[Paper]](https://arxiv.org/abs/2305.02499) ![](https://img.shields.io/badge/arXiv-2023.05-red?logo=arxiv) [[Code](https://github.com/Significant-Gravitas/AutoGPT)] [[AI Review]](https://ai-researcher.net/abs/2305.02499)
*   AutoGen: Enabling Next-Gen LLM Applications via Multi-Agent Conversation [[Paper]](https://arxiv.org/abs/2308.08155) ![](https://img.shields.io/badge/arXiv-2023.08-red?logo=arxiv) [[Code](https://github.com/microsoft/autogen)] [[Review](https://openreview.net/forum?id=tEAF9LBdgu)]
*   MentaLLaMA: Interpretable Mental Health Analysis on Social Media with Large Language Models [[Paper]](https://arxiv.org/abs/2309.13567) ![](https://img.shields.io/badge/arXiv-2023.09-red?logo=arxiv) [[Code](https://github.com/SteveKGYang/MentaLLaMA)] [[Review](https://openreview.net/forum?id=KPq438T0uC)]
*   MLAgentBench: Evaluating Language Agents on Machine Learning Experimentation [[Paper]](https://arxiv.org/abs/2310.03302) ![](https://img.shields.io/badge/arXiv-2023.10-red?logo=arxiv) [[Code](https://github.com/snap-stanford/MLAgentBench/)] [[Review](https://openreview.net/forum?id=1Fs1LvjYQW)]
*   MechAgents: Large language model multi-agent collaborations can solve mechanics problems, generate new data, and integrate knowledge [[Paper]](https://arxiv.org/abs/2311.08166) ![](https://img.shields.io/badge/arXiv-2023.11-red?logo=arxiv) [[Code](https://github.com/lamm-mit/MechAgents)] [[AI Review]](https://ai-researcher.net/abs/2311.08166)
*   An autonomous laboratory for the accelerated synthesis of novel materials [[Paper]](https://www.nature.com/articles/s41586-023-06734-w) ![](https://img.shields.io/badge/Nature-2023-green) [[Code](https://github.com/mattmcdermott/novel-materials-screening)] [No Review]
*   Autonomous chemical research with large language models [[Paper]](https://doi.org/10.1038/s41586-023-06792-0) ![](https://img.shields.io/badge/Nature-2023-green) [[Code](https://github.com/gomesgroup/coscientist)] [No Review] 
*   LLM-in-the-loop: Leveraging Large Language Model for Thematic Analysis [[Paper]](https://aclanthology.org/2023.findings-emnlp.669/) ![](https://img.shields.io/badge/EMNLP_Findings-2023-blue) [[Code](https://github.com/sjdai/LLM-thematic-analysis)] [[Review](https://openreview.net/forum?id=NuMemgzPYT)]
*   Training socially aligned language models on simulated social interactions [[Paper]](https://openreview.net/forum?id=NddKiWtdUm) ![](https://img.shields.io/badge/ICLR-2024-blue) [No Code] [[Review](https://openreview.net/forum?id=NddKiWtdUm)] 
*   SWE-bench: Can Language Models Resolve Real-world Github Issues? [[Paper]](https://openreview.net/forum?id=VTF8yNQM66) ![](https://img.shields.io/badge/ICLR-2024-blue) [[Code](https://github.com/swe-bench/SWE-bench)] [[Review](https://openreview.net/forum?id=VTF8yNQM66)]
*   Can Large Language Models Serve as Data Analysts? A Multi-Agent Assisted Approach for Qualitative Data Analysis [[Paper]](https://arxiv.org/abs/2402.01386) ![](https://img.shields.io/badge/arXiv-2024.02-red?logo=arxiv) [No Code] [[AI Review]](https://ai-researcher.net/abs/2402.01386)
*   Automated Statistical Model Discovery with Language Models [[Paper]](https://arxiv.org/abs/2402.17879) ![](https://img.shields.io/badge/arXiv-2024.02-red?logo=arxiv) [No Code] [[Review](https://openreview.net/forum?id=B5906M4Wnd)]
*   Large language model agent for hyper-parameter optimization [[Paper]](https://arxiv.org/abs/2402.01881) ![](https://img.shields.io/badge/arXiv-2024.02-red?logo=arxiv) [No Code] [[AI Review]](https://ai-researcher.net/abs/2402.01881)
*   Mlcopilot: Unleashing the power of large language models in solving machine learning tasks [[Paper]](https://aclanthology.org/2024.eacl-long.179) ![](https://img.shields.io/badge/EACL-2024-blue) [[Code](https://github.com/microsoft/CoML)] [No Review]
*   Researchagent: Iterative research idea generation over scientific literature with large language models [[Paper]](https://arxiv.org/abs/2404.07738) ![](https://img.shields.io/badge/arXiv-2024.04-red?logo=arxiv) [[Code](https://github.com/JinheonBaek/ResearchAgent)] [[Review](https://openreview.net/forum?id=I0oWWdH7cS)] 
*   Automated social science: Language models as scientist and subjects [[Paper]](https://arxiv.org/abs/2404.11794) ![](https://img.shields.io/badge/arXiv-2024.04-red?logo=arxiv) [No Code] [[AI Review]](https://ai-researcher.net/abs/2404.11794)
*   Crispr-gpt: An llm agent for automated design of gene-editing experiments [[Paper]](https://arxiv.org/abs/2404.18021) ![](https://img.shields.io/badge/arXiv-2024.04-red?logo=arxiv) [No Code] [[AI Review]](https://ai-researcher.net/abs/2404.18021) 
*   Position: LLMs can't plan, but can help planning in LLM-modulo frameworks [[Paper]](https://openreview.net/forum?id=Th8JPEmH4z) ![](https://img.shields.io/badge/ICML-2024-blue) [No Code] [[Review](https://openreview.net/forum?id=Th8JPEmH4z)]
*   Augmenting large language models with chemistry tools [[Paper]](https://doi.org/10.1038/s42256-024-00832-8) ![](https://img.shields.io/badge/Nat._Mach._Intell.-2024-green) [[Code](https://github.com/ur-whitelab/chemcrow-public)] [[Review](https://openreview.net/forum?id=wdGIL6lx3l)] 
*   Opening a conversation on responsible environmental data science in the age of large language models [[Paper]](https://doi.org/10.1017/eds.2024.12) ![](https://img.shields.io/badge/Environ._Data_Sci.-2024-green) [No Code] [No Review]
*   Meta-Designing Quantum Experiments with Language Models [[Paper]](https://arxiv.org/abs/2406.02470) ![](https://img.shields.io/badge/arXiv-2024.06-red?logo=arxiv) [No Code] [[Review](https://openreview.net/forum?id=QWP1HKMUtQ)]
*   Automatic benchmarking of large multimodal models via iterative experiment programming [[Paper]](https://arxiv.org/abs/2406.12321) ![](https://img.shields.io/badge/arXiv-2024.06-red?logo=arxiv) [[Code](https://github.com/altndrr/apex)] [[Review](https://openreview.net/forum?id=OlAoRrScsG)]
*   OpenHands: An Open Platform for AI Software Developers as Generalist Agents [[Paper]](https://arxiv.org/abs/2407.16741) ![](https://img.shields.io/badge/arXiv-2024.07-red?logo=arxiv) [[Code](https://github.com/All-Hands-AI/OpenHands)] [[Review](https://openreview.net/forum?id=OJd3ayDDoF)]
*   The AI Scientist: Towards Fully Automated Open-Ended Scientific Discovery [[Paper]](https://arxiv.org/abs/2408.06292) ![](https://img.shields.io/badge/arXiv-2024.08-red?logo=arxiv) [[Code](https://github.com/SakanaAI/AI-Scientist)] [[AI Review]](https://ai-researcher.net/abs/2408.06292) 
*   Mlr-copilot: Autonomous machine learning research based on large language models agents [[Paper]](https://arxiv.org/abs/2408.14033) ![](https://img.shields.io/badge/arXiv-2024.08-red?logo=arxiv) [[Code](https://github.com/du-nlp-lab/MLR-Copilot)] [[Review](https://openreview.net/forum?id=06afwQOoU3)]
*   DSBench: How Far Are Data Science Agents to Becoming Data Science Experts? [[Paper]](https://arxiv.org/abs/2409.07703) ![](https://img.shields.io/badge/arXiv-2024.09-red?logo=arxiv) [[Code](https://github.com/LiqiangJing/DSBench)] [[Review](https://openreview.net/forum?id=DSsSPr0RZJ)]
*   AutoML-Agent: A Multi-Agent LLM Framework for Full-Pipeline AutoML [[Paper]](https://arxiv.org/abs/2410.02958) ![](https://img.shields.io/badge/arXiv-2024.10-red?logo=arxiv) [No Code] [[Review](https://openreview.net/forum?id=stolHkh6Nc)]
*   Chain of ideas: Revolutionizing research via novel idea development with llm agents [[Paper]](https://arxiv.org/abs/2410.13185) ![](https://img.shields.io/badge/arXiv-2024.10-red?logo=arxiv) [[Code](https://github.com/DAMO-NLP-SG/CoI-Agent)] [[Review](https://openreview.net/forum?id=GHJzxPgFa6¬eId=tN3UypVtcw)]
*   ScienceAgentBench: Toward Rigorous Assessment of Language Agents for Data-Driven Scientific Discovery [[Paper]](https://arxiv.org/abs/2410.05080) ![](https://img.shields.io/badge/arXiv-2024.10-red?logo=arxiv) [[Code](https://github.com/OSU-NLP-Group/ScienceAgentBench)] [[Review](https://openreview.net/forum?id=6z4YKr0GK6)]
*   Agent-as-a-Judge: Evaluate Agents with Agents [[Paper]](https://arxiv.org/abs/2410.10934) ![](https://img.shields.io/badge/arXiv-2024.10-red?logo=arxiv) [[Code](https://github.com/metauto-ai/agent-as-a-judge)] [[Review](https://openreview.net/forum?id=DeVm3YUnpj)]
*   SELA: Tree-Search Enhanced LLM Agents for Automated Machine Learning [[Paper]](https://arxiv.org/abs/2410.17238) ![](https://img.shields.io/badge/arXiv-2024.10-red?logo=arxiv) [[Code](https://github.com/geekan/MetaGPT)] [[Review](https://openreview.net/forum?id=fv2hL5n2mh)]
*   AAAR-1.0: Assessing AI's Potential to Assist Research [[Paper]](https://arxiv.org/abs/2410.22394) ![](https://img.shields.io/badge/arXiv-2024.10-red?logo=arxiv) [No Code] [[Review](https://openreview.net/forum?id=neQuqKgH6e)]
*   An automatic end-to-end chemical synthesis development platform powered by large language models [[Paper]](https://doi.org/10.1038/s41467-024-54457-x) ![](https://img.shields.io/badge/Nat._Commun.-2024-green) [[Code](https://github.com/Ruan-Yixiang/LLM-RDF)] [No Review] 
*   MatPilot: an LLM-enabled AI Materials Scientist under the Framework of Human-Machine Collaboration [[Paper]](https://arxiv.org/abs/2411.08063) ![](https://img.shields.io/badge/arXiv-2024.11-red?logo=arxiv) [No Code] [[AI Review]](https://ai-researcher.net/abs/2411.08063)
*   AI agents in chemical research: GVIM – an intelligent research assistant system [[Paper]](https://pubs.rsc.org/en/content/articlelanding/2025/dd/d4dd00398e) ![](https://img.shields.io/badge/Digital_Discovery-2025-green) [[Code](https://github.com/KangyongMa/GVIM)] [No Review]
*   Dolphin: Closed-loop Open-ended Auto-research through Thinking, Practice, and Feedback [[Paper]](https://arxiv.org/abs/2501.03916) ![](https://img.shields.io/badge/arXiv-2025.01-red?logo=arxiv) [No Code] [[Review](https://openreview.net/forum?id=bGTpYaPJqD)] 
*   Agent Laboratory: Using LLM Agents as Research Assistants [[Paper]](https://arxiv.org/abs/2501.04227) ![](https://img.shields.io/badge/arXiv-2025.01-red?logo=arxiv) [[Code](https://github.com/SamuelSchmidgall/AgentLaboratory)] [[AI Review]](https://ai-researcher.net/abs/2501.04227) 
*   SWE-bench Multimodal: Do AI Systems Generalize to Visual Software Domains? [[Paper]](https://openreview.net/forum?id=riTiq3i21b) ![](https://img.shields.io/badge/ICLR_Sub-2025-blue) [No Code] [[Review](https://openreview.net/forum?id=riTiq3i21b)]
*   AIDE: AI-Driven Exploration in the Space of Code [[Paper]](https://arxiv.org/abs/2502.13138) ![](https://img.shields.io/badge/arXiv-2025.02-red?logo=arxiv) [[Code](https://github.com/WecoAI/aideml)] [[AI Review]](https://ai-researcher.net/abs/2502.13138)
*   MLGym: A New Framework and Benchmark for Advancing AI Research Agents [[Paper]](https://arxiv.org/abs/2502.14499) ![](https://img.shields.io/badge/arXiv-2025.02-red?logo=arxiv) [[Code](https://github.com/facebookresearch/MLGym)] [[AI Review]](https://ai-researcher.net/abs/2502.14499)



# 📝 Paper Writing

<!-- omit in toc -->
## Main Writing & Summarization
*   Towards Automated Related Work Summarization [[Paper]](https://aclanthology.org/C10-2049/) ![](https://img.shields.io/badge/COLING-2010-blue) [No Code] [No Review]
*   Neural Related Work Summarization with a Joint Context-driven Attention Mechanism [[Paper]](https://aclanthology.org/D18-1204/) ![](https://img.shields.io/badge/EMNLP-2018-blue) [[Data]](https://github.com/kuadmu/2018EMNLP) [No Review]
*   PaperRobot: Incremental Draft Generation of Scientific Ideas [[Paper]](https://aclanthology.org/P19-1191/) ![](https://img.shields.io/badge/ACL-2019-blue) [[Code]](https://github.com/EagleW/PaperRobot) [No Review]
*   ScisummNet: A Large Annotated Corpus and Content-Impact Models for Scientific Paper Summarization with Citation Networks [[Paper]](https://ojs.aaai.org/index.php/AAAI/article/view/4727) ![](https://img.shields.io/badge/AAAI-2019-blue) [No Code] [No Review]
*   Automatic Generation of Citation Texts in Scholarly Papers: A Pilot Study [[Paper]](https://aclanthology.org/2020.acl-main.550/) ![](https://img.shields.io/badge/ACL-2020-blue) [[Code]](https://github.com/XingXinyu96/citation_generation) [No Review]
*   Expertise Style Transfer: A New Task Towards Better Communication between Experts and Laymen [[Paper]](https://aclanthology.org/2020.acl-main.100/) ![](https://img.shields.io/badge/ACL-2020-blue) [[Project]](https://srhthu.github.io/expertise-style-transfer/#disclaimer) [No Review]
*   Automatic related work section generation: experiments in scientific document abstracting [[Paper]](https://link.springer.com/article/10.1007/s11192-020-03630-2) ![](https://img.shields.io/badge/Scientometrics-2020-green) [[Code]](https://github.com/AhmedAbuRaed/SPSeq2Seq) [No Review]
*   Automatic Related Work Section Generation by Sentence Extraction and Reordering [[Paper]](https://ceur-ws.org/Vol-2871/paper8.pdf) ![](https://img.shields.io/badge/BIR@ECIR-2021-blue) [No Code] [No Review]
*   Automatic Title Generation for Text with Pre-trained Transformer Language Model [[Paper]](https://ieeexplore.ieee.org/abstract/document/9364613) ![](https://img.shields.io/badge/IEEE_Access-2021-green) [[Code]](https://github.com/BradLin0819/Automatic-Citation-Text-Generation-with-Citation-Intent-Control) [No Review]
*   AutoCite: Multi-Modal Representation Fusion for Contextual Citation Generation [[Paper]](https://dl.acm.org/doi/10.1145/3437963.3441739) ![](https://img.shields.io/badge/WSDM-2021-blue) [[Code]](https://github.com/qqingwang/AutoCite) [No Review]
*   BACO: A Background Knowledge- and Content-Based Framework for Citing Sentence Generation [[Paper]](https://aclanthology.org/2021.acl-long.116/) ![](https://img.shields.io/badge/ACL-2021-blue) [No Code] [No Review]
*   Intent-Controllable Citation Text Generation [[Paper]](https://www.mdpi.com/2227-7390/10/10/1763) ![](https://img.shields.io/badge/Mathematics-2022-green) [[Code]](https://github.com/BradLin0819/Automatic-Citation-Text-Generation-with-Citation-Intent-Control) [No Review]
*   Read, revise, repeat: A system demonstration for human-in-the-loop iterative text revision [[Paper]](https://arxiv.org/abs/2204.03685) ![](https://img.shields.io/badge/ACL_Demo-2022-blue) [[Code]](https://github.com/vipulraheja/IteraTeR) [[AI Review]](https://ai-researcher.net/abs/2204.03685)
*   Generating Scientific Definitions with Controllable Complexity [[Paper]](https://aclanthology.org/2022.acl-long.569/) ![](https://img.shields.io/badge/ACL-2022-blue) [[Code]](https://github.com/talaugust/definition-complexity) [[Review](https://openreview.net/forum?id=S8x2x5EpWj)]
*   Understanding Iterative Revision from Human-Written Text [[Paper]](https://aclanthology.org/2022.acl-long.250/) ![](https://img.shields.io/badge/ACL-2022-blue) [[Code]](https://github.com/vipulraheja/iterater) [No Review]
*   Disencite: Graph-based disentangled representation learning for context-specific citation generation [[Paper]](https://doi.org/10.1609/aaai.v36i10.21397) ![](https://img.shields.io/badge/AAAI-2022-blue) [No Code] [No Review]
*   CORWA: A Citation-Oriented Related Work Annotation Dataset [[Paper]](https://aclanthology.org/2022.naacl-main.397.pdf) ![](https://img.shields.io/badge/NAACL-2022-blue) [[Code]](https://github.com/jacklxc/CORWA) [[Review](https://openreview.net/forum?id=7jPYpDEMFLk)]
*   Controllable citation sentence generation with language models [[Paper]](https://arxiv.org/abs/2211.07066) ![](https://img.shields.io/badge/arXiv-2022.11-red?logo=arxiv) [[Code]](https://github.com/nianlonggu/LMCiteGen) [[AI Review]](https://ai-researcher.net/abs/2211.07066)
*   Improving Iterative Text Revision by Learning Where to Edit from Other Revision Tasks [[Paper]](https://aclanthology.org/2022.emnlp-main.678/) ![](https://img.shields.io/badge/EMNLP-2022-blue) [[Code]](https://github.com/vipulraheja/iterater) [No Review]
*   Making Science Simple: Corpora for the Lay Summarisation of Scientific Literature [[Paper]](https://aclanthology.org/2022.emnlp-main.724/) ![](https://img.shields.io/badge/EMNLP-2022-blue) [[Code]](https://github.com/TGoldsack1/Corpora_for_Lay_Summarisation) [No Review]
*   Can artificial intelligence help for scientific writing? [[Paper]](https://link.springer.com/article/10.1186/s13054-023-04380-2) ![](https://img.shields.io/badge/Crit._Care-2023-green) [No Code] [No Review]
*   Text revision in scientific writing assistance: An overview [[Paper]](https://arxiv.org/abs/2303.16726) ![](https://img.shields.io/badge/arXiv-2023.03-red?logo=arxiv) [No Code] [[Review](https://openreview.net/forum?id=1NNEFGoFcd)]
*   Using ChatGPT for language editing in scientific articles [[Paper]](https://link.springer.com/content/pdf/10.1186/s40902-023-00381-x.pdf) ![](https://img.shields.io/badge/Gynecol._Oncol._Rep.-2023-green) [No Code] [No Review]
*   Good Practices for Scientific Article Writing with ChatGPT and Other Artificial Intelligence Language Models [[Paper]](https://www.mdpi.com/2673-687X/3/2/9) ![](https://img.shields.io/badge/Medicina-2023-green) [No Code] [No Review]
*   Comparing scientific abstracts generated by ChatGPT to real abstracts with detectors and blinded human reviewers [[Paper]](https://www.nature.com/articles/s41746-023-00819-6) ![](https://img.shields.io/badge/npj_Digit._Med.-2023-green) [No Code] [No Review]
*   Decoding the End-to-end Writing Trajectory in Scholarly Manuscripts [[Paper]](https://arxiv.org/abs/2304.00121) ![](https://img.shields.io/badge/In2Writing@CHI-2023-blue) [[Code]](https://github.com/minnesotanlp/reward-system) [[Review](https://openreview.net/forum?id=tmwSCMT6kc)]
*   Exploring the boundaries of reality: investigating the phenomenon of artificial intelligence hallucination in scientific writing through ChatGPT references [[Paper]](https://pubmed.ncbi.nlm.nih.gov/37182055/) ![](https://img.shields.io/badge/Cureus-2023-green) [No Code] [No Review]
*   The role of ChatGPT in scientific communication: writing better scientific review articles [[Paper]](https://pmc.ncbi.nlm.nih.gov/articles/PMC10164801/) ![](https://img.shields.io/badge/Ann._Biomed._Eng.-2023-green) [No Code] [No Review]
*   SciLit: A platform for joint scientific literature discovery, summarization and citation generation [[Paper]](https://doi.org/10.18653/v1/2023.acl-demo.22) ![](https://img.shields.io/badge/ACL_Demo-2023-blue) [No Code] [No Review]
*   Artificial intelligence in scientific writing: a friend or a foe? [[Paper]](https://pubmed.ncbi.nlm.nih.gov/37142479/) ![](https://img.shields.io/badge/J._Transl._Med.-2023-green) [No Code] [No Review]
*   Transformers Go for the LOLs: Generating (Humourous) Titles from Scientific Abstracts End-to-End [[Paper]](https://aclanthology.org/2023.eval4nlp-1.6/) ![](https://img.shields.io/badge/EVAL4NLP@IJCNLP-2023-blue) [[Code]](https://github.com/cyr19/A2T)] [[Review](https://openreview.net/forum?id=NgD0dJk7uk)]
*   Enabling large language models to generate text with citations [[Paper]](https://doi.org/10.18653/v1/2023.emnlp-main.398) ![](https://img.shields.io/badge/EMNLP-2023-blue) [[Code]](https://github.com/princeton-nlp/ALCE)] [[Review](https://openreview.net/forum?id=bxFwIn0wZ0¬eId=PwrzCuM4n5)]
*   Towards a unified framework for reference retrieval and related work generation [[Paper]](https://doi.org/10.18653/v1/2023.findings-emnlp.385) ![](https://img.shields.io/badge/EMNLP_Findings-2023-blue) [No Code] [[Review](https://openreview.net/forum?id=f6S1411OlZ)]
*   ‘Don’t Get Too Technical with Me’: A Discourse Structure-Based Framework for Science Journalism [[Paper]](https://aclanthology.org/2023.emnlp-main.76.pdf) ![](https://img.shields.io/badge/EMNLP-2023-blue) [No Code] [[Review](https://openreview.net/forum?id=uZp3i8yEs4¬eId=rPDqCmgBHt)]
*   Leveraging Large Language Models for Literature Review Tasks - A Case Study Using ChatGPT [[Paper]](https://link.springer.com/chapter/10.1007/978-3-031-48858-0_25) ![](https://img.shields.io/badge/ICDM_Workshops-2023-blue) [No Code] [No Review]
*   Explaining Relationships Among Research Papers [[Paper]](https://arxiv.org/abs/2402.13426) ![](https://img.shields.io/badge/arXiv-2024.02-red?logo=arxiv) [No Code] [[AI Review]](https://ai-researcher.net/abs/2402.13426)
*   Shallow synthesis of knowledge in gpt-generated texts: A case study in automatic related work composition [[Paper]](https://arxiv.org/abs/2402.12255) ![](https://img.shields.io/badge/arXiv-2024.02-red?logo=arxiv) [No Code] [[Review](https://openreview.net/forum?id=11PgOVDy1Q)]
*   LitLLM: A Toolkit for Scientific Literature Review [[Paper]](https://arxiv.org/abs/2402.01788) ![](https://img.shields.io/badge/arXiv-2024.02-red?logo=arxiv) [[Code](https://github.com/LitLLM/litllms-for-literature-review-tmlr)] [[AI Review]](https://ai-researcher.net/abs/2402.01788)
*   Techniques for supercharging academic writing with generative AI [[Paper]](https://www.nature.com/articles/s41551-024-01185-8) ![](https://img.shields.io/badge/Nat._Biomed._Eng.-2024-green) [No Code] [No Review]
*   Automating Research Synthesis with Domain-Specific Large Language Model Fine-Tuning [[Paper]](https://arxiv.org/abs/2404.08680) ![](https://img.shields.io/badge/arXiv-2024.04-red?logo=arxiv) [[Code](https://github.com/peterjhwang/slr-helper)] [[AI Review]](https://ai-researcher.net/abs/2404.08680)
*   Mapping the Increasing Use of LLMs in Scientific Papers [[Paper]](https://arxiv.org/abs/2404.01268v1) ![](https://img.shields.io/badge/arXiv-2024.04-red?logo=arxiv) [No Code] [[Review](https://openreview.net/forum?id=YX7QnhxESU#discussion)]
*   Autonomous LLM-Driven Research—from Data to Human-Verifiable Research Papers [[Paper]](https://arxiv.org/abs/2404.17605) ![](https://img.shields.io/badge/arXiv-2024.04-red?logo=arxiv) [[Code](https://github.com/Technion-Kishony-lab/data-to-paper)] [[AI Review]](https://ai-researcher.net/abs/2404.17605)
*   A publishing infrastructure for Artificial Intelligence (AI)-assisted academic authoring [[Paper]](https://doi.org/10.1093/jamia/ocae139) ![](https://img.shields.io/badge/JAMIA-2024-green) [[Code](https://github.com/manubot/manubot-ai-editor)] [No Review]
*   Step-Back Profiling: Distilling User History for Personalized Scientific Writing [[Paper]](https://arxiv.org/abs/2406.14275) ![](https://img.shields.io/badge/arXiv-2024.06-red?logo=arxiv) [[Code](https://github.com/gersteinlab/step-back-profiling)] [[Review](https://openreview.net/forum?id=2UKQEcUJX9)]
*   AutoSurvey: Large Language Models Can Automatically Write Surveys [[Paper]](https://arxiv.org/abs/2406.10252) ![](https://img.shields.io/badge/arXiv-2024.06-red?logo=arxiv) [[Code](https://github.com/AutoSurveys/AutoSurvey)] [[Review](https://openreview.net/forum?id=FExX8pMrdT)]
*   The Ability of ChatGPT in Paraphrasing Texts and Reducing Plagiarism: A Descriptive Analysis [[Paper]](https://pmc.ncbi.nlm.nih.gov/articles/PMC11250043/) ![](https://img.shields.io/badge/Cureus-2024-green) [No Code] [No Review]
*   Pelican: Correcting Hallucination in Vision-LLMs via Claim Decomposition and Program of Thought Verification [[Paper]](https://arxiv.org/abs/2407.02352) ![](https://img.shields.io/badge/arXiv-2024.07-red?logo=arxiv) [No Code] [[Review](https://openreview.net/forum?id=N23cmqtO0F)]
*   Reinforced Subject-Aware Graph Neural Network for Related Work Generation [[Paper]](https://doi.org/10.1007/978-981-97-5492-2_16) ![](https://img.shields.io/badge/KSEM-2024-blue) [No Code] [[Review](https://openreview.net/forum?id=4JUeRBE9Nn)]
*   Reference hallucination score for medical artificial intelligence chatbots: development and usability study [[Paper]](https://medinform.jmir.org/2024/1/e54345) ![](https://img.shields.io/badge/JMIR_Med._Inform.-2024-green) [No Code] [No Review]
*   LongWriter: Unleashing 10,000+ Word Generation from Long Context LLMs [[Paper]](https://arxiv.org/abs/2408.07055) ![](https://img.shields.io/badge/arXiv-2024.08-red?logo=arxiv) [[Code](https://github.com/THUDM/LongWriter)] [[Review](https://openreview.net/forum?id=kQ5s9Yh0WI)]
*   Automated focused feedback generation for scientific writing assistance [[Paper]](https://doi.org/10.18653/v1/2024.findings-acl.580) ![](https://img.shields.io/badge/ACL_Findings-2024-blue) [[Code](https://github.com/ericchamoun/FocusedFeedbackGeneration)] [No Review]
*   Instruct Large Language Models to Generate Scientific Literature Survey Step by Step [[Paper]](https://arxiv.org/pdf/2408.07884) ![](https://img.shields.io/badge/NLPCC-2024-blue) [No Code] [No Review]
*   Aries: A corpus of scientific paper edits made in response to peer reviews [[Paper]](https://doi.org/10.18653/v1/2024.acl-long.377) ![](https://img.shields.io/badge/ACL-2024-blue) [[Code](https://github.com/allenai/aries)] [[Review](https://openreview.net/forum?id=Zr96FfaUGR)]
*   Toward Structured Related Work Generation with Novelty Statements [[Paper]](https://aclanthology.org/2024.sdp-1.5/) ![](https://img.shields.io/badge/SDP@ACL-2024-blue) [[Code](https://github.com/omron-sinicx/STRoGeNS)] [No Review]
*   The AI Scientist: Towards Fully Automated Open-Ended Scientific Discovery [[Paper]](https://arxiv.org/abs/2408.06292) ![](https://img.shields.io/badge/arXiv-2024.08-red?logo=arxiv) [[Code](https://github.com/SakanaAI/AI-Scientist)] [[AI Review]](https://ai-researcher.net/abs/2408.06292)
*   LongReward: Improving Long-context Large Language Models with AI Feedback [[Paper]](https://arxiv.org/abs/2410.21252) ![](https://img.shields.io/badge/arXiv-2024.10-red?logo=arxiv) [[Code](https://github.com/THUDM/LongReward)] [[AI Review]](https://ai-researcher.net/abs/2410.21252)
*   Taxonomy Tree Generation from Citation Graph [[Paper]](https://arxiv.org/abs/2410.03761) ![](https://img.shields.io/badge/arXiv-2024.10-red?logo=arxiv) [No Code] [[AI Review]](https://ai-researcher.net/abs/2410.03761)
*   CycleResearcher: Improving Automated Research via Automated Review [[Paper]](https://arxiv.org/abs/2411.00816) ![](https://img.shields.io/badge/arXiv-2024.11-red?logo=arxiv) [[Code](https://github.com/zhu-minjun/Researcher)] [[Review](https://openreview.net/forum?id=bjcsVLoHYs)]
*   Cocoa: Co-Planning and Co-Execution with AI Agents [[Paper]](https://arxiv.org/abs/2412.10999) ![](https://img.shields.io/badge/arXiv-2024.12-red?logo=arxiv) [No Code] [[AI Review]](https://ai-researcher.net/abs/2412.10999)
*   ResearchTown: Simulator of Human Research Community [[Paper]](https://arxiv.org/abs/2412.17767) ![](https://img.shields.io/badge/arXiv-2024.12-red?logo=arxiv) [[Code](https://github.com/ulab-uiuc/research-town)] [[Review](https://openreview.net/forum?id=IwhvaDrL39)]
*   Agent Laboratory: Using LLM Agents as Research Assistants [[Paper]](https://arxiv.org/abs/2501.04227) ![](https://img.shields.io/badge/arXiv-2025.01-red?logo=arxiv) [[Code](https://github.com/SamuelSchmidgall/AgentLaboratory)] [[AI Review]](https://ai-researcher.net/abs/2501.04227)
*   LongEval: A Comprehensive Analysis of Long-Text Generation Through a Plan-based Paradigm [[Paper]](https://arxiv.org/abs/2502.19103) ![](https://img.shields.io/badge/arXiv-2025.02-red?logo=arxiv) [[Code](https://github.com/Wusiwei0410/LongEval)] [[AI Review]](https://ai-researcher.net/abs/2502.19103)
*   FutureGen: LLM-RAG Approach to Generate the Future Work of Scientific Article [[Paper]](https://arxiv.org/abs/2503.16561) ![](https://img.shields.io/badge/arXiv-2025.03-red?logo=arxiv) [[Dataset]](https://huggingface.co/datasets/iaadlab/FutureGen) [[AI Review]](https://ai-researcher.net/abs/2503.16561)
*   AgentRxiv: Towards Collaborative Autonomous Research [[Paper]](https://arxiv.org/abs/2503.18102) ![](https://img.shields.io/badge/arXiv-2025.03-red?logo=arxiv) [[Code]](https://github.com/SamuelSchmidgall/AgentLaboratory) [[AI Review]](https://ai-researcher.net/abs/2503.18102)
*   SurveyForge: On the Outline Heuristics, Memory-Driven Generation, and Multi-dimensional Evaluation for Automated Survey Writing [[Paper]](http://arxiv.org/abs/2503.04629) ![](https://img.shields.io/badge/arXiv-2025.03-red?logo=arxiv) [[Code]](https://github.com/Alpha-Innovator/SurveyForge) [[AI Review]](https://ai-researcher.net/abs/2503.04629)
*   CorpusStudio: Surfacing Emergent Patterns in a Corpus of Prior Work while Writing [[Paper]](https://arxiv.org/abs/2503.12436) ![](https://img.shields.io/badge/ACM_CHI-2025-blue) [No Code] [[AI Review]](https://ai-researcher.net/abs/2503.12436)
*   ResearchBench: Benchmarking LLMs in Scientific Discovery via Inspiration-Based Task Decomposition [[Paper]](http://arxiv.org/abs/2503.21248) ![](https://img.shields.io/badge/arXiv-2025.03-red?logo=arxiv) [No Code] [[AI Review]](https://ai-researcher.net/abs/2503.21248)
*   CodeScientist: End-to-End Semi-Automated Scientific Discovery with Code-based Experimentation [[Paper]](http://arxiv.org/abs/2503.22708) ![](https://img.shields.io/badge/arXiv-2025.03-red?logo=arxiv) [[Code]](https://github.com/allenai/codescientist) [[AI Review]](https://ai-researcher.net/abs/2503.22708)
*   DORA AI Scientist: Multi-agent Virtual Research Team for Scientific Exploration Discovery and Automated Report Generation [[Paper]](http://biorxiv.org/lookup/doi/10.1101/2025.03.06.641840) ![](https://img.shields.io/badge/bioRxiv-2025.03-orange) [No Code] [No Review] [[Project]](https://pharma.ai/dora)
*   How Deep Do Large Language Models Internalize Scientific Literature and Citation Practices? [[Paper]](http://arxiv.org/abs/2504.02767) ![](https://img.shields.io/badge/arXiv-2025.04-red?logo=arxiv) [[Code]](https://github.com/AndresAlgaba/LLMs_scientific_literature) [[AI Review]](https://ai-researcher.net/abs/2504.02767)

<!-- omit in toc -->
## Figure Generation
*   Data2Vis: Automatic Generation of Data Visualizations Using Sequence-to-Sequence Recurrent Neural Networks [[Paper]](https://ieeexplore.ieee.org/document/8744242) ![](https://img.shields.io/badge/IEEE_TVCG-2019-green) [[Code](https://github.com/victordibia/data2vis)] [No Review]
*   ADVISor: Automatic Visualization Answer for Natural-Language Question on Tabular Data [[Paper]](https://ieeexplore.ieee.org/document/9438784) ![](https://img.shields.io/badge/IEEE_PacificVis-2021-blue) [No Code] [No Review]
*   SCICAP: Generating Captions for Scientific Figures [[Paper]](https://aclanthology.org/2021.findings-emnlp.277/) ![](https://img.shields.io/badge/EMNLP_Findings-2021-blue) [[Code](https://github.com/tingyaohsu/scicap)] [No Review]
*   Sevi: Speech-to-Visualization through Neural Machine Translation [[Paper]](https://dl.acm.org/doi/pdf/10.1145/3514221.3520150) ![](https://img.shields.io/badge/IUI_Companion-2022-blue) [[Code](https://github.com/Thanksyy/Sevi)] [No Review]
*   Chat2VIS: Generating Data Visualizations via Natural Language Using ChatGPT, Codex and GPT-3 Large Language Models [[Paper]](https://ieeexplore.ieee.org/abstract/document/10121440) ![](https://img.shields.io/badge/IEEE_PacificVis_Wkshp-2023-blue) [No Code] [No Review]
*   AutomaTikZ: Text-Guided Synthesis of Scientific Vector Graphics with TikZ [[Paper]](https://openreview.net/forum?id=v3K5TVP8kZ) ![](https://img.shields.io/badge/ICLR-2024-blue) [[Code](https://github.com/potamides/AutomaTikZ)] [[Review](https://openreview.net/forum?id=v3K5TVP8kZ)]
*   Plots Made Quickly: An Efficient Approach for Generating Visualizations from Natural Language Queries [[Paper]](https://aclanthology.org/2024.lrec-main.1119/) ![](https://img.shields.io/badge/LREC--COLING-2024-blue) [No Code] [No Review]
*   DiagrammerGPT: Generating Open-Domain, Open-Platform Diagrams via LLM Planning [[Paper]](https://openreview.net/forum?id=NV8yRJRET1#discussion) ![](https://img.shields.io/badge/ACL-2024-blue) [[Code](https://github.com/aszala/DiagrammerGPT)] [[Review](https://openreview.net/forum?id=NV8yRJRET1)]
*   SciDoc2Diagrammer-MAF: Towards Generation of Scientific Diagrams from Documents guided by Multi-Aspect Feedback Refinement [[Paper]](https://aclanthology.org/2024.findings-emnlp.780/) ![](https://img.shields.io/badge/EMNLP_Findings-2024-blue) [[Code](https://github.com/Ishani-Mondal/SciDoc2DiagramGeneration)] [No Review]
*   DeTikZify: Synthesizing Graphics Programs for Scientific Figures and Sketches with TikZ [[Paper]](https://openreview.net/forum?id=bcVLFQCOjc) ![](https://img.shields.io/badge/EMNLP-2024-blue) [[Code](https://github.com/potamides/DeTikZify)] [[Review](https://openreview.net/forum?id=bcVLFQCOjc)]
*   ChartMimic: Evaluating LMM's Cross-Modal Reasoning Capability via Chart-to-Code Generation [[Paper]](https://arxiv.org/abs/2503.08957) ![](https://img.shields.io/badge/arXiv-2025.03-red?logo=arxiv) [[Code](https://github.com/ChartMimic/ChartMimic)] [[Review](https://openreview.net/forum?id=sGpCzsfd1K)]
*   ScImage: How Good Are Multimodal Large Language Models at Scientific Text-to-Image Generation? [[Paper]](https://arxiv.org/abs/2503.03447) ![](https://img.shields.io/badge/arXiv-2025.03-red?logo=arxiv) [[Code](https://github.com/leixin-zhang/Scimage)] [[Review](https://openreview.net/forum?id=ugyqNEOjoU)]

<!-- omit in toc -->
## Table Generation
*   gTBLS: Generating Tables from Text by Conditional Question Answering [[Paper]](https://arxiv.org/abs/2403.14457) ![](https://img.shields.io/badge/arXiv-2024.03-red?logo=arxiv) [No Code] [[Review](https://openreview.net/forum?id=klEM9YXtkPZ)]
*   OpenTE: Open-Structure Table Extraction From Text [[Paper]](https://ieeexplore.ieee.org/document/10448427) ![](https://img.shields.io/badge/IEEE_Access-2024-green) [No Code] [No Review]
*   ArxivDIGESTables: Synthesizing Scientific Literature into Tables using Language Models [[Paper]](https://aclanthology.org/2024.emnlp-main.538/) ![](https://img.shields.io/badge/EMNLP-2024-blue) [[Code](https://github.com/bnewm0609/arxivDIGESTables)] [No Review]
*   Is This a Bad Table? A Closer Look at the Evaluation of Table Generation from Text [[Paper]](https://aclanthology.org/2024.emnlp-main.1239/) ![](https://img.shields.io/badge/EMNLP-2024-blue) [No Code] [[Review](https://openreview.net/forum?id=EJ8QDeLqXZ)]
*   LATTE: Improving Latex Recognition for Tables and Formulae with Iterative Refinement [[Paper]](https://arxiv.org/abs/2409.14201) ![](https://img.shields.io/badge/arXiv-2025.02-red?logo=arxiv) [No Code] [[AI Review]](https://ai-researcher.net/abs/2409.14201)

<!-- omit in toc -->
## Slides & Poster Generation
*   SlidesGen: Automatic Generation of Presentation Slides for a Technical Paper Using Summarization [[Paper]](https://aaai.org/papers/flairs-2009-22/) ![](https://img.shields.io/badge/FLAIRS-2009-blue) [No Code] [No Review]
*   PPSGen: learning to generate presentation slides for academic papers [[Paper]](https://dl.acm.org/doi/10.5555/2540128.2540430) ![](https://img.shields.io/badge/KDD-2013-blue) [No Code] [No Review]
*   Learning to Generate Posters of Scientific Papers [[Paper]](https://ojs.aaai.org/index.php/AAAI/article/view/10000) ![](https://img.shields.io/badge/AAAI-2016-blue) [No Code] [No Review]
*   Phrase-Based Presentation Slides Generation for Academic Papers [[Paper]](https://aaai.org/papers/10481-aaai-31-2017/) ![](https://img.shields.io/badge/AAAI-2017-blue) [No Code] [No Review]
*   Towards Topic-Aware Slide Generation For Academic Papers With Unsupervised Mutual Learning [[Paper]](https://ojs.aaai.org/index.php/AAAI/article/view/17564) ![](https://img.shields.io/badge/AAAI-2021-blue) [[Code](https://github.com/daviddwlee84/TopicAwarePaperSlideGeneration?tab=readme-ov-file)] [No Review]
*   D2S: Document-to-Slide Generation Via Query-Based Text Summarization [[Paper]](https://aclanthology.org/2021.naacl-main.111/) ![](https://img.shields.io/badge/NAACL-2021-blue) [[Code](https://github.com/IBM/document2slides)] [No Review]
*   DOC2PPT: Automatic Presentation Slides Generation from Scientific Documents [[Paper]](https://ojs.aaai.org/index.php/AAAI/article/view/19943) ![](https://img.shields.io/badge/AAAI-2022-blue) [No Code] [No Review]
*   PosterBot: A System for Generating Posters of Scientific Papers with Neural Models [[Paper]](https://ojs.aaai.org/index.php/AAAI/article/view/21738) ![](https://img.shields.io/badge/AAAI_Demo-2022-blue) [[Review](https://openreview.net/forum?id=92Q73NYpk4)]
*   Presentations by the Humans and For the Humans: Harnessing LLMs for Generating Persona-Aware Slides from Documents [[Paper]](https://aclanthology.org/2024.eacl-long.163/) ![](https://img.shields.io/badge/EACL-2024-blue) [No Code] [[Review](https://openreview.net/forum?id=jkay-UKF_1)]
*   Enhancing Presentation Slide Generation by LLMs with a Multi-Staged End-to-End Approach [[Paper]](https://aclanthology.org/2024.inlg-main.18/) ![](https://img.shields.io/badge/INLG-2024-blue) [No Code] [No Review]
*   Presentations are not always linear! GNN meets LLM for Text Document-to-Presentation Transformation with Attribution [[Paper]](https://aclanthology.org/2024.findings-emnlp.936/) ![](https://img.shields.io/badge/EMNLP_Findings-2024-blue) [No Code] [No Review]

# ✅ Paper Review

*   Online software spots genetic errors in cancer papers [[Paper]](https://www.nature.com/articles/nature.2017.23003) ![](https://img.shields.io/badge/Nature_News-2017-green) [No Review]
*   Argument Mining for Understanding Peer Reviews [[Paper]](https://aclanthology.org/N19-1219/) ![](https://img.shields.io/badge/NAACL-2019-blue) [No Review]
*   DeepSentiPeer: Harnessing Sentiment in Review Texts to Recommend Peer Review Decisions [[Paper]](https://aclanthology.org/P19-1106/) ![](https://img.shields.io/badge/ACL-2019-blue) [[Code]](https://github.com/rajevv/DeepSentiPeer) [[Review]](https://openreview.net/forum?id=DcSuD6vp6I)
*   Exploring the Potential of GPT-2 for Generating Fake Reviews of Research Papers [[Paper]](https://ebooks.iospress.nl/doi/10.3233/FAIA200717) ![](https://img.shields.io/badge/FAIA@ECAI-2020-blue) [[Code]](https://github.com/allenai/PeerRead) [No Review]
*   Aspect-based Sentiment Analysis of Scientific Reviews [[Paper]](https://dl.acm.org/doi/10.1145/3383583.3398541) ![](https://img.shields.io/badge/JCDL-2020-blue) [[Review]](https://openreview.net/forum?id=r3N6wrQ8WY)
*   ReviewRobot: Explainable Paper Review Generation based on Knowledge Synthesis [[Paper]](https://aclanthology.org/2020.inlg-1.44/) ![](https://img.shields.io/badge/INLG-2020-blue) [[Code]](https://github.com/EagleW/ReviewRobot) [No Review]
*   Uncertainty-aware machine support for paper reviewing on the interspeech 2019 submission corpus [[Paper]](https://www.isca-archive.org/interspeech_2020/stappen20_interspeech.html) ![](https://img.shields.io/badge/Interspeech-2020-blue) [[Code]](https://github.com/TUD-STKS/U-Interspeech19) [No Review]
*   Multi-task Peer-Review Score Prediction [[Paper]](https://aclanthology.org/2020.sdp-1.14/) ![](https://img.shields.io/badge/SDP@EMNLP-2020-blue) [No Review]
*   APE: Argument Pair Extraction from Peer Review and Rebuttal via Multi-task Learning [[Paper]](https://aclanthology.org/2020.emnlp-main.569/) ![](https://img.shields.io/badge/EMNLP-2020-blue) [[Code]](https://github.com/LiyingCheng95/ArgumentPairExtraction) [No Review]
*   Can We Automate Scientific Reviewing? [[Paper]](https://doi.org/10.1613/jair.1.12862) ![](https://img.shields.io/badge/JAIR-2022-blue) [[Code]](https://github.com/neulab/ReviewAdvisor) [No Review]
*   Argument Mining Driven Analysis of Peer-Reviews [[Paper]](https://ojs.aaai.org/index.php/AAAI/article/view/16607) ![](https://img.shields.io/badge/AAAI-2021-blue) [[Code]](https://github.com/fromm-m/aaai2021-am-peer-reviews) [No Review]
*   A Deep Neural Architecture for Decision-Aware Meta-Review Generation [[Paper]](https://ieeexplore.ieee.org/document/9651825) ![](https://img.shields.io/badge/IEEE_Access-2021-green) [[Review]](https://openreview.net/forum?id=1lsfIvyzUW)
*   PEERAssist: Leveraging on Paper-Review Interactions to Predict Peer Review Decisions [[Paper]](https://link.springer.com/chapter/10.1007/978-3-030-91669-5_33) ![](https://img.shields.io/badge/ICONIP-2021-blue) [[Code]](https://github.com/PrabhatkrBharti/PEERAssist) [[Review]](https://openreview.net/forum?id=cooUcim100)
*   HedgePeer: A Dataset for Uncertainty Detection in Peer Reviews [[Paper]](https://ieeexplore.ieee.org/document/9852963) ![](https://img.shields.io/badge/IEEE_Access-2022-green) [[Code]](https://github.com/Tirthankar-Ghosal/HedgePeer-Dataset) [No Review]
*   KID-Review: Knowledge-Guided Scientific Review Generation with Oracle Pre-training [[Paper]](https://doi.org/10.1609/aaai.v36i10.21418) ![](https://img.shields.io/badge/AAAI-2022-blue) [No Code] [No Review] <!-- Code Link Broken in original -->
*   Assessing Scientific Research Papers with Knowledge Graphs [[Paper]](https://dl.acm.org/doi/pdf/10.1145/3477495.3531879) ![](https://img.shields.io/badge/SIGIR-2022-blue) [[Code]](https://github.com/kianasun/kg4rr) [No Review]
*   SciFact-Open: Towards open-domain scientific claim verification [[Paper]](https://arxiv.org/abs/2210.13777) ![](https://img.shields.io/badge/arXiv-2022.10-red?logo=arxiv) [[Data]](https://github.com/kianasun/kg4rr) [[AI Review]](https://ai-researcher.net/abs/2210.13777)
*   The Quality Assist: A Technology-Assisted Peer Review Based on Citation Functions to Predict the Paper Quality [[Paper]](https://doi.org/10.1109/ACCESS.2022.3225871) ![](https://img.shields.io/badge/IEEE_Access-2022-green) [No Code] [No Review]
*   Exploiting Labeled and Unlabeled Data via Transformer Fine-tuning for Peer-Review Score Prediction [[Paper]](https://doi.org/10.18653/v1/2022.findings-emnlp.164) ![](https://img.shields.io/badge/EMNLP_Findings-2022-blue) [[Code]](https://github.com/panitan-m/gamma_trans) [No Review]
*   CARE: Collaborative AI-Assisted Reading Environment [[Paper]](https://arxiv.org/abs/2302.12611v1) ![](https://img.shields.io/badge/arXiv-2023.02-red?logo=arxiv) [[Code]](https://github.com/UKPLab/CARE) [[AI Review]](https://ai-researcher.net/abs/2302.12611)
*   PolitePEER: does peer review hurt? A dataset to gauge politeness intensity in the peer reviews [[Paper]](https://link.springer.com/article/10.1007/s10579-023-09662-3) ![](https://img.shields.io/badge/Scientometrics-2023-green) [[Code]](https://github.com/PrabhatkrBharti/PolitePEER) [No Review]
*   Scientific Fact-Checking: A Survey of Resources and Approaches [[Paper]](https://arxiv.org/abs/2305.16859) ![](https://img.shields.io/badge/arXiv-2023.05-red?logo=arxiv) [[Review]](https://openreview.net/forum?id=vgiLGYyu2v)
*   Scientific Opinion Summarization: Meta-review Generation with Checklist-guided Iterative Introspection [[Paper]](https://arxiv.org/abs/2305.14647) ![](https://img.shields.io/badge/arXiv-2023.05-red?logo=arxiv) [[Code]](https://github.com/Mankeerat/orsum-meta-review-generation) [[Review]](https://openreview.net/forum?id=ZAFJmDqcYI)
*   Gpt4 is slightly helpful for peer-review assistance: A pilot study [[Paper]](https://arxiv.org/abs/2307.05492) ![](https://img.shields.io/badge/arXiv-2023.06-red?logo=arxiv) [[Code]](https://github.com/zrobertson466920/GPT_Auto_Review) [[AI Review]](https://ai-researcher.net/abs/2307.05492)
*   ReviewerGPT? An Exploratory Study on Using Large Language Models for Paper Reviewing [[Paper]](https://arxiv.org/abs/2306.00622) ![](https://img.shields.io/badge/arXiv-2023.06-red?logo=arxiv) [[Code]](https://github.com/niharshah/ReviewerGPT2023) [[AI Review]](https://ai-researcher.net/abs/2306.00622)
*   Unveiling the Sentinels: Assessing AI Performance in Cybersecurity Peer Review [[Paper]](https://arxiv.org/abs/2309.05457) ![](https://img.shields.io/badge/arXiv-2023.09-red?logo=arxiv) [No Code] [[AI Review]](https://ai-researcher.net/abs/2309.05457)
*   ChatGPT and the Future of Journal Reviews: A Feasibility Study [[Paper]](https://pmc.ncbi.nlm.nih.gov/articles/PMC10524821/) ![](https://img.shields.io/badge/Cureus-2023-green) [No Code] [No Review]
*   A Critical Examination of the Ethics of AI-Mediated Peer Review [[Paper]](https://arxiv.org/abs/2309.12356v1) ![](https://img.shields.io/badge/arXiv-2023.09-red?logo=arxiv) [No Code] [[AI Review]](https://ai-researcher.net/abs/2309.12356)
*   Can large language models provide useful feedback on research papers? A large-scale empirical analysis [[Paper]](https://arxiv.org/abs/2310.01783) ![](https://img.shields.io/badge/arXiv-2023.10-red?logo=arxiv) [[Code]](https://github.com/Weixin-Liang/LLM-scientific-feedback) [[AI Review]](https://ai-researcher.net/abs/2310.01783)
*   Automatic Analysis of Substantiation in Scientific Peer Reviews [[Paper]](https://arxiv.org/abs/2311.11967v1) ![](https://img.shields.io/badge/arXiv-2023.11-red?logo=arxiv) [[Data]](https://github.com/YanzhuGuo/SubstanReview) [[Review]](https://openreview.net/forum?id=N6f1iHjWvB¬eId=kaeJzW4m3T)
*   Summarizing Multiple Documents with Conversational Structure for Meta-Review Generation [[Paper]](https://doi.org/10.18653/v1/2023.findings-emnlp.472) ![](https://img.shields.io/badge/EMNLP_Findings-2023-blue) [[Code]](https://github.com/oaimli/PeerSum) [[Review]](https://openreview.net/forum?id=Z7O1kA3pjB¬eId=IBtwHSY7RG)
*   When Reviewers Lock Horn: Finding Disagreement in Scientific Peer Reviews [[Paper]](https://doi.org/10.18653/v1/2023.emnlp-main.1038) ![](https://img.shields.io/badge/EMNLP-2023-blue) [[Code]](https://github.com/sandeep82945/Contradiction-in-Peer-Review) [No Review]
*   PaperMage: A Unified Toolkit for Processing, Representing, and Manipulating Visually-Rich Scientific Documents [[Paper]](https://aclanthology.org/2023.emnlp-demo.45.pdf) ![](https://img.shields.io/badge/EMNLP_Demo-2023-blue) [[Code]](https://github.com/allenai/papermage) [No Review]
*   The Intended Uses of Automated Fact-Checking Artefacts: Why, How and Who [[Paper]](https://aclanthology.org/2023.findings-emnlp.577/) ![](https://img.shields.io/badge/EMNLP_Findings-2023-blue) [[Data]](https://github.com/Cartus/Automated-Fact-Checking-Resources) [[Review]](https://openreview.net/forum?id=SzH7d4617q)
*   Exploring Jiu-Jitsu Argumentation for Writing Peer Review Rebuttals [[Paper]](https://aclanthology.org/2023.emnlp-main.894/) ![](https://img.shields.io/badge/EMNLP-2023-blue) [[Code]](https://github.com/UKPLab/EMNLP2023_jiu_jitsu_argumentation_for_rebuttals) [[Review]](https://openreview.net/forum?id=5IFMe8TuSy)
*   MARG: Multi-Agent Review Generation for Scientific Papers [[Paper]](https://arxiv.org/abs/2401.04259) ![](https://img.shields.io/badge/arXiv-2024.01-red?logo=arxiv) [[Code]](https://github.com/allenai/marg-reviewer) [[AI Review]](https://ai-researcher.net/abs/2401.04259)
*   ReviewFlow: Intelligent Scaffolding to Support Academic Peer Reviewing [[Paper]](https://arxiv.org/abs/2402.03530) ![](https://img.shields.io/badge/arXiv-2024.02-red?logo=arxiv) [No Code] [[AI Review]](https://ai-researcher.net/abs/2402.03530)
*   Reviewer2: Optimizing Review Generation Through Prompt Generation [[Paper]](https://arxiv.org/abs/2402.10886v1) ![](https://img.shields.io/badge/arXiv-2024.02-red?logo=arxiv) [No Code] [[Review]](https://openreview.net/forum?id=RWYxCEbMvy)
*   Emerging plagiarism in peer-review evaluation reports: a tip of the iceberg? [[Paper]](https://link.springer.com/article/10.1007/s11192-024-04960-1) ![](https://img.shields.io/badge/Scientometrics-2024-green) [No Code] [No Review]
*   MetaWriter: Exploring the Potential and Perils of AI Writing Support in Scientific Peer Review [[Paper]](https://doi.org/10.1145/3637371) ![](https://img.shields.io/badge/PACMHCI@CSCW-2024-blue) [No Code] [No Review]
*   How We Refute Claims: Automatic Fact-Checking through Flaw Identification and Explanation [[Paper]](https://dl.acm.org/doi/10.1145/3589335.3651521) ![](https://img.shields.io/badge/TheWebConf-2024-blue) [[Data]](https://github.com/NYCU-NLP-Lab/FlawCheck) [[Review]](https://openreview.net/forum?id=HjEtzRgf44)
*   What Can Natural Language Processing Do for Peer Review? [[Paper]](https://arxiv.org/abs/2405.06563) ![](https://img.shields.io/badge/arXiv-2024.05-red?logo=arxiv) [[Data]](https://github.com/OAfzal/nlp-for-peer-review) [[Review]](https://openreview.net/forum?id=snnsuSbBOe)
*   Monitoring AI-Modified Content at Scale: A Case Study on the Impact of ChatGPT on AI Conference Peer Reviews [[Paper]](https://arxiv.org/abs/2403.07183v2) ![](https://img.shields.io/badge/arXiv-2024.06-red?logo=arxiv) [[Code]](https://github.com/Weixin-Liang/Mapping-the-Increasing-Use-of-LLMs-in-Scientific-Papers) [[Review]](https://openreview.net/forum?id=bX3J7ho18S)
*   RelevAI-Reviewer: A Benchmark on AI Reviewers for Survey Paper Relevance [[Paper]](https://arxiv.org/abs/2406.10294) ![](https://img.shields.io/badge/arXiv-2024.06-red?logo=arxiv) [[Code]](https://github.com/paulohenriquecrs/RelevAI-Reviewer) [[AI Review]](https://ai-researcher.net/abs/2406.10294)
*   Peer Review as A Multi-Turn and Long-Context Dialogue with Role-Based Interactions [[Paper]](https://arxiv.org/abs/2406.05688) ![](https://img.shields.io/badge/arXiv-2024.06-red?logo=arxiv) [[Data]](https://github.com/chengtan9907/ReviewMT) [[Review]](https://openreview.net/forum?id=uV3Gdoq2ez)
*   Automated Peer Reviewing in Paper SEA: Standardization, Evaluation, and Analysis [[Paper]](https://arxiv.org/abs/2407.12857v2) ![](https://img.shields.io/badge/arXiv-2024.07-red?logo=arxiv) [[Code]](https://github.com/ecnu-sea/sea) [[Review]](https://openreview.net/forum?id=ygMjku9x3P)
*   AI-Driven Review Systems: Evaluating LLMs in Scalable and Bias-Aware Academic Reviews [[Paper]](https://arxiv.org/pdf/2408.10365) ![](https://img.shields.io/badge/arXiv-2024.08-red?logo=arxiv) [[Code]](https://github.com/EagleW/ReviewRobot) [[AI Review]](https://ai-researcher.net/abs/2408.10365)
*   GLIMPSE: Pragmatically Informative Multi-Document Summarization for Scholarly Reviews [[Paper]](https://doi.org/10.18653/v1/2024.acl-long.688) ![](https://img.shields.io/badge/ACL-2024-blue) [No Code] [[Review]](https://openreview.net/forum?id=jxxG0Th1f0)
*   Automated Focused Feedback Generation for Scientific Writing Assistance [[Paper]](https://doi.org/10.18653/v1/2024.findings-acl.580) ![](https://img.shields.io/badge/ACL_Findings-2024-blue) [[Code]](https://github.com/ericchamoun/FocusedFeedbackGeneration) [No Review]
*   A sentiment consolidation framework for meta-review generation [[Paper]](https://doi.org/10.18653/v1/2024.acl-long.547) ![](https://img.shields.io/badge/ACL-2024-blue) [[Code]](https://github.com/oaimli/MetaReviewingLogic) [No Review]
*   Missci: Reconstructing Fallacies in Misrepresented Science [[Paper]](https://aclanthology.org/2024.acl-long.240/) ![](https://img.shields.io/badge/ACL-2024-blue) [[Code]](https://github.com/UKPLab/acl2024-missci) [[Review]](https://openreview.net/forum?id=7ZUb34PAy9)
*   The AI Scientist: Towards Fully Automated Open-Ended Scientific Discovery [[Paper]](https://arxiv.org/abs/2408.06292) ![](https://img.shields.io/badge/arXiv-2024.08-red?logo=arxiv) [[Code]](https://github.com/SakanaAI/AI-Scientist) [[AI Review]](https://ai-researcher.net/abs/2408.06292)
*   The emergence of Large Language Models (LLM) as a tool in literature reviews: an LLM automated systematic review [[Paper]](https://arxiv.org/abs/2409.04600v1) ![](https://img.shields.io/badge/arXiv-2024.09-red?logo=arxiv) [No Code] [[AI Review]](https://ai-researcher.net/abs/2409.04600)
*   Language agents achieve superhuman synthesis of scientific knowledge [[Paper]](https://arxiv.org/abs/2409.13740) ![](https://img.shields.io/badge/arXiv-2024.09-red?logo=arxiv) [No Code] [[AI Review]](https://ai-researcher.net/abs/2409.13740)
*   AgentReview: Exploring Peer Review Dynamics with LLM Agents [[Paper]](https://aclanthology.org/2024.emnlp-main.70) ![](https://img.shields.io/badge/EMNLP-2024-blue) [[Code]](https://github.com/Ahren09/AgentReview) [[Review]](https://openreview.net/forum?id=4j9QByagyP)
*   Peer Reviews of Peer Reviews: A Randomized Controlled Trial and Other Experiments [[Paper]](https://arxiv.org/abs/2311.09497) ![](https://img.shields.io/badge/arXiv-2024.11-red?logo=arxiv) [No Code] [[Review]](https://openreview.net/forum?id=13QBO0mPtu)
*   CycleResearcher: Improving Automated Research via Automated Review [[Paper]](https://arxiv.org/abs/2411.00816) ![](https://img.shields.io/badge/arXiv-2024.11-red?logo=arxiv) [[Code]](https://github.com/zhu-minjun/Researcher) [[Review]](https://openreview.net/forum?id=bjcsVLoHYs)
*   On the Rigour of Scientific Writing: Criteria, Analysis, and Insights [[Paper]](https://aclanthology.org/2024.findings-emnlp.380/) ![](https://img.shields.io/badge/EMNLP_Findings-2024-blue) [No Code] [No Review]
*   ResearchTown: Simulator of Human Research Community [[Paper]](https://arxiv.org/abs/2412.17767) ![](https://img.shields.io/badge/arXiv-2024.12-red?logo=arxiv) [[Code]](https://github.com/ulab-uiuc/research-town) [[Review]](https://openreview.net/forum?id=IwhvaDrL39)
*   Prompting LLMs to Compose Meta-Review Drafts from Peer-Review Narratives of Scholarly Manuscripts [[Paper]](https://arxiv.org/abs/2402.15589) ![](https://img.shields.io/badge/arXiv-2025.02-red?logo=arxiv) [[Data]](https://github.com/BridgeAI-Lab/LLM-as-Meta-Reviewer) [[AI Review]](https://ai-researcher.net/abs/2402.15589)
*   Grounding Fallacies Misrepresenting Scientific Publications in Evidence [[Paper]](https://arxiv.org/abs/2408.12812) ![](https://img.shields.io/badge/arXiv-2025.02-red?logo=arxiv) [[Code]](https://github.com/UKPLab/naacl2025-missciplus) [[Review]](https://openreview.net/forum?id=944ahoVisE)
*   Claim Verification in the Age of Large Language Models: A Survey [[Paper]](https://arxiv.org/abs/2408.14317) ![](https://img.shields.io/badge/arXiv-2025.02-red?logo=arxiv) [No Code] [[AI Review]](https://ai-researcher.net/abs/2408.14317)
*   PeerArg: Argumentative Peer Review with LLMs [[Paper]](https://arxiv.org/abs/2409.16813) ![](https://img.shields.io/badge/arXiv-2025.02-red?logo=arxiv) [No Code] [[AI Review]](https://ai-researcher.net/abs/2409.16813)
*   OpenReviewer: A Specialized Large Language Model for Generating Critical Scientific Paper Reviews [[Paper]](https://arxiv.org/abs/2412.11948) ![](https://img.shields.io/badge/arXiv-2025.03-red?logo=arxiv) [[Code]](https://huggingface.co/maxidl/Llama-OpenReviewer-8B) [[AI Review]](https://ai-researcher.net/abs/2412.11948)
*   ReviewAgents: Bridging the Gap Between Human and AI-Generated Paper Reviews [[Paper]](https://arxiv.org/abs/2503.08506) ![](https://img.shields.io/badge/arXiv-2025.03-red?logo=arxiv) [No Code] [[AI Review]](https://ai-researcher.net/abs/2503.08506)
*   DeepReview: Improving LLM-based Paper Review with Human-like Deep Thinking Process [[Paper]](https://arxiv.org/abs/2503.08569) ![](https://img.shields.io/badge/arXiv-2025.03-red?logo=arxiv) [[Code]](https://github.com/zhu-minjun/Researcher) [[AI Review]](https://ai-researcher.net/abs/2503.08569)
*   Enabling Inclusive Systematic Reviews: Incorporating Preprint Articles with Large Language Model-Driven Evaluations [[Paper]](https://arxiv.org/abs/2503.13857) ![](https://img.shields.io/badge/arXiv-2025.03-red?logo=arxiv) [No Code] [[AI Review]](https://ai-researcher.net/abs/2503.13857)
*   Overview of the Context24 Shared Task on Contextualizing Scientific Claims [[Paper]](https://aclanthology.org/2024.sdp-1.3/) ![](https://img.shields.io/badge/SDP@ACL-2024-blue) [No Review]
*   ReviewEval: An Evaluation Framework for AI-Generated Reviews [[Paper]](https://arxiv.org/abs/2502.11736) ![](https://img.shields.io/badge/arXiv-2502.11736-red?logo=arxiv) [No Code] [[AI Review]](https://ai-researcher.net/abs/2502.11736)
*   AgentRxiv: Towards Collaborative Autonomous Research [[Paper]](https://arxiv.org/abs/2503.18102) ![](https://img.shields.io/badge/arXiv-2503.18102-red?logo=arxiv) [[Code]](https://github.com/SamuelSchmidgall/AgentLaboratory) [[AI Review]](https://ai-researcher.net/abs/2503.18102)
*   ResearchBench: Benchmarking LLMs in Scientific Discovery via Inspiration-Based Task Decomposition [[Paper]](http://arxiv.org/abs/2503.21248) ![](https://img.shields.io/badge/arXiv-2025.03-red?logo=arxiv) [No Code] [[AI Review]](https://ai-researcher.net/abs/2503.21248)
*   CLAIMCHECK: How Grounded are LLM Critiques of Scientific Papers? [[Paper]](http://arxiv.org/abs/2503.21717) ![](https://img.shields.io/badge/arXiv-2025.03-red?logo=arxiv) [[Code]](https://github.com/JHU-CLSP/CLAIMCHECK) [[AI Review]](https://ai-researcher.net/abs/2503.21717)
*   CodeScientist: End-to-End Semi-Automated Scientific Discovery with Code-based Experimentation [[Paper]](http://arxiv.org/abs/2503.22708) ![](https://img.shields.io/badge/arXiv-2025.03-red?logo=arxiv) [[Code]](https://github.com/allenai/codescientist) [[AI Review]](https://ai-researcher.net/abs/2503.22708)



# 🏆 Benchmarks

*   **AI2 Scientific Reasoning Challenge (ARC)** [[Dataset]](https://allenai.org/data/arc)
*   **MLAgentBench** [[Paper]](https://arxiv.org/abs/2310.03302) ![](https://img.shields.io/badge/arXiv-2023.10-red?logo=arxiv) [[Code](https://github.com/snap-stanford/MLAgentBench/)]
*   **SWE-bench** [[Paper]](https://openreview.net/forum?id=VTF8yNQM66) ![](https://img.shields.io/badge/ICLR-2024-blue) [[Code](https://github.com/swe-bench/SWE-bench)]
*   **ScienceAgentBench** [[Paper]](https://arxiv.org/abs/2410.05080) ![](https://img.shields.io/badge/arXiv-2024.10-red?logo=arxiv) [[Code](https://github.com/OSU-NLP-Group/ScienceAgentBench)]
*   **DSBench** [[Paper]](https://arxiv.org/abs/2409.07703) ![](https://img.shields.io/badge/arXiv-2024.09-red?logo=arxiv) [[Code](https://github.com/LiqiangJing/DSBench)]
*   **AAAR-1.0** [[Paper]](https://arxiv.org/abs/2410.22394) ![](https://img.shields.io/badge/arXiv-2024.10-red?logo=arxiv)
*   **MLGym** [[Paper]](https://arxiv.org/abs/2502.14499) ![](https://img.shields.io/badge/arXiv-2025.02-red?logo=arxiv) [[Code](https://github.com/facebookresearch/MLGym)]
*   **PaperBench** [[Paper]](https://cdn.openai.com/papers/22265bac-3191-44e5-b057-7aaacd8e90cd/paperbench.pdf) ![](https://img.shields.io/badge/OpenAI_Report-2025-brown) [[Code](https://github.com/openai/preparedness)]

# 🌐 Community

Connect with fellow researchers, share insights, and stay updated!

<!-- omit in toc -->
## 📅 Upcoming Events

We encourage you to get involved! Stay updated on the latest discussions and breakthroughs by joining these community events:

*   **(Upcoming)** **AIResearcher Workshop @ ICLR 2025** 🔥
    *   **Conference:** ![](https://img.shields.io/badge/ICLR-2025-blue)
    *   **Website:** [![Visit Site](https://img.shields.io/badge/Event_Website-blue)](https://ai-researcher.net/social-iclr-2025)

<!-- omit in toc -->
## 💬 Discussion Forums

Join the conversation and exchange ideas in these online communities:

*   **AI Research Discord:** [![Join Discord](https://img.shields.io/badge/Discord-7289DA?style=for-the-badge&logo=discord&logoColor=white)](https://discord.gg/HeubHd6d)
    *   *An active community for general AI research discussions.*

*   **AI Scientist Research Discussion Group:** [![Platform](https://img.shields.io/badge/WeChat-07C160?style=for-the-badge&logo=wechat&logoColor=white)]() <!-- Removed placeholder link -->
    </br>
    <img src="https://raw.githubusercontent.com/ResearAI/Awesome-AI-Scientist/main/img/WeChat%20Group%20QR%20Code.jpg" alt="AI Scientist WeChat Group QR Code" width="150">
    </br>*(Scan QR Code to join. If expired, please contact maintainer via Email: 18856306350@163.com or WeChat: nauhcutnil)*



# 👋 Contributing

We welcome contributions! Please follow this workflow:

1.  **Fork** the repository.
2.  **Create a new branch:** `git checkout -b feature/your-contribution`
3.  **Add or modify resources.** Please try to follow the existing format, including adding conference/journal badges.
4.  **Submit a Pull Request (PR)** with a clear description of your changes.

*For detailed guidelines, please see `CONTRIBUTING.md`.*

# 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
