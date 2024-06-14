# BB-GeoGPT

![framework](framework.png)
The framework for training a large language model for the geographic information science, termed BB-GeoGPT. Firstly, a comprehensive set of training resources, comprising model pretraining data (BB-GeoPT) and supervised fine-tuning instructions (BB-GeoSFT) is curated. Then, BB-GeoGPT is obtained by first adapting an open-source general-domain LLM,LLaMA-2-7B model to the pretraining data BB-GeoPT, and then utilizing the instruction tuning data BB-GeoSFT to further supervise fine-tuning the model. A lightweight training strategy is used in both of these stages.

## Data
The Subjective Questions data and Objective Questions data is the experimental data used in the paper "BB-GeoGPT: A Framework for Learning a Large Language Model for Geographic Information Science", which has been accepted by the Information Processing & Management. If you need to use this dataset, please cite our paper.

