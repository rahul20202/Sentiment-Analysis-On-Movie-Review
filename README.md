Sentiment Analysis on Movie Reviews 🎬
This project is an end-to-end Python application that performs sentiment analysis on movie reviews. It uses a classic machine learning model trained on the popular IMDB dataset to classify text as either positive or negative.

The core of the application is a Logistic Regression model, which provides a robust and interpretable solution for text classification. The project is designed as an interactive command-line tool, allowing users to get instant sentiment predictions for their own reviews.

✨ Key Features
Sentiment Classification: A machine learning model trained on over 10,000 movie reviews to predict sentiment with high accuracy.

Interactive Console UI: A user-friendly command-line interface to analyze any movie review you provide in real-time.

Text Preprocessing Pipeline: Includes functions for cleaning raw text data by removing noise like HTML tags and punctuation.

TF-IDF Feature Extraction: Implements the TF-IDF (Term Frequency-Inverse Document Frequency) technique to convert text into meaningful numerical features for the model.

🛠️ Tech Stack
Language: Python

Data Manipulation: Pandas, NumPy

Machine Learning: Scikit-learn (TfidfVectorizer, LogisticRegression)

🚀 Getting Started
Follow these instructions to get a copy of the project up and running on your local machine.

Prerequisites
Python 3.7+

The IMDB Dataset.csv file, which can be downloaded from Kaggle. Place this file in the root directory of the project.

Installation
Clone the repository:

git clone [[your-repository-url](https://github.com/rahul20202/Sentiment-Analysis-On-Movie-Review)]
cd [Sentiment-Analysis-On-Movie-Review]

Install the required Python libraries:

pip install pandas scikit-learn

Usage
Run the script from your terminal:

python your_script_name.py

Follow the on-screen instructions to enter a movie name and your review. The program will output the predicted sentiment and its confidence score.
