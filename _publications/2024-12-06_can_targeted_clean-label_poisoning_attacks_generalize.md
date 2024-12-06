---
title: "Can Targeted Clean-Label Poisoning Attacks Generalize?"
collection: publications
category: preprints
permalink: /publication/2024-12-06_can_targeted_clean-label_poisoning_attacks_generalize
date: 2024-12-06
venue: 'arXiv Preprint'
paperurl: 'https://arxiv.org/pdf/2412.03908'
citation: 'Zhizhen Chen, Subrat Kishore Dutta, Zhengyu Zhao, Chenhao Lin, Chao Shen, and Xiao Zhang. &quot;Can Targeted Clean-Label Poisoning Attacks Generalize?&quot;  <i>arXiv preprint arXiv: 2412.03908</i>, 2024.'
---

![](/images/can_targeted_clean-label_poisoning_attacks_generalize.png)

# Abstract

Targeted poisoning attacks aim to compromise the model's prediction on specific target samples. In a common clean-label setting, they are achieved by slightly perturbing a subset of training samples given access to those specific targets. Despite continuous efforts, it remains unexplored whether such attacks can generalize to unknown variations of those targets. In this paper, we take the first step to systematically study this generalization problem. Observing that the widely adopted, cosine similarity-based attack exhibits limited generalizability, we propose a well-generalizable attack that leverages both the direction and magnitude of model gradients. In particular, we explore diverse target variations, such as an object with varied viewpoints and an animal species with distinct appearances. Extensive experiments across various generalization scenarios demonstrate that our method consistently achieves the best attack effectiveness. For example, our method outperforms the cosine similarity-based attack by 20.95% in attack success rate with similar overall accuracy, averaged over four models on two image benchmark datasets. The code is available at [https://github.com/jiaangk/generalizable_tcpa](https://github.com/jiaangk/generalizable_tcpa).