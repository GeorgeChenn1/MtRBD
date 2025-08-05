# MtRBD:Advancing iRBD Analysis with Multi-Task Learning for Joint Sleep Staging and RSWA Detection


## 1. Background

The **MtRBD (Multi-task REM Sleep Behavior Disorder)** model is designed to address a critical challenge in sleep disorder research: simultaneously performing **sleep staging** and **RSWA (REM Sleep Without Atonia)** detection, which are essential tasks for diagnosing **iRBD (idiopathic REM Sleep Behavior Disorder)**. iRBD is a precursor to neurodegenerative diseases such as Parkinson’s, and RSWA detection is a hallmark phenomenon of RBD. Our model leverages the power of **multi-task learning** to improve the accuracy and efficiency of these tasks, enhancing the potential for clinical applications in diagnosing sleep disorders. While previous models have focused on individual tasks, our framework integrates both sleep staging and RSWA detection, allowing for more comprehensive and robust results.

![Background Image](https://github.com/GeorgeChenn1/MtRBD/tree/main/Figure/Fig.1.png)

## 2. Model Overview

The **MtRBD model** is built upon the backbone network **MIABNet** (Multi-scale Information Attention Bottleneck Network), which effectively fuses multi-channel EEG and EOG signals across temporal scales. **MIABNet** performs the crucial task of **sleep staging** before the multi-task approach is applied. The **MtRBD** model enhances this architecture by incorporating a **Multi-task Learning (MTL)** framework, enabling joint optimization of both sleep staging and RSWA detection tasks. 

In addition to **MIABNet**, the model utilizes **Dynamic Feature Enhancement Modules (DFEM)** and **Self-Attention Mechanisms (SAM)**, which allow the model to focus on the most relevant features across both tasks. The integration of these advanced techniques enables **MtRBD** to achieve superior performance, providing a comprehensive solution for diagnosing sleep disorders. 

For sleep staging, **MtRBD** achieved impressive results, with particularly high accuracy in classifying stages. For RSWA detection, it demonstrated high accuracy, significantly outperforming previous state-of-the-art models.

![Model Architecture](https://github.com/GeorgeChenn1/MtRBD/tree/main/Figure/Fig.2.png)

## 3. Model Parameter Ablation and Selection Validation

We have conducted comprehensive experiments on model parameter ablation and selection to validate the impact of each component. These experiments are included in the supplementary materials for further details. You can refer to our **supplementary materials** document, **MtRBD_supplementary_materials.pdf**, for the full analysis of these experiments.

## 4. Code Availability

We are currently in the process of organizing and preparing the code for open-source release. The code will be made available shortly after we complete the final preparation and application processes. We are committed to providing a clear and efficient framework for researchers and practitioners interested in sleep disorder diagnosis.

## 5. Contact Information

If you have any questions or would like to inquire further about the model, please feel free to contact us:

- **Email**: [Xiaoyuchen23@m.fudan.edu.cn]  
- **Institution**: [the Department of Biomedical Engineering, Fudan University, Shanghai 200433, China]  

We welcome any feedback, contributions, or collaboration inquiries.
