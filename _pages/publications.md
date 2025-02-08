---
title: "Research"
layout: archive
sitemap: true
permalink: /research/
author_profile: true
---


## Topic 1: Stochastic Convex/Nonconvex Optimization with Applications in Strategic Machine Learning

**Goal**: To design efficient stochastic algorithms with strong theoretical guarantees, addressing various data-driven challenges.

<style>
.float-image {
    float: right;
    margin: 0 0 1em 1em; /* Adjust margins to control spacing around the image */
    width: 350px; /* Set your preferred width */
}
</style>

<img src="/assets/images/sc.png" class="float-image" alt="">

**Background**: Traditional supervised learning has achieved impressive results across tasks such as classification, regression, and prediction. These methods typically assume that data is static: people who generate or provide data passively participate without modifying their behavior in response to the learning process.

> **But what happens when human behavior interacts with learning outcomes?**

Consider a hiring scenario. Job applicants might tailor their resumes or gain relevant experience based on a company’s job description. As the employer evaluates applicants, those who prepared strategically have an advantage, potentially improving their chances of being hired.

**Performative Prediction** provides a new framework that takes into account the ways humans adapt in response to the learning process itself. This framework models human behavior as active inputs with agency, capturing more realistic behavior "in the wild."

**Project Overview**: This research sits at the intersection of machine learning and game theory. We focus on developing efficient first- and zeroth-order algorithms that help a learning agent make robust decisions in complex, dynamic settings. These settings may include environments that evolve over time, or scenarios involving adversarial actions that attempt to manipulate outcomes. By leveraging stochastic optimization techniques, our work aims to improve decision-making processes in these challenging, real-world situations.

**Selected Publications:**

