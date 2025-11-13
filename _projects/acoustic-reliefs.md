---
title: Acoustic Reliefs
header:
  teaser: /assets/images/acoustic-reliefs/rep_image.png
excerpt: Create acoustic diffusers with custom images!
---

**Jeremy Chew**<sup>1</sup>, Michal Piovarči<sup>1</sup>, Kangrui Xue<sup>2</sup>, Doug L. James<sup>2</sup>, Bernd Bickel<sup>1</sup>

<sup>1</sup>ETH Zürich, <sup>2</sup>Stanford University

Published at Siggraph Asia 2025

## Abstract

We present a framework to optimize and generate *Acoustic Reliefs*: Acoustic diffusers that not only perform well acoustically in scattering sound uniformly in all directions, but are also visually interesting and can approximate user-provided images. To this end, we develop a differentiable acoustics simulator based on the boundary element method, and integrate it with a differentiable renderer coupled with a vision model to jointly optimize for acoustics, appearance, and fabrication constraints at the same time. We generate various examples and fabricate two room-scale reliefs. The result is a validated simulation and optimization scheme for generating acoustic reliefs whose appearances can be guided by a provided image.

## Useful Links

Learn more about this project on our [project page](https://cdl.ethz.ch/publications/acoustic-reliefs/).

Access the code [on Github](https://github.com/mickey1356/acoustic_reliefs).

Watch the supplementary video [here](https://cdl.ethz.ch/wp-content/uploads/2025/11/acoustic_reliefs_supp_video.mov).

## Examples

![Rep](/assets/images/acoustic-reliefs/rep_image.png)

### 0.6m Diffusers
![60](/assets/images/acoustic-reliefs/60.png)

### 0.9m Diffusers
![90](/assets/images/acoustic-reliefs/90.png)

### Office Diffusers
![office](/assets/images/acoustic-reliefs/office.png)
