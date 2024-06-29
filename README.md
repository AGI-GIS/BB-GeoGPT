# BB-GeoGPT

![framework](framework.png)
The framework for training a large language model for the geographic information science, termed BB-GeoGPT. Firstly, a comprehensive set of training resources, comprising model pretraining data (BB-GeoPT) and supervised fine-tuning instructions (BB-GeoSFT) is curated. Then, BB-GeoGPT is obtained by first adapting an open-source general-domain LLM,LLaMA-2-7B model to the pretraining data BB-GeoPT, and then utilizing the instruction tuning data BB-GeoSFT to further supervise fine-tuning the model. A lightweight training strategy is used in both of these stages. In this repository, we will share the following data.

1. We release the core data for training BB-GeoGPT, which includes the directive fine-tuning dataset stored in ./Data/BB-GeoSFT.json and the pre-training dataset stored in ./Data/BB-GeoPT.txt.
2.  We release a benchmark named BB-GeoEval, stored in ./Evaluation, for evaluating the language model's capabilities from both objective and subjective perspectives.

## Data
The Subjective Questions data and Objective Questions data is the experimental data used in the paper "BB-GeoGPT: A Framework for Learning a Large Language Model for Geographic Information Science", which has been accepted by the Information Processing & Management. If you need to use this dataset, please cite our paper.

## License
BB-GeoGPT and all our publicly available data are intended for research preview and non-commercial use only, subject to the model License of LLaMA2. Please contact us if you find any potential violations. If you have any questions, you can emaill us yuwh@cug.edu.cn.

## Citation
'''
@article{zhang2024bb,
  title={BB-GeoGPT: A framework for learning a large language model for geographic information science},
  author={Zhang, Yifan and Wang, Zhiyun and He, Zhengting and Li, Jingxuan and Mai, Gengchen and Lin, Jianfeng and Wei, Cheng and Yu, Wenhao},
  journal={Information Processing \& Management},
  volume={61},
  number={5},
  pages={103808},
  year={2024},
  publisher={Elsevier}
}
'''
