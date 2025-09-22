# Hate Speech Detection using Machine Learning

## Overview

This project implements a machine learning-based text classifier to detect hate speech in tweets. Utilizing Natural Language Processing (NLP) techniques and models like Decision Tree Classifier, it classifies tweets into three categories:

- **Hate Speech**
- **Offensive Language**
- **Neither**

## Features

- **Data Preprocessing**: Cleans and prepares tweet data by removing links, punctuation, numbers, stopwords, and applying stemming.
- **Text Vectorization**: Converts text into numerical vectors using CountVectorizer.
- **Model Training**: Trains a Decision Tree Classifier on the processed data.
- **User Interface**: Provides a Streamlit app for easy user interaction.

## Project Structure

├── HSD.py # Main script for model training and prediction
├── HSD_dataset.csv # Dataset containing tweet data
├── requirements.txt # Python dependencies
└── README.md # Project documentation

## Requirements

- Python 3.x
- NLTK
- scikit-learn
- pandas
- streamlit

Install the necessary dependencies:

pip install -r requirements.txt

## How to Run

1. Clone the repository:

git clone https://github.com/Shreyash9Sangle/hate-speech-detection.git
cd hate-speech-detection

2. Run the Streamlit app:

streamlit run HSD.py

3.Open the provided local URL in your browser to interact with the application.

## Author
Shreyash Sangle
