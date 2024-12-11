---
title: "Human-in-the-Loop Feature Discovery for Tabular Data"
collection: publications
permalink: /publication/hil-autofeat
excerpt: 'In this paper, we introduce the first user-driven human-in-theloop feature discovery method called HILAutoFeat. We demonstrate the capabilities of HILAutoFeat, which effectively combines
automated feature discovery with user-driven insights. Our demonstration is centred around two scenarios: (𝑖) an automated feature
discovery scenario – HILAutoFeat acts as a steward in a large data
lake where the user is unaware of the quality and relevance of the
data, and (𝑖𝑖) a scenario where HILAutoFeat and the user work
together – the user drives the feature discovery process by adding
his domain and business knowledge, while HILAutoFeat performs
the intensive computations.'
date: 2024-10-21
venue: 'CIKM Demo'
paperurl: 'https://dl.acm.org/doi/pdf/10.1145/3627673.3679211'
authors: 'Andra Ionescu, Zeger Mouw, Efthimia Aivaloglou, Rihan Hai, Asterios Katsifodimos'
---

In recent years, researchers have developed several methods to automate discovering datasets and augmenting features for training Machine Learning (ML) models. Together with feature selection, these
efforts have paved the way towards what is termed the feature discovery process. Data scientists and engineers use automated feature
discovery over tabular datasets to add new features from different
sources and enrich training data. By surveying data practitioners,
we have observed that automated feature discovery approaches do
not allow data scientists to use their domain knowledge during the
feature discovery process. In addition, automated feature discovery
methods can leak private features or introduce biased ones.

In this paper, we introduce the first user-driven human-in-theloop feature discovery method called HILAutoFeat. We demonstrate the capabilities of HILAutoFeat, which effectively combines
automated feature discovery with user-driven insights. Our demonstration is centred around two scenarios: (𝑖) an automated feature
discovery scenario – HILAutoFeat acts as a steward in a large data
lake where the user is unaware of the quality and relevance of the
data, and (𝑖𝑖) a scenario where HILAutoFeat and the user work
together – the user drives the feature discovery process by adding
his domain and business knowledge, while HILAutoFeat performs
the intensive computations.

<ul>
    <li> 
        <a href="https://dl.acm.org/doi/pdf/10.1145/3627673.3679211" target="_blank"><i class="fa-solid fa-file-pdf"></i> Paper [pdf]</a>
    </li>
    <li> 
        <a href="https://youtu.be/tjXxCb2C3hU" target="_blank"><i class="fa-brands fa-youtube"></i> Demo [video]</a>
    </li>
</ul>


- Bibtex: 
```
@inproceedings{ionescu2024human,
  title={Human-in-the-Loop Feature Discovery for Tabular Data},
  author={Ionescu, Andra and Mouw, Zeger and Aivaloglou, Efthimia and Hai, Rihan and Katsifodimos, Asterios},
  booktitle={Proceedings of the 33rd ACM International Conference on Information and Knowledge Management},
  pages={5215--5219},
  year={2024}
}
```