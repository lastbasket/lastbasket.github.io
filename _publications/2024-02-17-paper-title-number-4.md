---
title: "Endo-4DGS: Endoscopic Monocular Scene Reconstruction with 4D Gaussian Splatting"
collection: publications
permalink: /publication/2024-02-17-paper-title-number-4
excerpt: "<img src='/images/gs.png' width='450' height='150'>"
paperurl: 'https://arxiv.org/abs/2401.16416'
citation: 'Huang, Y., Cui, B., Bai, L., Guo, Z., Xu, M., & Ren, H. (2024). Endo-4DGS: Endoscopic Monocular Scene Reconstruction with 4D Gaussian Splatting. <i>Arxiv</i>.'
---

In the realm of robot-assisted minimally invasive surgery, dynamic scene reconstruction can significantly enhance downstream tasks and improve surgical outcomes. Neural Radiance Fields (NeRF)-based methods have recently risen to prominence for their exceptional ability to reconstruct scenes but are hampered by slow inference speed, prolonged training, and inconsistent depth estimation. Some previous work utilizes ground truth depth for optimization but is hard to acquire in the surgical domain. To overcome these obstacles, we present Endo-4DGS, a real-time endoscopic dynamic reconstruction approach that utilizes 3D Gaussian Splatting (GS) for 3D representation. Specifically, we propose lightweight MLPs to capture temporal dynamics with Gaussian deformation fields. To obtain a satisfactory Gaussian Initialization, we exploit a powerful depth estimation foundation model, Depth-Anything, to generate pseudo-depth maps as a geometry prior. We additionally propose confidence-guided learning to tackle the ill-pose problems in monocular depth estimation and enhance the depth-guided reconstruction with surface normal constraints and depth regularization. Our approach has been validated on two surgical datasets, where it can effectively render in real-time, compute efficiently, and reconstruct with remarkable accuracy.
