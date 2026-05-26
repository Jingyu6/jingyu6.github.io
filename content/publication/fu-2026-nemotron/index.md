---
title: "Nemotron-Labs-Diffusion: A Tri-Mode Language Model Unifying Autoregressive, Diffusion, and Self-Speculation Decoding"
authors:
  - Yonggan Fu
  - Lexington Whalen
  - Abhinav Garg
  - Chengyue Wu
  - Maksim Khadkevich
  - Nicolai Oswald
  - Enze Xie
  - Daniel Egert
  - Sharath Turuvekere Sreenivas
  - Shizhe Diao
  - Chenhan Yu
  - Ye Yu
  - Weijia Chen
  - Sajad Norouzi
  - admin
  - Shiyi Lan
  - Ligeng Zhu
  - Jin Wang
  - Jindong Jiang
  - Morteza Mardani
  - Mehran Maghoumi
  - Song Han
  - Ante Jukić
  - Nima Tajbakhsh
  - Jan Kautz
  - Pavlo Molchanov
date: '2026-05-19'
publishDate: '2026-05-19'
publication_types:
  - report
publication: "Nvidia Research"
url_pdf: https://d1qx31qr3h6wln.cloudfront.net/publications/Nemotron_Diffusion_Tech_Report.pdf?VersionId=1tm4XZATEzGV7cs51XAf.xmWupU20vYW
url_project: https://research.nvidia.com/publication/2026-05_nemotron-labs-diffusion-tri-mode-language-model-unifying-autoregressive

abstract: "We introduce Nemotron-Labs-Diffusion, a tri-mode language model (LM) that unifies AR, diffusion, and self-speculation decoding within a single architecture. Trained with a joint AR-diffusion objective, NemotronLabs-Diffusion can switch modes to sustain high throughput across deployment settings and concurrency levels. Our study shows that (1) AR and diffusion objectives are complementary: diffusion improves lookahead planning, while AR provides left-to-right linguistic priors. (2) In self-speculation mode, diffusion drafts while AR verifies, outperforming multi-token prediction (MTP) methods in both acceptance rate and real-device efficiency. (3) A speed-of-light analysis further demonstrates diffusion’s long-term potential, with up to 76.5% more tokens per forward pass than self-speculation under an optimal sampler. Scaling to 3B, 8B, and 14B parameters, our Nemotron-Labs-Diffusion family, including base, instruct, and vision-language models, consistently outperforms state-of-the-art open-source AR and diffusion LMs in both accuracy and speed. For example, Nemotron-Labs-Diffusion-8B decodes 6× more tokens per forward than Qwen3-8B with comparable accuracy, translating to 4× higher throughput on SPEED-Bench with SGLang on a GB200 GPU."
---
