---
title: "Object-aware Monocular Depth Prediction with Instance Convolutions"
collection: publications
excerpt: 'With the advent of deep learning, estimating depth from a single RGB image has recently received a lot of attention, being capable of empowering many different applications ranging from path planning for robotics to computational cinematography. Nevertheless, while the depth maps are in their entirety fairly reliable, the estimates around object discontinuities are still far from satisfactory. This can be contributed to the fact that the convolutional operator naturally aggregates features across object discontinuities, resulting in smooth transitions rather than clear boundaries. Therefore, in order to circumvent this issue, we propose a novel convolutional operator which is explicitly tailored to avoid feature aggregation of different object parts. In particular, our method is based on estimating per-part depth values by means of superpixels. The proposed convolutional operator, which we dub "Instance Convolution", then only considers each object part individually on the basis of the estimated superpixels. Our evaluation with respect to the NYUv2 as well as the iBims dataset clearly demonstrates the superiority of Instance Convolutions over the classical convolution at estimating depth around occlusion boundaries, while producing comparable results elsewhere.'
date: 2022-01-01
venue: 'IEEE Robotics and Automation Letters (RA-L)'
paperurl: 'https://arxiv.org/abs/2112.01521'
---

