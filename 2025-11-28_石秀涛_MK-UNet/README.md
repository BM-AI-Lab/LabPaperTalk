日期：2025-11-28

汇报人：石秀涛


## MK-UNet: Multi-kernel Lightweight CNN for Medical Image Segmentation
- 发布时间：2025-09-23
- 收录情况：arxiv
- 作者单位：Md Mostafijur Rahman,The University of Texas at Austin
           Radu Marculescu,The University of Texas at Austin


### 摘要
In this paper, we introduce MK-UNet, a paradigm shift towards ultra-lightweight, multi-kernel U-shaped CNNs tailored for medical image segmentation. Central to MK-UNet is the multi-kernel depth-wise convolution block (MKDC) we design to adeptly process images through multiple kernels, while capturing complex multi-resolution spatial relationships. MK-UNet also emphasizes the images salient
features through sophisticated attention mechanisms, including channel, spatial, and grouped gated attention. Our MK-UNet network, with a modest computational footprint of only 0.316M parameters and 0.314G FLOPs, represents not only a remarkably lightweight, but also signifi-
cantly improved segmentation solution that provides higher accuracy over state-of-the-art (SOTA) methods across six
binary medical imaging benchmarks. Specifically, MKUNet outperforms TransUNet in DICE score with nearly 333x and 123X fewer parameters and FLOPs, respectively. Similarly, when compared against UNeXt, MK-UNet exhibits superior segmentation performance, improving the
DICE score up to 6.7% margins while operating with 4.7X fewer #Params. Our MK-UNet also outperforms other recent lightweight networks such as MedT, CMUNeXt, EGEUNet, and Rolling-UNet, with much lower computational resources. This leap in performance, coupled with drastic computational gains, positions MK-UNet as an unparalleled solution for real-time, high-fidelity medical diagnostics in resource-limited settings, such as point-of-care devices.


### 链接
- 论文：https://arxiv.org/abs/2509.18493
- 代码：https://github.com/SLDGroup/MK-UNet



## 讨论记录
如何实现超轻量级的，想想创新点