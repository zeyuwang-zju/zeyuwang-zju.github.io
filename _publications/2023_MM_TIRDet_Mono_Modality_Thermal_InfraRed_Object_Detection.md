---
title: "TIRDet: Mono-Modality Thermal InfraRed Object Detection Based on Prior Thermal-To-Visible Translation"
collection: publications
permalink: /publication/2023_MM_TIRDet_Mono_Modality_Thermal_InfraRed_Object_Detection
excerpt: '__Zeyu Wang__, Fabien Colonnier, Jinghong Zheng, Jyotibdha Acharya, Wenyu Jiang, Kejie Huang'
date: 2023-07-17
venue: ' ACM International Conference on Multimedia (MM)'
paperurl: 'http://zeyuwang-zju.github.io/files/2023_MM_TIRDet_Mono-Modality_Thermal_InfraRed_Object_Detection.pdf'
---

__Abstract:__ Cross-modality images that combine visible-infrared spectra can provide complementary information for object detection. In particular, they are well-suited for autonomous vehicle applications in dark environments with limited illumination. However, it is time-consuming to acquire a large number of pixel-aligned visible-thermal image pairs, and real-time alignment is challenging in practical driving systems. Furthermore, the quality of visible-spectrum images can be adversely affected by complex environmental conditions. In this paper, we propose a novel neural network called TIRDet, which only utilizes Thermal InfraRed (TIR) images for mono-modality object detection. To compensate for the lacked visible-band information, we adopt a prior Thermal-To-Visible (T2V) translation model to obtain the translated visible images and the latent T2V codes. In addition, we introduce a novel attention-based Cross-Modality Aggregation (CMA) module, which can augment the modality-translation awareness of TIRDet by preserving the T2V semantic information. Extensive experiments on FLIR and LLVIP datasets demonstrate that our TIRDet significantly outperforms all mono-modality detection methods based on thermal images, and it even surpasses most State-Of-The-Art (SOTA) multispectral methods using visible-thermal image pairs. Code is available at https://github.com/zeyuwang-zju/TIRDet.

![image](https://github.com/zeyuwang-zju/TIRDet/assets/112078495/78f6c706-8b9b-4be2-909b-87b778d7a074)

![image](https://github.com/zeyuwang-zju/TIRDet/assets/112078495/8ff7acff-10ad-4e64-b7d4-303ef13c8aef)
