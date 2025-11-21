日期：2025-11-21

汇报人：BM-AI-Lab 唐苒轩


Title：A vision-language pretrained transformer for versatile clinical respiratory disease applications
- 发布时间：2025-11-06
- 收录情况：Nature Biomedical Engineering
- 作者单位：School of Software, Tsinghua University, Beijing, China;Institute for Brain and Cognitive Sciences, BNRist, Tsinghua University, Beijing, China;China State Key Laboratory of Respiratory Disease and National Clinical Research Center for Respiratory Disease,The First Affiliated Hospital of Guangzhou Medical University, Guangzhou, China;Guizhou Provincial People's Hospital, Guiyang, China;The First Affiliated Hospital of Guangzhou Medical University, Guangzhou, China;Beijing Tiantan Hospital, Capital Medical University, Beijing, China;China National Clinical Research Center for Neurological Diseases, Beijing, China;

### 摘要
General artificial intelligence models have unique challenges in clinical practice when applied to diverse modalities and complex clinical tasks.Here we present MedMPT, a versatile, clinically oriented pretrained model tailored for respiratory healthcare, trained on 154,274 pairs of chest computed-tomography scans and radiograph reports. MedMPT adopts self-supervised learning to acquire medical insights and is capable of handling multimodal clinical data and supporting various clinical tasks aligned with clinical workflows. We evaluate the performance of MedMPT on a broad spectrum of chest-related pathological conditions, involving common medical modalities such as computed tomography images,radiology reports, laboratory tests and drug relationship graphs. MedMPT consistently outperforms the state-of-the-art multimodal pretrained models in the medical domain, achieving significant improvements in diverse clinical tasks. Extensive analysis indicates that MedMPT effectively harnesses the potential of medical data, showing both data and parameter efficiency and offering explainable insights for decision-making. MedMPT highlights the potential of multimodal pretrained models in the realm of general-purpose artificial intelligence for clinical practice.


### 链接
- 论文：https://doi.org/10.1038/s41551-025-01544-z
- 代码：https://github.com/maliangdi/MedMPT
- 数据集： https://cdas.cancer.gov/datasets/nlst/       https://github.com/michaelwfry/MosMedData-Chest-CT-Scans-with-COVID-19-RelatedFindings/


## 讨论记录
1.可以学习这个模型的架构，以及可以根据这个模型的文本编码器来构建适合帕金森病的架构。
2.可以多利用知识图谱来促进大模型的输出。