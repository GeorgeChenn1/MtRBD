# MtRBD: Advancing iRBD Analysis with Multi-Task Learning for Joint Sleep Staging and RSWA Detection

## 1. Background

The **MtRBD (Multi-task REM Sleep Behavior Disorder)** model is designed to address a critical challenge in sleep disorder research: simultaneously performing **sleep staging** and **RSWA (REM Sleep Without Atonia)** detection, which are essential tasks for diagnosing **iRBD (idiopathic REM Sleep Behavior Disorder)**. 


## 2. Model Overview

The **MtRBD model** is built upon the backbone network **MIABNet** (Multi-scale Information Attention Bottleneck Network), which effectively fuses multi-channel EEG and EOG signals across temporal scales. **MIABNet** performs the crucial task of **sleep staging** before the multi-task approach is applied. The **MtRBD** model enhances this architecture by incorporating a **Multi-task Learning (MTL)** framework, enabling joint optimization of both sleep staging and RSWA detection tasks. In addition to **MIABNet**, the model utilizes **Dynamic Feature Enhancement Modules (DFEM)**.



## 3. Model Parameter Ablation and Selection Validation

We have conducted comprehensive experiments on model parameter ablation and selection to validate the impact of each component. These experiments are included in the supplementary materials for further details. You can refer to our **supplementary materials** document, **MtRBD_supplementary_materials.pdf**, for the full analysis of these experiments.

## 4. Code Availability

We are currently in the process of organizing and preparing the code for open-source release. The code will be made available shortly after we complete the final preparation and application processes. We are committed to providing a clear and efficient framework for researchers and practitioners interested in sleep disorder diagnosis.

## 5. Contact Information

If you have any questions or would like to inquire further about the model, please feel free to contact us:

- **Email**: [Xiaoyuchen23@m.fudan.edu.cn]  
- **Institution**: [Department of Biomedical Engineering, Fudan University, Shanghai 200433, China]  

We welcome any feedback, contributions, or collaboration inquiries.
