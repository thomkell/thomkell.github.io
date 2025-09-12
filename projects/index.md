---
layout: default
title: "Projects"
---

# Projects
A selection of projects spanning digital pathology, applied AI, and computational science.

## Digital Pathology with Foundation Models *(Ellison Medical Institute – publication forthcoming)*
As part of my work at Ellison Medical Institute in Los Angeles, I engineered AI pipelines for computational pathology using **histopathology slides** as the core data source. Leveraging foundation models such as **Gigapath** and **Canvoi**, I extracted high-dimensional embeddings from whole slide images to enable downstream machine learning tasks, including:
- Classifying **high vs. low BMI groups** from histopathology data.  
- Predicting **HER2-positive vs. HER2-negative** breast cancer using embeddings from multiple magnifications (**5x, 10x, 20x**).  

This work integrates cloud-based infrastructure and automated workflows for scalability and reliability, and will be featured in an upcoming scientific publication.

<!-- ## [Adlatus Chatbot](https://github.com/thomkell/adlatus-chatbot)
A Retrieval-Augmented Generation (RAG) chatbot developed for **Adlatus Zürich**, designed to make organizational knowledge easily accessible.  
The chatbot combines:
- **FastAPI backend** for lightweight deployment  
- **FAISS vector search** for efficient document retrieval  
- **OpenAI’s Responses API** for natural language interaction  

It can answer questions based on website content, internal documents, and structured contact data, and is built to run both locally and in the cloud (e.g., Render). This project highlights how AI can be integrated into companies’ daily operations to improve knowledge access and support decision-making.
-->

## [Deep Neural Network in C with 2 layers](https://github.com/thomkell/DeepNeuralNetwork)
A deep neural network implementation in C, designed with a focus on parallelizing the training process. This project demonstrates the use of parallel computing techniques to enhance the efficiency and speed of neural network training using OpenMP and CUDA.

## [COPD Severity Staging using U-net](https://github.com/thomkell/COPD-Severity-Staging)
This project utilizes the U-Net architecture to stage the severity of Chronic Obstructive Pulmonary Disease (COPD) based on medical imaging data. The U-Net model is used for precise image segmentation, aiding in the automated classification of COPD severity, which can be crucial for clinical decision-making.

## [Perona Malik with Mimetic Method](https://github.com/thomkell/PeronaMalikwithMimeticMethod)
An implementation of the Perona-Malik anisotropic diffusion model using the Mimetic Method. This project primarily focuses on denoising in image processing, enhancing image quality while maintaining important structural features.