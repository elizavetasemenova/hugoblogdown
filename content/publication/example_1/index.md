---
abstract: 'Gaussian processes (GPs), implemented through multivariate Gaussian distributions for a finite collection of data, are the most popular approach in small-area spatial statistical modelling. In this context, they are used to encode correlation structures over space and can generalize well in interpolation tasks. Despite their flexibility, off-the-shelf GPs present serious computational challenges which limit their scalability and practical usefulness in applied settings. Here, we propose a novel, deep generative modelling approach to tackle this challenge, termed PriorVAE: for a particular spatial setting, we approximate a class of GP priors through prior sampling and subsequent fitting of a variational autoencoder (VAE). Given a trained VAE, the resultant decoder allows spatial inference to become incredibly efficient due to the low dimensional, independently distributed latent Gaussian space representation of the VAE. Once trained, inference using the VAE decoder replaces the GP within a Bayesian sampling framework. This approach provides tractable and easy-to-implement means of approximately encoding spatial priors and facilitates efficient statistical inference. We demonstrate the utility of our VAE two-stage approach on Bayesian, small-area estimation tasks.' 
author_notes:
- Equal contribution
authors:
- admin
- Yidan Xu
- Adam Howes
- Theo Rashid
- Samir Bhatt
- Swapnil Mishra 
- Seth Flaxman
date: "2022-07-01T00:00:00Z"
doi: "https://doi.org/10.1098/rsif.2022.0094"
featured: true
image:
  caption: 'MCMC inference using PriorVAE'
  focal_point: ""
  preview_only: false
projects:
- example
publication: In *Journal of the Royal Society Interface*
publication_short:
publication_types:
- "1"
publishDate: "2017-01-01T00:00:00Z"
#slides: example
summary: Encoding spatial priors with variational autoencoders for small-area estimation
tags: []
title: 'PriorVAE: encoding spatial priors with variational autoencoders for small-area estimation'
url_code: "https://github.com/elizavetasemenova/priorvae"
url_dataset: ""
url_pdf: "https://royalsocietypublishing.org/doi/full/10.1098/rsif.2022.0094"
url_poster: ""
url_project: ""
url_slides: ""
url_source: ""
url_video: ""
---

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
