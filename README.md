# Isotropic3D [![arXiv](https://img.shields.io/badge/arXiv-2403.10395-b31b1b.svg?style=flat-square)](https://arxiv.org/abs/2403.10395)

### **Contributions**

- We propose a novel image-to-3D pipeline called Isotropic3D that takes only
an image CLIP embedding as input. Isotropic3D aims to give full play to
2D diffusion model priors without requiring the target view to be utterly
consistent with the input view
- We introduce a view-conditioned multi-view diffusion model that integrates
Explicit Multi-view Attention (EMA), aimed at enhancing view generation
through fine-tuning. EMA combines noisy multi-view images with the noisefree reference image as an explicit condition. Such a design allows the reference image to be discarded from the whole network during the SDS-based
3D generation process
- Experiments demonstrate that with a single CLIP embedding, Isotropic3D
can generate promising 3D assets while still showing similarity to the reference image.
<!-- - We use HashGrid encoding and uniformly sample points along rays, while the paper uses Integrated Positional Encoding and sampling strategy from MipNeRF360.
- We adopt camera settings and density initialization strategy from Magic3D, which is slightly different from the DreamFusion paper.
- Some hyperparameters are different, such as the weighting of loss terms. -->

### **Method overview**
![](https://isotropic3d.github.io/static/images/pipeline.png)
![](https://isotropic3d.github.io/static/images/mvd.png)


### **Comparison with other works**

[![](https://res.cloudinary.com/marcomontalbano/image/upload/v1718046621/video_to_markdown/images/video--2a77b5bbe7084fc55e8f9090a86f4cfb-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://isotropic3d.github.io/static/videos/compare_3D_1.mp4 "")


[![](https://res.cloudinary.com/marcomontalbano/image/upload/v1718046651/video_to_markdown/images/video--609b8ba891fb79fb509945d18020b696-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://isotropic3d.github.io/static/videos/compare_3D_2.mp4 "")

### **Key Takeaways**
- Single CLIP embedding to entire 3D generation
- **Mulitview Diffusion** model what takes the reference image and the noisy rendered 2D images
-  A single loop to actually make the generation better



# GaussianObject [![arXiv](https://img.shields.io/badge/arXiv-2402.10259-b31b1b.svg?style=flat-square)](https://arxiv.org/abs/2402.10259)

## **Contributions**
- We propose to optimize 3D Gaussians from highly sparse views
with explicit structure priors, where several techniques are designed, including the visual hull for initialization and floater
elimination for training.
- A Gaussian repair model based on diffusion models is proposed
to remove artifacts caused by omitted or highly compressed
object information, where the rendering quality can be further
improved.
- The overall framework GaussianObject shows strong performance on several challenging real-world datasets, consistently
outperforming previous state-of-the-art methods for both qualitative and quantitative evaluation.


### **Method overview**

![](https://gaussianobject.github.io/static/images/pipe.png)

### **Comparison with other works**
[![](https://res.cloudinary.com/marcomontalbano/image/upload/v1718054489/video_to_markdown/images/video--a8ded7cde8d5f7f68cae2659b9c26f66-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://gaussianobject.github.io/static/videos/teaser.mp4 "")

[![](https://res.cloudinary.com/marcomontalbano/image/upload/v1718054583/video_to_markdown/images/video--20385adcc2c848155c46bf08ab885b61-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://gaussianobject.github.io/static/videos/evolution.mp4 "")

### **Key Takeaways**
- Propose visual hull for coarse point cloud generation from 4 reference images
- Gaussian repair module and distance aware sampling
- 2D diffusion model and SDS loss to refine the initialized gaussians using gaussian rasterization for 2D rendering


# DreamGaussian [![arXiv](https://img.shields.io/badge/arXiv-2309.16653-b31b1b.svg?style=flat-square)](https://arxiv.org/abs/2309.16653)

## **Contributions**



### **Method overview**



### **Comparison with other works**


### **Key Takeaways**


# InstantMesh [![arXiv](https://img.shields.io/badge/arXiv-2404.07191-b31b1b.svg?style=flat-square)](https://arxiv.org/abs/2404.07191)

<video controls src="assets/322410754-dab3511e-e7c6-4c0b-bab7-15772045c47d-1.mp4" title="Title"></video>

## **Contributions**



### **Method overview**



### **Comparison with other works**


### **Key Takeaways**


# LRM (Large Reconstruction Model) [![arXiv](https://img.shields.io/badge/arXiv-2311.04400-b31b1b.svg?style=flat-square)](https://arxiv.org/abs/2311.04400)

[![](https://res.cloudinary.com/marcomontalbano/image/upload/v1718125572/video_to_markdown/images/video--b3c01110fed258bef84e9f56d221905f-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://yiconghong.me/LRM/static/i3d_videos/selected_samples_final_firefly%20-%20a%20campfire,%203d%20max,%20blender,%20white%20background,%20full%20view_renderings_converted.mp4 "")
[![](https://res.cloudinary.com/marcomontalbano/image/upload/v1718125847/video_to_markdown/images/video--5064685a5f925cd71411dee5e6c3ecda-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://yiconghong.me/LRM/static/i3d_videos/selected_samples_final_firefly%20-%20a%20light%20purple%20teddy%20bear,%20white%20background,%203ds%20max,%20blender_renderings_converted.mp4 "")

## **Contributions**
 - EXTREMELY FAST (5 second for single image to 3D generation)
 - 


### **Method overview**



### **Comparison with other works**


### **Key Takeaways**


# TripoSR (Large Reconstruction Model) [![arXiv](https://img.shields.io/badge/arXiv-2403.02151-b31b1b.svg?style=flat-square)](https://arxiv.org/abs/2403.02151)

![alt text](assets/teaser800.gif)

## **Contributions**
 - EXTREMELY FAST (<1 second for single image to 3D generation)
 - 


### **Method overview**



### **Comparison with other works**


### **Key Takeaways**


# LGM: Large Multi-View Gaussian Model for High-Resolution 3D Content Creation [![arXiv](https://img.shields.io/badge/arXiv-2403.02151-b31b1b.svg?style=flat-square)](https://arxiv.org/abs/2403.02151)

# GRM: Large Gaussian Reconstruction Model for Efficient 3D Reconstruction and Generation [![arXiv](https://img.shields.io/badge/arXiv-2403.14621-b31b1b.svg?style=flat-square)](https://arxiv.org/abs/2403.14621)

# Wonder3D: Single Image to 3D using Cross-Domain Diffusion [![arXiv](https://img.shields.io/badge/arXiv-2310.15008-b31b1b.svg?style=flat-square)](https://arxiv.org/abs/2310.15008)

# MVSplat: Efficient 3D Gaussian Splatting from Sparse Multi-View Images [![arXiv](https://img.shields.io/badge/arXiv-2403.14627-b31b1b.svg?style=flat-square)](https://arxiv.org/abs/2403.14627)

# MVControl: Controllable Text-to-3D Generation via Surface-Aligned Gaussian Splatting [![arXiv](https://img.shields.io/badge/arXiv-2403.09981-b31b1b.svg?style=flat-square)](https://arxiv.org/abs/2403.09981)

# DMV3D: Denoising Multi-view Diffusion with 3D LRM [![arXiv](https://img.shields.io/badge/arXiv-2311.09217-b31b1b.svg?style=flat-square)](https://arxiv.org/abs/2311.09217)

# Wonder3D: Single Image to 3D using Cross-Domain Diffusion [![arXiv](https://img.shields.io/badge/arXiv-2310.15008-b31b1b.svg?style=flat-square)](https://arxiv.org/abs/2310.15008)

![alt text](assets/pipeline.png)