---
title: "Using Progressive Context Encoders for Anomaly Detection in Digital Pathology Images"
collection: publications
permalink: /publication/p_cead
excerpt: 'This paper discussed the novel anomaly detection approach in identifying anomalous regions from high-resolution whole slide images'
date: 2021-07-04
venue: 'bioRxiv'
paperurl: 'https://www.biorxiv.org/content/10.1101/2021.07.02.450957v1.abstract'
citation: 'Gillard, R., Meroueh, C., Gu, Q., Prodduturi, N., Patil, S., Flotte, T., Hart, S. (2021). &quot;Paper Using Progressive Context Encoders for Anomaly Detection in Digital Pathology Images.&quot; <i>bioRxiv</i>. preprint.'
---
Details of this paper could be found in below:
* Abstract:
    * Whole slide imaging (WSI) is transforming the practice of pathology, converting a qualitative discipline into a quantitative one. However, one must exercise caution in interpreting algorithm assertions, particularly in pathology where an incorrect classification could have profound impacts on a patient, and rare classes exist that may not have been seen by the algorithm during training. 
    * A more robust approach would be to identify areas of an image for which the pathologist should concentrate their effort to make a final diagnosis. 
        * This anomaly detection strategy would be ideal for WSI, but given the extremely high resolution and large file sizes, such an approach is difficult. 
        * Here, we combine progressive generative adversarial networks with a flexible adversarial autoencoder architecture capable of learning the “normal distribution” of WSIs of normal skin tissue at extremely high resolution and demonstrate its anomaly detection performance. 
    * Our approach yielded pixel-level accuracy of 89% for identifying melanoma, suggesting that our label-free anomaly detection pipeline is a viable strategy for generating high quality annotations - without tedious manual segmentation by pathologists. The code is publicly available at our [GitHub P-CEAD repository](https://github.com/Steven-N-Hart/P-CEAD).

[Download the Full PDF Format Paper Here](https://www.biorxiv.org/content/10.1101/2021.07.02.450957v1.full.pdf)

Recommended citation: Gillard, R., Meroueh, C., Gu, Q., Prodduturi, N., Patil, S., Flotte, T., Hart, S. (2021). "Using Progressive Context Encoders for Anomaly Detection in Digital Pathology Images" <i>bioRxiv</i>. preprint.