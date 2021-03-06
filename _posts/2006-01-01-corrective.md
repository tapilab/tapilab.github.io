---
layout: post
category : Active Learning
title: Corrective Feedback and Persistent Learning for Information Extraction
venue: Artificial Intelligence 2006
authors: Aron Culotta, Trausti Kristjansson, Andrew McCallum and Paul Viola
key: culotta06corrective
tags: [CRFs]
---

{% include JB/setup %}

#### Abstract

To successfully embed statistical machine learning models in real world
applications, two post-deployment capabilities must be provided: (1) the
ability to solicit user corrections and (2) the ability to update the model
from these corrections. We refer to the former capability as *corrective
feedback* and the latter as *persistent learning*. While these
capabilities have a natural implementation for simple classification tasks
such as spam filtering, we argue that a more careful design is required for
*structured classification* tasks. One example of a structured
classification task is *information extraction*, in which raw text is
analyzed to automatically populate a database. In this work, we augment a
probabilistic information extraction system with corrective feedback and
persistent learning components to assist the user in building, correcting, and
updating the extraction model. We describe methods of guiding the user to
incorrect predictions, suggesting the most *informative* fields to
correct, and incorporating corrections into the inference algorithm. We also
present an active learning framework that minimizes not only how many examples
a user must label, but also how difficult each example is to label. We
empirically validate each of the technical components in simulation and
quantify the user effort saved. We conclude that more efficient corrective
feedback mechanisms lead to more effective persistent learning.  #### Citation

#### Citation

	@article{culotta06corrective,
	  author = {Aron Culotta and Trausti Kristjansson and Andrew McCallum and Paul Viola},
	  title = {Corrective Feedback and Persistent Learning for Information Extraction},
	  journal = {Artificial Intelligence},
	  year = {2006},
	  volume = {170},
	  pages = {1101--1122},
	}
