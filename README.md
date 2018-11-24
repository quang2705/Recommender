# Recommendation-system
This is my self taught recommender system git repository.
Recommenddation system is field of study that trying to predict item similarity in a database given:
1. The feature score of each item in the database 
2. The ranking that each users given to each item in the database
In this github repository, I will look at all (possibly) algorithm that help us in building a recommendation system
## Getting Started 
### Prerequite:
1. Recommended learning ahead about machine learning, algorithm design and mathemtic linear algebra as well as calculus
2. Andrew Ng course in Machine Learning have a good introduction to Recommendation System: [https://www.coursera.org/learn/machine-learning/home/week/9]
3. Read the [https://www.kaggle.com/rounakbanik/movie-recommender-systems/notebook], he has a good python implementation of Simple Recommender, Content Based Recommendation and Collaborative Filterting Recommendation.
### Dataset:
I got my dataset from Movie Lense in the data.zip file, you can download using MovieLense Database

### Jupyternotebook file:
- DataProcessing.py:
This file calls the Movie Lense Api to get the movie database and do data processing so that we have a easier time using it latter
- RecommenderSystem.py:
This file is the reimplementation of the Kaggle file with more explanation on how the recommendation system actually work. 
