---
title: "Dicom_wsi: A Python Implementation for Converting Whole-Slide Images to Digital Imaging and Communications in Medicine Compliant Files"
collection: publications
permalink: /publication/dicom_wsi
excerpt: 'DICOM_WSI represents the first step in a long process of DICOM adoption for WSI. It is the first open source implementation released in the developer friendly Python programming language made available to the public.'
date: 2021-05-11
venue: 'Journal of Pathology Informatics'
paperurl: "https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8274303/"
citation: 'Gu, Q., Prodduturi, N., Jiang, J., Flotte, T., Hart, S. (2021). &quot;Dicom_wsi: A Python Implementation for Converting Whole-Slide Images to Digital Imaging and Communications in Medicine Compliant Files.&quot; <i>Journal of Pathology Informatics</i>. 12(21).'
---
Details of this paper could be found in below:
* Abstract:
    * Background:
        * Adoption of the Digital Imaging and Communications in Medicine (DICOM) standard for whole slide images (WSIs) has been slow, despite significant time and effort by standards curators. 
        * One reason for the lack of adoption is that there are few tools which exist that can meet the requirements of WSIs, given an evolving ecosystem of best practices for implementation. 
        * Eventually, vendors will conform to the specification to ensure enterprise interoperability, but what about archived slides? Millions of slides have been scanned in various proprietary formats, many with examples of rare histologies. 
        * Our hypothesis is that if users and developers had access to easy to use tools for migrating proprietary formats to the open DICOM standard, then more tools would be developed as DICOM first implementations.
    * Methods:
        * The technology we present here is dicom_wsi, a Python based toolkit for converting any slide capable of being read by the OpenSlide library into DICOM conformant and validated implementations. 
        * Moreover, additional postprocessing such as background removal, digital transformations (e.g., ink removal), and annotation storage are also described. dicom_wsi is a free and open source implementation that anyone can use or modify to meet their specific purposes.
    * Results:
        * We compare the output of dicom_wsi to two other existing implementations of WSI to DICOM converters and also validate the images using DICOM capable image viewers.
    * Conclusions:
        * dicom_wsi represents the first step in a long process of DICOM adoption for WSI. It is the first open source implementation released in the developer friendly Python programming language and can be freely downloaded at our [GitHub dicom_wsi repository](https://github.com/Steven-N-Hart/dicom_wsi).
    * Keywords:
        * Digital Imaging and Communications in Medicine
        * Informatics
        * Infrastructure
        * Whole-Slide Imaging

[Download the Full PDF Format Paper Here](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8274303/pdf/JPI-12-21.pdf)

* Recommended citation: 
    * Gu, Q., Prodduturi, N., Jiang, J., Flotte, T., Hart, S. (2021). "Dicom_wsi: A Python Implementation for Converting Whole-Slide Images to Digital Imaging and Communications in Medicine Compliant Files" <i>[Journal of Pathology Informatics](https://www.jpathinformatics.org/aboutus.asp)</i>. 12(21).