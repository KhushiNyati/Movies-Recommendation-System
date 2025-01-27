Movie_Recommendation_System

This project is a Movie Recommendation System designed to predict and suggest movies based on user preferences. In machine learning collaborative filtering techniques, this system analyzes vast amounts of data to deliver personalized recommendations.

Mainly three types of recommendation systems in machine learning based on filtering are used to suggest product and services to the consumers.

Content Filtering

Collaborative Filtering

Hybrid Filtering

Key features include:

Ensures highly relevant suggestions by analyzing similarities between users and movies.

Content-based Filtering: Utilizes metadata like genres, directors, and cast to recommend similar movies.

Interactive Interface: User-friendly UI allowing users to explore recommendations, rate movies, and receive instant feedback.


Both Content Filtering & Collaborative Filtering is used for the purpose. you-tube uses this algorithm for their strong recommendation system.

For this project, Content based filtering model more specifically item-based filtering concept has been used. Concept of Clustering, a subset of unsupervised machine learning has been used to build this recommendation system. TfidfVectorizer(Term Frequency & Inverse Document Frequency) of sklearn library has been used to count the frequency of the genres types. Hyper parameter of TfidfVectorizer gives better result. The TfidfVectorizer will tokenize documents, learn the vocabulary and inverse document frequency weightings, and allow you to encode new documents. Alternately, if you already have a learned CountVectorizer, you can use it with a TfidfTransformer to just calculate the inverse document frequencies and start encoding documents. Now for the finding the similarity in genres sigmoid_kernel has been used. (cosine, linear can also be used).
