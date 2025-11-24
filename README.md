<div align="center">

  <h2><b> Entropy Mechanism in RL for LLMs </b></h2>
  <h4> An overview of research in Entropy Mechanism in Reinforcement Learning for Large Language Models</h4>

</div>


</div>

## 👀 Introduction
This repository contains a regularly updated paper list for **Entropy Mechanism in RL for LLMs**.

Reinforcement learning with verifiable rewards (RLVR) has shown great promise in enhancing the reasoning abilities of large language models (LLMs). 
However, RLVR suffers from entropy collapse, causing premature convergence to suboptimal local minima and hinder further performance improvement.
Various approached have been proposed to mitigate entropy collapse, including

**1. Entropy Regularization**: incorporate entropy regularization to encourage exploration.

**2. Entropy-based token clip or advantage modification**: modify token clip stategy or token advantage/reward based on entropy. 


## Updates

- 2025-11-21: 🚀 Entropy Mechanism in RL for LLMs Repo launched!

## 📜Content
- [Keywords Convention](#keywords-convention)
- [Papers](#papers)
    - [Token clip/advantage modification](#Token-clip/advantage-modification)
    - [KL/Entropy Regularization](#(Adaptive)-KL/Entropy-Regularization)
    - [Positive and Negative Sample ](#Positive-&-Negative-Sample )

---

## Keywords Convention

![](https://img.shields.io/badge/Clip--Higher-blue) Main Features

![](https://img.shields.io/badge/AAAI2026-orange) Conference

![](https://img.shields.io/badge/GRPO-lightgray) Abbreviation

## 🚀 Papers

### Token clip/advantage modification

- [DAPO: An Open-Source LLM Reinforcement Learning System at Scale](https://arxiv.org/abs/2503.14476) [[code](https://dapo-sia.github.io/)] ![](https://img.shields.io/badge/abs-2025.03-orange) ![](https://img.shields.io/badge/Clip--Higher-blue) ![](https://img.shields.io/badge/DAPO-lightgray)
- [The Entropy Mechanism of Reinforcement Learning for Reasoning Language Models](https://arxiv.org/abs/2505.22617) [[code](https://github.com/PRIME-RL/Entropy-Mechanism-of-RL)] ![](https://img.shields.io/badge/abs-2025.05-orange) ![](https://img.shields.io/badge/Clip--Cov_&_KL--Cov-blue)
- [Beyond the 80/20 Rule: High-Entropy Minority Tokens Drive Effective Reinforcement Learning for LLM Reasoning](https://arxiv.org/abs/2506.01939) [[code](https://shenzhi-wang.github.io/high-entropy-minority-tokens-rlvr)] ![](https://img.shields.io/badge/NIPS2025-orange)
- [MiniMax-M1: Scaling Test-Time Compute Efficiently with Lightning Attention](https://arxiv.org/abs/2506.13585) [[code](https://github.com/MiniMax-AI/MiniMax-M1)] ![](https://img.shields.io/badge/abs-2025.06-orange) ![](https://img.shields.io/badge/CISPO-lightgray)
- [Reasoning with Exploration: An Entropy Perspective](https://arxiv.org/abs/2506.14758) ![](https://img.shields.io/badge/AAAI2026-orange)
- [Stabilizing Knowledge, Promoting Reasoning: Dual-Token Constraints for RLVR](https://arxiv.org/abs/2507.15778) [[code](https://github.com/wizard-III/ArcherCodeR)] ![](https://img.shields.io/badge/abs-2025.07-orange)
- [GTPO and GRPO-S: Token and Sequence-Level Reward Shaping with Policy Entropy](https://arxiv.org/abs/2508.04349) ![](https://img.shields.io/badge/abs-2025.08-orange) ![](https://img.shields.io/badge/GTPO_&_GRPO--S-lightgray)
- [Harnessing Uncertainty: Entropy-Modulated Policy Gradients for Long-Horizon LLM Agents](https://arxiv.org/abs/2509.09265) [[code](https://empgseed-seed.github.io/)] ![](https://img.shields.io/badge/abs-2025.09-orange) ![](https://img.shields.io/badge/EMPG-lightgray)
- [BAPO: Stabilizing Off-Policy Reinforcement Learning for LLMs via Balanced Policy Optimization with Adaptive Clipping](https://arxiv.org/abs/2510.18927) [[code](https://github.com/WooooDyy/BAPO)] ![](https://img.shields.io/badge/abs-2025.10-orange) ![](https://img.shields.io/badge/BAPO-lightgray)
- [Low-probability Tokens Sustain Exploration in Reinforcement Learning with Verifiable Reward](https://arxiv.org/abs/2510.03222) [[code](https://github.com/CarlanLark/Lp-Reg)] ![](https://img.shields.io/badge/abs-2025.10-orange) ![](https://img.shields.io/badge/Lp--Reg-lightgray)
- [Agentic Entropy-Balanced Policy Optimization](https://arxiv.org/abs/2510.14545) [[code](https://github.com/dongguanting/ARPO)] ![](https://img.shields.io/badge/abs-2025.10-orange) ![](https://img.shields.io/badge/AEPO-lightgray)
- [Revisiting Entropy in Reinforcement Learning for Large Reasoning Models](https://arxiv.org/abs/2511.05993) ![](https://img.shields.io/badge/abs-2025.11-orange)
- [EntroPIC: Towards Stable Long-Term Training of LLMs via Entropy Stabilization with Proportional-Integral Control](https://arxiv.org/abs/2511.15248) [[code](https://github.com/yk7333/EntroPIC)] ![](https://img.shields.io/badge/abs-2025.11-orange) ![](https://img.shields.io/badge/EntroPIC-lightgray)
- [EARL: Entropy-Aware RL Alignment of LLMs for Reliable RTL Code Generation](https://arxiv.org/abs/2511.12033) ![](https://img.shields.io/badge/abs-2025.11-orange) ![](https://img.shields.io/badge/EARL-lightgray)


### KL/Entropy Regularization

- [T1: Advancing Language Model Reasoning through Reinforcement Learning and Inference Scaling](https://arxiv.org/abs/2501.11651) ![](https://img.shields.io/badge/ICML2025-orange) ![](https://img.shields.io/badge/Auxiliary_entropy_bonus-blue)
- [An Empirical Study on Eliciting and Improving R1-like Reasoning Models](https://arxiv.org/abs/2503.04548) ![](https://img.shields.io/badge/abs-2025.03-orange)
- [Skywork Open Reasoner 1 Technical Report](https://arxiv.org/abs/2505.22312) [[code](https://github.com/SkyworkAI/Skywork-OR1)] ![](https://img.shields.io/badge/abs-2025.05-orange) ![](https://img.shields.io/badge/Adaptive_Entropy_Control-blue)
- [ProRL: Prolonged Reinforcement Learning Expands Reasoning Boundaries in Large Language Models](https://arxiv.org/abs/2505.24864) [[code](https://huggingface.co/nvidia/Nemotron-Research-Reasoning-Qwen-1.5B)] ![](https://img.shields.io/badge/abs-2025.05-orange) ![](https://img.shields.io/badge/ProRL-lightgray)


### Positive & Negative Sample 
- [A Minimalist Approach to LLM Reasoning: from Rejection Sampling to Reinforce](https://arxiv.org/abs/2504.11343) ![](https://img.shields.io/badge/abs-2025.04-orange) ![](https://img.shields.io/badge/Reinforce--Rej-lightgray)
- [The Surprising Effectiveness of Negative Reinforcement in LLM Reasoning](https://arxiv.org/abs/2506.01347) [[code](https://github.com/TianHongZXY/RLVR-Decomposed)] ![](https://img.shields.io/badge/NIPS2025-orange) ![](https://img.shields.io/badge/PSR_&_NSR-lightgray)
- [Quantile Advantage Estimation for Entropy-Safe Reasoning](https://arxiv.org/abs/2509.22611) [[code](https://github.com/junkangwu/QAE)] ![](https://img.shields.io/badge/abs-2025.09-orange) ![](https://img.shields.io/badge/QAE-lightgray)
