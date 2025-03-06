# [WACV 2025] Explicit Guidance for Robust Video Frame Interpolation against Discontinuous Motions


This is the official PyTorch implementation of our paper:

> **Explicit Guidance for Robust Video Frame Interpolation against Discontinuous Motions** \
> [JaeHyun Park], [Namik Cho]
> IEEE/CVF Winter Conference on Applications of Computer Vision (WACV) 2025

[[Paper(WACV)](https://openaccess.thecvf.com/content/WACV2025/html/Park_Explicit_Guidance_for_Robust_Video_Frame_Interpolation_against_Discontinuous_Motions_WACV_2025_paper.html)]
## Overview

## Abstract
Nowadays many videos contain graphic elements such as logos subtitles and user interfaces. These overlayed elements exhibit discontinuous motions characterized by static or instantaneous motions that are neither spatially nor temporally coherent. As existing Video Frame Interpolation (VFI) methods rely on motion-compensation techniques they work best for videos with continuous motions but face limitations against videos with discontinuous motion. In this paper we propose a simple framework to enhance the robustness of existing VFI models against discontinuous motion. We first identify key properties that distinguish discontinuous from continuous motion. They are then leveraged by the Discontinuity map (D-map) estimator to explicitly guide the classification of continuous and discontinuous areas through a coherence mask and an additional supervisory signal. Our framework separately interpolates the predicted continuous and discontinuous regions to achieve state-of-the-art performance against synthetic discontinuous motions while also generalizing well to real-world discontinuous motions. Moreover our framework's `plug-and-play' design enables easy application to existing VFI models without the need for retraining and maintains strong performance on continuous motion.


## Citation
```

```
