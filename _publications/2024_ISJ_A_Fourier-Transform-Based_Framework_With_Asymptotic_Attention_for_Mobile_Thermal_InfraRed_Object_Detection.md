---
title: "A Fourier-Transform-Based Framework with Asymptotic Attention for Mobile Thermal InfraRed Object Detection"
collection: publications
permalink: /publication/2024_ISJ_A_Fourier-Transform-Based_Framework_With_Asymptotic_Attention_for_Mobile_Thermal_InfraRed_Object_Detection
excerpt: '__Zeyu Wang__, Haibin Shen, Wenyu Jiang , Kejie Huang'
date: 2024-05-01
venue: 'IEEE Sensors Journal (ISJ)'
paperurl: 'http://academicpages.github.io/files/2024_ISJ_A_Fourier-Transform-Based_Framework_With_Asymptotic_Attention_for_Mobile_Thermal_InfraRed_Object_Detection.pdf'
---

Thermal InfraRed (TIR) technology has emerged as a significant tool in autonomous driving systems. Unlike natural images, TIR images are distinguished by their enriched thermal and illumination information while lacking chromatic contrast. Traditional object detection on natural images normally uses deep neural networks based on convolutional layers or attention modules. However, TIR-based object detection necessitates high computational efficiency to eliminate the extraction of redundant chromatic features. Furthermore, the robust space–frequency perception and expansive receptive field are critical due to the distinct brightness and contour features of TIR images. In this article, we propose a novel network, namely a lightweight Fourier-transform detector (LFTDet), meticulously designed to strike a balance between computational efficiency and accuracy in TIR object detection. Specifically, our innovative Fourier transform-efficient layer aggregation network (FT-ELAN) backbone takes advantage of Fourier transform (FT) in synergy with deep neural networks. In addition, we propose the detection neck called asymptotic attention-based feature pyramid network (AA-FPN) that integrates the SimA mechanism in the asymptotic structure to facilitate the FT-based operation. Extensive experiments conducted on FLIR and LLVIP datasets demonstrate that LFTDet surpasses all baselines while maintaining an extremely low computational cost. The code is available at https://github.com/zeyuwang-zju/LFTDet.
