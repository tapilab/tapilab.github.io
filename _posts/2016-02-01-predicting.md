---
layout: post
category: User Attribute Inference
title: Predicting Twitter User Demographics using Distant Supervision from Website Traffic Data
venue: JAIR
authors: Aron Culotta, Nirmal Kumar Ravi, Jennifer Cutler
tags : [Twitter, regression, distant supervision]
key: culotta16predicting
code: https://github.com/tapilab/jair-2016-demographics
---
{% include JB/setup %}
#### Abstract

Understanding the demographics of users of online social networks has
important applications for health, marketing, and public messaging. Whereas
most prior approaches rely on a supervised learning approach, in which
individual users are labeled with demographics for training, we instead create
a distantly labeled dataset by collecting audience measurement data for 1,500
websites (e.g., 50% of visitors to gizmodo.com are estimated to have a
bachelor's degree). We then fit a regression model to predict these
demographics from information about the followers of each website on
Twitter. Using patterns derived both from textual content and the social
network of each user, our final model produces an average held-out correlation
of .77 across seven different variables (age, gender, education, ethnicity,
income, parental status, and political preference). We then apply this model
to classify individual Twitter users by ethnicity, gender, and political
preference, finding performance that is surprisingly competitive with a fully
supervised approach.

#### Citation

	@Article{culotta16predicting,
		author =       {Aron Culotta and and Nirmal Kumar Ravi and Jennifer Cutler},
		title =        {Predicting Twitter User Demographics using Distant Supervision from Website Traffic Data},
		journal =      {Journal of Artificial Intelligence Research},
                volume =       {55},
		year =         2016,
                pages =        {389--408},
	}
