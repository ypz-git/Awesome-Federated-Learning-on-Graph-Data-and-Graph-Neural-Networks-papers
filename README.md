# Awesome-Federated-Learning-on-Graph-Data-and-Graph-Neural-Networks-papers

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

## Info
This is about collection of papers related with Federated Learning on Graph Data and GNNs.

## Contents

- [Survey and Framework papers](#Survey-and-Framework-papers)
- [Papers](#Papers)


## Survey and Framework papers

|Title|Year|Venue|Category|Link|
|:----|:---|:---:|:------:|:---|
|Federated Graph Neural Networks: Overview, Techniques and Challenges|2022|preprint|survey|[[paper]](https://arxiv.org/pdf/2202.07256.pdf)|
|FederatedScope-GNN: Towards a Unified, Comprehensive and Efficient Package for Federated Graph Learning|2022|preprint|framework|[[paper]](https://arxiv.org/pdf/2204.05562.pdf) [[code]](https://github.com/alibaba/FederatedScope)|Cora, CiteSeer, PubMed, FedDBLP, Ciao, Taobao, WN18, FB15k-237, HIV, Proteins, IMDB, Mol|
|Federated Graph Learning - A Position Paper|2021|preprint|survey|[[paper]](https://arxiv.org/pdf/2105.11099.pdf)|
|FedGraphNN: A Federated Learning Benchmark System for Graph Neural Networks|2021|ICLR|framework|[[paper]](http://www.cs.emory.edu/~jyang71/files/fedgraphnn.pdf) [[code]](https://github.com/FedML-AI/FedGraphNN)|
|STFL: A Spatial-Temporal Federated Learning Framework for Graph Neural Networks|2021|preprint|framework|[[paper]](https://arxiv.org/pdf/2111.06750.pdf) [[code]](https://github.com/JW9MsjwjnpdRLFw/TSFL)|ISRUC_S3|



## Papers

[Notice]

**Level** 

The level of federated graph data on devices:
- `node`: each client holds a node of the whole graph data.
- `subgraph`: each client holds a subset of graph data by overlapping or separating.
- `graph`: each client holds a graph data or several graph data.


**Task** 

The tasks defined on graph data in FL refer to [Trustworthy Graph Neural Networks: Aspects, Methods and Trends](https://arxiv.org/pdf/2205.07424.pdf):
- `NC`: Node Classification.
- `GC`: Graph Classification.
- `R`: Recommendation.

other tasks:
- `TFF` indicates Traffic Flow Forecasting.

|Title|Year|Venue|Keywords|Level|Task |Link|Datasets|
|:----|:---|:---:|:-------|:---:|:---:|:---|:-------|
|A Federated Graph Neural Network Framework for Privacy-Preserving Personalization|2022|NC|recommendation, privacy-preserving|`graph`|`R`|[[paper]](https://assets.researchsquare.com/files/rs-1191595/v1_covered.pdf?c=1641937201)|MovieLens, Flixster, Douban, YahooMusic|
|FedGCN: Convergence and Communication Tradeoffs in Federated Training of Graph Convolutional Networks|2022|preprint|communication cost, non-i.i.d|`subgraph`|`NC`|[[paper]](https://arxiv.org/pdf/2201.12433.pdf)|Cora, CiteSeer, PubMed|
|FedGCN: Federated Learning-Based Graph Convolutional Networks for Non-Euclidean Spatial Data|2022|Mathematics|graph convolutional neural network, non-Euclidean spatial data, attention mechanism|`graph`|`GC`|[[paper]](https://www.mdpi.com/2227-7390/10/6/1000/htm)|D&D, ENZYMES, IMDB-BINARY, REDDIT, PROTEINS, GITHUB-STARGAZERS, COLLAB, IMDB-MULTI, NCI1|
|FedGraph: Federated Graph Learning with Intelligent Sampling|2022|IEEE TPDS|graph sampling, reinforcement learning|`subgraph`|`NC`|[[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9606516)|Cora, CiteSeer, PubMed, Reddit|
|More is Better (Mostly): On the Backdoor Attacks in Federated Graph Neural Networks|2022|preprint|robustness|`graph`|`GC`|[[paper]](https://arxiv.org/pdf/2202.03195.pdf)|MOLT-4H, NCI1, PROTEINS, TRIANGLES|
|Privatized Graph Federated Learning|2022|preprint|privatized learning, differntial privacy|-|-|[[paper]](https://arxiv.org/pdf/2203.07105.pdf)|-|
|A Graph Federated Architecture with Privacy Preserving Learning|2021|IEEE SPAWC|differential privacy, secure aggregation|-|-|[[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9593148)|-|
|ASFGNN: Automated separated-federated graph neural network|2021|P2P Networking and Applications|Bayesian optimization, privacy preserving|`subgraph`|`NC`|[[paper]](https://link.springer.com/content/pdf/10.1007/s12083-021-01074-w.pdf)|-|
|Cross-Node Federated Graph Neural Network for Spatio-Temporal Data Modeling|2021|KDD|traffic flow prediction, split learning|`node`|`TFF`|[[paper]](https://dl.acm.org/doi/pdf/10.1145/3447548.3467371) [[code]](https://github.com/mengcz13/KDD2021_CNFGNN)|PEMS-BAY, METR-LA|
|Decentralized Federated Graph Neural Networks|2021|IJCAI|serverless|`graph`|`GC`|[[paper]](https://federated-learning.org/fl-ijcai-2021/FTL-IJCAI21_paper_20.pdf)|ESQL, FreeSolv, Lipophilicity, hERG, BACE, BBBP, SIDER, ClinTox, Tox21|
|Differentially Private Federated Knowledge Graphs Embedding|2021|CIKM|knowledge graph|`subgraph`|`NC`|[[paper]](https://dl.acm.org/doi/pdf/10.1145/3459637.3482252) [[code]](https://github.com/HKUST-KnowComp/FKGE)|(Knowlege Graphs)|
|Federated Graph Classification over Non-IID Graphs|2021|NIPS|non-i.i.d, cross-dataset, cross-domain|`graph`|`GC`|[[paper]](https://proceedings.neurips.cc/paper/2021/file/9c6947bd95ae487c81d4e19d3ed8cd6f-Paper.pdf)|-|
|Federated Graph Neural Network for Cross-graph Node Classification|2021|preprint|PATE, privacy-preserving|`graph`|`NC`|[[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9754598)|Citation, DBLP, ACM|
|Federated Social Recommendation with Graph Neural Network|2021|ACM TIST|recommendation, privacy-preserving|`node`/`subgraph`|`R`|[[paper]](https://arxiv.org/pdf/2111.10778.pdf)|Ciao, Epinions, Filmtrust|
|Glint: Decentralized Federated Graph Learning with Traffic Throttling and Flow Scheduling|2021|IWQOS|traffic throttling, flow scheduling| | |[[paper]](https://ieeexplore.ieee.org/abstract/document/9521331)|Cora, PubMed, Coauthor physics, Reddit|
|SpreadGNN: Serverless Multi-task Federated Learning for Graph Neural Networks|2021|preprint|serverless, multi-task learning, non-i.i.d|`graph`|`GC`|[[paper]](https://arxiv.org/pdf/2106.02743.pdf) [[code]](https://github.com/FedML-AI/SpreadGNN)|SIDER, Tox21, MUV, QM8|
|Subgraph Federated Learning with Missing Neighbor Generation|2021|NIPS|neighbor generation|`subgraph`|`NC`|[[paper]](https://proceedings.neurips.cc/paper/2021/file/34adeb8e3242824038aa65460a47c29e-Paper.pdf)|Cora, CiteSeer, PubMed, MSAcademic|
|GraphFederator: Federated Visual Analysis for Multi-party Graphs|2020|preprint| |`graph`|`GC`|[[paper]](https://arxiv.org/pdf/2008.11989.pdf)|DBLP, NEGP|
|Towards Federated Graph Learning for Collaborative Financial Crimes Detection|2019|NIPS Workshop| |`graph`|`GC`|[[paper]](https://arxiv.org/pdf/1909.12946.pdf)|TechSprint|
|SGNN: A Graph Neural Network Based Federated Learning Approach by Hiding Structure|2019|BigData| |`subgraph`/`graph`|`NC`|[[paper]](https://ieeexplore.ieee.org/abstract/document/9005983)|Aminer, Brazil, Europe|
|Peer-to-Peer Federated Learning on Graphs|2019|preprint| |-|-|[[paper]](https://arxiv.org/pdf/1901.11173.pdf)|-|
