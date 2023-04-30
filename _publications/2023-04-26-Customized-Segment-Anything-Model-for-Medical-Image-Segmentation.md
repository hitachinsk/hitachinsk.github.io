---
title: "Customized Segment Anything Model for Medical Image Segmentation"
collection: publications
permalink: /publication/2023-04-26-Customized-Segment-Anything-Model-for-Medical-Image-Segmentation
authors: <b>Kaidong Zhang</b>, Dong Liu
date: 2023-04-26
excerpt: 'We propose SAMed, which firstly adopt Segment Anything Model (SAM) in medical image semantic segmentation. In consideration of performance, deployment and storage overhead comprehensively, we adopt low rank approximation technology to customize a small fraction of parameters in image encoder of SAM. With the finetuning of mask decoder and the prompt encoder and a series training strategies, we achieve highly competitive performance on Synapse multi-organ segmentation dataset.'
venue: 'Arxiv preprint, 2023'
citation: ' Kaidong Zhang, Dong Liu, &quot;Customized Segment Anything Model for Medical Image Segmentation.&quot; Arxiv preprint, 2023.'
---

### Abstract
We propose SAMed, a general solution for medical image segmentation. Different from the previous methods, SAMed is built upon the
large-scale image segmentation model, Segment Anything Model (SAM),
to explore the new research paradigm of customizing large-scale models for medical image segmentation. SAMed applies the low-rank-based
(LoRA) finetuning strategy to the SAM image encoder and finetunes it
together with the prompt encoder and the mask decoder on labeled medical image segmentation datasets. We also observe the warmup finetuning
strategy and the AdamW optimizer lead SAMed to successful convergence and lower loss. Different from SAM, SAMed could perform semantic segmentation on medical images. Our trained SAMed model achieves
81.88 DSC and 20.64 HD on the Synapse multi-organ segmentation
dataset, which is on par with the state-of-the-art methods. We conduct
extensive experiments to validate the effectiveness of our design. Since
SAMed only updates a small fraction of the SAM parameters, its deployment cost and storage cost are quite marginal in practical usage.

### Links
[Paper](https://arxiv.org/pdf/2304.13785.pdf) / [Codes](https://github.com/hitachinsk/SAMed)
![Star](https://img.shields.io/github/stars/hitachinsk/SAMed?style=social) ![Fork](https://img.shields.io/github/forks/hitachinsk/SAMed?style=social)

<iframe style="width:100%;height:auto;min-width:600px;min-height:400px;" src="https://star-history.com/embed?secret=Z2hwXzhBVzZ6ZXJEdHlKNjJuSzc1bGEwTjdPYVVIcVpmRzRkVXRGWg==#hitachinsk/SAMed&Date" frameBorder="0"></iframe>

### Bibtex
```bibtex
@article{samed,
  title={Customized Segment Anything Model for Medical Image Segmentation},
  author={Kaidong Zhang, and Dong Liu},
  journal={arXiv preprint arXiv:2304.13785},
  year={2023}
}
```
