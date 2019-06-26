---
layout: post
category : Public Health
title: Discovering and Controlling for Latent Confounds in Text Classification Using Adversarial Domain Adaptation
venue: SDM 2019
authors: Virgile Landeiro, Aron Culotta
tags : [Twitter, confounding, classification]
key: landeiro2019discovering
---
{% include JB/setup %}
#### Abstract

In text classification, the testing data often systematically differ
from the training data, a problem called dataset shift. In this paper,
we investigate a type of dataset shift we call confounding shift.
Such a setting exists when two conditions are met: (a) there is
a confound variable Z that influences both text features X and
class label Y ; (b) the relationship between Z and Y changes from
training to testing. While recent work in this area has required
confounds to be known ahead of time, this is unrealistic for many
settings. To address this shortcoming, we propose a method both
to discover and to control for potential confounds. The approach
first uses neural network-based topic modeling to discover potential
confounds that differ between training and testing data, then uses
adversarial training to fit a classification model that is invariant
to these discovered confounds. We find the resulting method to
improve over state-of-the-art domain adaptation method, while also
producing results that are competitive with those obtained when
confounds are known ahead of time.


#### Citation
    @InProceedings{landeiro2019discovering,
      author =       {Virgile Landeiro and Tuan Tran and Aron Culotta},
      title =        {Discovering and Controlling for Latent Confounds in Text Classification Using Adversarial Domain Adaptation},
      booktitle = {Proceedings of the SIAM International Conference on Data Mining (SDM19)},
      year =         2019,
    }


