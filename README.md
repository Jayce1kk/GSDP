# A Graph-Based Synthetic Data Pipeline for Scaling High-Quality Reasoning Instructions



-----

<a href='#'><img src='https://img.shields.io/badge/Project-Page-Green'></a>
<a href='https://arxiv.org/abs/2412.08864'><img src='https://img.shields.io/badge/Paper-PDF-orange'></a> 
<a href='https://github.com/Jayce1kk/GSDP/blob/main/sampled_GSDP_20K.jsonl'><img src='https://img.shields.io/badge/Dataset-HuggingFace-blue'></a>

**This work was done during my internship at [Beijing Yuanshi Technology](https://huggingface.co/MetaStoneTec) and contributed to the training data for the [MetaStone-L1-7B](https://huggingface.co/MetaStoneTec/MetaStone-L1-7B#citation) model.**

-----------

### Updates

- 2024-12-12: 📄 Our paper is now available on [Arxiv](https://arxiv.org/abs/2412.08864).
- 2025-4-10: We have publicly released [20K samples](https://github.com/Jayce1kk/GSDP/blob/main/sampled_GSDP_20K.jsonl) from the GSDP-MATH dataset. This is a randomly sampled subset from GSDP-MATH.

### TODO

- We will open-source the **complete data, synthsis pipleline and models** after this manuscript being accept immediately.

### Overview

Synthesizing high-quality reasoning data for continual training has proven effective in enhancing the reasoning capabilities of Large Language Models (LLMs). However, previous synthetic approaches struggle to scale up data cost-efficiently and often generate data similar to the seed. In this paper, we propose the Graph-based Synthetic Data Pipeline (GSDP), an elegant and efficient framework for scaling high-quality reasoning instructions. Inspired by the cognitive mechanism in human learning, we extract knowledge points from seed data and construct a knowledge point relationships graph to explore their interconnections. We innovatively propose to leverage both explicit and implicit relationships in the graph for new data synthesis, which achieves a 255-fold data expansion and generates more diverse data. Furthermore, GSDP, powered by open-source models, produces synthesis quality comparable to GPT-4-0613 while keeping costs 100 times lower. Focusing on the challenging domain of mathematical reasoning, we present the GSDP-MATH dataset comprising over 1.91 million math question-solution pairs. Experimental results demonstrate that GSDP-MATH features superior data quality, and models fine-tuned on it outperform other methods in mathematical and out-of-domain reasoning tasks.

### Applicable Domains
This synthetic data pipeline is applicable to mathematics, coding, and most scientific domains.

## Citation

```bibtext
@article{wang2024graph,
  title={A Graph-Based Synthetic Data Pipeline for Scaling High-Quality Reasoning Instructions},
  author={Wang, Jiankang and Xu, Jianjun and Wang, Xiaorui and Wang, Yuxin and Xing, Mengting and Fang, Shancheng and Chen, Zhineng and Xie, Hongtao and Zhang, Yongdong},
  journal={arXiv preprint arXiv:2412.08864},
  year={2024}
}
```
