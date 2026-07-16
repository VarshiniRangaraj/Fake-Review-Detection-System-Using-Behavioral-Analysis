# Fake Review Detection using Machine Learning

## Overview

Fake Review Detection using Machine Learning is a Python-based application that identifies deceptive product reviews by combining Natural Language Processing (NLP) techniques with behavioral feature engineering. The model analyzes both textual content and reviewer behavior to classify reviews as genuine or fake.

## Features

- Perform fake review detection using Machine Learning
- Apply TF-IDF vectorization with word and character n-grams
- Extract behavioral features such as review length, word count, uppercase ratio, and exclamation count
- Detect sentiment-rating mismatches and repeated review patterns
- Train a Logistic Regression classifier with balanced class weights
- Predict whether a review is genuine or fake using custom review inputs

## Tech Stack

- **Language:** Python
- **Libraries:** Pandas, NumPy, Scikit-learn, SciPy
- **Machine Learning:** TF-IDF Vectorization, Logistic Regression
- **Concepts:** Natural Language Processing (NLP), Feature Engineering

## Model Performance

- **Accuracy:** ~90%
- **Evaluation Metrics:**
  - Precision
  - Recall
  - F1-Score
  - Confusion Matrix

## How to Run

1. Install the required libraries:

```bash
pip install pandas numpy scikit-learn scipy
```

2. Run the program:

```bash
python Main.py
```

## Dataset

The model is trained on a labeled fake review dataset containing genuine and deceptive product reviews. The dataset is preprocessed before feature extraction and model training.

## Project Workflow

1. Load and preprocess the review dataset
2. Clean and normalize review text
3. Extract textual and behavioral features
4. Convert text into numerical vectors using TF-IDF
5. Train a Logistic Regression classifier
6. Evaluate the model using standard performance metrics
7. Predict whether new reviews are genuine or fake

## Future Enhancements

- Experiment with advanced machine learning and deep learning models
- Enhance feature engineering for improved detection accuracy
- Develop a web interface for real-time fake review prediction
- Integrate explainable AI techniques to interpret model predictions
- Support multilingual review analysis
