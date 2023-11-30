---
layout: post
title: Introducing Frugal Prompting
date:   2023-11-29
categories: nlp dialog gpt-3 prompting
---

<!-- ![FrugalPrompting](assets/frugal-standardprompting.drawio.png) -->

<!-- ## Table of Contents

- [Abstract](#abstract)
- [Paper](#paper)
- [Getting Access](#getting-access-to-the-source-code-or-pretrained-models)
- [Intuition](#intuition)
- [Results](#results)
- [Error Analysis](#error-analysis)
- [Authors](#contributors)
- [Acknowledgements](#acknowledgements) -->


## Abstract

The use of large language models (LLMs) in natural language processing (NLP) tasks is rapidly increasing, leading to changes in how researchers approach problems in the field. To fully utilize these models' abilities, a better understanding of their behavior for different input protocols is required. With LLMs, users can directly interact with the models through a text-based interface to define and solve various tasks. Hence, understanding the conversational abilities of these LLMs, which may not have been specifically trained for dialog modeling, is also important. This study examines different approaches for building dialog systems using LLMs by considering various aspects of the prompt. As part of prompt tuning, we experiment with various ways of providing instructions, exemplars, current query and additional context. The research also analyzes the representations of dialog history that have the optimal usable-information density. Based on the findings, the paper suggests more compact ways of providing dialog history information while ensuring good performance and reducing model's inference-API costs. The research contributes to a better understanding of how LLMs can be effectively used for building interactive systems.

## Paper

- The FrugalPrompting approach is proposed in our EMNLP 2023 paper - [**Frugal Prompting for Dialog Models**](https://arxiv.org/abs/2305.14919).

## Source Code

- The source code for the FrugalPrompting approach is available at [**bsantraigi/FrugalPrompting**](https://github.com/bsantraigi/Frugal-Prompting).

<!-- ### Note

The requesting third party
1. **Can download and use these deliverables for research as well as commercial use,**
2. **Modify it as they like but should include citation to our work and include this readme**, and
3. **Cannot redistribute strictly to any other organization.** -->

**Cite As**

```bibtex
@inproceedings{santra2022representation,
  title={Frugal Prompting for Dialog Models},
  author={Santra, Bishal and Basak, Sakya and De, Abhinandan and Gupta, Manish and Goyal, Pawan},
  booktitle={Proceedings of the 2023 Conference of Empirical Methods in Natural Language Processing (EMNLP)},
  year={2023}
}
```

<!-- ## Intuition

![DMI_Cover](assets/DMI-coverimage.png)


## Results

![results_combined](assets/results-combined.png)
![results_ablations](assets/results-ablations.png)

## Error Analysis

![eintent-error](assets/eintent_error_analysis.png)
 -->
## Authors

- [Bishal Santra](https://bsantraigi.github.io)
- Sakya Basak
- Abhinandan Dey
- [Manish Gupta](https://www.microsoft.com/en-us/research/people/gmanish/)
- [Pawan Goyal](https://cse.iitkgp.ac.in/~pawang/index.html)

## Acknowledgements

This work was partially supported by Microsoft Academic Partnership Grant (MAPG) 2022. The first author was also supported by Prime Minister’s Research Fellowship (PMRF), India. Conference travel was funded by CNeRG Travel Grant.

