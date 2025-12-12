# Awesome Continual Learning

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of awesome papers, resources, and tools for Continual Learning (also known as Lifelong Learning, Incremental Learning, or Never-Ending Learning).

## Table of Contents

- [Prompt-based](#prompt-based)
- [Regularization-based](#regularization-based)
- [Replay-based](#replay-based)
- [Architecture-based](#architecture-based)
- [Meta-Learning-based](#meta-learning-based)
- [Optimization-based](#optimization-based)
- [Surveys and Benchmarks](#surveys-and-benchmarks)

## Prompt-based

State-of-the-art papers on prompt-based continual learning approaches:

* **Learning to Prompt for Continual Learning** (CVPR 2022)
  - Paper: [https://arxiv.org/abs/2112.08654](https://arxiv.org/abs/2112.08654)
  - Code: [https://github.com/google-research/l2p](https://github.com/google-research/l2p)

* **DualPrompt: Complementary Prompting for Rehearsal-free Continual Learning** (ECCV 2022)
  - Paper: [https://arxiv.org/abs/2204.04799](https://arxiv.org/abs/2204.04799)
  - Code: [https://github.com/google-research/l2p](https://github.com/google-research/l2p)

* **S-Prompts Learning with Pre-trained Transformers: An Occam's Razor for Domain Incremental Learning** (NeurIPS 2022)
  - Paper: [https://arxiv.org/abs/2207.12819](https://arxiv.org/abs/2207.12819)
  - Code: [https://github.com/iamwangyabin/S-Prompts](https://github.com/iamwangyabin/S-Prompts)

* **CODA-Prompt: COntinual Decomposed Attention-based Prompting for Rehearsal-Free Continual Learning** (CVPR 2023)
  - Paper: [https://arxiv.org/abs/2211.13218](https://arxiv.org/abs/2211.13218)
  - Code: [https://github.com/GT-RIPL/CODA-Prompt](https://github.com/GT-RIPL/CODA-Prompt)

* **Continual Vision Transformer (ConViT): Incremental Learning with Attention Maps** (2023)
  - Paper: [https://arxiv.org/abs/2303.15023](https://arxiv.org/abs/2303.15023)

* **Progressive Prompts: Continual Learning for Language Models** (ICLR 2023)
  - Paper: [https://arxiv.org/abs/2301.12314](https://arxiv.org/abs/2301.12314)

* **AttriCLIP: A Non-Incremental Learner for Incremental Knowledge Learning** (CVPR 2023)
  - Paper: [https://arxiv.org/abs/2305.11488](https://arxiv.org/abs/2305.11488)
  - Code: [https://github.com/bhrqw/AttriCLIP](https://github.com/bhrqw/AttriCLIP)

* **PIVOT: Prompting for Video Continual Learning** (CVPR 2023)
  - Paper: [https://arxiv.org/abs/2212.04842](https://arxiv.org/abs/2212.04842)
  - Code: [https://github.com/bhrqw/PIVOT](https://github.com/bhrqw/PIVOT)

## Regularization-based

Methods that use regularization techniques to prevent catastrophic forgetting:

* **Learning without Forgetting (LwF)** (ECCV 2016)
  - Paper: [https://arxiv.org/abs/1606.09282](https://arxiv.org/abs/1606.09282)
  - Code: [https://github.com/lizhitwo/LearningWithoutForgetting](https://github.com/lizhitwo/LearningWithoutForgetting)

* **Elastic Weight Consolidation (EWC)** (PNAS 2017)
  - Paper: [https://arxiv.org/abs/1612.00796](https://arxiv.org/abs/1612.00796)
  - Code: [https://github.com/ariseff/overcoming-catastrophic](https://github.com/ariseff/overcoming-catastrophic)

* **Synaptic Intelligence (SI)** (ICML 2017)
  - Paper: [https://arxiv.org/abs/1703.04200](https://arxiv.org/abs/1703.04200)

* **Memory Aware Synapses (MAS)** (ECCV 2018)
  - Paper: [https://arxiv.org/abs/1711.09601](https://arxiv.org/abs/1711.09601)
  - Code: [https://github.com/rahafaljundi/MAS-Memory-Aware-Synapses](https://github.com/rahafaljundi/MAS-Memory-Aware-Synapses)

## Replay-based

Methods that use memory replay or pseudo-replay to retain previous knowledge:

* **iCaRL: Incremental Classifier and Representation Learning** (CVPR 2017)
  - Paper: [https://arxiv.org/abs/1611.07725](https://arxiv.org/abs/1611.07725)
  - Code: [https://github.com/srebuffi/iCaRL](https://github.com/srebuffi/iCaRL)

* **Gradient Episodic Memory (GEM)** (NeurIPS 2017)
  - Paper: [https://arxiv.org/abs/1706.08840](https://arxiv.org/abs/1706.08840)
  - Code: [https://github.com/facebookresearch/GradientEpisodicMemory](https://github.com/facebookresearch/GradientEpisodicMemory)

* **Dark Experience for General Continual Learning (DER/DER++)** (NeurIPS 2020)
  - Paper: [https://arxiv.org/abs/2004.07211](https://arxiv.org/abs/2004.07211)
  - Code: [https://github.com/aimagelab/mammoth](https://github.com/aimagelab/mammoth)

* **Experience Replay for Continual Learning (ER)** (NeurIPS 2019)
  - Paper: [https://arxiv.org/abs/1902.10486](https://arxiv.org/abs/1902.10486)

## Architecture-based

Methods that use dynamic architectures or parameter isolation:

* **Progressive Neural Networks** (2016)
  - Paper: [https://arxiv.org/abs/1606.04671](https://arxiv.org/abs/1606.04671)

* **PackNet: Adding Multiple Tasks to a Single Network by Iterative Pruning** (CVPR 2018)
  - Paper: [https://arxiv.org/abs/1711.05769](https://arxiv.org/abs/1711.05769)
  - Code: [https://github.com/arunmallya/packnet](https://github.com/arunmallya/packnet)

* **Dynamically Expandable Neural Networks (DEN)** (ICML 2018)
  - Paper: [https://arxiv.org/abs/1708.01547](https://arxiv.org/abs/1708.01547)

## Meta-Learning-based

Methods that use meta-learning principles for continual learning:

* **Meta-Learning Representations for Continual Learning (MRCL)** (NeurIPS 2019)
  - Paper: [https://arxiv.org/abs/1905.12588](https://arxiv.org/abs/1905.12588)
  - Code: [https://github.com/khurramjaved96/mrcl](https://github.com/khurramjaved96/mrcl)

* **Online Meta-Learning (OML)** (ICML 2019)
  - Paper: [https://arxiv.org/abs/1902.08438](https://arxiv.org/abs/1902.08438)

## Optimization-based

Methods that use specialized optimization techniques:

* **Orthogonal Gradient Descent (OGD)** (NeurIPS 2019)
  - Paper: [https://arxiv.org/abs/1910.07104](https://arxiv.org/abs/1910.07104)

* **Adam-NSCL: Continual Learning with the Adam Optimizer** (2020)
  - Paper: [https://arxiv.org/abs/2003.09722](https://arxiv.org/abs/2003.09722)

## Surveys and Benchmarks

Comprehensive surveys and benchmark papers:

* **Continual Lifelong Learning with Neural Networks: A Review** (Neural Networks 2019)
  - Paper: [https://arxiv.org/abs/1802.07569](https://arxiv.org/abs/1802.07569)

* **Three Scenarios for Continual Learning** (NeurIPS 2019 Continual Learning Workshop)
  - Paper: [https://arxiv.org/abs/1904.07734](https://arxiv.org/abs/1904.07734)

* **Continual Learning: A Comparative Study on How to Defy Forgetting** (2019)
  - Paper: [https://arxiv.org/abs/1909.08383](https://arxiv.org/abs/1909.08383)

* **A Continual Learning Survey: Defying Forgetting in Classification Tasks** (TPAMI 2021)
  - Paper: [https://arxiv.org/abs/1909.08383](https://arxiv.org/abs/1909.08383)

* **Continual Learning with Deep Architectures** (2020)
  - Paper: [https://arxiv.org/abs/2008.12748](https://arxiv.org/abs/2008.12748)

---

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For adding new papers, please follow the format:
```
* **Paper Title** (Conference/Journal Year)
  - Paper: [link]
  - Code: [link] (if available)
```

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)