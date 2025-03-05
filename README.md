## awesome-graph-transformer

![PRs Welcome](https://img.shields.io/badge/PRs-Welcome-green)  [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) ![Created](https://img.shields.io/badge/Created-2021--09-green.svg) ![Stars](https://img.shields.io/github/stars/ChandlerBang/awesome-graph-transformer?color=yellow)

<!--![PRs Welcome](https://img.shields.io/badge/PRs-Welcome-green)  [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) ![Stars](https://img.shields.io/github/stars/ChandlerBang/awesome-self-supervised-gnn?color=yellow)  ![Forks](https://img.shields.io/github/forks/ChandlerBang/awesome-self-supervised-gnn?color=blue&label=Fork) -->

This repository contains a list of papers on the Graph Transformers; we categorize them based on their detailed techniques.

We will try to make this list updated. If you found any error or any missed paper, please don't hesitate to open an issue or pull request.

### Structural Encoding / Postional Encoding for Graph Transformers
#### Spectral Positional Encoding
1. Rethinking Graph Transformers with Spectral Attention. NeurIPS 2021. [[paper]](https://arxiv.org/abs/2106.03893)
1. A Generalization of Transformer Networks to Graphs. AAAI workshop 2021. [[paper]](https://arxiv.org/pdf/2012.09699)
1. Transformers Meet Directed Graphs. ICML 2023. [[paper]](https://dl.acm.org/doi/10.5555/3618408.3618855)

#### Other Structure-aware Encoding
1. Do Transformers Really Perform Bad for Graph Representation? NeurIPS 2021. [[paper]](https://arxiv.org/abs/2106.05234)
1. Graph Neural Networks with Learnable Structural and Positional Representations. ICLR 2022. [[paper]](https://arxiv.org/abs/2110.07875)
1. GRPE: Relative Positional Encoding for Graph Transformer. ICLR 2022 Workshop MLDD [[paper]](https://openreview.net/forum?id=GNfAFN_p1d)
1. Global Self-Attention as a Replacement for Graph Convolution. KDD 2022. [[paper]](https://arxiv.org/abs/2108.03348)
1. Pure Transformers are Powerful Graph Learners. NeurIPS 2022. [[paper]](https://arxiv.org/abs/2207.02505)
1. Are More Layers Beneficial to Graph Transformers? ICLR 2023. [[paper]](https://openreview.net/forum?id=uagC-X9XMi8)
1. Graph Inductive Biases in Transformers without Message Passing. ICML 2023. [[paper]](https://dl.acm.org/doi/10.5555/3618408.3619379)
1. Rethinking Structural Encodings: Adaptive Graph Transformer for Node Classification Task. WWW 2023. [[paper]](https://dl.acm.org/doi/abs/10.1145/3543507.3583464)
1. HINormer: Representation Learning On Heterogeneous Information Networks with Graph Transformer. WWW 2023. [[paper]](https://dl.acm.org/doi/abs/10.1145/3543507.3583493)
1. Graph Propagation Transformer for Graph Representation Learning. IJCAI 2023. [[paper]](https://www.ijcai.org/proceedings/2023/0396.pdf)
1. LGI-GT: Graph Transformers with Local and Global Operators Interleaving. IJCAI 2023. [[paper]](https://www.ijcai.org/proceedings/2023/0501.pdf)
1. On Structural Expressive Power of Graph Transformers. KDD 2023. [[paper]](https://dl.acm.org/doi/10.1145/3580305.3599451)
1. LPFormer: An Adaptive Graph Transformer for Link Prediction. Arxiv 2024. [[paper]](https://arxiv.org/abs/2310.11009)
1. Triplet Interaction Improves Graph Transformers: Accurate Molecular Graph Learning with Triplet Graph Transformers. Arxiv 2024. [[paper]](https://arxiv.org/abs/2402.04538)
   
#### Graph Neural Networks as Structural Encoder
1. GraphiT: Encoding Graph Structure in Transformers. arXiv 2021. [[paper]](https://arxiv.org/abs/2106.05667)
1. Representing Long-Range Context for Graph Neural Networks with Global Attention. NeurIPS 2021. [[paper]](https://proceedings.neurips.cc/paper/2021/file/6e67691b60ed3e4a55935261314dd534-Paper.pdf)
1. Structure-Aware Transformer for Graph Representation Learning. ICML 2022. [[paper]](https://proceedings.mlr.press/v162/chen22r.html)
1. Recipe for a General, Powerful, Scalable Graph Transformer. NeurIPS 2022. [[paper]](https://arxiv.org/abs/2205.12454)

### Scalability of Graph Transformers (Graph Transformers on Large Graphs)
#### Transformers with Sampling
1. A Self-Attention Network based Node Embedding Model. ECML-PKDD 2020. [[paper]](https://arxiv.org/abs/2006.12100)
1. Heterogeneous Graph Transformer. WWW 2020. [[paper]](https://arxiv.org/abs/2003.01332)
1. Gophormer: Ego-Graph Transformer for Node Classification. arXiv 2021. [[paper]](https://arxiv.org/abs/2110.13094)
1. Coarformer: Transformer for large graph via graph coarsening. Openreview 2021. [[paper]](https://openreview.net/forum?id=fkjO_FKVzw)
1. Hierarchical Graph Transformer with Adaptive Node Sampling. NeurIPS 2022. [[paper]](https://arxiv.org/abs/2210.03930)
1. NAGphormer: A Tokenized Graph Transformer for Node Classification in Large Graphs. ICLR 2023. [[paper]](https://openreview.net/forum?id=8KYeilT3Ow)
1. Hierarchical Transformer for Scalable Graph Learning. IJCAI 2023. [[paper]](https://www.ijcai.org/proceedings/2023/0523.pdf)
1. LPFormer: An Adaptive Graph Transformer for Link Prediction. Arxiv 2024. [[paper]](https://arxiv.org/abs/2310.11009)

#### Transformers with Adapted Attention
1. From block-Toeplitz matrices to differential equations on graphs: towards a general theory for scalable masked Transformers. ICML 2022. [[paper]](https://arxiv.org/abs/2107.07999)
1. Recipe for a General, Powerful, Scalable Graph Transformer. NeurIPS 2022. [[paper]](https://arxiv.org/abs/2205.12454)
1. Deformable Graph Transformer. arXiv 2022. [[paper]](https://arxiv.org/abs/2206.14337)
1. NodeFormer: A Scalable Graph Structure Learning Transformer for Node Classification. NeurIPS 2022. [[paper]](https://openreview.net/forum?id=sMezXGG5So)
1. DIFFormer: Scalable (Graph) Transformers Induced by Energy Constrained Diffusion. ICLR 2023. [[paper]](https://arxiv.org/abs/2301.09474)
1. GOAT: A Global Transformer on Large-scale Graphs. ICML 2023. [[paper]](https://dl.acm.org/doi/10.5555/3618408.3619124)
1. EXPHORMER: Sparse Transformers for Graphs. ICML 2023. [[paper]](https://dl.acm.org/doi/10.5555/3618408.3619718)
1. KDLGT: A Linear Graph Transformer Framework via Kernel Decomposition Approach. IJCAI 2023. [[paper]](https://www.ijcai.org/proceedings/2023/0263.pdf)
1. Gapformer: Graph Transformer with Graph Pooling for Node Classification. IJCAI 2023. [[paper]](https://www.ijcai.org/proceedings/2023/0244.pdf)
1. Polynormer: Polynomial-Expressive Graph Transformer in Linear Time. ICLR 2024. [[paper]](https://openreview.net/forum?id=hmv1LpNfXa)

### Applications of Graph Transformers (Molecules, Texts, Knowledge Graphs, Recommendation, Medical, Traffic, etc)
1. Modeling Graph Structure in Transformer for Better AMR-to-Text Generation. EMNLP 2019. [[paper]](https://aclanthology.org/D19-1548/)
1. Heterogeneous Graph Transformer for Graph-to-Sequence Learning. ACL 2020. [[paper]](https://aclanthology.org/2020.acl-main.640/)
1. Molecule Attention Transformer. arXiv 2020. [[paper]](https://arxiv.org/abs/2002.08264)
1. Interpretable Rumor Detection in Microblogs by Attending to User Interactions. AAAI 2020. [[paper]](https://ojs.aaai.org/index.php/AAAI/article/view/6405)
1. Graph Transformer for Graph-to-Sequence Learning. AAAI 2020. [[paper]](https://ojs.aaai.org/index.php/AAAI/article/view/6243)
1. Self-Supervised Graph Transformer on Large-Scale Molecular Data. NeurIPS 2020. [[paper]](https://proceedings.neurips.cc/paper/2020/hash/94aef38441efa3380a3bed3faf1f9d5d-Abstract.html)
1. SE(3)-Transformers: 3D Roto-Translation Equivariant Attention Networks. NeurIPS 2020. [[paper]](https://proceedings.neurips.cc/paper/2020/hash/15231a7ce4ba789d13b722cc5c955834-Abstract.html)
1. Modeling Graph Structure via Relative Position for Text Generation from Knowledge Graphs. TextGraphs 2021. [[paper]](https://arxiv.org/abs/2006.09242)
1. GraphFormers: GNN-nested Transformers for Representation Learning on Textual Graph. NeurIPS 2021. [[paper]](https://arxiv.org/pdf/2105.02605.pdf)
1. Systematic Generalization with Edge Transformers. NeurIPS 2021. [[paper]](https://proceedings.neurips.cc/paper/2021/file/0a4dc6dae338c9cb08947c07581f77a2-Paper.pdf)
1. Mesh Graphormer. ICCV 2021. [[paper]](https://openaccess.thecvf.com/content/ICCV2021/html/Lin_Mesh_Graphormer_ICCV_2021_paper.html)
1. Relative Molecule Self-Attention Transformer. arXiv 2021. [[paper]](https://arxiv.org/abs/2110.05841)
1. Masked Label Prediction: Unified Message Passing Model for Semi-Supervised Classification. IJCAI 2021. [[paper]](https://www.ijcai.org/proceedings/2021/0214)
1. A graph-transformer for whole slide image classification. TMI 2023. [[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9779215)
1. Neighbour Interaction based Click-Through Rate Prediction via Graph-masked Transformer. arXiv 2022. [[paper]](https://arxiv.org/abs/2201.13311)
1. Equivariant Transformers for Neural Network based Molecular Potentials. ICLR 2022. [[paper]](https://openreview.net/forum?id=zNHzqZ9wrRB)
1. Periodic Graph Transformers for Crystal Material Property Prediction. NeurIPS 2022. [[pper]](https://arxiv.org/abs/2209.11807)
1. Brain Network Transformer. NeurIPS 2022. [[paper]](https://openreview.net/forum?id=1cJ1cbA6NLN)
1. Multi-Relational Graph Transformer for Automatic Short Answer Grading. NAACL-HLT 2022. [[paper]](https://aclanthology.org/2022.naacl-main.146.pdf)
1. Mask and Reason: Pre-Training Knowledge Graph Transformers for Complex Logical Queries. KDD 2022. [[paper]](https://dl.acm.org/doi/10.1145/3534678.3539472)
1. Relphormer: Relational Graph Transformer for Knowledge Graph Representations. arXiv 2022. [[paper]](https://arxiv.org/abs/2205.10852)
1. CoAtGIN: Marrying Convolution and Attention for Graph-based Molecule Property Prediction. BIBM 2022. [[paper]](https://ieeexplore.ieee.org/abstract/document/9995324)
1. GRIP: Graph Representation of Immune Repertoire Using Graph Neural Network and Transformer. AAAI 2023. [[paper]](https://ojs.aaai.org/index.php/AAAI/article/view/25645)
1. MulGT: Multi-Task Graph-Transformer with Task-Aware Knowledge Injection and Domain Knowledge-Driven Pooling for Whole Slide Image Analysis. AAAI 2023. [[paper]](https://ojs.aaai.org/index.php/AAAI/article/view/25471)
1. Inductive Graph Transformer for Delivery Time Estimation. WSDM 2023. [[paper]](https://dl.acm.org/doi/10.1145/3539597.3570409)
1. LightGT: A Light Graph Transformer for Multimedia Recommendation. SIGIR 2023. [[paper]](https://dl.acm.org/doi/10.1145/3539618.3591716)
1. Graph Transformer for Recommendation. SIGIR 2023. [[paper]](https://dl.acm.org/doi/abs/10.1145/3539618.3591723)
1. DiGress: Discrete Denoising diffusion for graph generation. ICLR 2023. [[paper]](https://arxiv.org/abs/2209.14734)
1. Relational Attention: Generalizing Transformers for Graph-Structured Tasks. ICLR 2023. [[paper]](https://openreview.net/forum?id=cFuMmbWiN6)
1. Heterformer: A Transformer Architecture for Node Representation Learning on Heterogeneous Text-Rich Networks. arXiv 2022. [[paper]](https://arxiv.org/abs/2205.10282)
1. Edgeformers: Graph-Empowered Transformers for Representation Learning on Textual-Edge Networks. ICLR 2023. [[paper]](https://arxiv.org/abs/2302.11050)
1. Single-Cell Multimodal Prediction via Transformers. CIKM 2023. [[paper]](https://arxiv.org/pdf/2303.00233.pdf)
1. Single Cells Are Spatial Tokens: Transformers for Spatial Transcriptomic Data Imputation. arXiv 2023. [[paper]](https://arxiv.org/pdf/2302.03038.pdf)
1. A Retrieve-and-Read Framework for Knowledge Graph Link Prediction. CIKM 2023. [[paper]](https://arxiv.org/pdf/2212.09724.pdf)
1. GTMGC: Using Graph Transformer to Predict Molecule’s Ground-State Conformation. ICLR 2024. [[paper]](https://openreview.net/forum?id=F7QnIKlC1N)
1. Graph Transformers on EHRs: Better Representation Improves Downstream Performance. ICLR 2024. [[paper]](https://openreview.net/forum?id=pe0Vdv7rsL)


### Pre-training with Graph Transformers
1. Self-supervised graph transformer on large-scale molecular data. NeurIPS 2020. [[paper]](https://arxiv.org/abs/2007.02835)
1. Graph-Bert: Only Attention is Needed for Learning Graph Representations. arXiv 2020. [[paper]](https://arxiv.org/abs/2001.05140)
1. Pre-training Graph Transformer with Multimodal Side Information for Recommendation. MM 2021. [[paper]](https://dl.acm.org/doi/abs/10.1145/3474085.3475709)
1. Graph Masked Autoencoders with Transformers. arXiv 2022. [[paper]](https://arxiv.org/abs/2202.08391)
1. A Graph is Worth K Words: Euclideanizing Graph using Pure Transformer. ICML 2024. [[paper]](https://arxiv.org/abs/2402.02464)

### Survey
1. Transformer for Graphs: An Overview from Architecture Perspective. arXiv 2022. [[paper]](https://arxiv.org/abs/2202.08455)
1. A Survey on Graph Neural Networks and Graph Transformers in Computer Vision: A Task-Oriented Perspective. arXiv 2022. [[paper]](https://arxiv.org/abs/2209.13232)
1. Attending to Graph Transformers. arXiv 2022. [[paper]](https://arxiv.org/abs/2302.04181)

### Neural Architecture Search (NAS) for Graph Transformers
1. AutoGT: Automated Graph Transformer Architecture Search. ICLR 2023. [[paper]](https://openreview.net/forum?id=GcM7qfl5zY)

### Benchmarks and Analyses
1. Transformers Generalize DeepSets and Can be Extended to Graphs & Hypergraphs. NeurIPS 2021. [[paper]](https://proceedings.neurips.cc/paper/2021/file/ec0f40c389aeef789ce03eb814facc6c-Paper.pdf)
1. Universal Graph Transformer Self-Attention Networks. WWW 2022. [[paper]](https://dl.acm.org/doi/abs/10.1145/3487553.3524258)
1. Long Range Graph Benchmark. NeurIPS 2022. [[paper]](https://openreview.net/forum?id=in7XC5RcjEn)
1. Rethinking the Expressive Power of GNNs via Graph Biconnectivity. ICLR 2023. [[paper]](https://openreview.net/forum?id=r9hNv76KoT3)
1. On the Connection Between MPNN and Graph Transformer. ICML 2023. [[paper]](https://proceedings.mlr.press/v202/cai23b/cai23b.pdf)
1. A Generalization of ViT/MLP-Mixer to Graphs. ICML 2023. [[paper]](https://dl.acm.org/doi/10.5555/3618408.3618925)
1. Demystifying Oversmoothing in Attention-Based Graph Neural Networks. NeurIPS 2023. [[paper]](https://openreview.net/forum?id=Kg65qieiuB)
1. Transformers vs. Message Passing GNNs: Distinguished in Uniform. ICLR 2024. [[paper]](https://openreview.net/forum?id=AcSChDWL6V)

