# recommender system and datasets
## Links of datasets and tutorials for simple recommender system as a precursor to group project

### Tutorials, ready-to-use:

##### Short and simple challenge with Youtube video tutorial

###### https://github.com/llSourcell/recommender_system_challenge
###### https://www.youtube.com/watch?v=9gBC9R-msAk&list=PL2-dafEMk2A6QKz1mrk1uIGfHkC1zZ6UU&index=3


##### Walkthrough of song recommender system:

###### https://towardsdatascience.com/how-to-build-a-simple-song-recommender-296fcbc8c85
###### https://github.com/llSourcell/recommender_live



### Well-documented rec-sys projects on Kaggle *

Great kernel that covers the three types of recommendations systems using the Movies Dataset: 
  * Demographic Filtering
  > generalized recommendations to every user, based on movie popularity and/or genre(too simple)
  * Content Based Filtering
  > They suggest similar items based on a particular item. This system uses item metadata, such as genre, director, description, actors, etc. for movies, to make these recommendations. The general idea behind these recommender systems is that if a person liked a particular item, he or she will also like an item that is similar to it.
  * Collaborative Filtering
  > This system matches persons with similar interests and provides recommendations based on this matching. Collaborative filters do not require item metadata like its content-based counterparts.
https://www.kaggle.com/ibtesama/getting-started-with-a-movie-recommendation-system **


Same MovieLens dataset, good walkthrough, covers content-based, collaborative, and hybrid of the two systems:
https://www.kaggle.com/rounakbanik/movie-recommender-systems *


Another well-written kernel for movies, compares different algorithms and approaches to recommendation systems (more technical than the one above), including deep learning with Keras:
https://www.kaggle.com/morrisb/how-to-recommend-anything-deep-recommender/comments *


Restaurant dataset: simple content-based recommender (writeup is a bit lengthy):
https://www.kaggle.com/liyenhsu/simple-content-based-recommenders


Anime dataset - collaborative filtering *
 > For collaborative filtering we'll need to create a pivot table of users on one axis and tv show names along the other. The pivot table will help us in defining the similarity between users and shows to better predict who will like what.

https://www.kaggle.com/ajmichelutti/collaborative-filtering-on-anime-data *


Simple content-based anime recommendation system for Anime Recommendations Database - rec based on 'ratings' and 'genre':
https://www.kaggle.com/astandrik/simple-anime-recommendation-system-content-based

Same dataset, content-based rec sys using KNN:
https://www.kaggle.com/mohammed94/content-based-anime-recommender#KNN-for-finding-similar-animes


### Datasets

##### Kaggle datasets
List of the 7 main recommender datasets on Kaggle (as of late-2018), except for movie datasets which seem to be the most popular
https://www.kaggle.com/general/65109#384033 (restaurants, hotels, books, anime, Jester jokes)

Note that goodbooks-10k dataset (Ten thousand books, one million ratings. Also books marked to read, and tags.
) is obsolete. Improved version is available at https://github.com/zygmuntz/goodbooks-10k. *
 > It has duplicates removed, and more ratings (six million), sorted by time. Book and user IDs are the same.


9MB download, "a medium sized song list, ideal to practice collaborative filter algorithms"
https://www.kaggle.com/rymnikski/dataset-for-collaborative-filters
(has one short project using fast.ai for collaborative filtering, but no comments)


##### dataset for a company to predict ad clicks 
(no projects/tutorials available on data.world)
https://data.world/hackerearth/predict-the-ad-clicks



### Possibly relevant/For Later:

##### Criteo (French company specializing in recsys, and author of 1TB Clicks dataset) 
##### highlighted some recent papers at a recsys conference:
###### https://labs.criteo.com/2017/10/criteos-take-recsys-2017-10-papers-not-miss/
##### more about their work:
###### https://labs.criteo.com/2016/09/product-recommendation-criteo/

##### Their famous ad dataset here, challenge for predicting ad click-through rate
https://www.kaggle.com/c/criteo-display-ad-challenge/overview
##### using google cloud ML
https://cloud.google.com/blog/products/gcp/using-google-cloud-machine-learning-to-predict-clicks-at-scale

##### Yelp dataset challenge
###### more for image recognition or sentiment analysis? on till Dec 2019
###### https://www.yelp.com/dataset/challenge

##### Coursera courses and specialization on rec sys
###### https://www.coursera.org/specializations/recommender-systems
###### https://www.coursera.org/learn/recommender-systems-introduction
