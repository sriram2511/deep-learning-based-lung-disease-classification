# Chest X-Ray Disease Classification
Abstract

Chest X-ray images (CXR) play a crucial role in the early detection of lung diseases. This repository contains the implementation of deep learning models for disease classification based on the National Institutes of Health (NIH) chest X-ray dataset. The models, developed using a convolutional neural network (CNN), are trained on a comprehensive dataset comprising 112,120 X-ray images with corresponding disease labels from 30,805 individual patients.
Table of Contents

    Introduction
    Dataset
    Methodology
    Results
    Conclusion

1. Introduction

Chest X-rays provide valuable insights into various lung and heart conditions. The NIH Chest X-ray dataset, consisting of over 100,000 annotated images, serves as a rich resource for studying thoracic pathologies. This project aims to explore and analyze these pathologies using advanced machine learning and deep learning techniques to develop models for accurate classification.
![image](https://github.com/sriram2511/deep-learning-based-lung-disease-classification/assets/125891471/b4caa485-a5e5-4d51-82ca-2962cb19fa01)


2. Dataset

The NIH Chest X-ray dataset includes a diverse array of thoracic abnormalities such as atelectasis, cardiomegaly, effusion, infiltration, mass, nodule, pneumonia, pneumothorax, consolidation, edema, emphysema, fibrosis, pleural thickening, and hernia. The dataset facilitates a comprehensive analysis of the distribution, prevalence, and characteristics of these thoracic pathologies.

3. Methodology

Our approach involves obtaining the NIH chest X-ray dataset, preprocessing the images, and developing deep learning models using convolutional neural networks (CNN). The models are trained on the entire dataset, allowing them to effectively capture significant features and enable accurate identification of different disease categories. The model's performance is evaluated using ROC curve analysis, providing a comprehensive assessment of its classification capabilities.

4. Results

We implemented three deep learning architectures (DenseNet121, EfficientNet B1, and CustomNet) and evaluated their performance on various disease labels. The results demonstrate competitive performance for DenseNet121 and EfficientNet B1, with slight variations in performance for specific diseases. CustomNet, incorporating domain-specific modifications, generally exhibited slightly lower accuracy.
Disease Label	DenseNet 121	EfficientNet B1	CustomNet
![image](https://github.com/sriram2511/deep-learning-based-lung-disease-classification/assets/125891471/b3d2f634-4154-44fa-8e3d-c1ad49e86784)

5. Conclusion

In conclusion, DenseNet121 and EfficientNet B1 demonstrate competitive performance in medical image classification tasks. These models serve as valuable tools for automated disease diagnosis, assisting medical professionals in making informed decisions. The findings of this project contribute to the growing field of medical imaging analysis, emphasizing the potential for advanced machine learning techniques to improve diagnostic accuracy.
