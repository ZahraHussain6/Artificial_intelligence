# Artificial intelligence
# Game Flow Recommender Project Report

# Introduction
The Game Flow Recommender project aims to develop a recommendation system for video games based on content-based filtering techniques. The system utilizes a dataset obtained from Kaggle and undergoes a series of preprocessing steps including data cleaning, feature engineering, and content-based filtering to provide personalized game recommendations to users.

# Workflow Overview
1. Data Preprocessing
2. Feature Engineering
3. Content-Based Filtering
4. Data visualisation
5. User Interface
6. ML/DL models
   
# Module Descriptions: 
## Data Collection:
The dataset is obtained from Kaggle, containing information about various video games.
## Data Preprocessing:
1.  We have removed unnecessary columns such as 'popular_tags', 'languages', 'game_description', 'mature_content', 'minimum_requirements', etc that don't help with recommendations based on correlation.
2. We have also fixed the columns like conversion of price from dollars to rupees and correction of the format of the release date.
3. Also Handled the null values.
## Feature Engineering:
1. Module focuses on transforming raw data into meaningful features for the recommendation system such as Categorical encoding of reviews Numerical transformation of discount and release date.
2. Aggregation/grouping of sentiments of the game into numerical values (e.g., 'Very Positive': 4, 'Overwhelmingly Positive': 3, 'Mostly Positive': 2, 'Mixed': 1. 
## Content-Based Filtering:
1. This Module employs TF-IDF transformation and cosine similarity calculations on key features such as 'average_reviews','developer_popularity', and 'discount_percentage', the system can generate personalized game recommendations aligned with user preferences.
2. Recommendations are based on the recommended genre.
## User Interface:
To ensure accessibility and ease of use, the project incorporates a user-friendly interface allowing users to input their preferred genre and receive trending game recommendations accordingly.
## Data Visualization:
This plays a crucial role in clarifying insights from the dataset and evaluating model performance. Through box graphs, bar graphs, and histograms, we visualizes various aspects of the dataset and evaluates model performance.
![Alt text](C:/Users/TECH ZONE/Pictures/Screenshots/Screenshot%202024-05-04%20185753.png)
![Alt text](C:/Users/TECH ZONE/Pictures/Screenshots/Screenshot%202024-05-04%20185859.png)
![Alt text](C:/Users/TECH ZONE/Pictures/Screenshots/Screenshot%202024-05-04%20185913.png)

## Machine Learning Models:
In addition to content-based filtering, this project explores the application of machine learning models such as logistic regression and random forest to further enhance recommendation accuracy. By comparing the performance of these models against the content-based approach, we gain deeper insights into the efficiency of different algorithms in delivering relevant game recommendations.
## Deep Learning Models:
The project extends its exploration to deep learning methodologies, employing artificial neural networks (ANN) and long short-term memory (LSTM) models for recommendation.We wanted to see if these advanced techniques can make our recommendations even better.
## Conclusion
The Game Flow Recommender project demonstrates the development of a robust recommendation system for video games. By employing content-based filtering techniques and machine learning and deep learning models, the system is able to deliver personalized game recommendations to users based on their preferences. Through data preprocessing, feature engineering, and model evaluation, the project showcases the effectiveness of various algorithms in enhancing the gaming experience for users.

## References
Kaggle dataset: https://www.kaggle.com/datasets/kanchana1990/steam-store-2024-hot-picks-and-reviews/data

Scikit-learn library for machine learning algorithms: [Documentation](https://scikit-learn.org/0.21/documentation.html)

TensorFlow library for deep learning models: [Documentation](https://www.tensorflow.org/api_docs)
