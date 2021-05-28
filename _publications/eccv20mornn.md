---
title: "Recurrent Image Annotation With Explicit Inter-Label Dependencies"
collection: publications
permalink: /publication/eccv20mornn
excerpt: 'Inspired by the success of the CNN-RNN framework in the image captioning task, several works have explored this in multi-label image annotation with the hope that the RNN followed by a CNN would encode inter-label dependencies better than using a CNN alone. To do so, for each training sample, the earlier methods converted the ground- truth label-set into a sequence of labels based on their frequencies (e.g., rare-to-frequent) for training the RNN. However, since the ground-truth is an unordered set of labels, imposing a fixed and predefined sequence on them does not naturally align with this task. To address this, some of the recent papers have proposed techniques that are capable to train the RNN without feeding the ground-truth labels in a particular se- quence/order. However, most of these techniques leave it to the RNN to implicitly choose one sequence for the ground-truth labels corresponding to each sample at the time of training, thus making it inherently biased. In this paper, we address this limitation and propose a novel approach in which the RNN is explicitly forced to learn multiple relevant inter- label dependencies, without the need of feeding the ground-truth in any particular order. Using thorough empirical comparisons, we demonstrate that our approach outperforms several state-of-the-art techniques on two popular datasets (MS-COCO and NUS-WIDE). Additionally, it provides a new perspecitve of looking at an unordered set of labels as equivalent to a collection of different permutations (sequences) of those labels, thus naturally aligning with the image annotation task.'
date: 
venue: '16th European Conference On Computer Vision (ECCV, 2020'
paperurl:
citation:
---

[Paper](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123740188.pdf)
[Code](https://github.com/ayushidutta/multi-order-rnn/)
