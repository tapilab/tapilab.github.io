---
layout: post
category : Scalable Machine Learning
title: Tractable Learning and Inference with High-Order Representations
venue: ICML 2006 Workshop
authors: Aron Culotta and Andrew McCallum
key: culotta06tractable
tags: [coreference, MCMC]
---

{% include JB/setup %}

#### Abstract

Representing high-order interactions in data often results in large models
with an intractable number of hidden variables. In these models, inference and
learning must operate without instantiating the entire set of variables. This
paper presents a Metropolis-Hastings sampling approach to address this issue,
and proposes new methods to discriminatively estimate the proposal and target
distribution of the sampler using a ranking function over configurations. We
demonstrate our approach on the task of paper and author deduplication,
showing that our method enables complex, advantageous representations of the
data while maintaining tractable learning and inference procedures.

#### Citation

	@inproceedings{culotta06tractable,
	  author = {Aron Culotta and Andrew McCallum},
	  title = {Tractable Learning and Inference with High-Order Representations},
	  booktitle = {International Conference on Machine Learning Workshop on Open Problems in Statistical Relational Learning},
	  address = {Pittsburgh, PA},
	  year = {2006},
 	}
