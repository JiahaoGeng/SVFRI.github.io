# <center> Single-View Facial Reflectance Inference With a Differentiable Renderer </center>
<center> Jiahao Geng<sup>1</sup>, Yanlin Weng<sup>1,2*</sup>, Lvdi Wang<sup>2</sup>, Kun Zhou<sup>1,2</sup> </center>  

<center> <sup>1</sup>State Key Lab of CAD&CG, Zhejiang University, China; </center>  

<center> <sup>2</sup> ZJU-FaceUnity Joint Lab of Intelligent Graphics, China. </center>  

### Abstruct

We introduce a deep-learning based algorithm to infer high-fidelity facial reflectance maps from a single image. The algorithm uses convolutional neural networks to encode the input image into a latent representation, from which a decoder and detail enhancing network reconstruct decoupled facial reflectance (albedo, specular, and normal maps) as well as the lighting environment (spherical harmonic coefficients). These decoupled components, together with a 3D facial mesh estimated from the image, are then fed into a differentiable renderer to produce a rendered facial image. This allows us to iteratively optimize the latent representation of the image by minimizing the image-space reconstruction loss. Experimental results show that optimizing the latent representation through the differentiable renderer can effectively reduce the discrepancy between the original image and the rendered one, leading to more accurate reconstruction of characteristic facial features such as skin tone, lip color, and facial hair.

### Download urls
[Supplementary video](/demo.mp4)


```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/JiahaoGeng/SVFRI.github.io/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
