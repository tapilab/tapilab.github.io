---
layout: post
category : Active Learning
title: Interactive information extraction with constrained conditional random fields
venue: AAAI 2004
authors: Trausti Kristjannson, Aron Culotta, Paul Viola, and Andrew McCallum
key: kristjannson04interactive
tags: [CRFs]
---

{% include JB/setup %}


#### Abstract

Information Extraction methods can be used to automatically "fill-in" database
forms from unstructured data such as Web documents or email. State-of-the-art
methods have achieved low error rates but invariably make a number of
errors. The goal of an *interactive information extraction* system is to
assist the user in filling in database fields while giving the user confidence
in the integrity of the data. The user is presented with an interactive
interface that allows both the rapid verification of automatic field
assignments and the correction of errors. In cases where there are multiple
errors, our system takes into account user corrections, and immediately
propagates these constraints such that other fields are often corrected
automatically. Linear-chain conditional random fields (CRFs) have been shown
to perform well for information extraction and other language modelling tasks
due to their ability to capture arbitrary, overlapping features of the input
in a Markov model. We apply this framework with two extensions: a constrained
Viterbi decoding which finds the optimal field assignments consistent with the
fields explicitly specified or corrected by the user; and a mechanism for
estimating the confidence of each extracted field, so that low-confidence
extractions can be highlighted. Both of these mechanisms are incorporated in a
novel user interface for form filling that is intuitive and speeds the entry
of data---providing a 23% reduction in error due to automated corrections.

*Best Paper Award (Honorable Mention)*

#### Citation

	@inproceedings{kristjannson04interactive,
	  author = {Trausti Kristjannson and Aron Culotta and Paul Viola and Andrew McCallum},
	  title = {Interactive information extraction with constrained conditional random fields},
	  shortbooktitle = {AAAI},
	  booktitle = {Nineteenth National Conference on Artificial Intelligence (AAAI)},
	  address = {San Jose, CA},
	  year = {2004},
	}
