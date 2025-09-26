# Video-based Pose-Estimation Data as Source for Transfer Learning in Human Activity Recognition [[ICPR 2022](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9956405)]

Human Activity Recognition (HAR) using on-body
devices identifies specific human actions in unconstrained envi-
ronments. HAR is challenging due to the inter and intra-variance
of human movements; moreover, annotated datasets from on-
body devices are scarce. This problem is mainly due to the
difficulty of data creation, i.e., recording, expensive annotation,
and lack of standard definitions of human activities. Previous
works demonstrated that transfer learning is a good strategy for
addressing scenarios with scarce data. However, the scarcity of
annotated on-body device datasets remains. This paper proposes
using datasets intended for human-pose estimation as a source for
transfer learning; specifically, it deploys sequences of annotated
pixel coordinates of human joints from video datasets for HAR
and human pose estimation. We pre-train a deep architecture
on four benchmark video-based source datasets. Finally, an
evaluation is carried out on three on-body device datasets
improving HAR performance.

<p align="center">
  <img src="media/network.png" width = "650" />
 
  
</p>

Create synthetic IMU data from videos

Goal - Use a source dataset with poses, transform them to acceleration (synthetic IMU data). Then test it on target dataset.
