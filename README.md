# Movie_Recommendation_System
Movie Recommendation System based on Popularity, Content Based and Collaborative Filtering using Python.

### Project Objective and Overview:
Three Recommendation Systems are implemented in this project:

- __Popular movies:__
  * Recommend movies based on popularity and average rating. 
  * The dataset used for this is 'movie_dataset.csv'.
  
- __Content based recomendation system:__
  * Recommend movies to the user where the contents is similar to the contents of the movie viewed by the user recently. 
  * Similarity of the movies will be based on features such as genre, director, cast, keywords and tagline.
  * The dataset used for this is 'movie_dataset.csv'.  
  * Implemented using Cosine Similarity method in scikit-learn.
  
- __Collaborative filtering:__ 
  * Recommend movies for user based on his/her rating of movies.
  * The dataset used for this is 'movies.csv' and 'ratings.csv'.
  * Implemented using Pearson method in scikit-learn.


