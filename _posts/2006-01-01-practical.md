---
layout: post
category : Scalable Machine Learning
title: Practical Markov logic containing first-order quantifiers with application to identity uncertainty
venue: HLT/NAACL 2006 Workshop
authors: Aron Culotta and Andrew McCallum
key: culotta06practical
tags: [coreference]
---

{% include JB/setup %}

#### Abstract

*Markov logic* is a highly expressive language recently introduced to specify
 the connectivity of a Markov network using first-order logic. While Markov
 logic is capable of constructing arbitrary first-order formulae over the
 data, the complexity of these formulae is often limited in practice because
 of the size and connectivity of the resulting network. In this paper, we
 present approximate inference and estimation methods that incrementally
 instantiate portions of the network as needed to enable first-order
 existential and universal quantifiers in *Markov logic networks*. When
 applied to the problem of identity uncertainty, this approach results in a
 conditional probabilistic model that can reason about objects, combining the
 expressivity of recently introduced BLOG models with the predictive power of
 conditional training. We validate oualgorithms on the tasks of citation
 matching and author disambiguation.

#### Citation

	@inproceedings{culotta06practical,
	  author = {Aron Culotta and Andrew McCallum},
	  title = {Practical Markov logic containing first-order quantifiers with application to identity uncertainty},
	  booktitle = {Human Language Technology Workshop on Computationally Hard Problems and Joint Inference in Speech and Language Processing (HLT/NAACL)},
	  year = {2006},
	  month = {June},
	}
