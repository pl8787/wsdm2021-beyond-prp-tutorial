# WSDM2021 Tutorial: Beyond Probability Ranking Principle: Modeling the Dependencies among Documents

This WSDM2021 tutorial will be held on Monday, March 8th, 2021, with online mode, by [Liang Pang](http://www.bigdatalab.ac.cn/~pangliang/) `<pangliang[AT]ict.ac.cn>`, [Qingyao Ai](http://ir.aiqingyao.org/) `<aiqy[AT]cs.utah.edu>`, and [Jun Xu](http://ai.ruc.edu.cn/academicfaculty/20191112002.html) `<junxu[AT]ruc.edu.cn>`. 

## Overview
Probability Ranking Principle (PRP) is the fundamental principle for ranking, which assumes that each document has a unique and independent probability to satisfy a particular information need. Previously, traditional heuristic features and well-known learning-to-rank approaches are designed following PRP principle. Besides, recent deep learning enhanced ranking models, also referred to as ``deep text matching'', also obey PRP principle. However, PRP is not an optimal for ranking, due to each document is not independent from the rest in many recent ranking tasks, such as pseudo relevance feedback, interactive information retrieval and so on. 
To solve this problem, a new trend of ranking models turn to model the dependencies among documents. In this tutorial, we aim to give a comprehensive survey on recent progress that the ranking models go beyond PRP principle. In this way, we expect researchers focus on this field which will lead to a big improvement in the information retrieval.

This tutorial mainly consists of three parts. Firstly, we introduce the ranking problem and the well-known probability ranking principle. Secondly, we present traditional approaches under PRP principle. Lastly, we illustrate the limitations of PRP principle and introduce most recent work that model the dependencies among document in a sequential way and in a global way.

A more detailed introduction can be found [here](docs/wsdm2021-tutorial.pdf).

## Tutorial Slides

<!-- #### **NEW: All the slides are available now!** -->
<!-- We recommend reading our draft slides before the tutorial. We may have some minor last-minute changes, so please check out the latest version before the live session. -->

1. [Introduction](slides/Part1-Introduction.pdf)
1. [Ranking with Sequential Dependency](slides/Part2-Sequensial Dependency.pdf)
1. [Ranking with Global Dependency](slides/Part3-Global Dependency.pdf)

## Reading List

### Feature based ranking method (early work)

### Deep text matching model (apply deep learning to text matching)
1. [Text Matching as Image Recognition](https://arxiv.org/pdf/1602.06359). Liang Pang, Yanyan Lan, Jiafeng Guo, Jun Xu, Shengxian Wan, Xueqi Cheng. AAAI 2016.
1. [DeepRank: a New Deep Architecture for Relevance Ranking in Information Retrieval](https://arxiv.org/pdf/1710.05649). Liang Pang, Yanyan Lan, Jiafeng Guo, Jun Xu, Jingfang Xu, Xueqi Cheng. CIKM 2017.
1. [A Deep Architecture for Semantic Matching with Multiple Positional Sentence Representations](https://arxiv.org/pdf/1511.08277). Shengxian Wan, Yanyan Lan, Jiafeng Guo, Jun Xu, Liang Pang and Xueqi Cheng. AAAI 2016.
1. [Match-SRNN: Modeling the Recursive Matching Structure with Spatial RNN](https://arxiv.org/pdf/1604.04378). Shengxian Wan, Yanyan Lan, Jiafeng Guo, Jun Xu, Liang Pang and Xueqi Cheng. IJCAI 2016.
1. [A Deep Look into Neural Ranking Models for Information Retrieval](https://doi.org/10.1016/j.ipm.2019.102067). Jiafeng Guo, Yixing Fan, Liang Pang, Liu Yang, Qingyao Ai, Hamed Zamani, Chen Wu, W. Bruce Croft and Xueqi Cheng. Information Processing & Management (IPM).

### Deep contextual ranking model (recent work)
#### Sequential dependency
1. [Reinforcement Learning to Rank with Markov Decision Process](https://dl.acm.org/doi/10.1145/3077136.3080685). Wei Zeng, Jun Xu, Yanyan Lan, Jiafeng Guo, and Xueqi Cheng. SIGIR 2017.
1. [Adapting Markov Decision Process for Search Result Diversification](https://dl.acm.org/doi/10.1145/3077136.3080775). Long Xia, Jun Xu, Yanyan Lan, Jiafeng Guo, Wei Zeng, and Xueqi Cheng. SIGIR 2017.
1. [From Greedy Selection to Exploratory Decision-Making: Diverse Ranking with Policy-Value Networks](https://dl.acm.org/doi/10.1145/3209978.3209979). Yue Feng, Jun Xu, Yanyan Lan, Jiafeng Guo, Wei Zeng, and Xueqi Cheng. SIGIR 2018.
#### Global dependency
1. [Learning a Deep Listwise Context Model for Ranking Refinement](https://arxiv.org/pdf/1804.05936.pdf). Qingyao Ai, Keping Bi, Jiafeng Guo and W. Bruce Croft. SIGIR 2018.
1. [Learning Groupwise Multivariate Scoring Functions Using Deep Neural Networks](https://arxiv.org/abs/1811.04415). Qingyao Ai, Xuanhui Wang, Sebastian Bruch, Nadav Golbandi, Michael Bendersky and Marc Najork. ICTIR 2019.
1. [SetRank: Learning a Permutation-Invariant Ranking Model for Information Retrieval](https://arxiv.org/pdf/1912.05891). Liang Pang, Jun Xu, Qingyao Ai, Yanyan Lan, Xueqi Cheng, and Jirong Wen. SIGIR 2020.
1. [Analysis of Multivariate Scoring Functions for Automatic Unbiased Learning to Rank](https://arxiv.org/abs/2008.09061v1). Yang, Tao, Shikai Fang, Shibo Li, Yulan Wang, and Qingyao Ai. CIKM 2020.

We understand this is a long reading list :) In case you wonder where you should start with, we plan to discuss the papers in bold in depth during our tutorial.

