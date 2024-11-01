---
title: "DiffX: Guide Your Layout to Cross-Modal Generative Modeling"
collection: publications
permalink: /publication/2024_DiffX_Guide_Your_Layout_to_Cross_Modal_Generative_Modeling
excerpt: '__Zeyu Wang__, Jingyu Lin, Yifei Qian, Yi Huang, Shicen Tian, Qu Yang, Bosong Chai, Juncan Deng, Lan Du, Cunjian Chen, Kejie Huang'
date: 2024-07-16
venue: '(Under Review)'
---

Diffusion models have made significant strides in language-driven and layout-driven image generation. However, most diffusion models are limited to visible RGB image generation. In fact, human perception of the world is enriched by diverse viewpoints, such as chromatic contrast, thermal illumination, and depth information. In this paper, we introduce a novel diffusion model for general layout-guided cross-modal generation, called DiffX. Notably, our DiffX presents a simple yet effective cross-modal generative modeling pipeline, which conducts diffusion and denoising processes in the modality-shared latent space. Moreover, we introduce the Joint-Modality Embedder (JME) to enhance the interaction between layout and text conditions by incorporating a gated attention mechanism. To facilitate the user-instructed training, we construct the cross-modal image datasets with detailed text captions by the Large-Multimodal Model (LMM) and our human-in-the-loop refinement. Through extensive experiments, our DiffX demonstrates robustness in cross-modal “RGB+X” image generation on FLIR, MFNet, and COME15K datasets, guided by various layout conditions. It also shows the potential for the adaptive generation of “RGB+X+Y(+Z)” images or more diverse modalities on COME15K and MCXFace datasets. Our code and constructed cross-modal image datasets are available at https://github.com/zeyuwang-zju/DiffX.