| <img src="/assets/images/privacyPP2024.jpg" width="350px" alt=""> | **Qiang Li**, Hoi-To Wai. Stochastic Optimization Schemes for Performative Prediction with Nonconvex Loss, 2024, (<span style="color:blue; font-weight:bold">NeurIPS 2024</span>). [[arXiv link](https://arxiv.org/abs/2405.17922)], [[code](https://github.com/Qiang-CU/nips2024-ncvxpp)], [[poster](/assets/pdf/Fancy_Posters_NeurIPS2024.pdf)], [[slides](/assets/pdf/Slides_Neurips2024.pdf)]|


<!-- 
这是一个分隔符
 -->

## Topic 2: Large Scale (Multi-agent) Optimization

**Goal**: To design realistic algorithms for optimal solution-seeking in multi-agent optimization systems.

<style>
.float-image {
    float: right;
    margin: 0 0 1em 1em; /* Adjust margins to control spacing around the image */
    width: 300px; /* Set your preferred width */
}
</style>

<img src="/assets/images/network.png" class="float-image" alt="Illustration of Multi-agent Optimization">

**Background**: In fields like wireless sensor networks, multi-agent reinforcement learning, and federated learning, decentralized optimization algorithms play a crucial role and have attracted significant attention. Widely used methods include gradient descent-based algorithms and gossip-based communication mechanisms, such as Decentralized SGD, Push-Sum, Gradient Tracking algorithms, and NEXT algorithms, which are designed to handle (un)directed and time-varying graphs.

> **How can we design decentralized algorithms for more complex environments, such as those with heterogeneous data (addressing out-of-distribution issues) or strategic data?**

Motivated by these challenges, our work investigates ways to improve the performance of decentralized algorithms and adapt them to new problem setups, with rigorous convergence guarantees. This project aims to fully leverage computational resources from cloud centers, addressing key issues in distributed implementation and enhancing algorithmic efficiency for real-world applications.

**Selected Publications:**

| <img src="/assets/images/neurips2022.png" width="400px" alt=""> | **Qiang Li**, Chung-Yiu Tau, Hoi-To Wai. Multi-agent Performative Prediction with Greedy Deployment and Consensus Seeking Agents, 36th Conference on Neural Information Processing Systems (<span style="color:blue; font-weight:bold">NeurIPS 2022</span>). [[link](https://proceedings.neurips.cc/paper_files/paper/2022/file/fad7c708dda11f3e72cc1629bb130379-Paper-Conference.pdf)] [[slides](/assets/pdf/Slides_Neurips.pdf)] [[video](https://slideslive.com/38990568/multiagent-performative-prediction-with-greedy-deployment-and-consensus-seeking-agents?ref=search-presentations)] [[poster](/assets/pdf/Fancy_Posters_NeurIPS.pdf)]|




## Published Articles

Most of my publications should be indexed in my [Google Scholar profile](https://scholar.google.com/citations?user=NjVNiJ8AAAAJ&hl=en), and I will try to keep the most recent version of my publications here as well. 

### Graduae Research

| <img src="/assets/images/tac-trantime.png" width="350px" alt=""> | **Qiang Li**, Hoi-To Wai. Tighter Analysis for Decentralized Stochastic Gradient Method: Impact of Data Homogeneity, 2024, **IEEE Transactions on Automatic Control**. [[arXiv link](https://arxiv.org/abs/2409.04092)], [[code](https://github.com/Qiang-CU/IEEE-TAC)]


| <img src="/assets/images/privacyPP2024.jpg" width="350px" alt=""> | **Qiang Li**, Hoi-To Wai. Stochastic Optimization Schemes for Performative Prediction with Nonconvex Loss, 2024, (<span style="color:blue; font-weight:bold">NeurIPS 2024</span>). [[arXiv link](https://arxiv.org/abs/2405.17922)], [[code](https://github.com/Qiang-CU/nips2024-ncvxpp)] |


| <img src="/assets/images/dp2024.png" width="600px" alt=""> | **Qiang Li**, Michal Yemini, Hoi-To Wai. Privacy-Efficacy Tradeoff of Clipped SGD with Decision-dependent Data, (<span style="color:blue; font-weight:bold">ICML 2024</span>) - Humans, Algorithmic Decision-Making and Society: Modeling Interactions and Impact Workshop. [[link](https://icml.cc/virtual/2024/38255)] [[slides](https://icml.cc/media/icml-2024/Slides/38255_IImlZvq.pdf)] [[poster](https://icml.cc/media/PosterPDFs/ICML%202024/38255.png?t=1720597917.7397864)] |


| <img src="/assets/images/icml2024.png" width="400px" alt=""> | Haitong Liu, **Qiang Li**, Hoi-To Wai. Two-timescale Derivative Free Optimization for Performative Prediction with Markovian Data, 41st International Conference on Machine Learning (<span style="color:blue; font-weight:bold">ICML 2024</span>). [[link](https://openreview.net/pdf?id=Aj18fUB6Th)] [[poster](/assets/pdf/Two_timescale_DFO_Poster.pdf)]  |

| <img src="/assets/images/cdc2022.png" width="430px" alt=""> | **Qiang Li**,  Hoi-To Wai. On the role of Data Homogeneity in Multi-Agent Non-convex Stochastic Optimization, 2022 IEEE 61st Conference on Decision and Control, (<span style="color:blue; font-weight:bold">IEEE CDC 2022</span>). [[link](https://arxiv.org/pdf/2208.13162.pdf)] [[slides](/assets/pdf/Slides_CDC.pdf)]|

| <img src="/assets/images/neurips2022.png" width="400px" alt=""> | **Qiang Li**, Chung-Yiu Tau, Hoi-To Wai. Multi-agent Performative Prediction with Greedy Deployment and Consensus Seeking Agents, 36th Conference on Neural Information Processing Systems (<span style="color:blue; font-weight:bold">NeurIPS 2022</span>). [[link](https://proceedings.neurips.cc/paper_files/paper/2022/file/fad7c708dda11f3e72cc1629bb130379-Paper-Conference.pdf)] [[slides](/assets/pdf/Slides_Neurips.pdf)] [[video](https://slideslive.com/38990568/multiagent-performative-prediction-with-greedy-deployment-and-consensus-seeking-agents?ref=search-presentations)] [[poster](/assets/pdf/Fancy_Posters_NeurIPS.pdf)]|

| <img src="/assets/images/aistats2022.png" width="400px" alt=""> | **Qiang Li**, Hoi-To Wai, State Dependent Performative Prediction with Stochastic Approximation, Society for Artificial Intelligence and Statistics (<span style="color:blue; font-weight:bold">AiSTAT 2022</span>). [[link](https://proceedings.mlr.press/v151/li22c.html)] [[poster](/assets/pdf/Fancy_Posters_AISTAT.pdf)]|



### Undergraduate Research

| <img src="/assets/images/cnsns2019.png" width="430px" alt=""> | Yao XU, **Qiang Li**,  Wenxue Li. Periodically intermittent discrete observation control for synchronization of fractional-order coupled systems, Communications in Nonlinear Science and Numerical Simulation 2019, (**CNSNS 2019**). [[link](https://www.sciencedirect.com/science/article/abs/pii/S1007570419300826)] |


| <img src="/assets/images/chaos2018.png" width="430px" alt=""> | Yongbao WU, **Qiang Li**,  Wenxue Li. Novel aperiodically intermittent stability criteria for Markovian switching stochastic delayed coupled systems, Chaos: An Interdisciplinary Journal of Nonlinear Science (**Chaos 2018**). [[link](https://pubs.aip.org/aip/cha/article-abstract/28/11/113117/569922/Novel-aperiodically-intermittent-stability?redirectedFrom=fulltext)] |


## Professional Service

- Conference Reviewer:
  - NeurIPS 2024;
  - Neural Information Processing Systems (NeurIPS), 2021, 2022;
  - International Conference on Machine Learning (ICML) 2023.

- Journal Reviewer:
  - IEEE Transactions on Signal Processing (TSP), 2022;
  - European Signal Processing Conference (EUSIPCO) 2022; 




<!-- | <img src="/assets/images/cleanedmsas.png" width="400px" alt=""> | **Hawkins, J. A.**, Kaczmarek, M. E., Müller, M. A., Drosten, C., Press, W. H., & Sawyer, S. L. (2019). A metaanalysis of bat phylogenetics and positive selection based on genomes and transcriptomes from 18 species. Proceedings of the National Academy of Sciences, 116(23), 11351-11360. [[press release](https://www.oden.utexas.edu/about/news/573/)] [[doi](https://doi.org/10.1073/pnas.1814995116)] [[code](https://github.com/hawkjo/mixr)] | -->
<!-- This paper studies the performative prediction problem which optimizes a stochastic loss function with data distribution that depends on the decision variable. We consider a forgotful settings of performative prediction problem, where the update dynamics is controlled by a Markov chain. Besides, we show that the expected squared distance to the fixed point solution decreases as $O(1/k)$, where $k$ is the iteration number.  -->