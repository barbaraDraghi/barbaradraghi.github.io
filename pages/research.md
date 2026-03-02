---
layout: page
title: "Published Research"
permalink: /pages/research/
description: "Peer-reviewed research papers and collaborations."
---
<section class="pub-section">
  {% include publication.html
     title="Bayesboost: Identifying and Handling Bias Using Synthetic Data Generators"
     authors="Barbara Draghi, Zhenchen Wang, Puja Myles, Allan Tucker"
     journal="PMLR 154:49–62, 2021"
     doi="https://dx.doi.org/10.2139/ssrn.4052302"
     abstract="Advanced synthetic data generators can model sensitive personal datasets by creating simulated samples of data with realistic correlation structures and distributions, but with a greatly reduced risk of identifying individuals. This has huge potential in medicine where sensitive patient data can be simulated and shared, enabling the development and robust validation of new AI technologies for diagnosis and disease management. However, even when massive ground truth datasets are available (such as UK-NHS databases which contain patient records in the order of millions) there is a high risk that biases still exist which are carried over to the data generators. For example, certain cohorts of patients may be under-represented due to cultural sensitivities amongst some communities, or due to institutionalised procedures in data collection. The under-representation of groups is one of the forms in which bias can manifest itself in machine learning, and it is the one we investigate in this work. These factors may also lead to structurally missing data or incorrect correlations and distributions which will be mirrored in the synthetic data generated from biased ground truth datasets. In this paper, we explore methods to improve synthetic data generators by using probabilistic methods to firstly identify the under-represented samples in ground truth data, and then to boost these types of data when generating synthetic samples. The paper explores attempts to create synthetic data that contain more realistic distributions and that lead to predictive models with better performance."
  %}

  {% include publication.html
     title="Identifying and Handling Data Bias Within Primary Healthcare Data Using Synthetic Data Generators"
     authors="Barbara Draghi, Zhenchen Wang, Puja Myles, Allan Tucker"
     journal="Heliyon, 2024"
     doi="https://doi.org/10.1016/j.heliyon.2024.e24164"
     abstract="Advanced synthetic data generators can simulate data samples that closely resemble sensitive personal datasets while significantly reducing the risk of individual identification. The use of these advanced generators holds enormous potential in the medical field, as it allows for the simulation and sharing of sensitive patient data. This enables the development and rigorous validation of novel AI technologies for accurate diagnosis and efficient disease management. Despite the availability of massive ground truth datasets (such as UK-NHS databases that contain millions of patient records), the risk of biases being carried over to data generators still exists. These biases may arise from the under-representation of specific patient cohorts due to cultural sensitivities within certain communities or standardised data collection procedures. Machine learning models can exhibit bias in various forms, including the under-representation of certain groups in the data. This can lead to missing data and inaccurate correlations and distributions, which may also be reflected in synthetic data. Our paper aims to improve synthetic data generators by introducing probabilistic approaches to first detect difficult-to-predict data samples in ground truth data and then boost them when applying the generator. In addition, we explore strategies to generate synthetic data that can reduce bias and, at the same time, improve the performance of predictive models."
  %}

  {% include publication.html
     title="Bias-aware Synthetic Data Generation: A Tailored Use-Case Driven Approach"
     authors="Barbara Draghi, Puja Myles, Allan Tucker"
     journal="Proceedings of the Workshop on Bias and Fairness in AI, September 2024"
     pdf="https://drive.google.com/file/d/1ro7EKzs9Znp21t5RAC8fH6Jmr7nzW4Fz/view"
     abstract="The terms bias and fairness are often mistakenly used interchangeably in discussions about AI systems. This confusion is particularly problematic in healthcare, where biased data and models can lead to unfair treatment recommendations and diagnostic inaccuracies. Measuring bias and fairness is crucial to ensure equitable patient care and accurate diagnostics. This paper presents an approach to (1) quantify data biases using appropriate data-based metrics, and (2) use the findings of this analysis to guide a bias-aware synthetic data generation process  We also explore (3) the use of bias-aware synthetic data generators to address biases in three different use cases: one focusing on balancing labels, one on balancing sensitive attributes, and one addressing both simultaneously. Lastly, we propose an evaluation framework to assess data- and model-based metrics for quantifying fairness improvements. Our preliminary findings suggest that synthetic data generated using bias-aware generators can improve inclusivity, balance performance with fairness, and reduce representation bias, potentially contributing to more equitable healthcare outcomes. This study underscores the importance of aligning synthetic data generation with the intended research objectives and highlights the potential of robust synthetic data generators to meet diverse healthcare needs, thereby improving their overall utility."
  %}
</section>

<section class="pub-section">
  <h1 class="page-title">Collaborations</h1>

  {% include publication.html
     title="High-Fidelity Synthetic Data Applications for Data Augmentation"
     authors="Zhenchen Wang, <strong>Barbara Draghi</strong>, Ylenia Rotalinti, et al."
     journal="IntechOpen, 2024"
     doi="http://dx.doi.org/10.5772/intechopen.113884"
  %}

  {% include publication.html
     title="The Impact of Bias on Drift Detection in AI Health Software"
     authors="Azar Khoshravan, <strong>Barbara Draghi</strong>, Ylenia Rotalinti, Puja Myles, Allan Tucker"
     journal="AIME 2023, Springer LNCS"
     doi="https://doi.org/10.1007/978-3-031-34344-5_37"
  %}

  {% include publication.html
     title="Probabilistic vs Deep Generative Models: A Fairness-Centred Evaluation of Synthetic Healthcare Data"
     authors="Dima Alattal, <strong>Barbara Draghi</strong>, Puja Myles, et al."
     journal="International Journal of Computational Intelligence Systems"
     doi="https://doi.org/10.21203/rs.3.rs-7565139/v1"
  %}
</section>
