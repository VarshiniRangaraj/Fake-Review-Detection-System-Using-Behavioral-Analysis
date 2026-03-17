Fake Review Detection using Machine Learning

This project helps identify fake product reviews by using machine learning and analyzing user behavior.
It uses both text features and specially created features to make the classification more accurate.

Features:
- Cleaning and preparing text data
- Using TF-IDF with word and character n-grams
- Creating behavioral features like:
- Length of the review and number of words
- Use of exclamation marks
- Ratio of uppercase letters
- Detecting repeated phrases
- Mismatch between sentiment and the rating given
- Using Logistic Regression with balanced classes
- A custom system to predict if a new review is fake or real

Tech Stack:
- Python
- Pandas
- Scikit-learn
- SciPy

Model Performance:
- Accuracy is about 90%
- Evaluated using:
- Precision
- Recall
- F1-score
- Confusion Matrix

How to run:
pip install pandas scikit-learn scipy
python Main.py
