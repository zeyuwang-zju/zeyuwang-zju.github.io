---
title: "Thermal Infrared Image Inpainting Via Edge-Aware Guidance"
collection: publications
permalink: /publication/TIR-Fill
excerpt: 'This paper is about the number 1. The number 2 is left for future work.'
date: 2023-02-16
venue: 'IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP)'
paperurl: 'http://academicpages.github.io/files/paper1.pdf'
---

Image inpainting has achieved fundamental advances with deep learning. However, almost all existing inpainting methods aim to process natural images, while few target Thermal Infrared (TIR) images, which have widespread applications. When applied to TIR images, conventional inpainting methods usually generate distorted or blurry content. In this paper, we propose a novel task—Thermal Infrared Image Inpainting, which aims to reconstruct missing regions of TIR images. Crucially, we propose a novel deep-learning-based model TIR-Fill. We adopt the edge generator to complete the canny edges of broken TIR images. The completed edges are projected to the normalization weights and biases to enhance edge awareness of the model. In addition, a refinement network based on gated convolution is employed to improve TIR image consistency. The experiments demonstrate that our method outperforms state-of-the-art image inpainting approaches on FLIR thermal dataset.
