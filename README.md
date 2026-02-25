# Awesome Learned Sparse Retrieval
An extensive and commented list of resources on Learned Sparse Retrieval.

## Learning

## Indexing
- *Faster top-k document retrieval using block-max indexes*<br>
  Shuai Ding, Torsten Suel<br>
  SIGIR, 2011<br>
  📄 [paper](https://doi.org/10.1145/2009916.2010048)
- *Optimizing top-k document retrieval strategies for block-max indexes*<br>
  Constantinos Dimopoulos, Sergey Nepomnyachiy, Torsten Suel<br>
  WSDM, 2013<br>
  📄 [paper](https://doi.org/10.1145/2433396.2433412)
- *Faster BlockMax WAND with Variable-sized Blocks*<br>
  Antonio Mallia, Giuseppe Ottaviano, Elia Porciani, Nicola Tonellotto, Rossano Venturini<br>
  SIGIR, 2017<br>
  📄 [paper](https://doi.org/10.1145/3077136.3080780)
- *Faster BlockMax WAND with Longer Skipping*<br>
  Antonio Mallia, Elia Porciani<br>
  ECIR, 2019<br>
  📄 [paper](https://doi.org/10.1007/978-3-030-15712-8_50)
- *Efficient and Robust Approximate Nearest Neighbor Search Using Hierarchical Navigable Small World Graphs*<br>
  Yury A. Malkov, Dmitry A. Yashunin<br>
  IEEE Transactions on Pattern Analysis and Machine Intelligence, 2020<br>
  📄 [paper](https://doi.org/10.1109/TPAMI.2018.2889473)
- *Wacky Weights in Learned Sparse Representations and the Revenge of Score-at-a-Time Query Evaluation*<br>
  Joel Mackenzie, Andrew Trotman, Jimmy Lin<br>
  CoRR, 2021<br>
  📄 [paper](https://doi.org/10.48550/arXiv.2110.11540) | 📥 [download pdf](https://arxiv.org/pdf/2110.11540)
- *Accelerating Learned Sparse Indexes Via Term Impact Decomposition*<br>
  Joel Mackenzie, Antonio Mallia, Alistair Moffat, Matthias Petri<br>
  EMNLP, 2022<br>
  📄 [paper](https://doi.org/10.18653/v1/2022.findings-emnlp.210) | 📥 [download pdf](https://aclanthology.org/2022.findings-emnlp.210.pdf)
- *An Efficiency Study for SPLADE Models*<br>
  Carlos Lassance, Stephane Clinchant<br>
  SIGIR, 2022<br>
  📄 [paper](https://doi.org/10.1145/3477495.3531883)
- *Faster Learned Sparse Retrieval with Guided Traversal*<br>
  Antonio Mallia, Joel Mackenzie, Torsten Suel, Nicola Tonellotto<br>
  SIGIR, 2022<br>
  📄 [paper](https://doi.org/10.1145/3477495.3531777)
- *IOQP: A simple Impact-Ordered Query Processor written in Rust*<br>
  Joel Mackenzie, Matthias Petri, Luke Gallagher<br>
  DESIRES, 2022<br>
  📄 [paper](https://doi.org/10.1145/3564295.3564299)
- *A Static Pruning Study on Sparse Neural Retrievers*<br>
  Carlos Lassance, Simon Lupart, Herve Dejean, Stephane Clinchant, Nicola Tonellotto<br>
  SIGIR, 2023<br>
  📄 [paper](https://doi.org/10.1145/3539618.3591941)
- *An Approximate Algorithm for Maximum Inner Product Search over Streaming Sparse Vectors*<br>
  Sebastian Bruch, Franco Maria Nardini, Amir Ingber, Edo Liberty<br>
  CoRR, 2023<br>
  📄 [paper](https://doi.org/10.48550/arXiv.2301.10622) | 📥 [download pdf](https://arxiv.org/pdf/2301.10622)
- *Efficient Document-at-a-time and Score-at-a-time Query Evaluation for Learned Sparse Representations*<br>
  Joel Mackenzie, Andrew Trotman, Jimmy Lin<br>
  ACM Transactions on Information Systems, 2023<br>
  📄 [paper](https://doi.org/10.1145/3576923) | 📥 [download pdf](https://dl.acm.org/doi/pdf/10.1145/3576923)
- *Optimizing Guided Traversal for Fast Learned Sparse Retrieval*<br>
  Yifan Qiao, Yingrui Yang, Haixin Lin, Tao Yang<br>
  WWW, 2023<br>
  📄 [paper](https://doi.org/10.1145/3543507.3583267) | 📥 [download pdf](https://arxiv.org/pdf/2302.04038)
- *Representation Sparsification with Hybrid Thresholding for Fast SPLADE-based Document Retrieval*<br>
  Yifan Qiao, Yingrui Yang, Shanxiu He, Tao Yang<br>
  SIGIR, 2023<br>
  📄 [paper](https://doi.org/10.1145/3539618.3591880)
- *Bridging Dense and Sparse Maximum Inner Product Search*<br>
  Sebastian Bruch, Franco Maria Nardini, Amir Ingber, Edo Liberty<br>
  ACM Transactions on Information Systems, 2024<br>
  📄 [paper](https://doi.org/10.1145/3652059)
- *Efficient Inverted Indexes for Approximate Retrieval over Learned Sparse Representations*<br>
  Sebastian Bruch, Franco Maria Nardini, Cosimo Rulli, Rossano Venturini<br>
  SIGIR, 2024<br>
  📄 [paper](https://doi.org/10.1145/3626772.3657769) | 📥 [download pdf](https://arxiv.org/pdf/2404.18812) | 🛠️ [code](https://github.com/TusKANNy/seismic)
- *Faster Learned Sparse Retrieval with Block-Max Pruning*<br>
  Antonio Mallia, Torsten Suel, Nicola Tonellotto<br>
  SIGIR, 2024<br>
  📄 [paper](https://doi.org/10.1145/3626772.3657872) | 📥 [download pdf](https://arxiv.org/pdf/2408.16928) | 🛠️ [code](https://github.com/pisa-engine/BMP)
- *Pairing Clustered Inverted Indexes with κ-NN Graphs for Fast Approximate Retrieval over Learned Sparse Representations*<br>
  Sebastian Bruch, Franco Maria Nardini, Cosimo Rulli, Rossano Venturini<br>
  CIKM, 2024<br>
  📄 [paper](https://doi.org/10.1145/3627673.3680049) | 🛠️ [code](https://github.com/TusKANNy/seismic)
- *Threshold-driven Pruning with Segmented Maximum Term Weights for Approximate Cluster-based Sparse Retrieval*<br>
  Yifan Qiao, Parker Carlson, Shanxiu He, Yingrui Yang, Tao Yang<br>
  EMNLP, 2024<br>
  📄 [paper](https://doi.org/10.18653/v1/2024.emnlp-main.1098) | 📥 [download pdf](https://aclanthology.org/2024.emnlp-main.1098.pdf)
- *Dynamic Superblock Pruning for Fast Learned Sparse Retrieval*<br>
  Parker Carlson, Wentai Xie, Shanxiu He, Tao Yang<br>
  SIGIR, 2025<br>
  📄 [paper](https://doi.org/10.1145/3726302.3730076) | 📥 [download pdf](https://dl.acm.org/doi/pdf/10.1145/3726302.3730076)
- *Efficient Sketching and Nearest Neighbor Search Algorithms for Sparse Vector Sets*<br>
  Sebastian Bruch, Franco Maria Nardini, Cosimo Rulli, Rossano Venturini<br>
  CoRR, 2025<br>
  📄 [paper](https://doi.org/10.48550/arXiv.2509.24815) | 🛠️ [code](https://github.com/TusKANNy/seismic)
- *Investigating the Scalability of Approximate Sparse Retrieval Algorithms to Massive Datasets*<br>
  Sebastian Bruch, Franco Maria Nardini, Cosimo Rulli, Rossano Venturini, Leonardo Venuta<br>
  ECIR, 2025<br>
  📄 [paper](https://doi.org/10.1007/978-3-031-88711-6_30) | 🛠️ [code](https://github.com/TusKANNy/seismic)
- *SINDI: an Efficient Index for Approximate Maximum Inner Product Search on Sparse Vectors*<br>
  Ruoxuan Li, Xiaoyao Zhong, Jiabao Jin, Peng Cheng, Wangze Ni, Lei Chen, Zhitao Shen, Wei Jia, Xiangyu Wang, Xuemin Lin, Heng Tao Shen, Jingkuan Song<br>
  CoRR, 2025<br>
  📄 [paper](https://doi.org/10.48550/arXiv.2509.08395) | 📥 [download pdf](https://arxiv.org/pdf/2509.08395)
- *kANNolo: Sweet and Smooth Approximate k-Nearest Neighbors Search*<br>
  Leonardo Delfino, Domenico Erriquez, Silvio Martinico, Franco Maria Nardini, Cosimo Rulli, Rossano Venturini<br>
  ECIR, 2025<br>
  📄 [paper](https://doi.org/10.1007/978-3-031-88711-6_27) | 🛠️ [code](https://github.com/TusKANNy/kannolo)
## Datasets

## Libraries
