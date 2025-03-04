BBC News Recommendation System

This project is a BBC News Recommendation System that suggests relevant news articles to users using a hybrid approach (Content-Based + Collaborative Filtering). The system is built with Python and leverages machine learning algorithms to provide personalized news recommendations.

Introduction

With the exponential growth of online news articles, users find it difficult to discover relevant news according to their preferences. This system aims to recommend personalized BBC news articles to users by analyzing content and user preferences.

Methodology

The system follows the following steps:

Data Collection: Scrape BBC news articles or use pre-existing datasets.

Data Preprocessing: Clean text, remove stopwords, and tokenize news content.

Feature Extraction: Convert text into numerical features using TF-IDF.

Hybrid Recommendation System: Combine Content-Based Filtering (based on news similarity) and Collaborative Filtering (based on user preferences).

Model Training: Train the system using machine learning algorithms.

Evaluation: Use accuracy, precision, recall, and RMSE for performance evaluation.

API Deployment: Deploy the system using Flask API.

Features

News Data Collection (Web Scraping or Dataset-based)

Data Preprocessing (Stopwords Removal, Tokenization)

Feature Extraction (TF-IDF or Word Embeddings)

Hybrid Recommendation System

Model Training and Evaluation

API Deployment with Flask

Tech Stack

Python

Scikit-learn

Pandas

Flask

Git


How to Run the Project

1. Clone the Repository

git clone https://github.com/your-username/BBC-News-Recommendation.git
cd BBC-News-Recommendation

2. Install Dependencies

pip install -r requirements.txt

3. Run Flask API

python src/app.py

API will be available at: http://localhost:5000

API Endpoints

Endpoint

Method

Description

/recommend?user_id=1

GET

Get news recommendations for a user

/all-news

GET

Fetch all available news articles

Dataset Description

Feature

Description

Title

News Title

Description

Short Description

pubDate

Publication Date

Link

News Article URL

Limitations & Future Work

The model currently works only with English text.

Collaborative Filtering requires more user interaction data.

Future work includes integrating deep learning models and improving recommendation accuracy.

To-Do List



Contributing

If you'd like to contribute, feel free to open a pull request!

Author: Nishant Niraula
