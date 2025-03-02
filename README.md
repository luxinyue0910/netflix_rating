# netflix_rating

### Overview of Unsupervised Learning Problem

This project uses unsupervised model to predict ratings for videos on Netflix. The problem is, if we know some people have rated some movies, but haven't seen others, what rating will these people give to the unseen ones? Then the recommendation system can promote the movies with potential high ratings.

The reason why I choose this, is that I am a subscriber of Netflix, and this is a good chance for me to tackle some real-word ML problems. 

This dataset also contains publish-year as a feature, which may give me more insight.

Also, this project has much bigger size compared to our weekly assignment, so I will work on some interesting `data trimming/regularization` techniques.



### Data source

The dataset is provided by Netflix on kaggle: https://www.kaggle.com/datasets/rishitjavia/netflix-movie-rating-dataset/data
The data contains 2 csv files:
- Netflix_Dataset_Movie.csv: list of movies
- Netflix_Dataset_Rating.csv: list of ratings



I will include the following sections:
- 1. Exploratory Data Analysis (EDA)
- 2. Model Building and Training
  - I will use 2 unsupervised algos: `Matrix Decomposition` and `Collaborative Filtering`
- 3. Model Comparisons
- 4. Conclusions
