---
title: 'Scaling Beyond Masked Diffusion Language Models'
authors:
  - Subham Sekhar Sahoo
  - Jean-Marie Lemercier
  - Zhihan Yang
  - Justin Deschenaux
  - admin
  - John Thickstun
  - Ante Jukic
  
author_notes:
  - ""
  - "Joint second author"
  - "Joint second author"
  - "Joint second author"
  - ""
  - ""
  - ""
  
date: '2026-02-17'
publishDate: '2026-02-17'
publication_types:
  - paper-conference
publication_types:
  - arxiv
publication: "Preprint"
url_pdf: https://arxiv.org/abs/2602.15014
url_project: https://s-sahoo.com/scaling-dllms

abstract: "Diffusion language models are a promising alternative to autoregressive models due to their potential for faster generation. Among discrete diffusion approaches, Masked diffusion currently dominates, largely driven by strong perplexity on language modeling benchmarks. In this work, we present the first scaling law study of uniform-state and interpolating discrete diffusion methods. We also show that Masked diffusion models can be made approximately 12% more FLOPs-efficient when trained with a simple cross-entropy objective. We find that perplexity is informative within a diffusion family but can be misleading across families, where models with worse likelihood scaling may be preferable due to faster and more practical sampling, as reflected by the speed-quality Pareto frontier. These results challenge the view that Masked diffusion is categorically the future of diffusion language modeling and that perplexity alone suffices for cross-algorithm comparison. Scaling all methods to 1.7B parameters, we show that uniform-state diffusion remains competitive on likelihood-based benchmarks and outperforms autoregressive and Masked diffusion models on GSM8K, despite worse validation perplexity. "
---
