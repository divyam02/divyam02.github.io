---
title: "How Not to Detect Prompt Injections with an LLM"
collection: publications
permalink: /publication/2025-08-01-how-not-to-aisec
excerpt: 'Recent defenses based on known-answer detection (KAD) have achieved near-perfect performance by using an LLM to classify inputs as clean or contaminated. In this work, we formally characterize the KAD framework and uncover a structural vulnerability in its design that invalidates its core security premise.'
date: 2025-08-01
venue: 'AISec 2025 (18th ACM Workshop on Artificial Intelligence and Security)'
---
LLM-integrated applications and agents are vulnerable to prompt injection attacks, in which adversaries embed malicious instructions within seemingly benign user inputs to manipulate the LLM's intended behavior. Recent defenses based on known-answer detection (KAD) have achieved near-perfect performance by using an LLM to classify inputs as clean or contaminated. In this work, we formally characterize the KAD framework and uncover a structural vulnerability in its design that invalidates its core security premise. We design a methodical adaptive attack, DataFlip, to exploit this fundamental weakness. It consistently evades KAD defenses with detection rates as low as 1.5% while reliably inducing malicious behavior with success rates of up to 88%, without needing white-box access to the LLM or any optimization procedures.

[[Paper](https://arxiv.org/abs/2507.05630)]

<!-- Recommended citation: Your Name, You. (2015). "Paper Title Number 3." <i>Journal 1</i>. 1(3). -->
