# <center> Single-View Facial Reflectance Inference With a Differentiable Renderer </center>
<center> Jiahao Geng<sup>1</sup>, Yanlin Weng<sup>1,2*</sup>, Lvdi Wang<sup>2</sup>, Kun Zhou<sup>1,2</sup> </center>  

<center> <sup>1</sup>State Key Lab of CAD&CG, Zhejiang University, China; </center>  

<center> <sup>2</sup> ZJU-FaceUnity Joint Lab of Intelligent Graphics, China. </center>  

### Abstruct

<p style="text-align:justify;"> We introduce a deep-learning based algorithm to infer high-fidelity facial reflectance maps from a single image. The algorithm uses convolutional neural networks to encode the input image into a latent representation, from which a decoder and detail enhancing network reconstruct decoupled facial reflectance (albedo, specular, and normal maps) as well as the lighting environment (spherical harmonic coefficients). These decoupled components, together with a 3D facial mesh estimated from the image, are then fed into a differentiable renderer to produce a rendered facial image. This allows us to iteratively optimize the latent representation of the image by minimizing the image-space reconstruction loss. Experimental results show that optimizing the latent representation through the differentiable renderer can effectively reduce the discrepancy between the original image and the rendered one, leading to more accurate reconstruction of characteristic facial features such as skin tone, lip color, and facial hair. </p>

### Download urls
[Supplementary video](./demo.mp4)
