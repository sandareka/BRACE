# Explanation-based Data Augmentation for Image Classification

Official implementation of BRACE (BetteR Accuracy from Concept-based Explanation) proposed in Explanation-based Data Augmentation for Image Classification paper. This paper is accepted to NeurIPS 2021. 

## Abstract

Existing works have generated explanations for deep neural network decisions to provide insights into  model behavior. We observe that these explanations can also be used  to identify concepts that caused misclassifications. This allows us to  understand  the possible limitations of the dataset used to train the model, in particular, the under-represented regions in the dataset. This work proposes a framework that utilizes concept-based explanations to automatically augment the dataset with  new images that can cover these under-represented regions  to improve the model performance. The framework is able to use the explanations generated by both interpretable classifiers and post-hoc explanations from black-box classifiers. Experiment results demonstrate that the proposed approach improves the accuracy of classifiers compared to state-of-the-art augmentation strategies.

Presentation vide can be found [here](https://recorder-v3.slideslive.com/#/share?share=52116&s=f0a2aefc-b9e7-4a1b-94f7-89d01c0021b6)
