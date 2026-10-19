---
title: "Efficiently Computed Marginal Likelihoods for Multivariate Mixture Models"
collection: publications
category: preprints
excerpt: 'We propose a new methodology for efficiently computing marginal likelihoods for univariate and multivariate mixture models.'
date: 2025-04-30
venue: 'arXiv'
bibtexurl: 'http://m-metodiev.github.io/files/2025_thames_mixtures_arxiv.bib'
paperurl: 'http://m-metodiev.github.io/files/2025_thames_mixtures_arxiv.pdf'
citation: 'Martin Metodiev, Marie Perrot-Dockès, Pierre Latouche, Adrian E. Raftery.
"Easily Computed Marginal Likelihoods for Multivariate Mixture Models Using the THAMES Estimator." arXiv preprint arXiv:2504.21812.'
---
We propose a new methodology for efficiently computing marginal likelihoods for univariate and multivariate mixture models. The estimator that this methodology proposes computes the marginal likelihood from Markov chain Monte Carlo (MCMC) samples, is consistent, asymptotically normal and of finite variance. In addition, it is invariant to label switching, does not require posterior samples from hidden allocation vectors, and is efficiently approximated, even for an arbitrarily high number of components. Its computational efficiency is based on an asymptotically optimal ordering of the parameter space, which can in turn be used to provide useful visualisations. We test it in simulation settings where the true marginal likelihood is available analytically. It performs well against state-of-the-art competitors, even in multivariate settings with a high number of components. We demonstrate its utility for inference and model selection on univariate and multivariate data sets.
