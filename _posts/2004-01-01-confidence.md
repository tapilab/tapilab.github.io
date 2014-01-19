---
layout: post
category : Information Extraction
title: Confidence estimation for information extraction
venue: HLT 2004
authors: Aron Culotta and Andrew McCallum
key: culotta04confidence
tags: [CRFs]
---

{% include JB/setup %}


#### Abstract

Information extraction techniques automatically create structured databases
from unstructured data sources, such as the Web or newswire documents. Despite
the successes of these systems, accuracy will always be imperfect. For many
reasons, it is highly desirable to accurately estimate the confidence the
system has in the correctness of each extracted field. The information
extraction system we evaluate is based on a linear-chain conditional random
field (CRF), a probabilistic model which has performed well on information
extraction tasks because of its ability to capture arbitrary, overlapping
features of the input in a Markov model. We implement several techniques to
estimate the confidence of both extracted fields and entire multi-field
records, obtaining an average precision of 98% for retrieving correct fields
and 87% for multi-field records.

#### Citation

	@inproceedings{culotta04confidence,
	  author = {Aron Culotta and Andrew McCallum},
	  title = {Confidence estimation for information extraction},
	  booktitle = {Human Language Technology Conference of the North American Chapter of the Association for Computational Linguistics (HLT/NAACL)},
	  address = {Boston, MA},
	  year = {2004},
	}
