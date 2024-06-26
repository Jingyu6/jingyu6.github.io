---
title: Effective Long-Context Scaling of Foundation Models
authors:
  - Wenhan Xiong
  - admin
  - Igor Molybog
  - Hejia Zhang
  - Prajjwal Bhargava
  - Rui Hou
  - Louis Martin
  - Rashi Rungta
  - Karthik Abinav Sankararaman
  - Barlas Oguz
  - Madian Khabsa
  - Han Fang
  - Yashar Mehdad
  - Sharan Narang
  - Kshitiz Malik
  - Angela Fan
  - Shruti Bhosale
  - Sergey Edunov
  - Mike Lewis
  - Sinong Wang
  - Hao Ma
author_notes:
  - "Equal Contribution"
  - "Equal Contribution"
date: '2023-09-27'
publishDate: '2023-09-27'
publication_types:
  - paper-conference
publication: "NAACL 2024 Main Conference"
url_pdf: https://arxiv.org/abs/2309.16039
url_project: https://about.fb.com/news/2023/09/introducing-ai-powered-assistants-characters-and-creative-tools

abstract: "We present a series of long-context LLMs that support effective context windows of up to 32,768 tokens. Our model series are built through continual pretraining from Llama 2 with longer training sequences and on a dataset where long texts are upsampled. We perform extensive evaluation on language modeling, synthetic context probing tasks, and a wide range of research benchmarks. On research benchmarks, our models achieve consistent improvements on most regular tasks and significant improvements on long-context tasks over Llama 2. Notably, with a cost-effective instruction tuning procedure that does not require human-annotated long instruction data, the 70B variant can already surpass gpt-3.5-turbo-16k's overall performance on a suite of long-context tasks. Alongside these results, we provide an in-depth analysis on the individual components of our method. We delve into Llama's position encodings and discuss its limitation in modeling long dependencies. We also examine the impact of various design choices in the pretraining process, including the data mix and the training curriculum of sequence lengths -- our ablation experiments suggest that having abundant long texts in the pretrain dataset is not the key to achieving strong performance, and we empirically verify that long context continual pretraining is more efficient and similarly effective compared to pretraining from scratch with long sequences. "
---
