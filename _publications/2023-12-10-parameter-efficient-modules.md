---
title: "Composing Parameter-Efficient Modules with Arithmetic Operations"
authors:
  - Jinghan Zhang
  - Shiqi Chen
  - Junteng Liu
  - Junxian He
publication_types: ["1"]
publication: NeurIPS 2023
date: 2023-12-10
---
# Abstract

Parameter-efficient fine-tuning (PEFT) methods, such as LoRA and adapters, have become popular for efficiently adapting large pre-trained models to downstream tasks. However, combining multiple PEFT modules for multi-task learning remains an open challenge. We explore composing parameter-efficient modules using arithmetic operations, which enables us to effectively leverage knowledge from multiple tasks. We show that module arithmetic, such as addition and subtraction, can effectively merge or separate task-specific adaptations in the weight space. Our experiments demonstrate that the composed model achieves competitive or superior performance compared to jointly trained baselines, while only requiring training on individual tasks.
# Code
[[Code]](https://github.com/LJT-Homepage/MoE-Arithmetic)
# PDF
[[PDF]](https://arxiv.org/abs/2308.15686)
# BibTeX
```bibtex
@inproceedings{zhang2023composing,
  title     = {Composing Parameter-Efficient Modules with Arithmetic Operations},
  author    = {Zhang, Jinghan and Chen, Shiqi and Liu, Junteng and He, Junxian},
  booktitle = {Advances in Neural Information Processing Systems},
  year      = {2023}
}
```
