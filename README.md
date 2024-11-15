# fraudy-or-not
This is a project for Essentials of Text and Speech Processing, FS24, University of Zurich.


# Essentials of Text and Speech Processing, 2024 Fall
A Comparison of Statistical Models and Deep
Learning Approaches in Predicting Fraudulent
Job Postings from Real-Life Data
## Overview
This repository contains the implementation and analysis of various models to detect fraudulent job postings. The project leverages both statistical models and deep learning approaches, including Logistic Regression, SVM, Multinomial Naive Bayes, LSTM, BERT and RoBERTa to classify job postings as either genuine or fraudulent.

## Dataset
The dataset used in this project is available on Kaggle:

- [Employment Scam Aegean Dataset (EMSCAD)](https://www.kaggle.com/datasets/shivamb/real-or-fake-fake-jobposting-prediction/data)

It consists of 17,880 job postings (17,014 legitimate and 866 fraudulent) with features like job title, company profile, job description, and more.

## Key Features
- **Data Exploration**: Combines text and metadata for enhanced fraud detection.
- **Deep Learning Models**: Incorporates state-of-the-art transformer models like BERT and RoBERTa.
- **Performance Metrics**: Evaluates models using metrics like accuracy, precision, recall, and F1-score.


## How to Use

### Clone the repository:
```bash
git clone https://github.com/your-username/fraudulent-job-detection.git
cd fraudulent-job-detection


## Project Structure
```bash
.
├── preprocessing/
│   ├── preprocessing.ipynb  # Preprocessing for models
│   
├── models/
│   ├── logistic_regression.ipynb  # Implementation of Logistic Regression
│   ├── svm.ipynb  # Implementation of Support Vector Machines
│   ├── multinomial_nb.ipynb  # Multinomial Naive Bayes
│   ├── lstm.ipynb  # LSTM implementation
│   ├── bert.ipynb  # BERT implementation
│   ├── roberta.ipynb  # RoBERTa implementation
├── 
