---
title: "Advancing Urban Traffic Accident Forecasting through Sparse Spatio-Temporal Dynamic Learning"
collection: publications
category: journal
permalink: /publication/2024-03-18-urban-traffic-accident-forecasting
header:
  teaser: publications/2024-03-18-urban-traffic-accident-forecasting.jpg

authors: "<strong>Pengfei Cui</strong>, Xiaobao Yang, Mohamed Abdel-Aty, Jinliang Zhang, Xuedong Yan"
venue: "Accident Analysis & Prevention"
date: 2024-03-18
year: 2024
status: "published"
method: "Sparse Spatio-Temporal Dynamic Learning (SSTDL) Network"
data: "NYC Manhattan Traffic Accident Data (2017-2019)"
objects: "Urban Traffic Accident Risk Forecasting"

abstract: "Traffic accident forecasting is a crucial component of advanced transportation management systems, playing a vital role in enhancing road safety and optimizing traffic flow[cite: 17]. [cite_start]However, accurate forecasting is challenging due to the intricate spatio-temporal dependencies and the sparsity of accident data[cite: 18]. [cite_start]Existing methods often rely on predefined, static graphs that fail to capture dynamic spatial correlations or effectively handle the zero-inflated nature of accident data[cite: 19]. [cite_start]To address these limitations, we propose a novel Sparse Spatio-Temporal Dynamic Learning (SSTDL) network[cite: 20]. [cite_start]The SSTDL integrates a Sparse Bayesian Graph Convolutional Network (SBGCN) to dynamically learn spatial dependencies and prune irrelevant connections, thereby accommodating the sparsity inherent in accident data[cite: 23]. [cite_start]Furthermore, we incorporate a Causal Dilated Convolution (CDC) module to capture long-term temporal dependencies and distinct accident patterns[cite: 24]. [cite_start]We evaluated our model using a real-world dataset from Manhattan, New York[cite: 25]. [cite_start]The experimental results demonstrate that SSTDL outperforms state-of-the-art baselines in accuracy and robustness[cite: 26]. [cite_start]The ablation study further validates the effectiveness of the sparse graph learning and dynamic temporal modeling components[cite: 27]. [cite_start]This study provides a new perspective on modeling sparse spatio-temporal data and offers a practical tool for proactive traffic safety management[cite: 28]."
description: "This paper proposes a Sparse Spatio-Temporal Dynamic Learning (SSTDL) network to forecast urban traffic accident risk. It features a Sparse Bayesian Graph Convolutional Network (SBGCN) to handle data sparsity and dynamic spatial correlations, and a Causal Dilated Convolution (CDC) for temporal dependencies, demonstrating superior performance on NYC accident data."

doi: "https://doi.org/10.1016/j.aap.2024.107564"
citation: 'Cui, P., Yang, X., Abdel-Aty, M., Zhang, J., & Yan, X. (2024). Advancing urban traffic accident forecasting through sparse spatio-temporal dynamic learning. <i>Accident Analysis & Prevention</i>, 200, 107564.'
bibtex: |
  @article{cui2024advancing,
  title={Advancing urban traffic accident forecasting through sparse spatio-temporal dynamic learning},
  author={Cui, Pengfei and Yang, Xiaobao and Abdel-Aty, Mohamed and Zhang, Jinliang and Yan, Xuedong},
  journal={Accident Analysis \& Prevention},
  volume={200},
  pages={107564},
  year={2024},
  publisher={Elsevier},
  doi={10.1016/j.aap.2024.107564}
  }
paperurl: "https://doi.org/10.1016/j.aap.2024.107564"
---