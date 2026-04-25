---
# the default layout is 'page'
icon: fas fa-info-circle
order: 4
---

Hi, I'm **Zhaoting Yang**, a Ph.D. researcher at the **Institute of Information Engineering, Chinese Academy of Sciences**. My work focuses on machine learning, retrieval and ranking, agent systems, and data-driven AI applications. I am particularly interested in privacy and security problems in large language models and agent systems, as well as building methods that are empirically grounded and practical to evaluate.

My recent work includes agent benchmarks and adaptive recovery, trajectory filtering for Agentic RL, weak supervision for enterprise email risk detection, retrieval systems for long-form legal documents, and cross-sectional quantitative research with factor modeling and machine learning.

## Education

### Institute of Information Engineering, Chinese Academy of Sciences
*Ph.D. in Intelligent Cognitive Security* | Sep 2025 - Present  
Major GPA: **3.92/4.0**

### University of Chinese Academy of Sciences
*B.S. in Cyber Security* | Sep 2021 - Jun 2025  
Major GPA: **3.74/4.0**

## Core Strengths

- **Programming:** Python, SQL, C, Linux, Git
- **Machine Learning:** scikit-learn, LightGBM, PyTorch, weak supervision, distillation, domain adaptation
- **NLP, Retrieval, and LLM Systems:** BM25, dense retrieval, reranking, long-document processing, retrieval-augmented generation, prompt-based labeling, LoRA fine-tuning, tool-use workflows, evaluation and failure analysis
- **Quantitative Research:** factor engineering, cross-sectional prediction, rolling validation, backtesting, robustness analysis
- **Data and Experimentation:** data cleaning, feature engineering, ablation studies, error analysis, reproducible pipelines
- **Certifications:** CFA Level I Passed
- **Languages:** English (Professional Working Proficiency, IELTS 7.0)

## Selected Projects

### Cross-Sectional Quant Research Pipeline
*Feb 2026 - May 2026*

- Built a research-oriented quantitative pipeline for U.S. equities using daily OHLCV data, covering data ingestion, dynamic universe construction, feature generation, rolling training, portfolio backtesting, and report generation.
- Designed cross-sectional factor features from momentum, volatility, volume-price interaction, and technical indicators, and compared Ridge and LightGBM under rolling and expanding validation schemes for 5-day return and excess return prediction.
- Implemented Top-K, decile, and long-short portfolio construction with transaction cost assumptions, execution analysis, capacity checks, drawdown analysis, and parameter sensitivity studies.
- Added experiment tracking, robustness analysis, and automated markdown reporting to support reproducible research and systematic result comparison.

### Agentic Reinforcement Learning for Code Task Trajectory Filtering
*Dec 2025 - Feb 2026*

- Reproduced an Agentic RL training and evaluation workflow for code-generation tasks based on Open-AgentRL, with a focus on low-quality rollout filtering in multi-step interaction settings.
- Designed trajectory quality rules to detect repeated actions, ineffective execution, and abnormally long trajectories, and used filtering and reweighting to reduce noisy training signals.
- Built baseline, full-filtering, and single-rule ablation experiments to measure the contribution of different filtering rules on policy learning.
- Improved task success rate on **LiveCodeBench code_generation_lite** from **22.83%** to **27.41%**, while reducing average trajectory length by **13.2%**.

### Evaluable Agent Benchmark & Adaptive Recovery Framework
*Oct 2025 - Dec 2026*

- Designed **AutoToolBench**, an offline benchmark covering **24 complex enterprise-style tasks** with strict validation based on outputs such as SQL results, logs, and file structures.
- Built a closed-loop adaptive framework with perceive, plan, execute, reflect, and replan stages.
- Introduced patch-and-replan recovery strategies and dynamic budget control to balance task success with execution cost.
- Improved complex task success rate from **25%** to **88%** under deterministic noise injection and tight execution budgets.

### Enterprise Email Risk Taxonomy & Domain Adaptation
*Jun 2025 - Sep 2025*

- Processed **24,000 heterogeneous unlabeled enterprise email logs** to build a **5-class** risk identification task covering phishing, impersonation, malicious links, and attachments.
- Designed structured prompting for weak supervision, combined with manual review and multi-teacher consensus to iteratively construct silver and gold datasets.
- Explored LLM-to-Transformer soft-label distillation and identified a weak distillation setting that improved generalization without amplifying long-tail noise.
- Achieved a **5% Macro-F1 improvement** over a multilingual BERT baseline while maintaining efficient deployment potential.

### Optimized RAG System for Legal Documents
*Dec 2024 - Mar 2025*

- Built an end-to-end RAG pipeline for **12,000+ Chinese legal documents**, covering PDF parsing, structured chunking, knowledge indexing, retrieval, and answer generation.
- Designed document-structure-aware chunking and context processing to preserve evidence integrity in long legal texts.
- Compared raw versus processed contexts and extractive baselines versus LLM generation through task-specific evaluation and error analysis.
- Verified that processed contexts delivered consistent gains, with LLM-based generation on processed contexts achieving the strongest overall performance.

## Honors

- **Outstanding Teaching Assistant**, Database Systems & Security (based on openGauss), Fall 2025-2026
- **Outstanding Communist Youth League Member**, UCAS, 2024-2025

## What I Am Looking For

I am most interested in roles where I can contribute to:

- **Machine Learning / Algorithm Engineering**
- **Research Engineering**
- **Applied AI Systems**
- **Quantitative Research Engineering**

I am especially interested in roles involving one or more of the following:

- data-centric modeling and evaluation
- retrieval, ranking, and knowledge-intensive systems
- robust LLM applications and agent workflows
- quantitative modeling, backtesting, and systematic experimentation
- research-to-engineering collaboration in high-standard teams

---
Feel free to reach out via [Email](mailto:yangzhaoting21@gmail.com) or connect with me on [LinkedIn](https://www.linkedin.com/in/zhaoting-yang).
