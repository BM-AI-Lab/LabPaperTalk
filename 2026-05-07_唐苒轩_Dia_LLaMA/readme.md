日期：2026-05-07

汇报人：BM-AI-Lab 唐苒轩


Title：Dia-LLaMA: Towards Large Language Model-driven CT Report Generation
- 发表情况： MICCAI 2025
- 收录情况：MICCAI 2025 Open Access
- 作者：Zhixuan Chen, Luyang Luo, Yequan Bie, Hao Chen，The Hong Kong University of Science and Technology

### 摘要
Medical report generation has become an important research direction in medical artificial intelligence, aiming to automatically produce clinically meaningful diagnostic reports from medical images. However, most existing studies mainly focus on chest X-ray report generation, while CT report generation remains more challenging due to the high-dimensional volumetric structure of CT images, sparse abnormal findings, and the imbalance between normal and abnormal disease patterns. To address these challenges, Dia-LLaMA proposes a large language model-driven framework for CT report generation. The model first employs a pretrained 3D vision transformer to extract visual representations from CT volumes and uses a Perceiver module to compress high-dimensional visual features into compact visual tokens suitable for large language model input. To enhance disease-related representation learning, Dia-LLaMA introduces a Disease-Aware Attention module to extract disease-specific features from CT patch embeddings. In addition, a Disease Prototype Memory Bank is constructed to model normal and abnormal prototypes for each disease, providing explicit diagnostic guidance and alleviating the impact of class imbalance. The predicted diagnostic information is further transformed into diagnostic text prompts and combined with visual tokens to guide LLaMA2-7B in generating CT reports. Experimental results demonstrate that Dia-LLaMA achieves superior performance compared with existing medical report generation methods in both natural language generation metrics and clinical efficacy metrics. Overall, this study shows that integrating visual feature extraction, disease-aware diagnostic modeling, and large language models can effectively improve the clinical reliability and diagnostic accuracy of CT report generation.


### 链接
- 论文：https://doi.org/10.1007/978-3-032-04981-0_14
- arXiv：https://arxiv.org/abs/2403.16386
- 代码：https://github.com/zhi-xuan-chen/Dia-LLaMA
- MICCAI页面：https://papers.miccai.org/miccai-2025/0229-Paper3319.html
- 数据集：CTRG-Chest-548K / CTRG-Chest dataset

## 讨论记录
## 讨论记录

1. 可以学习 Dia-LLaMA 的模型架构，即先提取 CT 图像特征，再构建疾病诊断提示，最后利用大语言模型生成医学报告。

2. 可以借鉴其 Diagnostic Text Prompts 的思想，将结构化诊断信息输入大语言模型，从而提高医学报告生成的准确性和临床可靠性。

3. 可以多利用知识图谱、疾病先验知识和临床诊断规则来约束大模型输出，使生成内容更加符合医学逻辑。

4. 对我的研究有启发：后续可以将手写、步态和语音等多模态评估结果转化为文本提示，用于生成帕金森病个体化评估报告。