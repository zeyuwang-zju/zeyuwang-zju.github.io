---
title: "Bridging Partial-Gated Convolution with Transformer for Smooth-Variation Image Inpainting"
collection: publications
permalink: /publication/2024_MTAP_Bridging_partial_gated_convolution_with_transformer
excerpt: '__Zeyu Wang__, Haibin Shen, Kejie Huang'
date: 2024-01-01
venue: 'Multimedia Tools and Applications (MTAP)'
paperurl: 'http://zeyuwang-zju.github.io/files/2024_MTAP_Bridging_partial_gated_convolution_with_transformer.pdf'
---

Deep learning has brought essential improvement to image inpainting technology. Conventional deep-learning methods primarily focus on creating visually appealing content in the missing parts of images. However, these methods usually generate edge variations and blurry structures in the filled images, which lead to imbalances in quantitative metrics PSNR/SSIM and LPIPS/FID. In this work, we introduce a pioneering model called PTG-Fill, which utilizes a coarse-to-fine architecture to achieve smooth-variation image inpainting. Our approach adopts the novel Stable-Partial Convolution to construct the coarse network, which integrates a smooth mask-update process to ensure its long-term operation. Meanwhile, we propose the novel Distinctive-Gated Convolution to construct the refined network, which diminishes pixel-level variations by the distinctive attention. Additionally, we build up a novel Transformer bridger to preserve the in-depth features for image refinement and facilitate the operation of the two-stage network. Our extensive experiments demonstrate that PTG-Fill outperforms previous state-of-the-art methods both quantitatively and qualitatively under various mask ratios on four benchmark datasets: CelebA-HQ, FFHQ, Paris StreetView, and Places2. Code and pre-trained weights are available at https://github.com/zeyuwang-zju/PTG-Fill.
