# Awesome Learned Sparse Retrieval
[![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re) ![Project Status](https://img.shields.io/badge/status-active-brightgreen)
<br>
An extensive and commented list of resources on Learned Sparse Retrieval (LSR). Most of the resources below refer to learned sparse representations for text retrieval.

## Contents
- [Awesome Learned Sparse Retrieval](#awesome-learned-sparse-retrieval)
  - [Contents](#contents)
  - [LSR Models](#lsr-models)
  - [Indexing LSR](#indexing-lsr)
    - [Tutorials](#tutorials)
    - [Software Libraries](#software-libraries)
    - [Datasets and Encodings](#datasets-and-encodings)
      - [`MS MARCO v1`](#ms-marco-v1)
      - [`MS MARCO v2`](#ms-marco-v2)
      - [`NQ`](#nq)
      - [`LoTTE-pooled`](#lotte-pooled)
      - [`Quora`](#quora)
    - [List Maintainers (alphabetical order)](#list-maintainers-alphabetical-order)

## LSR Models
- *From Neural Re-Ranking to Neural Ranking: Learning a Sparse Representation for Inverted Indexing*<br>
  Hamed Zamani, Mostafa Dehghani, W. Bruce Croft, Erik Learned-Miller, Jaap Kamps<br>
  CIKM, 2018<br> 📄 [paper](https://dl.acm.org/doi/10.1145/3269206.3271800)
- *Expansion via Prediction of Importance with Contextualization*<br>
  Sean MacAvaney, Franco Maria Nardini, Raffaele Perego, Nicola Tonellotto, Nazli Goharian, Ophir Frieder<br>
  SIGIR, 2020<br> 📄 [paper](https://dl.acm.org/doi/10.1145/3397271.3401262)
- *Context-Aware Term Weighting For First Stage Passage Retrieval*<br>
  Zhuyun Dai, Jamie Callan<br>
  SIGIR, 2020<br> 📄 [paper](https://dl.acm.org/doi/abs/10.1145/3397271.3401204)
- *Learning Passage Impacts for Inverted Indexes*<br>
  Antonio Mallia, Omar Khattab, Torsten Suel, Nicola Tonellotto<br>
  SIGIR, 2021<br> 📄 [paper](https://dl.acm.org/doi/10.1145/3404835.3463030)
- *SPLADE: Sparse Lexical and Expansion Model for First Stage Ranking*<br>
  Thibault Formal, Benjamin Piwowarski, Stephane Clinchant<br>
  SIGIR, 2021<br> 📄 [paper](https://dl.acm.org/doi/10.1145/3404835.3463098)
- *SPLADE v2: Sparse Lexical and Expansion Model for Information Retrieval*<br>
  Thibault Formal, Carlos Lassance, Benjamin Piwowarski, Stephane Clinchant<br>
  CoRR, 2021<br> 📄 [paper](https://arxiv.org/abs/2109.10086)
- *SPARTA: Efficient Open-Domain Question Answering via Sparse Transformer Matching Retrieval*<br>
  Tiancheng Zhao, Xiaopeng Lu, Kyusong Lee<br>
  NAACL, 2021<br> 📄 [paper](https://aclanthology.org/2021.naacl-main.47/)
- *TILDE: Term Independent Likelihood moDEl for Passage Re-ranking*<br>
  Shengyao Zhuang, Guido Zuccon<br>
  SIGIR, 2021<br> 📄 [paper](https://dl.acm.org/doi/10.1145/3404835.3462922)
- *From Distillation to Hard Negative Sampling: Making Sparse Neural IR Models More Effective*<br>
  Thibault Formal, Carlos Lassance, Benjamin Piwowarski, Stephane Clinchant<br>
  SIGIR, 2022<br> 📄 [paper](https://dl.acm.org/doi/10.1145/3477495.3531857)
- *An Efficiency Study for SPLADE Models*<br>
  Carlos Lassance, Stéphane Clinchant<br>
  SIGIR, 2022<br> 📄 [paper](https://dl.acm.org/doi/10.1145/3477495.3531833)
- *Learning a Sparse Representation Model for Neural CLIR*<br>
  Suraj Nair, Eugene Yang, Dawn J Lawrie, James Mayfield, Douglas W. Oard<br>
  DESIRES, 2022<br> 📄 [paper](https://ceur-ws.org/Vol-3480/paper-06.pdf)
- *LexMAE: Lexicon-Bottlenecked Pretraining for Large-Scale Retrieval*<br>
  Tao Shen, Xiubo Geng, Chongyang Tao, Can Xu, Xiaolong Huang, Binxing Jiao, Linjun Yang, Daxin Jiang<br>
  ICLR, 2023<br> 📄 [paper](https://openreview.net/forum?id=PfpEtB3-csK)
- *A Unified Framework for Learned Sparse Retrieval*<br>
  Thong Nguyen, Sean MacAvaney, Andrew Yates<br>
  ECIR, 2023<br> 📄 [paper](https://link.springer.com/chapter/10.1007/978-3-031-28241-6_7)
- *BLADE: Combining Vocabulary Pruning and Intermediate Pretraining for Scaleable Neural CLIR*<br>
  Suraj Nair, Eugene Yang, Dawn Lawrie, James Mayfield, Douglas W. Oard<br>
  SIGIR, 2023<br> 📄 [paper](https://dl.acm.org/doi/10.1145/3539618.3591644)
- *Learning Sparse Lexical Representations Over Specified Vocabularies for Retrieval*<br>
  Jeffrey M Dudek, Weize Kong, Cheng Li, Mingyang Zhang, Michael Bendersky<br>
  CIKM, 2023<br> 📄 [paper](https://dl.acm.org/doi/10.1145/3583780.3615207)
- *Improved Learned Sparse Retrieval with Corpus-Specific Vocabularies*<br>
  Puxuan Yu, Antonio Mallia, Matthias Petri<br>
  ECIR, 2024<br> 📄 [paper](https://link.springer.com/chapter/10.1007/978-3-031-56063-7_12)
- *Two-Step SPLADE: Simple, Efficient and Effective Approximation of SPLADE*<br>
  Carlos Lassance, Hervé Déjean, Stephane Clinchant, Nicola Tonellotto<br>
  ECIR, 2024<br> 📄 [paper](https://link.springer.com/chapter/10.1007/978-3-031-56060-6_23)
- *SPLATE: Sparse Late Interaction Retrieval*<br>
  Thibault Formal, Stephane Clinchant, Hervé Déjean, Carlos Lassance<br>
  SIGIR, 2024<br> 📄 [paper](https://dl.acm.org/doi/10.1145/3626772.3657968)
- *Multimodal Learned Sparse Retrieval with Probabilistic Expansion Control*<br>
  Thong Nguyen, Mariya Hendriksen, Andrew Yates, Maarten de Rijke<br>
  ECIR, 2024<br> 📄 [paper](https://link.springer.com/chapter/10.1007/978-3-031-56060-6_29)
- *DyVo: Dynamic Vocabularies for Learned Sparse Retrieval with Entities*<br>
  Thong Nguyen, Shubham Chatterjee, Sean MacAvaney, Iain Mackie, Jeff Dalton, Andrew Yates<br>
  EMNLP, 2024<br> 📄 [paper](https://aclanthology.org/2024.emnlp-main.45/)
- *SPLADE-v3: New baselines for SPLADE*<br>
  Carlos Lassance, Hervé Déjean, Thibault Formal, Stephane Clinchant<br>
  CoRR, 2024<br> 📄 [paper](https://arxiv.org/abs/2403.06789)
- *Towards Competitive Search Relevance For Inference-Free Learned Sparse Retrievers*<br>
  Zhichao Geng, Dongyu Ru, Yang Yang<br>
  CoRR, 2024<br> 📄 [paper](https://arxiv.org/abs/2411.04403)
- *Mistral-SPLADE: LLMs for better Learned Sparse Retrieval*<br>
  Meet Doshi, Vishwajeet Kumar, Rudra Murthy, Vignesh P, Jaydeep Sen<br>
  CoRR, 2024<br> 📄 [paper](https://arxiv.org/abs/2408.11119)
- *An Alternative to FLOPS Regularization to Effectively Productionize SPLADE-doc*<br>
  Aldo Porco, Dhruv Mehra, Igor Malioutov, Karthik Radhakrishnan, Moniba Keymanesh, Daniel Preotiuc-Pietro, Sean MacAvaney, Pengxiang Cheng<br>
  SIGIR, 2025<br> 📄 [paper](https://dl.acm.org/doi/10.1145/3726302.3730163)
- *Effective Inference-Free Retrieval for Learned Sparse Representations*<br>
  Franco Maria Nardini, Thong Nguyen, Cosimo Rulli, Rossano Venturini, Andrew Yates<br>
  SIGIR, 2025<br> 📄 [paper](https://dl.acm.org/doi/10.1145/3726302.3730185)
- *Exploring $\ell_0$ Sparsification for Inference-free Sparse Retrievers*<br>
  Xinjie Shen, Zhichao Geng, Yang Yang<br>
  SIGIR, 2025<br> 📄 [paper](https://dl.acm.org/doi/10.1145/3726302.3730192)
- *Enhancing Lexicon-Based Text Embeddings with Large Language Models*<br>
  Yibin Lei, Tao Shen, Yu Cao, Andrew Yates<br>
  ACL, 2025<br> 📄 [paper](https://aclanthology.org/2025.acl-long.930)
- *Leveraging decoder architectures for learned sparse retrieval*<br>
  Jingfen Qiao, Thong Nguyen, Evangelos Kanoulas, Andrew Yates<br>
  International Workshop on Knowledge-Enhanced Information Retrieval, 2025<br> 📄 [paper](https://arxiv.org/abs/2504.18151)
- *Scaling sparse and dense retrieval in decoder-only LLMs*<br>
  Hansi Zeng, Julian Killingback, Hamed Zamani<br>
  SIGIR, 2025<br> 📄 [paper](https://arxiv.org/abs/2502.15526)
- *CSPLADE: Learned Sparse Retrieval with Causal Language Models*<br>
  Zhichao Xu, Aosong Feng, Yijun Tian, Haibo Ding, Lin Lee Cheong<br>
  CoRR, 2025<br> 📄 [paper](https://arxiv.org/abs/2504.10816)
- *On the Reproducibility of Learned Sparse Retrieval Adaptations for Long Documents*<br>
  Emmanouil Georgios Lionis, Jia-Huei Ju<br>
  ECIR, 2025<br> 📄 [paper](https://arxiv.org/abs/2503.23824)
- *Learning Retrieval Models with Sparse Autoencoders*<br>
  Thibault Formal, Maxime Louis, Hervé Déjean, Stéphane Clinchant<br>
  ICLR, 2026<br> 📄 [paper](https://openreview.net/forum?id=TuFjICawSc)
- *Milco: Learned Sparse Retrieval Across Languages via a Multilingual Connector*<br>
  Thong Nguyen, Yibin Lei, Jia-Huei Ju, Eugene Yang, Andrew Yates<br>
  ICLR, 2026<br> 📄 [paper](https://arxiv.org/abs/2510.00671)
## Indexing LSR
- *Efficient and Robust Approximate Nearest Neighbor Search Using Hierarchical Navigable Small World Graphs*<br>
  Yury A. Malkov, Dmitry A. Yashunin<br>
  IEEE Transactions on Pattern Analysis and Machine Intelligence, 2020<br>
  📄 [paper](https://doi.org/10.1109/TPAMI.2018.2889473)
- *Efficiency Implications of Term Weighting for Passage Retrieval*<br>
  Joel Mackenzie, Zhuyun Dai, Luke Gallagher, Jamie Callan<br>
  SIGIR, 2020<br>
  📄 [paper](https://dl.acm.org/doi/10.1145/3397271.3401263)
- *Wacky Weights in Learned Sparse Representations and the Revenge of Score-at-a-Time Query Evaluation*<br>
  Joel Mackenzie, Andrew Trotman, Jimmy Lin<br>
  CoRR, 2021<br>
  📄 [paper](https://doi.org/10.48550/arXiv.2110.11540)
- *Accelerating Learned Sparse Indexes Via Term Impact Decomposition*<br>
  Joel Mackenzie, Antonio Mallia, Alistair Moffat, Matthias Petri<br>
  EMNLP, 2022<br>
  📄 [paper](https://aclanthology.org/2022.findings-emnlp.205/) | 🛠️ [code](https://github.com/jmmackenzie/postings-clipping)
- *An Efficiency Study for SPLADE Models*<br>
  Carlos Lassance, Stephane Clinchant<br>
  SIGIR, 2022<br>
  📄 [paper](https://dl.acm.org/doi/10.1145/3477495.3531833)
- *Faster Learned Sparse Retrieval with Guided Traversal*<br>
  Antonio Mallia, Joel Mackenzie, Torsten Suel, Nicola Tonellotto<br>
  SIGIR, 2022<br>
  📄 [paper](https://dl.acm.org/doi/10.1145/3477495.3531774)
- *IOQP: A simple Impact-Ordered Query Processor written in Rust*<br>
  Joel Mackenzie, Matthias Petri, Luke Gallagher<br>
  DESIRES, 2022<br>
  📄 [paper](https://jmmackenzie.io/publication/desires22/) | 🛠️ [code](https://github.com/jmmackenzie/ioqp)
- *A Static Pruning Study on Sparse Neural Retrievers*<br>
  Carlos Lassance, Simon Lupart, Herve Dejean, Stephane Clinchant, Nicola Tonellotto<br>
  SIGIR, 2023<br>
  📄 [paper](https://dl.acm.org/doi/10.1145/3539618.3591941)
- *An Approximate Algorithm for Maximum Inner Product Search over Streaming Sparse Vectors*<br>
  Sebastian Bruch, Franco Maria Nardini, Amir Ingber, Edo Liberty<br>
  ACM Transactions on Information Systems, 2024<br>
  📄 [paper](https://dl.acm.org/doi/10.1145/3609797)
- *Efficient Document-at-a-time and Score-at-a-time Query Evaluation for Learned Sparse Representations*<br>
  Joel Mackenzie, Andrew Trotman, Jimmy Lin<br>
  ACM Transactions on Information Systems, 2023<br>
  📄 [paper](https://dl.acm.org/doi/10.1145/3576922)
- *Optimizing Guided Traversal for Fast Learned Sparse Retrieval*<br>
  Yifan Qiao, Yingrui Yang, Haixin Lin, Tao Yang<br>
  WWW, 2023<br>
  📄 [paper](https://dl.acm.org/doi/10.1145/3543507.3583497) | 🛠️ [code](https://github.com/Qiaoyf96/2GTI)
- *Representation Sparsification with Hybrid Thresholding for Fast SPLADE-based Document Retrieval*<br>
  Yifan Qiao, Yingrui Yang, Shanxiu He, Tao Yang<br>
  SIGIR, 2023<br>
  📄 [paper](https://dl.acm.org/doi/10.1145/3539618.3592051) | 🛠️ [code](https://github.com/Qiaoyf96/HT)
- *Results of the Big ANN: NeurIPS'23 competition*<br>
  Harsha Vardhan Simhadri, Martin Aumüller, Amir Ingber, Matthijs Douze, George Williams, Magdalen Dobson Manohar, Dmitry Baranchuk, Edo Liberty, Frank Liu, Ben Landrum, Mazin Karjikar, Laxman Dhulipala, Meng Chen, Yue Chen, Rui Ma, Kai Zhang, Yuzheng Cai, Jiayang Shi, Yizhuo Chen, Weiguo Zheng, Zihao Wan, Jie Yin, Ben Huang<br>
  CoRR, 2023<br>
  📄 [paper](https://arxiv.org/abs/2409.17424) | 🛠️ [code](https://big-ann-benchmarks.com/neurips23.html)
- *Bridging Dense and Sparse Maximum Inner Product Search*<br>
  Sebastian Bruch, Franco Maria Nardini, Amir Ingber, Edo Liberty<br>
  ACM Transactions on Information Systems, 2024<br>
  📄 [paper](https://dl.acm.org/doi/full/10.1145/3665324)
- *Efficient Inverted Indexes for Approximate Retrieval over Learned Sparse Representations*<br>
  Sebastian Bruch, Franco Maria Nardini, Cosimo Rulli, Rossano Venturini<br>
  SIGIR, 2024<br>
  📄 [paper](https://dl.acm.org/doi/10.1145/3626772.3657769) | 🛠️ [code](https://github.com/TusKANNy/seismic)
- *Faster Learned Sparse Retrieval with Block-Max Pruning*<br>
  Antonio Mallia, Torsten Suel, Nicola Tonellotto<br>
  SIGIR, 2024<br>
  📄 [paper](https://dl.acm.org/doi/10.1145/3626772.3657906) | 🛠️ [code](https://github.com/pisa-engine/BMP)
- *Cluster-based Partial Dense Retrieval Fused with Sparse Text Retrieval*<br>
  Yingrui Yang, Parker Carlson, Shanxiu He, Yifan Qiao, Tao Yang<br>
  SIGIR, 2024<br>
  📄 [paper](https://doi.org/10.1145/3626772.3657972)
- *Pairing Clustered Inverted Indexes with κ-NN Graphs for Fast Approximate Retrieval over Learned Sparse Representations*<br>
  Sebastian Bruch, Franco Maria Nardini, Cosimo Rulli, Rossano Venturini<br>
  CIKM, 2024<br>
  📄 [paper](https://dl.acm.org/doi/10.1145/3627673.3679977) | 🛠️ [code](https://github.com/TusKANNy/seismic)
- *Threshold-driven Pruning with Segmented Maximum Term Weights for Approximate Cluster-based Sparse Retrieval*<br>
  Yifan Qiao, Parker Carlson, Shanxiu He, Yingrui Yang, Tao Yang<br>
  EMNLP, 2024<br>
  📄 [paper](https://aclanthology.org/2024.emnlp-main.1101/)
- *Foundations of Vector Retrieval*<br>
  Sebastian Bruch<br>
  Springer, 2024<br>
  📄 [book](https://arxiv.org/abs/2401.09350)
- *Dynamic Superblock Pruning for Fast Learned Sparse Retrieval*<br>
  Parker Carlson, Wentai Xie, Shanxiu He, Tao Yang<br>
  SIGIR, 2025<br>
  📄 [paper](https://dl.acm.org/doi/10.1145/3726302.3730183)
- *Efficient Sketching and Nearest Neighbor Search Algorithms for Sparse Vector Sets*<br>
  Sebastian Bruch, Franco Maria Nardini, Cosimo Rulli, Rossano Venturini<br>
  CoRR, 2025<br>
  📄 [paper](https://doi.org/10.48550/arXiv.2509.24815) | 🛠️ [code](https://github.com/TusKANNy/seismic)
- *Investigating the Scalability of Approximate Sparse Retrieval Algorithms to Massive Datasets*<br>
  Sebastian Bruch, Franco Maria Nardini, Cosimo Rulli, Rossano Venturini, Leonardo Venuta<br>
  ECIR, 2025<br>
  📄 [paper](https://link.springer.com/chapter/10.1007/978-3-031-88714-7_43) | 🛠️ [code](https://github.com/TusKANNy/seismic)
- *SINDI: an Efficient Index for Approximate Maximum Inner Product Search on Sparse Vectors*<br>
  Ruoxuan Li, Xiaoyao Zhong, Jiabao Jin, Peng Cheng, Wangze Ni, Lei Chen, Zhitao Shen, Wei Jia, Xiangyu Wang, Xuemin Lin, Heng Tao Shen, Jingkuan Song<br>
  CoRR, 2025<br>
  📄 [paper](https://doi.org/10.48550/arXiv.2509.08395) | 🛠️ [code](https://github.com/Roxanne0321/vsag/tree/sparse)
- *kANNolo: Sweet and Smooth Approximate k-Nearest Neighbors Search*<br>
  Leonardo Delfino, Domenico Erriquez, Silvio Martinico, Franco Maria Nardini, Cosimo Rulli, Rossano Venturini<br>
  ECIR, 2025<br>
  📄 [paper](https://link.springer.com/chapter/10.1007/978-3-031-88717-8_29) | 🛠️ [code](https://github.com/TusKANNy/kannolo)
- *Breaking the Curse of Dimensionality: On the Stability of Modern Vector Retrieval*<br>
  Vihan Lakshman, Blaise Munyampirwa, Julian Shun, Benjamin Coleman<br>
  CoRR, 2025<br>
  📄 [paper](https://arxiv.org/abs/2512.12458)
- *Efficiency Optimizations for Superblock-based Sparse Retrieval*<br>
  Parker Carlson, Wentai Xie, Rohil Shah, Tao Yang<br>
  CoRR, 2026<br>
  📄 [paper](https://arxiv.org/abs/2602.02883)
- *Evaluating the Efficiency and Effectiveness of Learned Sparse Retrieval with the lsr_benchmark*<br>
  Maik Fröbe, Ferdinand Schlatt, Cosimo Rulli, Tim Hagen, Jan Heinrich Merker, Gijs Hendriksen, Carlos Lassance, Franco Maria Nardini, Rossano Venturini, Martin Potthast<br>
  ECIR, 2026<br>
  📄 [paper]() | 🛠️ [code](https://github.com/reneuir/lsr-benchmark)
- *Forward Index Compression for Learned Sparse Retrieval*<br>
  Sebastian Bruch, Martino Fontana, Franco Maria Nardini, Cosimo Rulli, Rossano Venturini<br>
  ECIR, 2026<br>
  📄 [paper](https://arxiv.org/abs/2602.05445) | 🛠️ [code](https://github.com/TusKANNy/seismic)

### Tutorials
- [SIGIR 2024](https://lsr-tutorial.github.io/)

### Software Libraries
- [lsr-benchmark](https://github.com/reneuir/lsr-benchmark/) <img src="images/python-logo.svg" height="16" alt="Python"/><br>*Framework for the evaluation of the learned sparse retrieval paradigm to contrast efficiency and effectiveness across diverse retrieval scenarios*
- [kANNolo](https://github.com/TusKANNy/kannolo) <img src="images/python-logo.svg" height="16" alt="Python"/> <img src="images/rust-logo.svg" height="22" alt="Rust"/><br>*Library for fast dense/sparse learned retrieval with graph-based indexes.*
- [Seismic](https://github.com/TusKANNy/seismic) <img src="images/python-logo.svg" height="16" alt="Python"/> <img src="images/rust-logo.svg" height="22" alt="Rust"/><br>*State-of-the-Art library for fast sparse learned retrieval and indexing with focus on efficient inverted-index structures built on modern research*
- [Vectorium](https://github.com/TusKANNy/vectorium) <img src="images/python-logo.svg" height="16" alt="Python"/> <img src="images/rust-logo.svg" height="22" alt="Rust"/><br>*A library for storing and accessing datasets of dense and sparse vectors, with efficient support for brute-force search and the core operations required by vector indexing data structures.*
- [Sentence Transformer](https://sbert.net/) <img src="images/python-logo.svg" height="16" alt="Python"/><br>*Framework for generating sentence embeddings and sparse encoders for semantic and sparse retrieval in NLP applications.*
- [Pyserini](https://github.com/castorini/pyserini) <img src="images/python-logo.svg" height="16" alt="Python"/><br>*IR research toolkit built on Lucene that supports learned sparse retrieval models.*
- [NMSLib](https://github.com/nmslib/nmslib) <img src="images/python-logo.svg" height="16" alt="Python"/> <img src="images/cpp-logo.svg" height="20" alt="C++"/><br>*Non-Metric Space Library (NMSLIB): An efficient similarity search library and a toolkit for evaluation of k-NN methods for generic non-metric spaces.*
- [OpenSearch](https://opensearch.org/) <img src="images/python-logo.svg" height="16" alt="Python"/> <img src="images/java-logo.png" height="24" alt="Java"/><br>*Open-source search and analytics engine that supports scalable sparse, dense, and hybrid neural retrieval via plugins and vector extensions.*
- [Apache Lucene](https://lucene.apache.org/) <img src="images/python-logo.svg" height="16" alt="Python"/> <img src="images/java-logo.png" height="24" alt="Java"/><br>*High-performance Java search library providing inverted indexes and scoring infrastructure that underpins many learned sparse retrieval systems.*
- [Qdrant](https://qdrant.tech/) <img src="images/python-logo.svg" height="16" alt="Python"/> <img src="images/rust-logo.svg" height="22" alt="Rust"/><br>*Open-source vector database supporting dense, sparse, and hybrid retrieval with native sparse vector indexing based on an inverted index for exact high-dimensional sparse search.*
- [FlashRAG](https://github.com/RUC-NLPIR/FlashRAG) <img src="images/python-logo.svg" height="16" alt="Python"/><br>*A Python Toolkit for Efficient RAG Research.*
- [PyTerrier](https://github.com/terrier-org/pyterrier) <img src="images/python-logo.svg" height="16" alt="Python"/><br>*A Python framework for performing information retrieval experiments (supporting PISA and BMP).*



### Datasets and Encodings

#### `MS MARCO v1`
- **Documents**: `8,841,823`
- **Queries** [`dev.small`]: `6,980`
- **Reference Metric**: `MRR@10`

| Encoding | Link | Avg non-zero (docs) | Avg non-zero (queries) | MRR@10 |
|---|---|---:|---:|---:|
| `splade-cocondenser` | [link](https://huggingface.co/datasets/tuskanny/seismic-msmarco-splade-bin/tree/main) | `119` | `43` | `38.3` |
| `efficient-splade` | [link](https://huggingface.co/datasets/tuskanny/seismic-msmarco-effsplade) | `181` | `6` | `38.8` |
| `uniCOIL-T5` | [link](https://huggingface.co/datasets/tuskanny/seismic-msmarco-unicoilT5) | `68` | `6` | `35.2` |
| `splade-v3` | [link](https://huggingface.co/datasets/tuskanny/msmarco-spladev3/tree/main) | `168` | `24` | `40.3` |
| `li-lsr-big` | [link](https://huggingface.co/datasets/tuskanny/lilsr_big_msmarco) | `387` | `6` | `38.8` |

#### `MS MARCO v2`
- **Documents**: `138,363,364`
- **Queries** [`dev1.small`]: `3,903`
- **Reference Metric**: `MRR@10`

| Encoding | Link | Avg non-zero (docs) | Avg non-zero (queries) | MRR@10 |
|---|---|---:|---:|---:|
| `splade-cocondenser` | [link](https://huggingface.co/datasets/tuskanny/msmarco-v2-splade) | `127` | `44` | `10.88` |

#### `NQ`
- **Documents**: `2,680,893`
- **Queries**: `3,452`
- **Reference Metric**: `NDCG@10`

| Encoding | Link | Avg non-zero (docs) | Avg non-zero (queries) | NDCG@10 |
|---|---|---:|---:|---:|
| `splade-cocondenser` | [link](https://huggingface.co/datasets/tuskanny/seismic-nq-splade) | `153` | `51` | `53.9` |

#### `LoTTE-pooled`
- **Documents**: `2,428,854`
- **Queries** [`dev/search`]: `2,931`
- **Reference Metric**: `Success@5`

| Encoding | Link | Avg non-zero (docs) | Avg non-zero (queries) | Success@5 |
|---|---|---:|---:|---:|
| `splade-cocondenser` | `N/A` | `N/A` | `N/A` | `69.0` |
| `li-lsr-big` | [link](https://huggingface.co/datasets/tuskanny/lilsr_lotte) | `469` | `9` | `65.7` |

#### `Quora`
- **Documents**: `522,931`
- **Queries** [`test`] :  `10,000`
- **Reference Metric**: `nDCG@10`

| Encoding | Link | Avg non-zero (docs) | Avg non-zero (queries) | nDCG@10 |
|---|---|---:|---:|---:|
| `splade-v3` | [link](https://huggingface.co/datasets/tuskanny/quora-sparse) | `40` | `36` | `81.4` |

### List Maintainers (alphabetical order)
Franco Maria Nardini (ISTI-CNR, Pisa, Italy)<br>
Cosimo Rulli (ISTI-CNR, Pisa, Italy)<br>
Rossano Venturini (University of Pisa, Italy)<br>
