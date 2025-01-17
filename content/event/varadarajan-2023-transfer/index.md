---
title: 'Talk @ ACL 2023 Best Paper Awards on transfer and active learning for dissonance detection'

date: '2023-07-09'
publishDate: '2023-07-09T05:49:28.732098Z'

url_pdf: https://aclanthology.org/2023.acl-long.665/
url_video: https://aclanthology.org/2023.acl-long.665.mp4
event: Best Paper Award Presentations at The 61st Annual Meeting of the Association for Computational Linguistics.
event_url: https://2023.aclweb.org/program/best_papers/

abstract: While transformer-based systems have enabled greater accuracies with fewer training examples, data acquisition obstacles still persist for rare-class tasks -- when the class label is very infrequent (e.g. < 5% of samples). Active learning has in general been proposed to alleviate such challenges, but choice of selection strategy, the criteria by which rare-class examples are chosen, has not been systematically evaluated. Further, transformers enable iterative transfer-learning approaches. We propose and investigate transfer- and active learning solutions to the rare class problem of dissonance detection through utilizing models trained on closely related tasks and the evaluation of acquisition strategies, including a proposed probability-of-rare-class (PRC) approach. We perform these experiments for a specific rare class problem of collecting language samples of cognitive dissonance from social media. We find that PRC is a simple and effective strategy to guide annotations and ultimately improve model accuracy while transfer-learning in a specific order can improve the cold-start performance of the learner but does not benefit iterations of active learning.
# Summary. An optional shortened abstract.
summary: This study explores transfer- and active learning solutions for rare-class problems, focusing on detecting cognitive dissonance in social media. We propose a probability-of-rare-class (PRC) approach for selecting samples and evaluate various acquisition strategies. We find that PRC effectively guides annotations and improves model accuracy, while specific transfer-learning sequences enhance initial performance but don't benefit subsequent active learning iterations.
tags:
- human-in-the-loop, Active Learning, Large Language Models, dissonance, stance

featured: true
image:
  caption: 'Addressing needle-in-a-haystack problem for challenging NLP tasks'
  focal_point: ""
  preview_only: false
  
---
