---
title: "A lightweight building instance extraction method based on adaptive optimization of mask contour"
collection: publications
permalink: /publication/ALightweightBuilding
excerpt: "Xiaoxue Liu, Yiping Chen \ *, Cheng Wang, Kun Tan, Jonathan Li \ *<br/>International Journal of Applied Earth Observation and Geoinformation, August 2023<br/><img src='/images/ALightweightBuilding.jpg'>"
date: 2023-08-01
venue: ''
paperurl: 'http://AcaHomeC.github.io/files/ALightweightBuilding.pdf'
---
## Abstract
Automatic extraction of building instances from high spatial resolution optical remote sensing imagery is essential for urban infrastructure and smart management. In view of the severe challenges such as intricate building samples, high training overhead and inaccurate mask contours, this paper proposes a region-based, two-stage segmentation model assembled with components of adaptive feature extraction, guided anchoring and iterative subdivision mask, resulting in lightweight extraction of building instances and adaptive optimization of mask contours. We conducted comparison experiments with several classical, state-of-the-art instance segmentation methods on WHU aerial dataset, China city satellite dataset and Inria aerial dataset. The quantitative evaluation demonstrates that our method signally reduces the computational load by at least 34.5%, increases the mask AP on the three datasets by at least 0.8%, 4.6% and 4.1%, respectively, and increases the mean performance (mPC) and relative performance (rPC) under image corruption (12 corruptions and 2 severity levels) by at least 2.4% and 3.2%, respectively. The qualitative evaluation further verifies that our method is more discriminative for features such as color, texture, and shadow, and more adaptable to changes in shape, scale, and distribution and so on. Especially for large-sized buildings, various comparison methods either miss the partial interior area or excessively smooth the mask contour, whereas our method can output complete and accurate masks.

[Full text](https://doi.org/10.1016/j.jag.2023.103420)
