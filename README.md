# Deep opinion-unaware blind image quality assessment by learning and adapting from multiple annotators
This repository contains the implementations for the paper "Deep opinion-unaware blind image quality assessment by learning and adapting from multiple annotators", Zhihua Wang*, Xuelin Liu*, Jiebin Yan, Chao Huang, Jie Wen, International Joint Conferences on Artificial Intelligence (IJCAI), 2025. (*Equal contribution)

## Introduction
Existing deep neural network (DNN)-based blind image quality assessment (BIQA) methods primarily rely on human-rated datasets for training. However, collecting human labels is extremely time-consuming and labour-intensive, posing a significant bottleneck for practical applications. To address this challenge, we propose a Deep opinion-Unaware BIQA model by learning and adapting from Multiple Annotators, termed DUBMA, 10 thereby eliminating the need for human annotations. Specifically, we first generate a large-scale set of distorted image pairs and then assign relative quality rankings using existing full-reference IQA models. The resulting dataset is subsequently employed for training our DUBMA. Due to the inherent discrepancies between synthetic and real-world distortions, a domain shift may occur. To address this, we propose an outlier-robust unsupervised domain adaptation approach leveraging optimal transport. This strategy effectively reduces the gap between synthetic and real-world distortion domains, thereby boosting the model’s adaptability and overall performance. Extensive experiments show that DUBMA outperforms existing opinion-unaware BIQA methods in terms of prediction accuracy across multiple datasets.

## Method
To be continued.


## Citation
Please cite our papers if it helps your research:
```bibtex
@inproceedings{wang2025ijcai,
title={Deep opinion-unaware blind image quality assessment by learning and adapting from multiple annotators},
author={Wang, Zhihua and Liu, Xuelin and Yan, Jiebin and Huang, Chao and Wen, Jie},
booktitle={Thirty-Sixth AAAI Conference on Artificial Intelligence},
pages={},
year={2025}
}
