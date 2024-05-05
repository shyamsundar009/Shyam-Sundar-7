---
title: "Federated Learning on Multiclass Classification June 2022"
excerpt: "Implemented a federated learning algorithm as a security and privacy-preserving approach to training machine learning models.<br/><img src='/images/500x300.png'>"
collection: portfolio
---

Implemented a **federated learning** algorithm as a **security** and **privacy-preserving** approach to training machine learning models.
</br>

**Technical stack Used in the Project** - <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width ="16" height="100%"/> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/pytorch/pytorch-original.svg" width ="16" height="100%"/> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/jupyter/jupyter-original-wordmark.svg" width ="16" height="100%"/>

- The **CIFAR** dataset served as the training data, involving **20** client nodes, each engaging in training activities based on the **VGG-19** model.
- The central global model collected weight updates from **six** randomly selected client models, averaging the contributions, and disseminating the updated global model to all participating clients.
- Upon the successful completion of the training process, achieved a commendable accuracy rate of **78%**, showcasing the effectiveness of this federated learning approach in preserving data security and privacy while maintaining model performance.


The **Github code** is [here](https://github.com/Shyam-Sundar-7/federated_learning)