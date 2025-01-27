Movie_Recommendation_System

This project is a Movie Recommendation System designed to predict and suggest movies based on user preferences. In machine learning collaborative filtering techniques, this system analyzes vast amounts of data to deliver personalized recommendations.

Mainly three types of recommendation systems in machine learning based on filtering are used to suggest product and services to the consumers.

  1.  Content Filtering

  2.  Collaborative Filtering

  3.  Hybrid Filtering

  4.  Content Filtering:

      In this algorithm, we try finding items look alike. Once we have item look like matrix,

      we can easily recommend alike items to a customer, who has purchased any item from the store.

  5.  Collaborative Filtering:

      Here, we try to search for look alike customers and offer products based on what his/her lookalike has chosen.

      This algorithm is very effective but takes a lot of time and resources.

  6.  Hybrid Filtering (Content Filtering + Collaborative Filtering):

      Both Content Filtering & Collaborative Filtering is used for the purpose. you-tube uses this algorithm for their strong recommendation system.

Key features include:

   -Ensures highly relevant suggestions by analyzing similarities between users and movies.

   -Content-based Filtering: Utilizes metadata like genres, directors, and cast to recommend similar movies.

   -Interactive Interface: User-friendly UI allowing users to explore recommendations, rate movies, and receive instant feedback.


Both Content Filtering & Collaborative Filtering is used for the purpose. you-tube uses this algorithm for their strong recommendation system.

For this project, Content based filtering model more specifically item-based filtering concept has been used. Concept of Clustering, a subset of unsupervised machine learning has been used to build this recommendation system. TfidfVectorizer(Term Frequency & Inverse Document Frequency) of sklearn library has been used to count the frequency of the genres types. Hyper parameter of TfidfVectorizer gives better result. The TfidfVectorizer will tokenize documents, learn the vocabulary and inverse document frequency weightings, and allow you to encode new documents. Alternately, if you already have a learned CountVectorizer, you can use it with a TfidfTransformer to just calculate the inverse document frequencies and start encoding documents. Now for the finding the similarity in genres sigmoid_kernel has been used. (cosine, linear can also be used).

Data Gathered From: https://www.kaggle.com/grouplens/movielens-20m-dataset

Data Pre-Processing and Model Applied : https://github.com/KhushiNyati/Movies-Recommendation-System/blob/main/Recommender%20system.ipynb

Sub-set of The used Data set : https://github.com/KhushiNyati/Movies-Recommendation-System/blob/main/itdf.csv

Model Pickled for Web Scraping : https://github.com/KhushiNyati/Movies-Recommendation-System/blob/main/mod.py

Flask File : https://github.com/KhushiNyati/Movies-Recommendation-System/blob/main/main.py
