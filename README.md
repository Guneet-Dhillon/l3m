# L3Ms — Lagrange Large Language Models

This repository contains the code (coming soon) for the paper:

[Guneet Singh Dhillon](https://guneet-dhillon.github.io), [Xingjian Shi](https://sxjscience.github.io), [Yee Whye Teh](https://www.stats.ox.ac.uk/~teh/), [Alex Smola](https://alex.smola.org)  
**L3Ms — Lagrange Large Language Models** ([pdf](https://arxiv.org/pdf/2410.21533))  
*In Proceedings of the International Conference on Learning Representations (ICLR), 2025*

## Abstract

Supervised fine-tuning (SFT) and alignment of large language models (LLMs) are key steps in providing a good user experience. However, the concept of an appropriate alignment is inherently application-dependent, and current methods often rely on heuristic choices to drive optimization. In this work, we formulate SFT and alignment as a constrained optimization problem: the LLM is fine-tuned on a task while being required to meet application-specific requirements, without resorting to heuristics. To solve this, we propose Lagrange Large Language Models (L3Ms), which employ logarithmic barriers to enforce the constraints. This approach allows for the customization of L3Ms across diverse applications while avoiding heuristic-driven processes. We experimentally demonstrate the versatility and efficacy of L3Ms in achieving tailored alignments for various applications.

## Citation

If you use this code for your research, please cite our paper:
```
@inproceedings{dhillon2025lms,
  title={L3Ms {\textemdash} Lagrange Large Language Models},
  author={Guneet S. Dhillon and Xingjian Shi and Yee Whye Teh and Alex Smola},
  booktitle={The Thirteenth International Conference on Learning Representations},
  year={2025},
  url={https://openreview.net/forum?id=ULGbw2URE3}
}
```
