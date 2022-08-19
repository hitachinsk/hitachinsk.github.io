---
title: "Inertia-Guided Flow Completion and Style Fusion for Video Inpainting"
collection: publications
permalink: /publication/2022-06-01-Inertia-Guided-Flow-Completion-and-Style-Fusion-for-Video-Inpainting
authors: <b>Kaidong Zhang</b>, Jingjing Fu, Dong Liu
excerpt: 'We show the benefit of explicit inertia prior for flow completion, which leads to more accurate flow-guided content propagation for video inpainting. We also first discuss the style incoherence caused by flow warping across different frames and propose the style fusion mechanism to refine the style in the warped regions under the guidance of the styles from valid regions.'
date: 2022-06-19
venue: 'In the proceedings of Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)'
citation: ' Kaidong Zhang,  Jingjing Fu,  Dong Liu, &quot;Inertia-Guided Flow Completion and Style Fusion for Video Inpainting.&quot; In the proceedings of Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR), 2022.'
---

### Demo Video
[![ISVI demo](https://res.cloudinary.com/marcomontalbano/image/upload/v1659703995/video_to_markdown/images/youtube--dHuFDPDWkYc-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://www.youtube.com/watch?v=dHuFDPDWkYc&t=4s "ISVI demo")

### Abstract
Physical objects have inertia, which resists changes in the velocity and motion direction. Inspired by this, we introduce inertia prior that optical flow, which reflects object motion in a local temporal window, keeps unchanged in the adjacent preceding or subsequent frame. We propose a flow completion network to align and aggregate f low features from the consecutive flow sequences based on the inertia prior. The corrupted flows are completed under the supervision of customized losses on reconstruction, f low smoothness, and consistent ternary census transform. The completed flows with high fidelity give rise to significant improvement on the video inpainting quality. Nevertheless, the existing flow-guided cross-frame warping methods fail to consider the lightening and sharpness variation across video frames, which leads to spatial incoherence after warping from other frames. To alleviate such problem, weproposetheAdaptiveStyle Fusion Network(ASFN), which utilizes the style information extracted from the valid regions to guide the gradient refinement in the warped regions. Moreover, we design a data simulation pipeline to reduce the training difficulty of ASFN. Extensive experiments show the superiority of our method against the state-of-theart methods quantitatively and qualitatively.


### Links
[Paper](https://openaccess.thecvf.com/content/CVPR2022/papers/Zhang_Inertia-Guided_Flow_Completion_and_Style_Fusion_for_Video_Inpainting_CVPR_2022_paper.pdf) /
[Supplementary](https://openaccess.thecvf.com/content/CVPR2022/supplemental/Zhang_Inertia-Guided_Flow_Completion_CVPR_2022_supplemental.pdf) /
[Codes](https://github.com/hitachinsk/ISVI) / 
[Keynotes](https://hitachinsk.github.io/files/ISVI_keynotes.pdf) /
[Demo (Bilibili)](https://www.bilibili.com/video/BV1AR4y1F7RB?spm_id_from=333.999.0.0)

![Stars](https://img.shields.io/github/stars/hitachinsk/ISVI?style=social) ![Forks](https://img.shields.io/github/forks/hitachinsk/ISVI?style=social)

<iframe style="width:100%;height:auto;min-width:600px;min-height:400px;" src="https://star-history.com/embed?secret=Z2hwX1BGZjQ4ODh2QzJoVm5MMjlMS2Qwazc5TWNnTGszdzRhYXdWYg==#hitachinsk/ISVI&Date" frameBorder="0"></iframe>

### Bibtex
```
@InProceedings{Zhang_2022_CVPR,
    author    = {Zhang, Kaidong and Fu, Jingjing and Liu, Dong},
    title     = {Inertia-Guided Flow Completion and Style Fusion for Video Inpainting},
    booktitle = {Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)},
    month     = {June},
    year      = {2022},
    pages     = {5982-5991}
}
```
