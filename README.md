# Medical Image Segmentation for Cardic

## **Three topics**
- Multi-task learning
- Cross-modality learning (Domain Adaptation)
- Inverse problem 
---
## Review Paper and Cardic Knowledge
- Automatic Whole Heart Segmentation Based on Image Registration [[paper]](https://zmiclab.github.io/zxh/0/files/zxhPhdThesistwoside.pdf) 

- Medical Image Analysis on Left Atrial LGE MRI for Atrial Fibrillation Studies: A Review [[paper]](https://arxiv.org/pdf/2106.09862.pdf)

- **2018ASC Challenge** Review: Deep Learning for Atrial
Segmentation From Late
Gadolinium-Enhanced MRIs [[paper]](https://www.frontiersin.org/articles/10.3389/fcvm.2020.00086/full)
## Multi-tasks Learning
- [Left Atrial and Scar Quantification & Segmentation Challenge 2022.4.1](https://zmiclab.github.io/projects/lascarqs22/index.html) \
**Three Important tasks: LA cavity segmentation, LA wall segmentation, LA scar quantification** 
    - Review paper for multi-tasks learning
        - 2022 Medical Image Analysis on Left Atrial LGE MRI for Atrial Fibrillation Studies: A Review [[paper]](https://arxiv.org/pdf/2106.09862.pdf)
    - Scar quantification 
        - 2020 joint segmentation and
quantification of left atrium and scars incorporating spatial and shape
information. [[paper]](https://arxiv.org/pdf/2008.04729.pdf) [[pytorch]](https://github.com/Marie0909/AtrialJSQnet)
    - LA cavity segmentation
        - 2018 Multi-Task Learning for Left Atrial Segmentation on GE-MRI(segmenation and pre/post classification) [[paper]](https://arxiv.org/pdf/1810.13205.pdf)

        - Two 3D V-Net(SOTA) [[paper]](https://ieeexplore.ieee.org/document/9005750)

        - See other algorithm in **Network** 
    - LA wall segmentation
        - 2021 LA-Net: A Multi-Task Deep Network for the Segmentation of the Left Atrium(wall and cavity) [[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9557323)
        
        - ShapeCut: Bayesian surface estimation using shape-driven graph [[paper]](https://www.sciencedirect.com/science/article/pii/S1361841517300634)

        - Evaluation on an open-source CT and MRI image database [[paper]](https://reader.elsevier.com/reader/sd/pii/S1361841518306431?token=91B9CE7059239E81C2E1DD52E8F348F7890B1F7C104BBDEB38BA8E97DC3C29A2E1BBCA7F09B874BCD29E97314558D232&originRegion=us-east-1&originCreation=20220228145449)


## Domain (Adaptation)

- 2020 **Domain Adaptation for Medical Image Analysis: A Survey** [[paper]](https://arxiv.org/pdf/2102.09508.pdf)

- 2020 Different Hosptial: AtrialGeneral: Domain Generalization for Left Atrial Segmentation of Multi-Center LGE MRIs [[paper]](https://arxiv.org/pdf/2106.08727.pdf)

- 2020 CF Distance: A New Domain Discrepancy Metric and Application to Explicit Domain Adaptation for Cross-Modality Cardiac Image Segmentation [[paper]](https://ieeexplore.ieee.org/abstract/document/9165963) [[pytorch]](https://github.com/FupingWu90/CFDnet)

- 2020 Unsupervised Domain Adaptation With
Variational Approximation for
Cardiac Segmentation [[paper]](https://arxiv.org/pdf/2106.08752.pdf) [[pytorch]](https://github.com/FupingWu90/VarDA)

- 2021 Disentangle domain features for cross-modality cardiac image segmentation [[paper]](https://www.sciencedirect.com/science/article/pii/S1361841521001249) [[tensorflow]](https://github.com/NanYoMy/cmmas)

- PnP-AdaNet: Plug-and-Play Adversarial Domain
Adaptation Network with a Benchmark at
Cross-modality Cardiac Segmentation [[paper]](https://arxiv.org/pdf/1812.07907.pdf)

- Unsupervised Bidirectional Cross-Modality
Adaptation via Deeply Synergistic Image and
Feature Alignment for Medical Image Segmentation [[paper]](https://arxiv.org/pdf/2002.02255.pdf)

 - Causality-inspired Single-source Domain Generalization for Medical Image Segmentation [[paper]](https://arxiv.org/pdf/2111.12525.pdf)

 ## Inverse problem
 ## Network
 - U-Net
 - U-Net++
 - Double-U-Net
 - nnFormer
 - nnUNet
 - SwinUNet
 - R2U-Net
 - ResUNet++
 - MSRF-Net: A Multi-Scale Residual Fusion
Network for Biomedical Image Segmentation [[paper]](https://arxiv.org/pdf/2105.07451.pdf)
    
