# Variable-Selection Network in PyTorch

## Introduction
Welcome to this repository, where you'll find a PyTorch implementation of Variable-Selection Network (VSN). VSN is a dynamic neural network architecture designed to learn and select relevant input variables, enhancing both model interpretability and performance. I chose PyTorch for VSN implementation due to the absence of an existing version online. The closest reference is a Keras example titled ["Classification with Gated Residual and Variable Selection Networks"](https://keras.io/examples/structured_data/classification_with_grn_and_vsn/).

## Inspiration
The VSN architecture is inspired by the paper ["Gated Residual and Variable Selection Networks for Tabular Data"](https://arxiv.org/pdf/1912.09363) and the winning solution of the Kaggle competition ["ICR - Identifying Age-Related Conditions"](https://www.kaggle.com/competitions/icr-identify-age-related-conditions), which utilized VSNs effectively.

## Dataset
Experiments utilized the dataset from the Kaggle competition "Prediction of spam with Bayesian model." Access the dataset [here](https://www.kaggle.com/competitions/lets-surpass-the-hosts-bayesian-model/data). The VSN implementation performed well in this competition.

