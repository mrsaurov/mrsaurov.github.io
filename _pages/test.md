---
layout: archive
title: "Research Highlights"
permalink: /research/
author_profile: true
---

{% include base_path %}

## [Attention-reﬁned U-Net with Skip Connections for Eﬀective Brain Tumor Segmentation from MRI Images](https://ieeexplore.ieee.org/abstract/document/10441092)

**Authors:** A. F. M. Minhazur Rahman and Md. Ali Hossain
<!-- 
**Download Paper:** [PDF](/files/attention_unet.pdf) -->

<div style="text-align: center;">
  <img src="/images/sc-se-unet.png" alt="Attention-refined U-Net with Skip Connections for Effective Brain Tumor Segmentation from MRI images" style="width: 70%;">
  <p><em>Figure 1: SC-SE U-Net architecture.</em></p>
</div>

<!-- ![Attention-refined U-Net with Skip Connections for Effective Brain Tumor Segmentation from MRI images](/images/sc-se-unet.png){: width="70%" .align-center}
*Figure 1: SC-SE U-Net architecture.* -->

**Contributions:**
* Developed SC-SE U-Net, integrating Squeeze-and-Excitation channel
attention blocks and skip connections similar to residual network
* Improved segmentation accuracy with an Intersection over Union
(loU) score of 84.22%


## [Ensemble-Based Transfer Learning Approach for Brain Tumor Segmentation from MRI Images](/files/bim_2023_crs.pdf)

**Authors:** A. F. M. Minhazur Rahman and Md. Ali Hossain

<!-- **Download Paper:** [PDF](/files/bim_2023_crs.pdf) -->

**Contributions:**
* Experimented with fine-tuned EfficientNet, DenseNet, VGG, and
ResNet encoder architectures in a modified U-Net architecture
* Combined outputs from top models through majority voting and
weighted voting ensembles for robust segmentation results
* Achieved an loU score of 85.15%

## [Hyperspectral Image Classification Using Factor Analysis and Convolutional Neural Networks](https://link.springer.com/chapter/10.1007/978-981-16-6636-0_11)

**Authors:** A. F. M. Minhazur Rahman and Boshir Ahmed

**Contributions:**
* Introduced the FA-CNN method, combining factor analysis for
dimension reduction with CNNs for spectral-spatial feature extraction
* Achieved high classification accuracy with 99.59% overall accuracy on
the Indian Pines dataset and 99.95% on the Pavia University dataset

## [An Attention-Based Deep Learning Approach to Knee Injury Classification from MRI Images](https://ieeexplore.ieee.org/document/10441340)

**Authors:** Kowshik Deb Nath, A. F. M. Minhazur Rahman and Md. Ali Hossain

<div style="text-align: center;">
  <img src="/images/attention_cnn.png" alt="An Attention-Based Deep Learning Approach to Knee Injury Classification from MRI Images" style="width: 90%;">
  <p><em>Figure 2: Attention-based CNN architecture for knee injury classiﬁcation.</em></p>
</div>

**Contributions:**
* Introduced an attention-based CNN model achieving 100% accuracy in binary classification and 91% in multi-class classification
* Demonstrated model effectiveness on two comprehensive knee MRI datasets

## Research Projects
**Project Title:** Brain Tumor Segmentation Using Effective Deep
Learning Approach

**Financed By:** University Grants Communication, Bangladesh and
Rajshahi University of Engineering & Technology.

<div style="text-align: center;">
  <img src="/images/sc-eff-net.png" alt="Attention-refined U-Net with Skip Connections for Effective Brain Tumor Segmentation from MRI images" style="width: 70%;">
  <p><em>Figure 3: EﬃcientNet-SE U-Net architecture.</em></p>
</div>

**Contribution:**
* Proposed a novel EfficientNet-SE U-Net model combining EfficientNetB4 encoder and Squeeze-and-Excitation (SE) blocks in decoder
* Achieved high performance with loU of 85.34%
* Enhanced feature extraction using transfer learning
* Improved segmentation precision with SE blocks