---
abstract: 'Predicting the toxicity of a compound preclinically enables better decision making, thereby reducing development costs and increasing patient safety. It is a complex issue, but in vitro assays and physicochemical properties of compounds can be used to predict clinical toxicity. Neural networks (NNs) are a popular predictive tool due to their flexibility and ability to model non-linearities, but they are prone to overfitting and therefore are not recommended for small data sets. Furthermore, they do not quantify uncertainty in the predictions. Bayesian neural networks (BNNs) are able to avoid these pitfalls by using prior distributions on the parameters of a NN model and representing uncertainty about the predictions in the form of a distribution. We model the severity of drug-induced liver injury (DILI) to provide an example of a BNN performing better than a traditional but less flexible proportional odds logistic regression (POLR) model. We use appropriate metrics to evaluate predictions of the ordinal data type. To demonstrate the effect of a hierarchical prior for BNNs as an alternative to hyperparameter optimisation for NNs, we compare the performance of a BNN against NNs with dropout or penalty regularisation. We reduce the task to multiclass classification in order to be able to perform this comparison. A BNN trained for the multiclass classification produces poorer results than a BNN that captures the order. The current work lays a foundation for more complex models built on larger datasets, but can already be adopted by safety pharmacologists for risk quantification.' 

authors:
- admin
- Williams, Dominic P 
- Afzal, Avid M 
- Lazic, Stanley E

date: "2020-11-08T00:00:00Z"
doi: ""
featured: true
image:
  caption: 
  focal_point: ""
  preview_only: false
projects:
- example
publication: In *Computational Toxicology*
publication_short:
publication_types:
- "2"
publishDate: "2022-07-29T00:00:00Z"
#slides: example
summary:
tags: []
title: 'A Bayesian neural network for toxicity prediction'
share: false
url_code: "https://github.com/elizavetasemenova/BNN_tox"
url_dataset: ""
url_pdf: "https://www.biorxiv.org/content/10.1101/2020.04.28.065532v3.full.pdf"
url_poster: ""
url_project: ""
url_slides: ""
url_source: ""
url_video: ""
---

This publication was the first industrial application of the Turing.jl probabilistic programming language. It was coveredby [JuliaComputing](https://juliacomputing.com/case-studies/astra-zeneca/) as a case-study. I presented this work at the Applied Machine Leaning Days 2020 conference, and the recording is availabl [here](https://www.youtube.com/watch?v=BCQ2oVlu_tY).


