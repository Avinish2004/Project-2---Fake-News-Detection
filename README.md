# Project-2---Fake-News-Detection

In this project, we aim to detect fake news using Python, TfidfVectorizer, and PassiveAggressiveClassifier. The model is trained on a dataset of news articles, and it classifies each article as real or fake based on its content.

Dataset
The dataset used in this project is a CSV file with 7796 rows and 4 columns. The columns are:

News: A unique identifier for each news article.
Title: The title of the news article.
Text: The text of the news article.
Label: The label of the news article, either real or fake.
Methodology
We used the following methodology to build the model:

We preprocessed the text data by removing stop words, punctuation, and other unnecessary characters.
We used TfidfVectorizer to convert the text data into a matrix of TF-IDF features.
We initialized a PassiveAggressiveClassifier and fit the model using the TF-IDF matrix and the corresponding labels.
We evaluated the model using accuracy score and confusion matrix.
Results
The model achieved an accuracy score of 93.05%. The confusion matrix shows that the model correctly classified 161 fake news articles and 595 real news articles, while it misclassified 21 fake news articles as real and 28 real news articles as fake.

Tools
The following tools were used in this project:

Python
TfidfVectorizer
PassiveAggressiveClassifier
Scikit-learn
Repository Structure
The repository contains the following files:

README.md: This file, which provides an overview of the project and instructions for running the code.
news.csv: The dataset used in this project.
fake_news_detection.ipynb: The Jupyter Notebook containing the code for the project.
Getting Started
To get started with this project, follow these steps:

Clone the repository to your local machine.
Open the fake_news_detection.ipynb file in Jupyter Notebook.
Run the cells in the notebook to preprocess the data, train the model, and evaluate its performance.
Conclusion
In this project, we built a model to detect fake news using Python, TfidfVectorizer, and PassiveAggressiveClassifier. The model achieved an accuracy score of 93.05%, which is reasonable for a small dataset. However, there is still room for improvement, and future work could include exploring other machine learning algorithms and feature engineering techniques.
