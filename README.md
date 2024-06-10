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



### **Method overview**



### **Comparison with other works**


### **Key Takeaways**

# DreamGaussian [![arXiv](https://img.shields.io/badge/arXiv-2309.16653-b31b1b.svg?style=flat-square)](https://arxiv.org/abs/2309.16653)

## **Contributions**



### **Method overview**



### **Comparison with other works**


### **Key Takeaways**
