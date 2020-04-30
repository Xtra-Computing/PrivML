# A Tutorial on Federated Learning Systems: Comparative Studies and Hand-on Demonstrations

This page introduces our tutorial on federated learning systems, which will appear in IJCAI-20. We will update this page with more detailed materials.

You can watch our video about the introduction to federated learning systems [here](https://github.com/Xtra-Computing/PrivML/tree/master/Tutorial/introduction.mp4).

## Table of Contents
* [Abstract](#Abstract)
* [Outline](#Outline)
* [References](#References)

## Abstract

Federated learning has become a hot research area in machine learning, which enables multiple parties collaboratively training a model without exchanging the local data. It is attractive to researchers working on many areas such as distributed learning, privacy, and fairness. Meanwhile, many companies have developed their federated learning systems such as [Webank FATE](https://github.com/FederatedAI/FATE) and [Google TensorFlow Federated](https://github.com/tensorflow/federated), which provide useful platforms for researchers.

In this tutorial, we will first introduce the concept of federated learning, including current widely used federated learning frameworks. Specifically, we will present comparative studies on existing system from the perspective of data partitioning, machine learning model, scale of federation, communication architectures, privacy mechanisms, and motivation of federations. Last, we will have a demo to show how to easily build federated learning models using existing system like PyTorch.


## Outline

* Introduction to Federated Learning (10 min)
    * Background
        * Data regulations such as General Data Protection Regulation (GDPR) and California Consumer Privacy Act (CCPA).
        * Data islands.
    * Motivation
        * From data transfer to model transfer.
    * Concept
        * Definition.
        * Comparison with distributed learning.
* Basic Federated Learning Frameworks/Techniques (20 min)
    * Federated averaging
    * Secure multi-party computation
    * Differential privacy
* Existing Federated Learning Systems (30 min)
    * Systems: Webank FATE, Google TensorFlow Federated (TFF), PySyft.
    * Characteristics: data partition, model implementation, privacy mechanism, and communication architecture.
* A Demo of Writing Federated Learning Program (40 min)
    * Introduction of our benchmark ORAF.
    * Implement federated averaging using PyTorch.
    * Demonstrate federated learning algorithms using FATE, TFF, and PySyft.
* Discussion (5 min)
    * Q&A.
    * Discuss existing challenges and future directions.
    
## References
[1] [A Survey on Federated Learning Systems: Vision, Hype and Reality for Data Privacy and Protection](https://qinbinli.com/files/FLSurvey.pdf) <br>
        Qinbin Li, Zeyi Wen, Zhaomin Wu, Sixu Hu, Naibo Wang, Bingsheng He<br>
    
