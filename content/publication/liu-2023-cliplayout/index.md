---
title: 'CLIP-Layout: Style-Consistent Indoor Scene Synthesis with Semantic Furniture
  Embedding'
authors:
  - admin
  - Wenhan Xiong
  - Ian Jones
  - Yixin Nie
  - Anchit Gupta
  - Barlas Oğuz
date: '2023-05-07'
publishDate: '2023-05-07'
publication_types:
  - article
url_pdf: https://arxiv.org/abs/2303.03565

abstract: "Indoor scene synthesis involves automatically picking and placing furniture appropriately on a floor plan, so that the scene looks realistic and is functionally plausible. Such scenes can serve as homes for immersive 3D experiences, or be used to train embodied agents. Existing methods for this task rely on labeled categories of furniture, e.g. bed, chair or table, to generate contextually relevant combinations of furniture. Whether heuristic or learned, these methods ignore instance-level visual attributes of objects, and as a result may produce visually less coherent scenes. In this paper, we introduce an auto-regressive scene model which can output instance-level predictions, using general purpose image embedding based on CLIP. This allows us to learn visual correspondences such as matching color and style, and produce more functionally plausible and aesthetically pleasing scenes. Evaluated on the 3D-FRONT dataset, our model achieves SOTA results in scene synthesis and improves auto-completion metrics by over 50%. Moreover, our embedding-based approach enables zero-shot text-guided scene synthesis and editing, which easily generalizes to furniture not seen during training. "
---
