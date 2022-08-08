# <p align=center>`awesome-generation`</p>
A collection of resources on generation. Maintained by [IIGroup](https://sites.google.com/view/iigroup-thu/home?authuser=0).

<!-- ## Contributing

If you think I have missed out on something (or) have any suggestions (papers, implementations and other resources), feel free to [pull a request](https://github.com/xiaweihao/awesome-image-translation/pulls). Feedback and contributions are welcome!

markdown format:
``` markdown
**Here is the Paper Name.**<br>
*[Author 1](homepage), Author 2, and Author 3.*<br>
Conference or Journal Year. [[PDF](link)] [[Project](link)] [[Github](link)] [[Video](link)] [[Data](link)]
``` -->

<details><summary>Table of Contents</summary><p>

- [GAN Inversion and Editing](#gan-inversion-and-editing)
- [3D-GAN](#3d-gan)
- [NeRF editing](#nerf-editing)
- [Style Transfer](#style-transfer)
- [Talking-Head Video Generation](#talking-head-video-generation)
- [Image Synthesis](#image-synthesis)
- [UV Space](#uv-space)
- [Denoising Diffusion](#denosing-diffusion)
</p></details><p></p>

## Image Synthesis

**StyleGAN-XL: Scaling StyleGAN to Large Diverse Datasets.** <br>
*Axel Sauer, Katja Schwarz, Andreas Geiger.*<br>
SIGGRAPH 2022. [[PDF](https://arxiv.org/abs/2202.00273)]

## GAN Inversion and Editing

**Expanding the Latent Space of StyleGAN for Real Face Editing.**<br>
*Yin Yu, Ghasedi Kamran, Wu HsiangTao, Yang Jiaolong, Tong Xi, Fu Yun.*<br>
Abstract: F Space Inversion.
ArXiv 2022. [[PDF](https://arxiv.org/abs/2204.12530)]

**Spatially-Adaptive Multilayer Selection for GAN Inversion and Editing**<br>
*Gaurav Parmar, Yijun Li, Jingwan Lu, Richard Zhang, Jun-Yan Zhu, Krishna Kumar Singh*<br>
Abstract: Invertibility and Multi-F Space Inversion.
CVPR 2022. [[PDF](https://openaccess.thecvf.com/content/CVPR2022/papers/Parmar_Spatially-Adaptive_Multilayer_Selection_for_GAN_Inversion_and_Editing_CVPR_2022_paper.pdf)]

**HyperStyle: StyleGAN Inversion with HyperNetworks for Real Image Editing.**<br>
*Yuval Alaluf, Omer Tov, Ron Mokady, Rinon Gal, Amit H. Bermano.*<br>
CVPR 2022. [[PDF](https://arxiv.org/abs/2111.15666)]

**Overparameterization Improves StyleGAN Inversion.**<br>
*Yohan Poirier-Ginter, Alexandre Lessard, Ryan Smith, Jean-François Lalonde.*<br>
CVPR WorkShop 2022. [[PDF](https://arxiv.org/abs/2205.06304)]

**Towards High-Fidelity Face Self-occlusion Recovery via Multi-view Residual-based GAN Inversion.**<br>
AAAI 2022. [[PDF](https://aaai-2022.virtualchair.net/poster_aaai2208)]

**NARRATE: A Normal Assisted Free-View Portrait Stylizer.**<br>
*Youjia Wang, Teng Xu, Yiwen Wu, Minzhang Li, Wenzheng Chen, Lan Xu, Jingyi Yu.*<br>
Submitted to SIGGRAPH Asia 2022.

## 3D-GAN

**Pix2NeRF: Unsupervised Conditional π-GAN for Single Image to Neural Radiance Fields Translation.**<br>
*Shengqu Cai, Anton Obukhov, Dengxin Dai, Luc Van Gool.*<br>
CVPR 2022. [[PDF](https://arxiv.org/abs/2202.13162)]

**IDE-3D: Interactive Disentangled Editing for High-Resolution 3D-aware Portrait Synthesis.**<br>
Submitted to SIGGRAPH-Asia. [[PDF](https://arxiv.org/abs/2205.15517)]

**Injecting 3D Perception of Controllable NeRF-GAN into StyleGAN for Editable Portrait Image Synthesis.**<br>
ECCV 2022. [[PDF](https://arxiv.org/abs/2207.10257)]

## NeRF Editing

**Controllable 3D Face Synthesis with Conditional Generative Occupancy Fields.**<br>
*MMlab & VGG*<br>
Submitted to NIPS 2022. [[PDF](https://arxiv.org/abs/2206.08361)]

## Style Transfer

**Quality Metric Guided Portrait Line Drawing Generation from Unpaired Training Data.**<br>
*Ran Yi, Yong-Jin Liu, Yu-Kun Lai, Paul L. Rosin.*<br>
TPAMI 2022. [[PDF](https://arxiv.org/abs/2202.03678)]

**Cross-Domain Style Mixing for Face Cartoonization.**<br>
Layer Swap and Style Mixing
Arxiv 2022. [[PDF](https://arxiv.org/abs/2205.12450)]

## Talking-Head Video Generation

**Dynamic Neural Textures: Generating Talking-Face Videos with Continuously Controllable Expressions.**<br>
*Zipeng Ye, Zhiyao Sun, Yu-Hui Wen, Yanan Sun, Tian Lv, Ran Yi, Yong-Jin Liu.*<br>
SIGGRAPH 2022. [[PDF](https://arxiv.org/abs/2204.06180)]

**One-Shot Face Reenactment on Megapixels.**<br>
Submitted to ECCV 2022. [[PDF](https://arxiv.org/abs/2205.13368)]

**Video2StyleGAN: Disentangling Local and Global Variations in a Video**<br>
*Rameen Abdal, Peihao Zhu, Niloy J. Mitra, Peter Wonka. KAUST*<br>
Submitted to SIGGRAPH-Asia 2022. [[PDF](https://arxiv.org/abs/2205.13996)]

**Dual-Generator Face Reenactment**<br>
*Gee-Sern, Hsu Chun-Hung, Tsai Hung-Yi Wu. National Taiwan University of Science and Technology*<br>
CVPR 2022. [[PDF](https://openaccess.thecvf.com/content/CVPR2022/papers/Hsu_Dual-Generator_Face_Reenactment_CVPR_2022_paper.pdf)]

**Structure-Aware Motion Transfer with Deformable Anchor Model**<br>
*Jiale Tao, Biao Wang, Borun Xu, Tiezheng Ge, Yuning Jiang, Wen Li, Lixin Duan*<br>
CVPR 2022. [[PDF](https://arxiv.org/abs/2204.05018)]

## Vector Quantisation - Token-based Generative Models
**Neural Discrete Representation Learning (VQVAE)**<br>
*Patrick Esser, Robin Rombach, Björn Ommer*<br>
NIPS 2017. [[PDF](https://arxiv.org/abs/1711.00937)]

**Taming Transformers for High-Resolution Image Synthesis (VQGAN)**<br>
*Aaron van den Oord, Oriol Vinyals, Koray Kavukcuoglu*<br>
CVPR 2021 oral. [[PDF](https://arxiv.org/abs/2012.09841)]

**Vector-quantized Image Modeling with Improved VQGAN (ViT-VQGAN)**<br>
*Jiahui Yu, Xin Li, Jing Yu Koh, Han Zhang, Ruoming Pang, James Qin, Alexander Ku, Yuanzhong Xu, Jason Baldridge, Yonghui Wu*<br>
ICLR 2022 spotlight. [[PDF](https://arxiv.org/abs/2110.04627)]

**MaskGIT: Masked Generative Image Transformer**<br>
*Huiwen Chang, Han Zhang, Lu Jiang, Ce Liu, William T. Freeman*<br>
CVPR 2022. [[PDF](https://arxiv.org/abs/2202.04200)]

## UV Space

**UV-GAN: Adversarial Facial UV Map Completion for Pose-invariant Face Recognition**<br>
CVPR 2018. [[PDF](https://openaccess.thecvf.com/content_cvpr_2018/papers/Deng_UV-GAN_Adversarial_Facial_CVPR_2018_paper.pdf)]

**A 3D GAN for Improved Large-pose Facial Recognition**<br>
CVPR 2021. [[PDF](https://openaccess.thecvf.com/content/CVPR2021/papers/Marriott_A_3D_GAN_for_Improved_Large-Pose_Facial_Recognition_CVPR_2021_paper.pdf)]

**StyleUV: Diverse and High-fidelity UV Map Generative Model**<br>
Arxiv 2020. [[PDF](https://arxiv.org/abs/2011.12893)]

**AUV-Net: Learning Aligned UV Maps for Texture Transfer and Synthesis**<br>
NVIDIA
CVPR 2022. [[PDF](https://nv-tlabs.github.io/AUV-NET/assets/auvnet-paper.pdf)]

## Denosing Diffusion

**Denoising Diffusion Probabilistic Models**<br>
*Jonathan Ho, Ajay Jain, Pieter Abbeel.*<br>
NeurIPS 2020. [[PDF](https://proceedings.neurips.cc/paper/2020/file/4c5bcfec8584af0d967f1ab10179ca4b-Paper.pdf)]

**Improved Denoising Diffusion Probabilistic Models**<br>
*Alex Nichol, Prafulla Dhariwal.*<br>
PMLR 2021.[[PDF](http://proceedings.mlr.press/v139/nichol21a/nichol21a.pdf)]
