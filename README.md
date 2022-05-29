# Movie-Recommender-
A movie recommendation system using algorithms 

## Content Based Movie recommendation system :
Content-based recommendation system describes the items that may be recommended to the user. Based on a data set, it predicts what movies a user will like considering the attributes present in the previously liked movies. Recommendation systems can recommend movies based on one or a combination of two or more attributes

## Algorithm used-
### COSINE SIMILARITY:
Cosine similarity is a metric used to measure how similar the documents are irrespective of their size. Mathematically, it measures the cosine of the angle between two vectors projected in a multi-dimensional space. The cosine similarity is advantageous because even if the two similar documents are far apart by the Euclidean distance (due to the size of the document), chances are they may still be oriented closer together. The smaller the angle, higher the cosine similarity.

#### COSINE SIMILARITY WORKING
firstly convert the dataset into vector through the vectorization process and then for each data set one can implement cosine similairt algorithm and in this project 5 most recommended movies will be shown. In this project 5000 movies dataset have been taken, so 5000D is craeted and for each one is converted into vector and then implemented the algorithm
![cosine](https://user-images.githubusercontent.com/99603868/170869925-2f2ff982-f321-4200-a232-186c40584e3b.jpg)



in this project, used sklearn for implementing cosine similarity algorithm and a dataset of 5000 movies has been taken.
the dataset can be collected from this website link :  https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata?select=tmdb_5000_movies.csv

