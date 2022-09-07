## awesome-graph-transformer

![PRs Welcome](https://img.shields.io/badge/PRs-Welcome-green)  [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) 
<!--![PRs Welcome](https://img.shields.io/badge/PRs-Welcome-green)  [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) ![Stars](https://img.shields.io/github/stars/ChandlerBang/awesome-self-supervised-gnn?color=yellow)  ![Forks](https://img.shields.io/github/forks/ChandlerBang/awesome-self-supervised-gnn?color=blue&label=Fork) -->

This repository contains a list of papers on the Graph Transformers; we categorize them based on their detailed techniques.

We will try to make this list updated. If you found any error or any missed paper, please don't hesitate to open an issue or pull request.

### Structural Encoding / Postional Encoding for Graph Transformers
#### Spectral Positional Encoding
1. Rethinking Graph Transformers with Spectral Attention. NeurIPS 2021. [[paper]](https://arxiv.org/abs/2106.03893)
1. A Generalization of Transformer Networks to Graphs. AAAI workshop 2021. [[paper]](https://arxiv.org/pdf/2012.09699)

#### Other Structure-aware Encoding
1. Do Transformers Really Perform Bad for Graph Representation? NeurIPS 2021. [[paper]](https://arxiv.org/abs/2106.05234)
1. Graph Neural Networks with Learnable Structural and Positional Representations. ICLR 2022. [[paper]](https://arxiv.org/abs/2110.07875)
1. GRPE: Relative Positional Encoding for Graph Transformer. ICLR 2022 Workshop MLDD [[paper]](https://openreview.net/forum?id=GNfAFN_p1d)

#### Graph Neural Network as Structural Encoder
1. Global Self-Attention as a Replacement for Graph Convolution. KDD 2022. [[paper]](https://arxiv.org/abs/2108.03348)
1. GraphiT: Encoding Graph Structure in Transformers. Arxiv 2021. [[paper]](https://arxiv.org/abs/2106.05667)
1. Structure-Aware Transformer for Graph Representation Learning. ICML 2022. [[paper]](https://proceedings.mlr.press/v162/chen22r.html)
1. Recipe for a General, Powerful, Scalable Graph Transformer. Arxiv 2022. [[paper]](https://arxiv.org/abs/2205.12454)
1. 

### Scalability of Graph Transformers (Graph Transformers on Large Graphs)
#### Transformers with Sampling
1. A Self-Attention Network based Node Embedding Model. ECML-PKDD 2020. [[paper]](https://arxiv.org/abs/2006.12100)
1. Heterogeneous Graph Transformer. WWW 2020. [[paper]](https://arxiv.org/abs/2003.01332)
1. Gophormer: Ego-Graph Transformer for Node Classification. Arxiv 2021. [[paper]](https://arxiv.org/abs/2110.13094)
1. Coarformer: Transformer for large graph via graph coarsening. Openreview 2021. [[paper]](https://openreview.net/forum?id=fkjO_FKVzw)

#### Transformers with Adapted Attention
1. From block-Toeplitz matrices to differential equations on graphs: towards a general theory for scalable masked Transformers. Arxiv 2022. [[paper]](https://arxiv.org/abs/2107.07999)
1. Recipe for a General, Powerful, Scalable Graph Transformer. Arxiv 2022. [[paper]](https://arxiv.org/abs/2205.12454)
1. Deformable Graph Transformer. Arxiv 2022. [[paper]](https://arxiv.org/abs/2206.14337)

### Applications of Graph Transformers (Molecules, Texts)
1. Modeling Graph Structure in Transformer for Better AMR-to-Text Generation. EMNLP 2019. [[paper]](https://aclanthology.org/D19-1548/)
1. Heterogeneous Graph Transformer for Graph-to-Sequence Learning. ACL 2020. [[paper]](https://aclanthology.org/2020.acl-main.640/)
1. Molecule Attention Transformer. Arxiv 2020. [[paper]](https://arxiv.org/abs/2002.08264)
1. Interpretable Rumor Detection in Microblogs by Attending to User Interactions. AAAI 2020. [[paper]](https://ojs.aaai.org/index.php/AAAI/article/view/6405)
1. Graph Transformer for Graph-to-Sequence Learning. AAAI 2020. [[paper]](https://ojs.aaai.org/index.php/AAAI/article/view/6243)
1. Self-Supervised Graph Transformer on Large-Scale Molecular Data. NeurIPS 2020. [[paper]](https://proceedings.neurips.cc/paper/2020/hash/94aef38441efa3380a3bed3faf1f9d5d-Abstract.html)
1. SE(3)-Transformers: 3D Roto-Translation Equivariant Attention Networks. NeurIPS 2020. [[paper]](https://proceedings.neurips.cc/paper/2020/hash/15231a7ce4ba789d13b722cc5c955834-Abstract.html)
1. Modeling Graph Structure via Relative Position for Text Generation from Knowledge Graphs. TextGraphs 2021. [[paper]](https://arxiv.org/abs/2006.09242)
1. GraphFormers: GNN-nested Transformers for Representation Learning on Textual Graph. NeurIPS 2021. [[paper]](https://arxiv.org/pdf/2105.02605.pdf)
1. Systematic Generalization with Edge Transformers. NeurIPS 2021. [[paper]](https://proceedings.neurips.cc/paper/2021/file/0a4dc6dae338c9cb08947c07581f77a2-Paper.pdf)
1. Mesh Graphormer. ICCV 2021. [[paper]](https://openaccess.thecvf.com/content/ICCV2021/html/Lin_Mesh_Graphormer_ICCV_2021_paper.html)
1. Relative Molecule Self-Attention Transformer. Arxiv 2021. [[paper]](https://arxiv.org/abs/2110.05841)
1. Neighbour Interaction based Click-Through Rate Prediction via Graph-masked Transformer. Arxiv 2022. [[paper]](https://arxiv.org/abs/2201.13311)
1. Equivariant Transformers for Neural Network based Molecular Potentials. ICLR 2022. [[paper]](https://openreview.net/forum?id=zNHzqZ9wrRB)

### Pre-training with Graph Transformers
1. Selfsupervised graph transformer on large-scale molecular data. NeurIPS 2020. [[paper]](https://arxiv.org/abs/2007.02835)
1. Graph-Bert: Only Attention is Needed for Learning Graph Representations. Arxiv 2020. [[paper]](https://arxiv.org/abs/2001.05140)
1. Graph Masked Autoencoders with Transformers. Arxiv 2022. [[paper]](https://arxiv.org/abs/2202.08391)

### Survey
1. Transformer for Graphs: An Overview from Architecture Perspective. Arxiv 2022. [[paper]](https://arxiv.org/abs/2202.08455)

### Uncategorized
1. Transformers Generalize DeepSets and Can be Extended to Graphs & Hypergraphs. NeurIPS 2021. [[paper]](https://proceedings.neurips.cc/paper/2021/file/ec0f40c389aeef789ce03eb814facc6c-Paper.pdf)
1. Representing Long-Range Context for Graph Neural Networks with Global Attention. NeurIPS 2021. [[paper]](https://proceedings.neurips.cc/paper/2021/file/6e67691b60ed3e4a55935261314dd534-Paper.pdf)
1. Universal Graph Transformer Self-Attention Networks. WWW 2022. [[paper]](https://dl.acm.org/doi/abs/10.1145/3487553.3524258)
1. Masked Label Prediction: Unified Message Passing Model for Semi-Supervised Classification. IJCAI 2021. [[paper]](https://www.ijcai.org/proceedings/2021/0214)
