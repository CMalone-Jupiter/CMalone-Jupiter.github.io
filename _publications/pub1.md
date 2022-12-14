---
title: RA-L 2022 - Improving Road Segmentation in Challenging Domains Using Similar Place Priors
paper_url: http://doi.org/10.1109/LRA.2022.3146894
---

<p style="line-height:0.75"> <font size="2">Road segmentation in challenging domains, such as night, snow or rain, is a difficult task. Most current approaches boost performance using fine-tuning, domain adaptation, style transfer, or by referencing previously acquired imagery. These approaches share one or more of three significant limitations: a reliance on large amounts of annotated training data that can be costly to obtain, both anticipation of and training data from the type of environmental conditions expected at inference time, and/or imagery captured from a previous visit to the location. In this research, we remove these restrictions by improving road segmentation based on similar places. We use Visual Place Recognition (VPR) to find similar but geographically distinct places, and fuse segmentations for query images and these similar place priors using a Bayesian approach and novel segmentation quality metric. Ablation studies show the need to re-evaluate notions of VPR utility for this task. We demonstrate the system achieving state-of-the-art road segmentation performance across multiple challenging condition scenarios including night time and snow, without requiring any prior training or previous access to the same geographical locations. Furthermore, we show that this method is network agnostic, improves multiple baseline techniques and is competitive against methods specialised for road prediction. </font></p>



|![Semantically similar but geographically separate places from WildDash](/assets/images/SimilarPlaces_RAL.PNG){:class="img-responsive"}|
|:--:|
|<b><font size="2">Semantically similar but geographically separate places from WildDash.</font></b>|