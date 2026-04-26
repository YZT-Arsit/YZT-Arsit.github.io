---
icon: fas fa-file-lines
order: 1
---

# Resume

## Summary

Ph.D. researcher at the Institute of Information Engineering, Chinese Academy of Sciences. My current work focuses on privacy and security for large language models and agent systems, with a growing interest in machine learning, retrieval and ranking, agent systems, and data-driven AI applications. I am interested in roles related to machine learning, research engineering, applied AI systems, and quantitative research engineering.

## Contact

- Email: [yangzhaoting21@gmail.com](mailto:yangzhaoting21@gmail.com)
- GitHub: [YZT-Arsit](https://github.com/YZT-Arsit)
- LinkedIn: [zhaoting-yang](https://www.linkedin.com/in/zhaoting-yang)
- Phone: `195-2562-4331`

## Education

### Institute of Information Engineering, Chinese Academy of Sciences
*Ph.D. in Intelligent Cognitive Security* | Sep 2025 - Present

- Major GPA: **3.92/4.0**
- Outstanding Teaching Assistant for Database Systems & Security based on openGauss, Fall 2025-2026

### University of Chinese Academy of Sciences
*B.S. in Cyber Security* | Sep 2021 - Jun 2025

- Major GPA: **3.74/4.0**

## Skills

- **Programming:** Python, SQL, C, Linux, Git
- **Frameworks and Tools:** PyTorch, scikit-learn, LightGBM, Pandas, NumPy, HuggingFace
- **Machine Learning:** weak supervision, distillation, domain adaptation, classification, ranking, model evaluation
- **NLP, Retrieval, and LLM Systems:** BM25, dense retrieval, reranking, long-document processing, retrieval-augmented generation, prompt-based labeling, LoRA fine-tuning, tool-use workflows
- **Quantitative Research:** factor engineering, cross-sectional prediction, rolling validation, backtesting, robustness analysis
- **Experimentation:** ablation studies, error analysis, reproducible pipelines, robustness testing
- **Certification:** CFA Level I Passed

## Selected Projects

### Cross-Sectional Quant Research Pipeline
*Feb 2026 - May 2026*

- Built a research-oriented quantitative pipeline for U.S. equities using daily OHLCV data, covering data ingestion, dynamic universe construction, feature generation, rolling training, portfolio backtesting, and report generation.
- Designed cross-sectional factor features from momentum, volatility, volume-price interaction, and technical indicators, and compared Ridge and LightGBM under rolling and expanding validation schemes for 5-day return and excess return prediction.
- Implemented Top-K, decile, and long-short portfolio construction with transaction cost assumptions, execution analysis, capacity checks, drawdown analysis, and parameter sensitivity studies.
- Added experiment tracking, robustness analysis, and automated markdown reporting to support reproducible research and systematic result comparison.

### Multi-Asset ETF Trend Following & Risk Allocation
*Feb 2026 - May 2026*

- Built a multi-asset ETF research pipeline covering data ingestion, time-series trend signal generation, risk allocation, backtesting, baseline comparison, parameter sweep, regime analysis, and report generation.
- Implemented momentum, moving-average crossover, breakout, and risk-adjusted momentum signals, and compared equal weight, inverse volatility, and risk parity allocation methods.
- Used the project as a complementary implementation to the cross-sectional equity selection pipeline, covering time-series momentum and multi-asset allocation research.

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

## Research Interests

- privacy and security for large language models
- privacy protection for agent systems
- machine learning and research engineering
- retrieval, ranking, and knowledge-intensive AI systems
- evaluation and robustness of complex AI workflows
- quantitative modeling and systematic experimentation

## Honors and Activities

- **Outstanding Teaching Assistant**, Database Systems & Security (based on openGauss), 2025-2026
- **Outstanding Communist Youth League Member**, UCAS, 2024-2025
