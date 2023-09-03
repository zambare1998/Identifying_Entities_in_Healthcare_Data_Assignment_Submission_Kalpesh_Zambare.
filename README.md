# Identifying_Entities_in_Healthcare_Data_Assignment_Submission_Kalpesh_Zambare.
Identifying Entities in Healthcare Data Assignment Submission 

# Identifying Entities in Healthcare Data Assignment

This repository contains code and data for the "Identifying Entities in Healthcare Data" assignment. The assignment focuses on developing a custom Named Entity Recognition (NER) system to identify diseases and their corresponding treatments in medical text.

## Problem Statement

Imagine a scenario where a health tech company aims to connect medical professionals with patients and generate a vast amount of healthcare-related data. The challenge is to automatically identify diseases and their treatments from this data, which is essential for various healthcare applications.

## Dataset

The dataset consists of medical text data, including sentences with labels for diseases (D), treatments (T), and other entities. It is divided into training and test datasets.

## Tasks

The assignment involves the following tasks:

1. **Data Preprocessing**: Process and format the data into sentences.
2. **Concept Identification**: Identify concepts (nouns and proper nouns) in the dataset.
3. **Feature Definition**: Define features for the Conditional Random Fields (CRF) model.
4. **Feature Extraction**: Extract features for each word in the dataset.
5. **Label Extraction**: Extract labels for each sentence.
6. **CRF Model Building**: Build a CRF model for named entity recognition.
7. **Model Evaluation**: Evaluate the CRF model's performance using the F1 score.
8. **Custom NER**: Identify diseases and their corresponding treatments using the model.

## Usage

- `train_sent`: Training sentence dataset
- `train_label`: Training label dataset
- `test_sent`: Test sentence dataset
- `test_label`: Test label dataset

## Requirements

- Python 3.x
- Required Python packages (install using `pip install <package-name>`):
  - `pycrf`
  - `sklearn-crfsuite`
  - `spacy`
  
## Run the Assignment

To run the assignment, follow these steps:

1. Clone this repository:

