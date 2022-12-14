---
title: ACRA 2021 - Improving Semantic Segmentation with Calibrated Whole Image and Patch-Based Similar Place Priors
paper_url: https://ssl.linklings.net/conferences/acra/acra2021_proceedings/views/includes/files/pap126s2-file1.pdf
---
<p style="line-height:0.75"> <font size="2">Semantic segmentation is a crucial but challenging capability for many autonomous systems, especially in challenging environmental conditions like rain, snow or night time. Current solutions achieve high performance in these scenarios by learning domain specific information through domain adaptation or style transfer, but don’t generalize and require both anticipation of and access to representative data. Here we present a domain-agnostic approach that uses Visual Place Recognition (VPR) techniques to find image patches from similar (but geographically distinct) places to the query location, but obtained under ideal conditions, and fuses the open loop segmentation results with those prior place segmentations. We present our new patch-based place similarity methods along with comparison to whole image-based methods as a baseline, and a new entropy-based calibration method for weighting which methods to use. Results are presented for several benchmark datasets demonstrating the effectiveness of using similar place priors, and analysing the performance of whole- and patch-based approaches.</font></p>


|![Example of patch-based similar place generation using the Dark Zurich Dataset.](/assets/images/Patch-Based_Similar_Places.PNG){:class="img-responsive"}|
|:--:|
|<b><font size="2">Example of patch-based similar place generation using the Dark Zurich Dataset.</font></b>|