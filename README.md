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

- **Spam:** Unwanted or promotional messages.
- **Ham:** Genuine and legitimate messages.

The project uses TF-IDF Vectorization for feature extraction and the Multinomial Naive Bayes algorithm for classification.

**Dataset note:** The implementation uses labelled SMS messages as training data to demonstrate spam classification techniques. These techniques can also be applied to email text.

## 2. Objectives

- Develop a spam classification model using machine learning.
- Understand and analyse labelled text datasets.
- Perform text cleaning and preprocessing.
- Apply Natural Language Processing techniques.
- Convert textual data into numerical features using TF-IDF.
- Implement a Naive Bayes classification algorithm.
- Evaluate the model using classification metrics.
- Test the model using new user-provided messages.

## 3. Dataset

**SMS Spam Collection Dataset**

Source: https://archive.ics.uci.edu/dataset/228/sms+spam+collection

The dataset contains approximately 5,500 labelled text messages belonging to two categories:

- `ham`: Legitimate messages.
- `spam`: Unwanted messages.

## 4. Technologies and Libraries

- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- NLTK
- Scikit-learn
- Jupyter Notebook
- TF-IDF Vectorization
- Multinomial Naive Bayes
- Natural Language Processing (NLP)

## 5. Project Workflow

1. **Data Collection:** Loaded the SMS Spam Collection dataset.
2. **Exploratory Data Analysis:** Analysed message distribution, message lengths, and frequently occurring words.
3. **Data Cleaning:** Removed duplicate records and handled missing values.
4. **Text Preprocessing:** Converted text to lowercase, removed unnecessary characters and URLs, removed stopwords, and applied stemming using Porter Stemmer.
5. **Feature Engineering:** Applied TF-IDF Vectorization and extracted additional numerical features such as message length, word count, digit count, and exclamation count.
6. **Data Splitting:** Divided the dataset into 80% training data and 20% testing data.
7. **Model Implementation:** Implemented the Multinomial Naive Bayes algorithm.
8. **Model Testing:** Tested the trained model on unseen messages and new user-provided text.
9. **Model Evaluation:** Evaluated performance using Accuracy, Precision, Recall, F1-Score, and Confusion Matrix.

## 6. Evaluation Metrics

- **Accuracy:** Measures the percentage of correctly classified messages.
- **Precision:** Measures how many predicted spam messages were actually spam.
- **Recall:** Measures how many actual spam messages were correctly identified.
- **F1-Score:** Provides a balance between precision and recall.
- **Confusion Matrix:** Visualizes correct and incorrect classifications.

---

# 🛠️ Installation and Execution

## Prerequisites

- Python 3.x
- Jupyter Notebook
- Internet connection for downloading datasets and required resources.

## Step 1: Clone the Repository

```bash
git clone YOUR_GITHUB_REPOSITORY_LINK
```

## Step 2: Navigate to the Project Folder

```bash
cd Machine-Learning-Projects
```

## Step 3: Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn scikit-learn scipy nltk jupyter
```

## Step 4: Open Jupyter Notebook

```bash
jupyter notebook
```

## Step 5: Run the Projects

Open the respective notebooks and execute all cells in sequence.

- `Movie_Recommendation_System.ipynb`
- `Spam_Email_Classifier.ipynb`

Both datasets are downloaded automatically when their respective notebooks are executed, provided an internet connection is available.

---

# 📁 Repository Structure

```text
Machine-Learning-Projects/
│
├── Movie_Recommendation_System.ipynb
│
├── Spam_Email_Classifier.ipynb
│
├── README.md
│
└── requirements.txt
```

---

# 🔮 Future Improvements

### Movie Recommendation System
- Implement Collaborative Filtering.
- Develop a Hybrid Recommendation System.
- Include additional movie information.
- Build an interactive recommendation application using Streamlit.

### Spam Email Classification
- Train the model on a larger email dataset.
- Experiment with Logistic Regression and Support Vector Machines.
- Implement advanced NLP techniques.
- Develop a web interface for real-time spam detection.

---

# 📚 Key Learnings

Through these projects, I gained practical experience in:

- Data Collection and Data Analysis.
- Exploratory Data Analysis (EDA).
- Data Cleaning and Preprocessing.
- Feature Engineering.
- Natural Language Processing.
- Machine Learning Model Implementation.
- Training and Testing Machine Learning Models.
- Model Evaluation and Performance Analysis.
- Python Programming and Data Visualization.

---

# 👩‍💻 Author

**Name:** Jasmine Singh

**Skills:** Python | Pandas | NumPy | Machine Learning | NLP | Scikit-learn | Data Analysis

---

⭐ If you find these projects useful, feel free to explore the notebooks and share your feedback!
