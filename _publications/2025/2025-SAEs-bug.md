---
title:          "Are Sparse Autoencoders Useful for Java Function Bug Detection?"
date:           2025-05-15 00:01:00 +0800
selected:       false
pub:            "arXiv preprint arXiv:2505.10375"
pub_date:       "2025"
abstract: >-
  Software vulnerabilities such as buffer overflows and SQL injections are a major source of security breaches. Traditional methods for vulnerability detection remain essential but are limited by high false positive rates, scalability issues, and reliance on manual effort. These constraints have driven interest in AI-based approaches to automated vulnerability detection and secure code generation. While Large Language Models (LLMs) have opened new avenues for classification tasks, their complexity and opacity pose challenges for interpretability and deployment. Sparse Autoencoders offer a promising solution to this problem. We explore whether SAEs can serve as a lightweight, interpretable alternative for bug detection in Java functions. We evaluate the effectiveness of SAEs when applied to representations from GPT-2 Small and Gemma 2B, examining their capacity to highlight buggy behaviour without fine-tuning the underlying LLMs. We found that SAE-derived features enable bug detection with an F1 score of up to 89%, consistently outperforming fine-tuned transformer encoder baselines. Our work provides the first empirical evidence that SAEs can be used to detect software bugs directly from the internal representations of pretrained LLMs, without any fine-tuning or task-specific supervision.
cover:          /assets/images/covers/arxiv.png
authors:
  - Rui Melo
  - Claudia Mamede
  - Andre Catarino
  - Rui Abreu
  - Henrique Lopes Cardoso
---

[arXiv:2505.10375 (submitted on 15 May 2025)](https://arxiv.org/abs/2505.10375)
