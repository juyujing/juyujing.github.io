---
layout: archive
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

## Education

- **University of Florida**, Gainesville, FL — PhD program in Biological and Medical Sciences; Master-en-route. Aug 2025 – Jan 2027 (expected). Research focus: AI and large language models.
- **Heriot-Watt University**, Edinburgh, UK — Bachelor's degree in Robotics. Sep 2021 – May 2025. First Class Honours.
- **Ocean University of China**, Qingdao, China — Computer Science. Sep 2021 – May 2024.

## Experience

### Algorithm Engineer Intern — Pharmaron
Beijing, China · Oct 2026 – Present

- Conduct small-model scaling experiments to extrapolate larger-run performance and guide model size, training-token budgets, and compute allocation for pharmaceutical LLMs; target competitive general benchmarks and expert-level domain capabilities.
- Investigate **Engram-augmented MoE scaling laws**, jointly varying active expert parameters, conditional-memory capacity, and training data; study compute–memory allocation under matched parameter and FLOPs budgets.
- Study **constant-time n-gram lookup** and the separation of static knowledge retrieval from neural computation to expand knowledge capacity with limited added compute and preserve neural capacity for reasoning.
- Optimize distributed training with **Megatron-LM, DeepSpeed, and Triton**, combining parameter/optimizer-state sharding, model parallelism, and GPU-kernel optimization for MoE workloads.

### Algorithm Engineer Intern — Hithink RoyalFlush
Hangzhou, China · Aug 2026 – Oct 2026  
**AIME Investment Assistant**

- Applied **GRPO post-training** to AInvest U.S. equity recommendations, combining time-series reasoning, verifiable forecast actions, and explainable stock selection; improved investment-task success by **5–10 percentage points (placeholder; pending validation)**. - Optimized long-horizon agent trajectories for market-data retrieval, evidence synthesis, and tool use; evaluated invalid calls and multi-step task completion, reducing invalid tool-call rate by **17–33% relative (placeholder; pending validation)**. - Designed quantitative stock-selection strategies and paper-trading simulations linking screening, portfolio decisions, and simulated execution; optimized training and rollout with VeRL, DeepSpeed, Megatron-LM, and Slime, reaching **1.2–1.4× baseline throughput (placeholder; pending validation)**.### Research Assistant — University of Florida
Gainesville, FL · Part-time · Aug 2025 – Present

- Conduct research on LLM evaluation, privacy-preserving fine-tuning, retrieval, and multi-agent systems.
- Built EHR privacy and ICD-coding benchmarks with **31,080 QA examples**, **4,440 patient-level samples**, and **1,860 valid ICD labels**.
- Developed an offline data-generation pipeline and distributed model training/evaluation workflows on the HiPerGator B200 cluster.

## Selected Research and Projects

### Asymmetric Feature Optimization for Recommendation
Heriot-Watt University · Sep 2024 – Aug 2025  
Advisor: [Wei Pang](https://researchportal.hw.ac.uk/en/persons/wei-pang)

- Developed Asymmetric Graph Convolution (AsymG), using Finsler geometry to model asymmetric relationships with spatial and spectral variants.
- Integrated AsymG into recommendation models and evaluated ranking performance across five datasets.

### Honours Dissertation: Directed Graph Modeling for Academic Recommendation
Heriot-Watt University · Sep 2024 – May 2025

- Investigated directed and heterogeneous graph structures for academic paper recommendation, preserving citation direction and author–paper relations.
- Evaluated ranking quality using Recall, NDCG, Hit Rate, and Precision@K.

[Project](https://github.com/juyujing/Graduation-Project)

### Group Recommendation
Ocean University of China · Jun 2023 – Jun 2024

- Built a GPU-accelerated multitask hypergraph recommendation system for item and participant prediction.
- Combined sparse graph propagation, gated experts, ranking objectives, and negative sampling.

[Project](https://github.com/juyujing/HyperGCN)

### Biomimetic Hexapod Robot Development
Ocean University of China · Feb 2024 – May 2024

- Designed a hexapod robot for visually guided target capture, integrating object recognition and motion planning.

[Project](https://github.com/juyujing/Capturer)

### Open Source Graph Modeling Library
Florida State University · Research internship, starting Jun 2024

- Integrated graph-based mathematical models and investigated computational efficiency.

[Lab](https://yushundong.github.io//students) · [Project](https://github.com/juyujing/GrOVe)

## Technical Skills

- **Post-training:** SFT, GRPO, RLHF/RLVR, PPO, DPO, SAC; agent trajectories and long-horizon agents.
- **Training frameworks:** PyTorch, VeRL, DeepSpeed, Megatron-LM, Slime, OpenRLHF, LLaMA-Factory, FSDP, LoRA/QLoRA.
- **LLM systems:** RAG, vector retrieval, multi-agent systems, distributed inference, evaluation.
- **Programming and systems:** Python, C++, Java, SQL, NumPy, pandas, Linux, Git, Docker, GPU clusters.
- **Robotics:** ROS, NVIDIA Jetson, STM32, Raspberry Pi, Arduino.

## Honors and Awards

- Innovation and Entrepreneurship Scholarship, 2022
- Outstanding Youth Volunteer Award, 2022
