---
title: "Image-to-image translation for automatic ink removal in whole slide images"
collection: publications
permalink: /publication/ink_removal
excerpt: 'This paper proposed a straightforward framework to digitally remove ink markings from whole slide images using a conditional generative adversarial network based on Pix2Pix.'
date: 2020-10-16
venue: 'Journal of Medical Imaging'
paperurl: 'https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7567133/'
citation: 'Jiang, J., Prodduturi, N., Chen, D., Gu, Q., Flotte, T., Feng, Q., Hart, S. (2020). &quot;Paper Image-to-image translation for automatic ink removal in whole slide images.&quot; <i>Journal of Medical Imaging</i>. 7(5).'
---
Details of this paper could be found in below:
* Abstract:
    * Purpose:
        * Deep learning models are showing promise in digital pathology to aid diagnoses. 
        * Training complex models requires a significant amount and diversity of well-annotated data, typically housed in institutional archives. 
            * These slides often contain clinically meaningful markings to indicate regions of interest. 
                * If slides are scanned with the ink present, then the downstream model may end up looking for regions with ink before making a classification. 
                * If scanned without the markings, the information regarding where the relevant regions are located is lost. 
        * A compromise solution is to scan the slide with the annotations present but digitally remove them.
    * Approach:
        * We proposed a straightforward framework to digitally remove ink markings from whole slide images using a conditional generative adversarial network based on Pix2Pix.
    * Results:
        * The peak signal-to-noise ratio increased 30%, structural similarity index increased 20%, and visual information fidelity increased 200% relative to previous methods.
    * Conclusions:
        * When comparing our digital removal of marked images with rescans of clean slides, our method qualitatively and quantitatively exceeds current benchmarks, opening the possibility of using archived clinical samples as resources to fuel the next generation of deep learning models for digital pathology.
    * Keywords:
        * Ink Removal
        * Whole Slide Image
        * Image to Image Translation

[Download the Full PDF Format Paper Here](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7567133/pdf/JMI-007-057502.pdf)

Recommended citation: Jiang, J., Prodduturi, N., Chen, D., Gu, Q., Flotte, T., Feng, Q., Hart, S. (2020). "Image-to-image translation for automatic ink removal in whole slide images" <i>Journal of Medical Imaging</i>. 7(5).