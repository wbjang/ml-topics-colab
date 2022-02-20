# ml-topics-colab
Colab Notebooks covering some ML(CV) topics

I would like to upload Colab Notebooks covering some interesting topics. <br>


### 1) Training ResNet based MLP with ViT-based Discriminator (20th Feb, 2022)

![Open ResNet features + ViT Discriminator in Colab](https://colab.research.google.com/assets/colab-badge.svg)
<a href = "https://colab.research.google.com/drive/1vP8wlBGLlZoGdFoWTfUjiNNLOWyovz02?usp=sharing">ResNet features MLP + ViT Discriminator</a>

ResNet features are very useful for regressing RGBs. GAN is still very hard to train - there is no objective loss function in GAN. 
<br/><br/>
Recently, Vision Transformer is widely used in the field of computer vision, and there is an amazing paper called <a href="https://arxiv.org/abs/2107.04589">ViT-GAN<a> which uses ViT for both generator and discriminator. 
<br/><br/>
Here, in this Colab Notebook, I adopt 'ViT-GAN Discriminator' along with 'ResNet features-based Generator'. Still, GAN is a bit hard to train - I just tried with easy-to-train generator. For the dataset, I use (famous) Tiny Lego dataset used in <a href = "https://colab.research.google.com/github/bmild/nerf/blob/master/tiny_nerf.ipynb">NeRF's colab</a>. We can train GAN-like model with 100 posed images.

