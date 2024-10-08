<h2>BB-GeoGPT: A framework for learning a large language model for geographic information science<h2>

## Framework
![framework](framework.png)
The framework for training a large language model for the geographic information science, termed BB-GeoGPT. Firstly, a comprehensive set of training resources, comprising model pretraining data (BB-GeoPT) and supervised fine-tuning instructions (BB-GeoSFT) is curated. Then, BB-GeoGPT is obtained by first adapting an open-source general-domain LLM,LLaMA-2-7B model to the pretraining data BB-GeoPT, and then utilizing the instruction tuning data BB-GeoSFT to further supervise fine-tuning the model. A lightweight training strategy is used in both of these stages. In this repository, we will share training data and evaluation data.

## Training data
We release the core data for training BB-GeoGPT, which is stored in Data.zip. This includes the instruction fine-tuning dataset in BB-GeoSFT.json and the pre-training dataset in BB-GeoPT.txt.

## Evaluation data 
We release a benchmark named BB-GeoEval, stored in ./Evaluation, for evaluating the language model's capabilities from both objective and subjective perspectives.

## License
BB-GeoGPT and all our publicly available data are intended for research preview and non-commercial use only, subject to the model License of LLaMA2. Please contact us if you find any potential violations. If you have any questions, you can emaill us yuwh@cug.edu.cn.

## Citation [Elsevier](https://www.sciencedirect.com/science/article/abs/pii/S0306457324001675)
If you use the data of BB-GeoGPT, please declare the following reference:
```
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
```
