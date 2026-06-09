---
permalink: /
title: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a Ph.D. student in the [Programming Languages Lab](https://pl.cs.pku.edu.cn/) at [Peking University](https://www.pku.edu.cn/). My research focuses on explainable and trustworthy AI, especially model-agnostic local explanation methods for modern machine learning systems and large language models.

Recently, I have been working on making interpretability more practical: reducing the cost of explaining black-box LLMs, accelerating rule-based explanations, and turning explanations into actionable tools for model and prompt optimization.

## Recent Publications

- **Focus-LIME: Surgical Interpretation of Long-Context Large Language Models via Proxy-Based Neighborhood Selection**<br>
  **IJCAI-ECAI 2026**. Second author.<br>
  We propose a coarse-to-fine framework that uses a proxy model to select an optimized neighborhood for faithful, fine-grained explanations of long-context large language models.<br>
  [[Paper](/files/focus-lime.pdf)] [[arXiv](https://arxiv.org/abs/2602.04607)]

- **MAnchors: Memorization-Based Acceleration of Anchors via Rule Reuse and Transformation**  
  **ICML 2026**. First author.  
  We propose a memorization-based acceleration framework for Anchors, reusing and transforming previously generated rules to reduce explanation time while preserving fidelity and understandability.  
  [[Paper](/files/icml2026_MAnchors.pdf)]

- **Revitalizing Black-Box Interpretability: Actionable Interpretability for LLMs via Proxy Models**  
  **ACL 2026**. Second author.  
  We introduce a budget-friendly proxy framework for LLM interpretability, using efficient models plus a statistical screen-and-apply mechanism to approximate expensive black-box explanations and support prompt compression and poisoned example removal.  
  [[Paper](/files/ACL2026_XLLM_Budget.pdf)] [[Code & Data](https://github.com/outerform/XLLM-Bench)]
