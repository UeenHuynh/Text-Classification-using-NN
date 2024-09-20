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

# Text Classification using Neural Networks

## Project Overview
This repository implements a **text classification** model using a **neural network** in PyTorch. It performs binary sentiment classification on Vietnamese text data.

## Project Structure
```bash
/Text-Classification-using-Neural-Network/
│
├── data/                           # Directory containing training, validation, and test data
│   ├── data_train/                 # Training data
│   ├── data_test/                  # Testing data
├── models/                         # Directory for saving trained models
├── notebooks/                      # Jupyter notebooks for exploration and visualization
├── src/                            # Python scripts for data processing, model training, etc.
│   ├── preprocess.py               # Preprocessing text data
│   ├── model.py                    # Neural network model definition
│   ├── train.py                    # Training loop
│   ├── evaluate.py                 # Model evaluation
│   └── predict.py                  # Prediction script
├── README.md                       # Project overview
└── requirements.txt                # Required dependencies
```

## Installation
```bash
# Clone the repository
git clone https://github.com/congnghia0609/ntc-scv.git
# Change to the project directory
cd Text-Classification-using-Neural-Network
# Install required dependencies
pip install -r requirements.txt
```

## Dataset
```bash
#Download and unzip the NTC-SCV dataset
git clone https://github.com/congnghia0609/ntc-scv.git
unzip ./ntc-scv/data/data_train.zip -d ./data
unzip ./ntc-scv/data/data_test.zip -d ./data
```
## Preprocessing
## Model Definition
## Training the Model
## Evaluation
## Prediction
```bash
def predict(text):
    with torch.no_grad():
        encoded_text = torch.tensor(vocabulary(tokenizer(text)))
        output = model(encoded_text, torch.tensor([0]))
        return output.argmax(1).item()
# Example usage
print(predict("Sản phẩm này rất tuyệt vời!"))

```


