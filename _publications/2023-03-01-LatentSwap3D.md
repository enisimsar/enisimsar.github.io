---
title: "LatentSwap3D: Semantic Edits on 3D Image GANs"
collection: publications
excerpt: 'Recent 3D GANs have the ability to generate latent codes for entire 3D volumes rather than only 2D images. While they offer desirable features like high-quality geometry and multi-view consistency, complex semantic image editing tasks for 3D GANs have only been partially explored, unlike their 2D counterparts, e.g., StyleGAN and its variants. To address this problem, we propose LatentSwap3D, a latent space discovery-based semantic edit approach which can be used with any off-the-shelf 3D or 2D GAN model and on any dataset. LatentSwap3D relies on identifying the latent code dimensions corresponding to specific attributes by feature ranking of a random forest classifier. It then performs the edit by swapping the selected dimensions of the image being edited with the ones from an automatically selected reference image. Compared to other latent space control-based edit methods, which were mainly designed for 2D GANs, our method on 3D GANs provides remarkably consistent semantic edits in a disentangled manner and outperforms others both qualitatively and quantitatively. We show results on seven 3D generative models (\pigan{}, GIRAFFE, StyleSDF, MVCGAN, EG3D, StyleNeRF, and VolumeGAN) and on five datasets (FFHQ, AFHQ, Cats, MetFaces, and CompCars).'
date: 2023-01-07
venue: 'IEEE/CVF Winter Conference on Applications of Computer Vision (WACV)'
paperurl: 'https://enis.dev/latentswap3d/'
---

