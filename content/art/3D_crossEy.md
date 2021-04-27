+++
showonlyimage = true
draft = false
image = "img/art/Art_SterEO_thmb.jpg"
date = "2016-11-05T18:25:22+05:30"
title = "Cross-eye Stereoscopy"
weight = 2
description = "Cross-eye stereoscopic imagery is the simplest technique to experience the esthetic of the spatial perception."
cover = "img/art/Ela_cross_1.jpg"
+++

Cross-eyed stereoscopic imagery is the simplest technique to experience the esthetic of the spatial perception.
<!--more-->

Original portrait stylized as an op-art pastiche, was a birthday gift for the friend. A year later, when I've started some experiments with FB 3D, I have created the Depth Map for a quite successful rendering of 3D portrait, that can be seen on FB, as long as it is supported there.
<!--more-->

The same depth map is used here to make the paralax displacement for all those stereoscopic twin images intended as a cross-eye work.
<!--more-->

![sample image](/img/art/Ela_cross_4.jpg)

Above presented is the set of images, kind of work in progress, (the development for the next time ;)).
I like to make some examination of fusion of colors and shape-background-noise for the imagery perception.

## 3D model for a depth map rendering

The 3D model is created using camera projection, subsequently it is rendered by the same camera as a Z-depth pass.
The next adjustment is done with masks correcting details for the foreground, and middle-ground layers.
Depth map is applied as a displacement map.

![sample image](/img/art/Depth-Map_process.jpg)
