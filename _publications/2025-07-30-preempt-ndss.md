---
title: "Preempt: Sanitizing Sensitive Prompts for LLMs"
collection: publications
permalink: /publication/2025-07-30-preempt-ndss
excerpt: 'We introduce a cryptographically inspired notion of a prompt sanitizer which transforms an input prompt to protect its sensitive tokens.'
date: 2025-07-30
venue: 'NDSS 2026 (Network and Distributed System Security Symposium)'
---
The rise of large language models (LLMs) has introduced new privacy challenges, particularly during inference where sensitive information in prompts may be exposed to proprietary LLM APIs. In this paper, we address the problem of formally protecting the sensitive information contained in a prompt while maintaining response quality. To this end, first, we introduce a cryptographically inspired notion of a prompt sanitizer which transforms an input prompt to protect its sensitive tokens. Second, we propose Prϵϵmpt, a novel system that implements a prompt sanitizer. Prϵϵmpt categorizes sensitive tokens into two types: (1) those where the LLM's response depends solely on the format (such as SSNs, credit card numbers), for which we use format-preserving encryption (FPE); and (2) those where the response depends on specific values, (such as age, salary) for which we apply metric differential privacy (mDP). Our evaluation demonstrates that Prϵϵmpt is a practical method to achieve meaningful privacy guarantees, while maintaining high utility compared to unsanitized prompts, and outperforming prior methods.

[[Paper](https://arxiv.org/abs/2504.05147)]

<!-- Recommended citation: Your Name, You. (2015). "Paper Title Number 3." <i>Journal 1</i>. 1(3). -->
