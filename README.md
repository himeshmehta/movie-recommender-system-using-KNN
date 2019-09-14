# movie-recommender-system-using-KNN
Project Overview
In this project, I am going to build a ITEM_BASED collabartive recommender system . In this recommender system , items will be clustered based on rating of item given by users and item will be recommends based on similar items.

ITEM-BASED recommender system
Collaborative filtering based systems use the actions of users to recommend other items. In general, they can either be user based or item based. User based collaborating filtering uses the patterns of users similar to me to recommend a product (users like me also looked at these other items). Item based collaborative filtering uses the patterns of users who browsed the same item as me to recommend me a product (users who looked at my item also looked at these other items). Item-based approach is usually prefered than user-based approach. User-based approach is often harder to scale because of the dynamic nature of users, whereas items usually don't change much, so item-based approach often can be computed offline.

Data-Sets
I used the data provided on this site MovieLens datasets. I used the small version of dataset due to limitation of laptop.This dataset contain 5 different file.

1) movies : this file contain movieId,title of movies and genre of movies.

2) rating : this file contain ratings given by userId to MovieId and rating given to movieId.

This dataset contain 9000 unique movies and 600 unique user . Total ratings in this dataset is around 300,000.
