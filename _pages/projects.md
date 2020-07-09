---
title:  "Projects"
layout: single
permalink: /projects/
author_profile: true
header:
  overlay_image: /assets/images/biology to artificial nngit.png
  overlay_filter: 0.5 # same as adding an opacity of 0.5 to a black background
---

# Semi-supervised Deep Learning strategy for image classication
Semi-supervised learning approaches provide ways to leverage on unlabeled samples to improve task performance for labeled examples. Here, we implemented two Deep Learning strategies to solve a 1k-label image classification task. Our first approach consists of a convolutional neural network with ResNet stacked on top of the encoding module of a convolutional auto-encoder (CAE). Our second model is a modification of the [Mean Teacher algorithm](https://papers.nips.cc/paper/6719-mean-teachers-are-better-role-models-weight-averaged-consistency-targets-improve-semi-supervised-deep-learning-results.pdf). Including unlabeled data using these strategies provided superior classication generalization. Our results were awarded the 3rd place winner Semi-supervised learning competition (2019). 

In collaboration with [Maple Li](https://github.com/Millebean) and ChiaoHsun Wang. [Python/PyTorch code](https://github.com/pedroherrerovidal/Semi-supervised_Learning_DL)

[![](../assets/images/SSL_DL.jpg)](https://github.com/pedroherrerovidal/Semi-supervised_Learning_DL)

# Models in Computational Neuroscience
This project compiles  a collection of methods in computational neuroscience to describe properies of neurons and neural networks with empashis in dynamics and Recurrent Neural Networks (RNNs). Each models is implemented from scratch and disected in a series of self-explanatory [Jupyter Notebooks](https://github.com/pedroherrerovidal/ComputationalNeuroscience). 

[![](../assets/images/compNS.jpg)](https://github.com/pedroherrerovidal/ComputationalNeuroscience)

# Sequencing data processing, analysis and visualization for biomedical research
This project developed a preprocessing and analysis pipeline to extract biomedically relevant information from transcriptomics data. Here, we started from raw nucleotide sequences, preprocess and curate them to extract tables of counts linking gene expression and physiological condition. Then we extracted significantily modulated genes for across conditions, correcting for multiple data comparisons, did unsupervised exploration of data structure using multidimensional scaling (MDS) and draw predictions between treatment conditions using generalized linear models (GLMs).

In collaboration with [Gunjan Gala](https://github.com/gunjangala). [R and Shell code](https://github.com/pedroherrerovidal/GeneTranscriptomicDataAnalysis)

[![](../assets/images/geneTools.jpg)](https://github.com/pedroherrerovidal/GeneTranscriptomicDataAnalysis)
