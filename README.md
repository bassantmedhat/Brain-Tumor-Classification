# Brain-Tumor-Classification 

### Team

Second Semester - Biomedical Machine Learning project created by:

| Team Members' Names                                  | Section | B.N. |
| ---------------------------------------------------- | :-----: | :--: |
| [Bassent Medhat](https://github.com/bassantmedhat)   |    1    |  21  |
| [Mariam Ahmed](https://github.com/MariamTurky)       |    2    |  30  |
| [Hager Sherif](https://github.com/HagerSherif)       |    2    |  50  |
| [Yousef Adham ](https://github.com/joeadham)         |    2    |  54  |

# Brain Tumor Classification with Machine Learning

This project aims to develop and evaluate machine learning models for classifying brain tumor types from MRI data. Accurate classification of brain tumors is essential for guiding treatment decisions and improving patient outcomes. In this repository, we provide code and documentation for the development and evaluation of these machine learning models.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Preprocessing](#preprocessing)
- [Models](#models)
- [Results](#results)
- [Related Work](#related-work)
- [Usage](#usage)

## Introduction

Brain tumors are a severe medical condition that can lead to impaired brain function and even death if left untreated. Early detection and accurate classification of brain tumor types are crucial for providing timely and appropriate treatment. This project focuses on using machine learning techniques to assist radiologists in classifying brain tumors based on MRI scans.

## Dataset

The dataset used in this project is publicly provided by [Kaggle user "MASOUD NICKPARVAR"](https://www.kaggle.com/your-kaggle-username/brain-tumor-detection). It contains 7,023 MRI images with a resolution of 512x512 pixels, divided into four classes: glioma, meningioma, no tumor, and pituitary. We split the data into training and validation sets, as well as a testing set.

## Preprocessing

Before training the machine learning models, we apply several preprocessing steps to the MRI images:
- Intensity normalization
- Smoothing to reduce noise
- Resizing for consistency

We also perform dimensionality reduction using Principal Component Analysis (PCA) to extract relevant features.

## Models

We experiment with various machine learning models, including:
- Support Vector Machine (SVM)
- Random Forest
- K-Nearest Neighbors (KNN)
- Stochastic Gradient Descent (SGD)
- Ensemble learning

These models are trained and evaluated for their performance in classifying the MRI scans into the four brain tumor classes.

## Results

After fine-tuning the hyperparameters of each model and conducting extensive evaluation, we have achieved the following results:

- SVM: 91% accuracy
- Random Forest: 89% accuracy
- KNN: 93% accuracy
- SGD: 56% accuracy
- Ensemble: 89% accuracy

The KNN model achieved the highest accuracy, classifying malignant and benign neoplasms with 93% accuracy.

## Related Work

We have reviewed related work in the field of brain tumor classification, including other studies that used feature extraction, deep learning methods, and machine learning techniques. We also discuss the strengths and weaknesses of different approaches.

## Usage

To use and replicate our results, follow these steps:

1. Clone this repository to your local machine.
2. Preprocess your MRI images, normalize them, and apply the necessary smoothing.
3. Train and evaluate the machine learning models with your data.
4. Fine-tune the hyperparameters to optimize model performance.
5. Compare the results of different models to find the most accurate one.

