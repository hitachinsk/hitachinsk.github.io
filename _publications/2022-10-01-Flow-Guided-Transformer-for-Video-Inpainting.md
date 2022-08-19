---
title: "Flow-Guided Transformer for Video Inpainting"
collection: publications
permalink: /publication/2022-10-01-Flow-Guided-Transformer-for-Video-Inpainting
authors: <b>Kaidong Zhang</b>, Jingjing Fu, Dong Liu
date: 2022-10-20
excerpt: 'We first integrate the philosophy of flow-guided method to transformer for video inpainting with reasonable structure and detailed texture simultaneously. We exploit the local correlation of motion fields and adopt the motion discrepancy in the completed flows to guide the transformer-based content synthesis. We also design elaborated window-partition and spatial-temporal decoupled transformer strategy for the balance between efficiency and performance.'
venue: 'In the proceedings of European Conference on Computer Vision (ECCV)'
citation: ' Kaidong Zhang,  Jingjing Fu,  Dong Liu, &quot;Flow-Guided Transformer for Video Inpainting.&quot; In the proceedings of European Conference on Computer Vision (ECCV), 2022.'
---

### Demo Video
[![FGT-demo](https://res.cloudinary.com/marcomontalbano/image/upload/v1660879749/video_to_markdown/images/youtube--BC32n-NncPs-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://www.youtube.com/watch?v=BC32n-NncPs&t=8s "FGT-demo")

### Abstract
We propose a flow-guided transformer, which innovatively leverage the motion discrepancy exposed by optical flows to instruct the attention retrieval in transformer for high fidelity video inpainting. More specially, we design a novel flow completion network to complete the corrupted flows by exploiting the relevant flow features in a local temporal window. With the completed flows, we propagate the content across video frames, and adopt the flow-guided transformer to synthesize the rest corrupted regions. We decouple transformers along temporal and spatial dimension, so that we can easily integrate the locally relevant completed flows to instruct spatial attention only. Furthermore, we design a flow-reweight module to precisely control the impact of completed flows on each spatial transformer. For the sake of efficiency, we introduce window partition strategy to both spatial and temporal transformers. Especially in spatial transformer, we design a dual perspective spatial MHSA, which integrates the global tokens to the window-based attention. Extensive experiments demonstrate the effectiveness of the proposed method qualitatively and quantitatively.

### Links
[Paper](https://arxiv.org/abs/2208.06768) / Supplementary / [Codes](https://github.com/hitachinsk/FGT) / Keynotes / Demo (Bilibili)

[![star](https://img.shields.io/github/stars/hitachinsk/FGT?style=social)]((https://github.com/hitachinsk/FGT)

<iframe style="width:100%;height:auto;min-width:600px;min-height:400px;" src="https://star-history.com/embed?secret=Z2hwX1BGZjQ4ODh2QzJoVm5MMjlMS2Qwazc5TWNnTGszdzRhYXdWYg==#hitachinsk/FGT&Date" frameBorder="0"></iframe>

### Bibtex
