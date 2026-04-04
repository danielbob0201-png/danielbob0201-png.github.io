---
title: "In-Context Sharpness as Alerts: An Inner Representation Perspective for Hallucination Mitigation"
authors:
  - Shiqi Chen
  - Miao Xiong
  - Junteng Liu
  - Zhengxuan Wu
  - Teng Xiao
  - Siyang Gao
  - Junxian He
publication_types: ["1"]
publication: ICML 2024
date: 2024-07-08
---
# Abstract

Large language models (LLMs) hallucinate — generating content that is irrational or fails to follow factual knowledge. We study the internal representations of LLMs during in-context learning to detect and mitigate hallucinations. We discover that the in-context sharpness, i.e., the degree to which the representation concentrates on a single direction, can serve as an effective signal for hallucination detection. By analyzing the inner representations of LLMs when processing in-context examples, we find that hallucinated generations are associated with different sharpness patterns compared to non-hallucinated ones. Based on this insight, we propose a method that uses in-context sharpness as an alert signal to detect potential hallucinations during generation.
DOI: 10.48550/arXiv.2312.01568
# Code
[[Code]](https://github.com/LJT-Homepage/LLMShap)
# PDF
[[PDF]](https://arxiv.org/abs/2312.01568)
# BibTeX
```bibtex
@inproceedings{chen2024incontextsharpness,
  title     = {In-Context Sharpness as Alerts: An Inner Representation Perspective for Hallucination Mitigation},
  author    = {Chen, Shiqi and Xiong, Miao and Liu, Junteng and Wu, Zhengxuan and Xiao, Teng and Gao, Siyang and He, Junxian},
  booktitle = {Proceedings of the 41st International Conference on Machine Learning},
  year      = {2024}
}
```
