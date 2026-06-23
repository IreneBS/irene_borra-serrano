---
title: "Multispecies weed mapping using deep learning on UAV imagery for SSWM in maize and tomato"
collection: "publications"
category: "manuscripts"
permalink: /publication/mesas_ruiz2025/
excerpt: ""
date: "2025-12-27"
venue: "Precision Agriculture"
slidesurl: #
paperurl: "https://link.springer.com/article/10.1007/s11119-025-10309-2"
#citation: ''
tags:
- Site-specific weed management (SSWM)
- Remote Sensing
- Vision transformers (ViT)
- Convolutional neural networks (CNN)
---

<p style = "text-align: justify; font-size: 10 pt">
Purpose: Accurate identification and mapping of multiple weed species at early growth stages is a critical step toward operational site-specific weed management (SSWM), yet most UAV-based studies have so far been limited to broad weed categories or single dominant species. This study aimed to evaluate and compare deep learning models for multispecies weed classification, detection and mapping in maize and tomato fields using UAV-based RGB imagery.

Methods: Three convolutional neural networks (Inception-ResNet-v2, EfficientNet-B0, YOLOv8) and two Vision Transformers (ViT-Base, Swin-T) were assessed for the classification of nine common weed species. The two best-performing classifiers were then implemented in object detection frameworks (YOLOv8m and DETA), and species-specific treatment maps were generated using adaptive economic weed thresholds applied to gridded density weed data.

Results: Swin-T and YOLOv8 achieved the highest classification metrics, with weighted F1-scores of 98.1% and 97.0%, respectively. For object detection, YOLOv8m outperformed DETA, reaching a mean Average Precision of 0.93 and a recall of 0.94, while substantially reducing inference time. The multispecies treatment maps revealed over 70% of weed-free areas, indicating the potential benefits of cost-saving approaches compared to uniform full-field treatments.

Conclusions: The proposed workflow enabled accurate multispecies weed classification, detection and mapping at early growth stages, providing valuable inputs for decision support systems and smart sprayers to gradually advance SSWM for a more selective, efficient and sustainable weed control.
</p>