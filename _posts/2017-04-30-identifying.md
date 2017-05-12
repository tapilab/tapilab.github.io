---
layout: post
category : Public Health
title:  Identifying leading indicators of product recalls from online reviews using positive unlabeled learning and domain adaptation
venue: ICWSM 2017
authors: Shreesh Kumara Bhat, Aron Culotta
tags : [Amazon, recalls, classification, domain adaptation, PU learning]
code: https://github.com/tapilab/icwsm-2017-recalls
key: bhat17identifying
---
{% include JB/setup %}
#### Abstract

 Consumer protection agencies are charged with safeguarding the public from hazardous products, but the thousands of products under their jurisdiction make it challenging to identify and respond to consumer complaints quickly. In this paper, we propose a system to mine Amazon.com reviews to identify products that may pose safety or health hazards. Since labeled data for this task are scarce, our approach combines positive unlabeled learning with domain adaptation to train a classifier from consumer complaints submitted to an online government portal. We find that our approach results in an absolute F1 score improvement of 8% over the best competing baseline. Furthermore, when we apply the classifier to Amazon reviews of known recalled products, we identify safety hazard reports prior to the recall date for 45% of the products. This suggests that the system may be able to provide an early warning system to alert consumers to hazardous products before an official recall is announced.

 Demo: https://shreeshbhat.github.io/recalls


#### Citation

	@InProceedings{bhat2017identifying,
      author =       {Shreesh Kumara Bhat and Aron Culotta},
      title =        {Identifying leading indicators of product recalls from online reviews using positive unlabeled learning and domain adaptation},
      booktitle = {Proceedings of the Eleventh International AAAI Conference on Web and Social Media (ICWSM 2017)},
      year =         2017
    }
