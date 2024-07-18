---
title: "Taming Vector-Wise Quantization for Wide-Range Image Blending with Smooth Transition"
collection: publications
permalink: /publication/2023_McGE_Taming_Vector_Wise_Quantization_for_Wide_Range_Image
excerpt: '__Zeyu Wang__, Haibin Shen, Kejie Huang'
date: 2023-07-15
venue: 'ACM International Conference on Multimedia (MM) Workshop on McGE'
paperurl: 'http://zeyuwang-zju.github.io/files/2023_McGE_Taming_Vector_Wise_Quantization_for_Wide_Range_Image.pdf'
---

Wide-range image blending is a novel image processing technique that merges two different images into a panorama with a transition region. Conventional image inpainting and outpainting methods have been used to complete this task, but always create significant distorted and blurry structures. The State-Of-The-Art (SOTA) method uses a U-Net-like model with a feature prediction module for content inference. However, it fails to generate panoramas with smooth transitions and visual realness, particularly when the input images have distinct scenery features. It indicates that the predicted features may deviate from the natural latent distribution of authentic images. In this paper, we propose an effective deep-learning model that integrates vector-wise quantization for feature prediction. This approach searches for the most-like latent features from a discrete codebook, resulting in high-quality wide-range image blending. In addition, we propose to use the global-local discriminator for adversarial training to improve the predicted content quality and smooth the transition. Our experiments demonstrate that our method generates visually appealing panoramic images and outperforms baseline approaches on the Scenery6000 dataset.
