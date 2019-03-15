---
layout: post
category : Public Health
title:  Forecasting the presence and intensity of hostility on Instagram using linguistic and social features 
venue: ICWSM 2018
authors: Ping Liu, Joshua Guberman, Libby Hemphill, Aron Culotta
tags : [Instagram, cyberbullying]
code: https://github.com/tapilab/icwsm-2018-hostility
key: liu2018forecasting
---
{% include JB/setup %}
#### Abstract

 Online antisocial behavior, such as cyberbullying, harassment, and trolling, is a widespread problem that threatens free discussion and has negative physical and mental health consequences for victims and communities. While prior work has proposed automated methods to identify hostile comments in online discussions, these methods work retrospectively on comments that have already been posted, making it difficult to intervene before an interaction escalates. In this paper we instead consider the problem of forecasting future hostilities in online discussions, which we decompose into two tasks: (1) given an initial sequence of non-hostile comments in a discussion, predict whether some future comment will contain hostility; and (2) given the first hostile comment in a discussion, predict whether this will lead to an escalation of hostility in subsequent comments. Thus, we aim to forecast both the presence and intensity of hostile comments based on linguistic and social features from earlier comments. To evaluate our approach, we introduce a corpus of over 30K annotated Instagram comments from over 1,100 posts. Our approach is able to predict the appearance of a hostile comment on an Instagram post ten or more hours in the future with an AUC of .82 (task 1), and can furthermore distinguish between high and low levels of future hostility with an AUC of .91 (task 2).


#### Citation
    @InProceedings{liu2018forecasting,
      author =       {Ping Liu and Joshua Guberman and Libby Hemphill and {\bf Aron Culotta},
      title =        {Forecasting the presence and intensity of hostility on Instagram using linguistic and social features},
      booktitle = {Proceedings of the Twelfth International AAAI Conference on Web and Social Media (ICWSM 2018)},
      year =         2018,
    }

