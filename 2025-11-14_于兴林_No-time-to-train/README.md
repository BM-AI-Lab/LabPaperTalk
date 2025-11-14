# No time to train! 完全无训练的实例分割方法

日期：2025-11-14

汇报人：于兴林


## No time to train! Training-Free Reference-Based Instance Segmentation
- 发布时间：2025-07-03
- 收录情况：ArXiv
- 作者单位：School of Engineering, University of Edinburgh; Meta;


### 摘要
The performance of image segmentation models has historically been constrained by the high cost of collecting large-scale annotated data. The Segment Anything Model (SAM) alleviates this original problem through a promptable, semantics-agnostic, segmentation paradigm and yet still requires manual visual-prompts or complex domain-dependent prompt-generation rules to process a new image. Towards reducing this new burden, our work investigates the task of object segmentation when provided with, alternatively, only a small set of reference images. Our key insight is to leverage strong semantic priors, as learned by foundation models, to identify corresponding regions between a reference and a target image. We find that correspondences enable automatic generation of instance-level segmentation masks for downstream tasks and instantiate our ideas via a multi-stage, training-free method incorporating (1) memory bank construction; (2) representation aggregation and (3) semantic-aware feature matching. Our experiments show significant improvements on segmentation metrics, leading to state-of-the-art performance on COCO FSOD (36.8% nAP), PASCAL VOC Few-Shot (71.2% nAP50) and outperforming existing training-free approaches on the Cross-Domain FSOD benchmark (22.4% nAP).


### 链接
- 论文：https://doi.org/10.48550/arXiv.2507.02798
- 代码：https://github.com/miquel-espinosa/no-time-to-train
- 网站：https://miquel-espinosa.github.io/no-time-to-train/


## 讨论记录
1. 可能严重依赖于SAM的分割效果
2. 按照这个思路，使用预训练的大型视觉基础模型，能否用在细胞图像上
3. 这篇文章的工作中，在构造Memory Bank的时候直接的特征平均是否会损失一些物体形状上的信息。该怎么样进行改进。