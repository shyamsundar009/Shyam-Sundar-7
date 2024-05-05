---
title: "Document Extraction Named Entity Recognition March 2024:"
excerpt: "Developed an AI model for extracting metadata from various document formats, including images (PNG, JPG) and documents (DOC), with a focus on Table of Contents extraction.<br/><img src='/images/500x300.png'>"
collection: portfolio
---

Demo Video:
<div style="position: relative; width: 100%; padding-bottom: 56.25%; height: 0;">
  <video style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;" poster="/images/dubai2.jpg" controls>
    <source src="https://github.com/Shyam-Sundar-7/Document_ext/assets/101181076/b7c3dc7f-da64-4e54-a158-2bbdddca0a3d" type="video/mp4">
  </video>
</div>

Skills - <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width ="16" height="100%"/>  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/jupyter/jupyter-original-wordmark.svg" width ="16" height="100%"/> <img src='/images/streamlit.png' width="16" height="100%"> <img src="/images/openai-svgrepo-com.svg" width="16" height="100%">          <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/fastapi/fastapi-original.svg" width="16" height="100%">
          


- Implemented a **Jupyter Notebook** (extraction_(doc,png,jpg)_to_text.ipynb) detailing the extraction process using pytesseract for image files and the open-docx library for document files.Created training and testing CSV files with attributes such as file name and extracted text to facilitate model training.
- Utilized the **zero-shot prompting** method outlined in the notebook using_openai.ipynb to extract required labels from files or images, assessing its effectiveness and limitations.
- Employed **OpenAI chat completion** with a prompting approach in one_shot_prompting.ipynb, comparing results with the zero-shot prompting method.
- Streamlined the process by integrating it into a **Streamlit** application, leveraging helper functions from helper_function.py, and incorporating **fastapi** for API calls, ensuring reliability and efficiency in document extraction.



The Github code is [here](https://github.com/Shyam-Sundar-7/Document_ext)
