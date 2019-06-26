---
layout: post
category : Public Health
title: Controlling for Unobserved Confounds in Classification Using Correlational Constraints 
venue: ICWSM 2017
authors: Virgile Landeiro, Aron Culotta
tags : [Twitter, confounding, classification, domain adaptation]
code: https://github.com/tapilab/icwsm-2017-confounds
key: landeiro17controlling
---
{% include JB/setup %}
#### Abstract

 As  classifiers become integrated into real-world  applications, it is important to consider not only their accuracy but also their robustness to changes in the data distribution. We consider the case where there is an unobserved confounding variable $z$ that influences both the features $x$ and the class variable $y$. When the influence of $z$ changes from training to testing data, classifier accuracy can degrade rapidly. In our approach, we assume that we can predict the value of $z$ at training time with some error. The prediction for $z$ is then fed to Pearl's back-door adjustment to build our model. Because of the attenuation bias caused by measurement error in $z$, standard approaches to controlling for $z$ are ineffective. In response, we propose a method to properly control for the influence of $z$ by first estimating its relationship with the class variable $y$, then updating predictions for $z$ to match that estimated relationship. By adjusting the influence of $z$, we show that we can build a model that exceeds competing baselines on accuracy as well as on robustness over a range of confounding relationships.


#### Citation

	@InProceedings{virgile2017controlling,
      author =       {Virgile Landeiro and Aron Culotta},
      title =        {Controlling for Unobserved Confounds in Classification Using Correlational Constraints},
      booktitle = {Proceedings of the Eleventh International AAAI Conference on Web and Social Media (ICWSM 2017)},
      year =         2017
    }
