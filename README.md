# Text-Classification-using-NN

## 1.Introduction
- Text Classification is one of the fundamental problems in natural language processing. The task involves assigning a label to a unit of text (such as a document, a paragraph, a sentence, or a word) based on a set of predefined labels.
- Token-level Classification: Part-of-speech Tagging, Named Entity Reconigtion
- Document-level Classification include Sentimental Analysis
- **Classification based on label:**
- Binary classfication
- Multiclass classification
- Multilabel classification
- **Application:**
- The text classification problem has many important applications. It is used in sentiment analysis of customer reviews on products, classifying fake information, and more.

## 2. Practical Application:
- Training Text-Classification model using Neuron-Net:
- Install dataset NTC-CSV
- Preprocessing
- Vectorization
- Build up a classification model
- Training model
- Predict and validate

## NTC-SCV Project

This repository contains the dataset and code for the NTC-SCV project (Vietnamese Sentiment Analysis). Below are the instructions on how to clone and set up the project.

## Getting Started

### 1. Clone the repository:

```bash
git clone https://github.com/congnghia0609/ntc-scv.git
unzip ./ntc-scv/data/data_test.zip -d ./data # Unzip the data_test.zip file into the ./data directory
unzip ./ntc-scv/data/data_train.zip -d ./data # Unzip the data_train.zip file into the ./data directory
rm -rf ./ntc-scv # Remove the ntc-scv directory and its contents
cd ntc-scv
```

### 2. Preprocessing:

