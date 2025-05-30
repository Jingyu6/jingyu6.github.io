---
title: "Speculative Prefill: Turbocharging TTFT with Lightweight and Training-Free Token Importance Estimation"
authors:
  - Jingyu Liu
  - Beidi Chen
  - Ce Zhang
date: '2025-02-05'
publishDate: '2025-02-05'
publication_types:
  - paper-conference
publication_types:
  - arxiv
publication: "ICML 2025"
url_pdf: https://arxiv.org/abs/2502.02789
url_project: https://github.com/Jingyu6/speculative_prefill

abstract: "Improving time-to-first-token (TTFT) is an essentially important objective in modern large language model (LLM) inference engines. Because optimizing TTFT directly results in higher maximal QPS and meets the requirements of many critical applications. However, boosting TTFT is notoriously challenging since it is purely compute-bounded and the performance bottleneck shifts from the self-attention to the MLP part. We present SpecPrefill, a training free framework that accelerates the inference TTFT for both long and medium context queries based on the following insight: LLMs are generalized enough to still preserve the quality given only a carefully chosen subset of prompt tokens. At its core, SpecPrefill leverages a lightweight model to speculate locally important tokens based on the context. These tokens, along with the necessary positional information, are then sent to the main model for processing. We evaluate SpecPrefill with a diverse set of tasks, followed by a comprehensive benchmarking of performance improvement both in a real end-to-end setting and ablation studies. SpecPrefill manages to serve Llama-3.1-405B-Instruct-FP8 with up to 7× maximal end-to-end QPS on real downstream tasks and 7.66× TTFT improvement during benchmarking."
---
