---
title: "Weed species classification with UAV imagery and standard CNN models: Assessing the frontiers of training and inference phases"
collection: "publications"
category: "manuscripts"
permalink: /publication/mesas_ruiz2024b/
excerpt: ""
date: "2024-08-01"
venue: "Crop Protection"
slidesurl: #
paperurl: "https://www.sciencedirect.com/science/article/pii/S0261219424001492?via%3Dihub"
#citation: ''
tags:
- Site-specific weed management (SSWM)
- Deep learning
- VGG16
- ResNet152
- Inception-ResNet-v2
- Faster R–CNN
---

<p style = "text-align: justify; font-size: 10 pt">
Accurate weed species identification is crucial for effective site-specific weed management (SSWM), enabling targeted and timely control measures for each weed in crop field. This study advanced the current approach to species-level weed identification during the early growth stage by integrating unmanned aerial vehicles (UAVs) imagery with standard convolutional neural networks (CNNs) models such as VGG16, Resnet152 and Inception-Resnet-v2. For this, a robust dataset was created with 33,467 labels of weeds (Atriplex patula, Chenopodium album, Convolvulus arvensis, Cyperus rotundus, Lolium rigidum, Portulaca oleracea, Salsola kali, Solanum nigrum) and crops (maize, tomato), which was subjected to different training, validation and test scenarios. Model inputs were adjusted in order to align them with the information represented by the UAV images. Initially, models were developed in balanced scenarios, gradually increasing label numbers to assess their performance. Inception-ResNet-v2 achieved over 90% accuracy with 400 labels, while ResNet152 and VGG16 required 600 and 800 labels, respectively, for similar accuracy. In a more complex and realistic scenarios with unbalanced datasets, Inception-ResNet-v2 outperformed, likely due to its deeper architecture and enhanced capability to capture intricate features and patterns within UAV images. The study emphasized the importance of the minority-to-majority species ratio in unbalanced datasets, which affects minority species classification. To prevent misclassification, it is crucial to determine the right number of labels for CNN model training and validation. Weed maps were generated after species classification using the Faster R–CNN algorithm as an object detector. This advancement in methodology facilitates the precise and efficient implementation of SSWM techniques.
</p>