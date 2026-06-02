# Movie Genre Classification using Machine Learning

## Project Overview

This project aims to build a Machine Learning model capable of predicting movie genres using movie plot summaries and textual descriptions.

The system uses Natural Language Processing (NLP) techniques to preprocess movie descriptions and train multiple classification algorithms for genre prediction.

The project compares multiple machine learning algorithms and automatically selects the best performing model for deployment.

---

## Problem Statement

Movie streaming platforms and databases contain thousands of movies across multiple genres.

The objective of this project is:

* Predict movie genre from plot summary
* Compare multiple machine learning algorithms
* Evaluate model performance using classification metrics
* Build an interactive prediction system

---

## Dataset

Dataset Used:

Kaggle IMDb Genre Classification Dataset

Dataset Link:

https://www.kaggle.com/datasets/hijest/genre-classification-dataset-imdb

Dataset contains movie information including:

* Movie ID
* Movie Title
* Genre Label
* Plot Description

The dataset contains training and testing files in TXT format separated using `:::` delimiters.

Files Used:

* train_data.txt
* test_data.txt
* test_data_solution.txt
* description.txt

---

## Technologies Used

Programming Language:

* Python

Libraries:

* Pandas
* NumPy
* Scikit-Learn
* Matplotlib
* Seaborn
* NLTK
* Joblib

Environment:

* Google Colab

Version Control:

* GitHub

---

## Project Workflow

### 1. Data Loading

* Load TXT datasets
* Parse delimiter separated data
* Create structured dataframes

### 2. Data Preprocessing

* Lowercasing
* Removing special characters
* Stopword removal
* Lemmatization
* Missing value handling

### 3. Data Visualization

* Genre distribution visualization
* Text length distribution
* Dataset inspection

### 4. Feature Engineering

TF-IDF Vectorization:

* Unigrams + Bigrams
* Maximum feature extraction
* Sparse vector representation

### 5. Model Training

Algorithms Implemented:

* Naive Bayes
* Logistic Regression
* Support Vector Machine (SVM)

### 6. Model Evaluation

Evaluation Metrics:

* Accuracy
* Precision
* Recall
* F1 Score
* Classification Report
* Confusion Matrix

### 7. Model Comparison

* Compare all algorithms
* Select best performing model

### 8. Deployment Components

* Save trained model
* Save vectorizer
* Interactive prediction system

---

## Machine Learning Algorithms Used

### Naive Bayes

Advantages:

* Fast training
* Suitable for text classification
* Performs well with TF-IDF features

### Logistic Regression

Advantages:

* Strong baseline classifier
* Handles sparse vectors efficiently

### Support Vector Machine (SVM)

Advantages:

* Effective for high-dimensional text data
* Usually produces higher accuracy in NLP tasks

---

## Best Performing Model

After training and evaluating all implemented algorithms, the project automatically compares performance using evaluation metrics such as:

* Accuracy
* Precision
* Recall
* F1 Score

The algorithm producing the highest performance is automatically selected as the final deployed model.

Model Selection Workflow:

* Train Naive Bayes
* Train Logistic Regression
* Train Support Vector Machine
* Compare model performance
* Automatically select highest performing algorithm
* Save best model for deployment

Saved Components:

* best_model.pkl
* tfidf.pkl

These components are used by the prediction system during inference.

Although Support Vector Machine commonly performs strongly for text classification problems, the final selected model depends on experimental evaluation performed on the dataset.

---

## Project Structure

Movie-Genre-Classification/

│

├── MovieGenreClassification.ipynb

├── best_model.pkl

├── tfidf.pkl

├── README.md

├── train_data.txt

├── test_data.txt

├── test_data_solution.txt

└── description.txt

---

## How To Run

### Step 1

Clone repository

git clone REPOSITORY_LINK

### Step 2

Open notebook in Google Colab

### Step 3

Install dependencies

pip install pandas numpy scikit-learn nltk matplotlib seaborn joblib

### Step 4

Run notebook cells sequentially

### Step 5

Use prediction system

---

## Prediction System

User enters:

Movie Plot Summary

System returns:

* Predicted Genre
* Confidence Score
* Unknown Genre Detection

Example:

Input:

A former soldier returns home and fights criminals threatening his family.

Output:

Predicted Genre:

Action

Confidence:

0.91

---

## Future Improvements

* Deep Learning Models
* Word Embeddings
* Transformer Models
* Multi-label Classification
* Web Application Deployment

---

## Results

The project performs comparative analysis across multiple machine learning algorithms using several evaluation metrics.

Performance analysis includes:

* Accuracy Comparison
* Precision Analysis
* Recall Analysis
* F1 Score Analysis
* Classification Reports
* Confusion Matrices

The highest-performing model is automatically selected and deployed for prediction tasks.

---

## Author

Name:

Deependra Pandey

Project:

Movie Genre Classification using Machine Learning

Program:

Virtual Internship Project

Domain:

Machine Learning / Natural Language Processing

Tools & Environment:

Python, Google Colab, Scikit-Learn, GitHub

---

## License

This project is licensed under the MIT License and is intended primarily for academic, educational, and research purposes.

Dataset rights and ownership remain with their respective creators and sources.


