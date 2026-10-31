# Machine Learning Projects – Movie Recommendation System & Spam Classification

## 📌 Project Overview

This repository contains two beginner-friendly Machine Learning projects developed using Python, Data Analysis, and Machine Learning techniques.

The projects demonstrate practical applications of machine learning in recommendation systems and Natural Language Processing (NLP).

### Projects Included

1. **Movie Recommendation System:** A content-based recommendation system that suggests movies based on movie genres, titles, and user preferences.

2. **Spam Email Classification:** A machine learning model that classifies text messages as Spam or Ham (Not Spam) using Natural Language Processing techniques.

---

# 🎬 Project 1: Movie Recommendation System

## 1. Introduction

The Movie Recommendation System is a machine learning project that recommends movies to users based on their interests and previously liked movies.

It uses Content-Based Filtering to identify similarities between movies by analysing their titles and genres.

The system uses TF-IDF Vectorization, Multi-Hot Encoding, and Cosine Similarity to generate personalized movie recommendations.

## 2. Objectives

- Develop a movie recommendation system using machine learning.
- Analyse movie datasets and user ratings.
- Perform data cleaning and preprocessing.
- Apply feature engineering techniques.
- Calculate similarities between movies.
- Generate recommendations based on user preferences.
- Evaluate the recommendation system using appropriate metrics.

## 3. Dataset

**MovieLens Latest Small Dataset**

Source: https://grouplens.org/datasets/movielens/latest/

The dataset contains approximately 100,000 movie ratings along with movie information.

Main files used:

- `movies.csv`: Movie IDs, titles, and genres.
- `ratings.csv`: User IDs, movie IDs, ratings, and timestamps.

## 4. Technologies and Libraries

- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- Jupyter Notebook
- TF-IDF Vectorization
- Multi-Hot Encoding
- Cosine Similarity

## 5. Project Workflow

1. **Data Collection:** Downloaded and loaded the MovieLens dataset.
2. **Exploratory Data Analysis:** Analysed movie ratings, popular movies, and genre distributions.
3. **Data Preprocessing:** Removed duplicate records, handled missing values, and cleaned the datasets.
4. **Feature Engineering:** Applied Multi-Hot Encoding for genres and TF-IDF Vectorization for movie titles.
5. **Data Splitting:** Divided user ratings into 80% training data and 20% testing data.
6. **Model Implementation:** Developed a Content-Based Filtering recommendation system using Cosine Similarity.
7. **Recommendation Generation:** Generated personalized movie recommendations based on highly rated movies.
8. **Model Evaluation:** Evaluated recommendation quality using Precision@10, Recall@10, F1-Score, and RMSE.

## 6. Evaluation Metrics

- **Precision@10:** Measures the proportion of relevant movies among the top 10 recommendations.
- **Recall@10:** Measures how many relevant movies were successfully recommended.
- **F1-Score:** Represents the balance between precision and recall.
- **RMSE:** Measures the difference between actual and predicted user ratings.

---

# 📧 Project 2: Spam Email Classification

## 1. Introduction

The Spam Email Classification project is a Machine Learning and Natural Language Processing project that identifies whether a text message is spam or legitimate (ham).

The model analyses message content and classifies messages into two categories:

- **Spam:** Un
