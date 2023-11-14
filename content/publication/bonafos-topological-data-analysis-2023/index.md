---
title: 'Topological Data Analysis of Human Vowels: Persistent Homologies across Representation
  Spaces'
authors:
- Guillem Bonafos
- Jean-Marc Freyermuth
- Pierre Pudlo
- Samuel Tronçon
- Arnaud Rey
date: '2023-10-01'
publishDate: '2023-11-14T18:04:37.233505Z'
publication_types:
- manuscript
publication: '*arXiv*'
doi: 10.48550/arXiv.2310.06508
abstract: "Topological Data Analysis (TDA) has been successfully used for various
  tasks in signal/image processing, from visualization to supervised/unsupervised
  classification. Often, topological characteristics are obtained from persistent
  homology theory. The standard TDA pipeline starts from the raw signal data or a
  representation of it. Then, it consists in building a multiscale topological structure
  on the top of the data using a pre-specified filtration, and finally to compute
  the topological signature to be further exploited. The commonly used topological
  signature is a persistent diagram (or transformations of it). Current research discusses
  the consequences of the many ways to exploit topological signatures, much less often
  the choice of the filtration, but to the best of our knowledge, the choice of the
  representation of a signal has not been the subject of any study yet. This paper
  attempts to provide some answers on the latter problem. To this end, we collected
  real audio data and built a comparative study to assess the quality of the discriminant
  information of the topological signatures extracted from three different representation
  spaces. Each audio signal is represented as i) an embedding of observed data in
  a higher dimensional space using Taken's representation, ii) a spectrogram viewed
  as a surface in a 3D ambient space, iii) the set of spectrogram's zeroes. From vowel
  audio recordings, we use topological signature for three prediction problems: speaker
  gender, vowel type, and individual. We show that topologically-augmented random
  forest improves the Out-of-Bag Error (OOB) over solely based Mel-Frequency Cepstral
  Coefficients (MFCC) for the last two problems. Our results also suggest that the
  topological information extracted from different signal representations is complementary,
  and that spectrogram's zeros offers the best improvement for gender prediction."
tags:
- Computer Science - Sound
- Electrical Engineering and Systems Science - Audio and Speech Processing
- Statistics - Applications
- Statistics - Machine Learning
links:
- name: arXiv
  url: https://arxiv.org/abs/2310.06508
---
