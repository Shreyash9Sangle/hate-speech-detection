HATE SPEECH DETECTION 🚨

This project is a Hate Speech Detection system built using Python, NLTK, and Scikit-learn. It classifies tweets into three categories:

Hate Speech

Offensive Language

No Hate and Offensive

A Decision Tree Classifier is used as the machine learning model, and a Streamlit app is provided for easy user interaction.

📌 FEATURES

Preprocesses tweets (removes links, punctuation, numbers, stopwords, and applies stemming).

Converts text into numerical vectors using CountVectorizer.

Classifies tweets into 3 categories.

Interactive Streamlit web app with real-time predictions.

Displays model accuracy on test data.

🛠️ TECH STACK

Python

Pandas, NumPy – Data handling

NLTK – Text preprocessing (stemming, stopwords removal)

Scikit-learn – ML model (Decision Tree Classifier, train-test split)

Streamlit – Web interface


PROJECT STRUCTURE
├── HSD.py              # Main project file with model & Streamlit app
├── HSD_dataset.csv     # Dataset used for training & testing
└── README.md           # Project documentation
