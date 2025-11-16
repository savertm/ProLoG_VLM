# ProLoG: Hybrid Prompt and LoRA Based Adaptation of Vision-Language Models for OOD Generalization, AAAI 2026


> Junwguk, Dong-Jun Han, Jaekyun Moon

Official repo of our AAAI 2026 paper

**<p align="justify"> Abstract:** *While vision-language models (VLMs) achieve remarkable performance when fine-tuned on downstream in-distribution (ID) data, this process compromises their generalization ability on out-of-distribution (OOD) data that deviate from the downstream tasks due to overfitting. To address this, we propose ProLoG, a new adaptation method that effectively fine-tunes VLMs on downstream tasks while achieving high OOD performance. Specifically, we design a unique integration of prompt tuning and LoRA, offering a robust hybrid platform to improve performance. During training, we propose an augmentationbased regularization loss that enhances the generalization of our hybrid network by using augmented image features aligned with LLM-generated texts containing key attributes of each class. By leveraging our hybrid design, we also introduce an adaptive inference strategy that flexibly applies trained prompts and LoRA based on a task similarity score to effectively handle both ID and OOD data. Experimental results demonstrate that our proposed method outperforms existing works on various datasets, confirming its advantages.* </p>


## Installation 
For installation and other package requirements, please follow the instructions detailed in [INSTALL.md](docs/INSTALL.md). 


## Data Preparation
Please follow the instructions at [DATASETS.md](docs/DATASETS.md) to prepare all datasets.


## Training and Evaluation
Please refer to the [TRAIN.md](docs/TRAIN.md) for detailed instructions on training/running our three ensemble strategies.


## Citation
If you find our work or this repository useful, please consider giving a star :star: and citation.
```bibtex
@article{lu2023beyond,
  title={Beyond Sole Strength: Customized Ensembles for Generalized Vision-Language Models},
  author={Lu, Zhihe and Bai, Jiawang and Li, Xin and Xiao, Zeyu and Wang, Xinchao},
  journal={arXiv preprint arXiv:2311.17091},
  year={2023}
}
```


## Contact
If you have any questions, please create an issue on this repository or contact at zhihelu.academic[at]gmail.com.


## Acknowledgements
Our code is based on [PromptSRC](https://github.com/muzairkhattak/PromptSRC), [MaPLe](https://github.com/muzairkhattak/multimodal-prompt-learning) and [CoCoOp and CoOp](https://github.com/KaiyangZhou/CoOp) repositories. We thank the authors for releasing their code. If you use our code, please consider citing these works as well.

