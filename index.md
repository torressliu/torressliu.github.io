---
layout: homepage
---

<h1 id="about-me"></h1>

<h2 style="margin: 60px 0px 10px;">Short Bio.</h2>

I am a Ph.D. candidate in Artificial Intelligence at the Hong Kong University of Science and Technology (ECE Department), advised by Prof. Ling Pan. I am honored to maintain deep research collaborations with Prof. Aaron Courville (Mila, co-author of the Deep Learning textbook) and Prof. Pablo Samuel Castro (DeepMind), with whom I investigate fundamental limitations of reinforcement learning through mechanistic analysis. 


I am particularly interested in demystifying the internal mechanisms and fundamental limitations of RL, and in broadening its applicability to new domains. Currently, I focus on RL-driven fine-tuning of large foundation models, aiming to develop more efficient, stable, and capable alignment methods for next-generation AI systems. Examples include RL algorithms adapted to advanced model architectures, and RL algorithm optimization adapted to large-scale Infra.

## Call for Collaborators: Building the Next Generation of Efficient RL Systems
Join our mission to reimagine reinforcement learning for foundation models—where simplicity outperforms complexity.
Are you frustrated by RL4LLM pipelines that layer redundant techniques without measurable gains? Do you believe alignment algorithms should be understandable, not just empirically tuned? Our team is assembling researchers who share a conviction: the future of RL lies in mechanistic insight.

### We're seeking collaborators who:
- Investigate RL failure modes (e.g., plasticity loss, reward hacking, sunk cost fallacy) with rigorous diagnostics.
- Design parameter- and data-efficient RL algorithms
- Explore implicit multi-agent dynamics within single models (e.g., mini-critics, internal debate heads) to avoid test-time overhead
- Study diverse generation processes with an emphasis on scalability and theoretical grounding.
- Prioritize reproducibility through clean codebases, ablation-driven validation, and transparent hyperparameter reporting.

### Why collaborate with us?
- Theory-meets-practice culture: We publish at top venues (NeurIPS/ICML/ICLR) while shipping algorithms into production (e.g., Alibaba...).
- Cross-institutional network: Active ties with Mila (Montreal), HKUST, and Deepmind—enabling both theoretical depth and real-world validation.

### Current frontiers we're exploring:
- RL architecture: Rethinking actor-critic training dynamics and credit assignment  
- Agentic RL: Algorithms for multi-turn tool-use and interactive workflows
- Continuous learning RL: Self-evolving agent systems; plasticity-aware training to escape suboptimal policies
- Asynchronous RL at scale: Training stability under off-policy data streams for agentic workflows

Beginner-friendly: If you're interested in RL but lack extensive experience—don't worry! We provide fine-grained, intensive guidance to help you contribute meaningfully.

→ Reach out: <a href="mailto:ljshasdream@gmail.com">ljshasdream@gmail.com</a>


## News
- **[Jan. 2026]** Paper "Tricks or Traps? A Deep Dive into RL for LLM Reasoning" (first technical report from Alibaba Future Living Lab (ROLL team)) and "Asymmetric Proximal Policy Optimization: mini-critics boost LLM reasoning" accepted to ICLR 2026.
- **[Jan. 2026]** "The Rank and Gradient Lost in Non-stationarity: Sample Weight Decay for Mitigating Plasticity Loss in Reinforcement Learning" accepted to ICLR 2026.
- **[Sep. 2025]** "Measure gradients, not activations! Enhancing neuronal activity in deep reinforcement learning" and "Learning Intractable Multimodal Policies with Reparameterization and Diversity Regularization" accepted to NeurIPS 2025.
- **[May 2025]** "The Courage to Stop: Overcoming Sunk Cost Fallacy in Deep Reinforcement Learning" accepted to ICML 2025.
- **[Mar. 2025]** Join Alibaba Future Living Lab.
- **[Jan. 2025]** "Neuroplastic Expansion in Deep Reinforcement Learning" accepted to ICLR 2025.
- **[Dec. 2024]** "Flow Factorization for Efficient Generative Flow Networks" accepted as Oral presentation (<5%) at AAAI 2025.

## Selected Publications

### Large Foundation Model

1. **Tricks or Traps? A Deep Dive into RL for LLM Reasoning**<br />
   Technical Report, Alibaba Future Living Lab (ROLL team)<br />
   Co-first author. First algorithmic technical report from ROLL team analyzing RL4LLM over-engineering.

2. **Asymmetric Proximal Policy Optimization: mini-critics boost LLM reasoning**<br />
   Technical Report, Alibaba Future Living Lab (ROLL team)<br />
   First author. Designed mini-critic architecture for implicit multi-agent debate within single-agent RL.

3. **Let It Flow: Agentic Crafting on Rock and Roll**<br />
   Technical Report, Alibaba Future Living Lab (ROLL team)<br />
   Core contributor. First open agentic model training pipeline (ROME Model) from ROLL team.

4. **Accelerating RLVR and Agentic Training with Asynchrony**<br />
   Technical Report, Alibaba Future Living Lab (ROLL team)<br />
   Contributor. Asynchronous post-training infrastructure (RoLL framework).

### Deep Reinforcement Learning

5. **Measure gradients, not activations! Enhancing neuronal activity in deep reinforcement learning**<br />
   NeurIPS 2025<br />
   Jiashun Liu, Zihao Wu, Johan Obando-Ceron, Pablo Samuel Castro, Aaron Courville, Ling Pan

6. **The Courage to Stop: Overcoming Sunk Cost Fallacy in Deep Reinforcement Learning**<br />
   ICML 2025<br />
   Jiashun Liu, Johan Obando-Ceron, Aaron Courville, Pablo Samuel Castro, Ling Pan

7. **Neuroplastic Expansion in Deep Reinforcement Learning**<br />
   ICLR 2025<br />
   Jiashun Liu, Johan Obando-Ceron, Aaron Courville, Ling Pan

8. **Flow Factorization for Efficient Generative Flow Networks**<br />
   AAAI 2025 (Oral, <5%)<br />
   Jiashun Liu, Chunhui Li, Cheng-Hao Liu, Dianbo Liu, Qingpeng Cai, Ling Pan

9. **Unlock the Intermittent Control Ability of Model Free Reinforcement Learning**<br />
   NeurIPS 2024<br />
   Jiashun Liu, Xiaotian Hao, Jianye Hao, Yi Ma, Yan Zheng, Yujing Hu, Tangjie Lv

10. **Unlock the Cognitive Generalization of Deep Reinforcement Learning via Granular Ball Representation**<br />
    ICML 2024<br />
    Jiashun Liu, Jianye Hao†, Yi Ma, Shuyin Xia†

11. **Hybrid CtrlFormer: Learning Adaptive Search Space Partition for Hybrid Action Control**<br />
    UAI 2024<br />
    Jiashun Liu, Xiaotian Hao, Yan Zheng, Jianye Hao†, Yujing Hu, Changjie Fan, Tangjie Lv, Zhipeng Hu


{% include_relative _includes/services.md %}

{% include_relative _includes/contact.md %}
