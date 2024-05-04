---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* M.Tech. in Modelling and Simulation, DIAT, 2023
* B.Tech. in Chemical Engineering, NIT - Trichy, 2021

Work experience
======
* USEReady 2024: Machine Learning Intern
  * Github University
  * Duties includes: Updates and improvements to template
  * Supervisor: The Users


Skills
======

* Languages
  * Python
  * SQL (Postgres)
  * Matlab
  * Latex
* Frameworks: 
  * Pytorch
  * Tensorflow
  * Flask
  * Pytorch Lightning
* Tools/Platform:
  * Tableau
  * Power Bi
  * Microsoft Azure
  * Git
  * Jupyter Notebook
  * Docker

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  

Portfolio
======
  <ul>{% for post in site.portfolio reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

### LLM-Powered Coupon Recommender | <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width ="16" height="100%"/> | <img src="assets\img\streamlit.png" width="16" height="100%"> | <img src="assets\img\langchain.png" width="16" height="100%"> | <img src="assets\img\openai-svgrepo-com.svg" width="16" height="100%"> | November 2023

Developed an innovative Q&A system for e-commerce platforms, specializing in personalized coupon and offer recommendations using **OpenAI's large language models (LLMs)**. [**[Code]**](https://github.com/Shyam-Sundar-7/coupon_Q-A)

- Implemented a **Streamlit**-based user interface designed for seamless interaction, enabling users to query and receive relevant offers instantly. This approach significantly enhanced user experience and engagement on e-commerce sites.
- Utilized a custom-built dataset, structured in a CSV file, to simulate real-world e-commerce scenarios. This dataset was integral in giving knoweldge based responce by incorporating **Langchain**.
- Integrated **FAISS (Facebook AI Similarity Search)** to optimize the recommendation process. By using vector database technology, the system could swiftly match user queries with the most relevant offers, thereby reducing screen time and streamlining decision-making.
 
### PeopleCare Insurance Prediction | <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width ="16" height="100%"/> |  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/jupyter/jupyter-original-wordmark.svg" width ="16" height="100%" /> | <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/azure/azure-original.svg" width ="16" height="100%" /> |  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/flask/flask-original-wordmark.svg" width ="16" height="100%" /> |  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-plain-wordmark.svg" width ="16" height="100%" /> | October 2023

Analyzed **PeopleCare's** expansion into vehicle insurance through the implementation of a predictive model for more **effective customer targeting**. [**[Code]**](https://github.com/Shyam-Sundar-7/PeopleCare)

  - Thoroughly examined customer behavior and other relevant features through a process of data visualization and data cleaning. This ensured the availability of accurate and high-quality data for the modeling task.  
  - Achieved an impressive prediction accuracy of **80%** by harnessing the robust capabilities of the **LightGBM** algorithm, optimizing its performance through hyperparameter tuning.
  - Streamlined the entire model deployment process using **Flask** and **Docker**, facilitating model delivery on the **Azure Container App** platform, optimizing operations and enhancing scalability.

### Hate Speech Prediction |  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width ="16" height="100%"/> | <img src="https://avatars.githubusercontent.com/u/58386951?s=200&v=4" width ="16" height="100%"> |  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/pytorch/pytorch-original.svg" width ="16" height="100%" /> |  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/flask/flask-original-wordmark.svg" width ="16" height="100%" /> |  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-plain-wordmark.svg" width ="16" height="100%" /> | October 2023

Developed a robust hate speech detection algorithm aimed at classifying speech as normal or blocked to facilitate content filtration. [**[Code]**](https://github.com/Shyam-Sundar-7/Hate-Speech-recognition)

  - Utilized the **OxAISH-AL-LLM/wiki_toxic** dataset from Hugging Face for model training, taking advantage of a pre-existing **BERT** model. Fine-tuned the last layer and added an additional output layer with two neurons for classification.
  - Delivered outstanding results with an exceptional accuracy of **91.95%**, a testament to the rigorous training and evaluation processes involved.
  - Implemented model deployment through **Flask** and **Docker**, ensuring scalability and ease of integration for content filtration solutions.

### Machine Failure Prediction  |  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/azure/azure-original.svg" width ="16" height="100%" />  | September 2023
Conducted an extensive investigation of a **Milling machine** to proactively identify and prevent machine failures, focusing on enhancing operational reliability. [**[Code]**](https://github.com/Shyam-Sundar-7/Machine-Failure-Prediction)

 - Analyzed the dataset comprising **10,000** data points, featuring **14** distinct machine-specific features, to identify potential failures and optimize machine performance.
 - Leveraged a diverse set of machine learning algorithms, culminating in an impressive **97\%** recall rate for predicting machine failures. This achievement was made possible through the strategic application of **logistic regression** and addressing class imbalance with the **SMOTE** approach.
 - Skillfully managed in **Azure Designer**, within Azure Machine Learning Workspaces, showcasing the capacity to construct machine learning pipelines for in-depth data analysis and predictive modeling.


### Pet Mind EDA | <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width ="16" height="100%"/> | <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/jupyter/jupyter-original-wordmark.svg" width ="16" height="100%" /> |February 2023
Conducted a comprehensive analysis of **Pet Mind** data, a **US-based retailer** of pet products, with the goal of boosting sales through increased repeat purchases of everyday pet products. [**[Code]**](https://github.com/Shyam-Sundar-7/Pet-supplies-eda)

- Utilized various data cleaning and processing techniques, including boxplots, to identify and remove outliers, ensuring the quality and reliability of the dataset.
- Discovered that products with average ratings and belonging to animal categories other than birds exhibited higher repeat purchase patterns among customers. 
- Arrived at a strategic approach to increase sales by reducing the pricing structure for medium-sized products to below **$30**, effectively targeting **potential repeat buyers**.



### Data Driven Model for Anomaly Detection and Path Prediction |  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width ="16" height="100%"/> |  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/tensorflow/tensorflow-original.svg" width ="16" height="100%" /> | <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/jupyter/jupyter-original-wordmark.svg" width ="16" height="100%"/> | July 2022 - April 2023
Investigated and enhanced the Automatic Identification System of cargo vessels for anomaly detection and path prediction.

  - Explored a dataset related to **AIS marine** activity, with data recorded between **January 1, 2022, and January 15, 2022**, featuring a total of **17** unique attributes.
  - Formulated a **statistical method** to analyze cargo ship vessels by considering time difference and speed over the ground for robust anomaly detection.
  - Engineered a path prediction algorithm using a **sequence-to-sequence model with an attention mechanism**, delivering a substantial **90%** reduction in error compared to Deep LSTM and GRU models.
  

### Federated Learning on Multicalss Classification |  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width ="16" height="100%"/> |  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/pytorch/pytorch-original.svg" width ="16" height="100%" /> |  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/jupyter/jupyter-original-wordmark.svg" width ="16" height="100%"/> | June 2022
Implemented a federated learning algorithm as a security and privacy-preserving approach to training machine learning models.
[**[Code]**](https://github.com/Shyam-Sundar-7/federated_learning)


<!-- <p align="center">
  <img src="assets\img\fed.jpeg" alt="Federated Learning on CIFAR-10 Dataset" width="200" height="200" />
</p> -->


- The **CIFAR** dataset served as the training data, involving **20** client nodes ,each engaging in training activities based on the **VGG-19** model.
- The central global model collected weight updates from **six** randomly selected client models, averaging the contributions, and disseminating the updated global model to all participating clients.
- Upon the successful completion of the training process, achieved a commendable accuracy rate of **78%**, showcasing the effectiveness of this federated learning approach in preserving data security and privacy while maintaining model performance.


## Data Visualization
1. Tableau Dashboard for Zomboville attrition report - [**[Link]**](https://github.com/Shyam-Sundar-7/hr_tableau_dashboard)

2. Tableau Credit Card Analysis Visualization project -[**[Link]**](https://github.com/Shyam-Sundar-7/credit-card-analysis---tableau) 

<!-- Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams -->
