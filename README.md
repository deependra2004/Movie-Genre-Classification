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

The dataset contains training and testing files in TXT format separated using `:::` delimiters. The dataset is designed for NLP-based genre prediction tasks.

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

### Support Vector Machine

Advantages:

* Effective for high-dimensional text data
* Usually produces higher accuracy in NLP tasks

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

The project compares multiple machine learning algorithms and automatically selects the best performing model based on evaluation metrics.

---

## Author

Name:

Your Name

Project:

Virtual Internship Project

Domain:

Machine Learning / NLP

---

## License

Educational Purpose Only
