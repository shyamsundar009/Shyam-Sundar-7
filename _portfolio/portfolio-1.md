---
title: "Handwritten Signature Authenticity Verification System April 2024:"
excerpt: "Developed a cutting-edge system for authenticating handwritten signatures, aimed at revolutionizing signature verification processes and bolstering security measures.<br/><img src='/images/handwritten.jpeg' style='max-width:100%;height:auto;display:block;margin:auto;' alt='handwitten'>"
collection: portfolio
---

Developed a cutting-edge system for authenticating handwritten signatures, aimed at revolutionizing signature verification processes and bolstering security measures.

**Demo Video :**
<div style="position: relative; width: 100%; padding-bottom: 56.25%; height: 0;">
  <video style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;" poster="/images/handwritten.jpeg" controls>
    <source src="https://github.com/Shyam-Sundar-7/signature-verification-similarity/assets/101181076/7119939f-3512-4d8b-a9fb-d91f11b80a3f" type="video/mp4">
  </video>
</div>
<br/>

**Technical stack Used in the Project** - <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width ="22" height="100%"/> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/pytorch/pytorch-original.svg" width ="22" height="100%"/> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/jupyter/jupyter-original-wordmark.svg" width ="22" height="100%"/> <img src="https://avatars.githubusercontent.com/u/58386951?s=200&v=4" width ="22" height="100%"> <img src='/images/streamlit.png' width="22" height="100%">



- Utilized the renowned **CEDAR dataset**, encompassing signatures from **55** individuals written in Latin script, comprising **24** genuine and **24** forged signatures per person, totaling **2,640** signature samples.
- Engineered two distinct PyTorch models:
  - **SiasemeNetwork1**: Employed Binary Cross Entropy as the loss function, achieving exceptional accuracy rates:
    - Train Acc: 98.59%
    - Val Acc: 98.08%
    - Test Acc: 98.11%
  - **SiameseNetwork2**: Leveraged Contrastive Loss for enhanced model optimization, with satisfactory accuracy metrics:
    - Train Acc: 65.07%
    - Val Acc: 64.88%
    - Test Acc: 65.00%
- Seamlessly integrated the models into a **Streamlit** application, providing an intuitive interface for signature authenticity verification, thus ensuring user-friendly interaction and streamlined deployment.


The **Github code** is [here](https://github.com/Shyam-Sundar-7/signature-verification-similarity)
