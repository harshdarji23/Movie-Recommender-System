# Movie-Recommender-System 
## User Interactive Application: 
Not Sure of which Movie to watch? Select your favourite Movies and get recommendation from the app:P
https://harshdarji.shinyapps.io/myapp/

## Introduction
At some point each one of us must have wondered where all the recommendations that Netflix, Amazon, Google give us, come from. We often rate products on the internet and all the preferences we express and data we share (explicitly or not), are used by recommender systems to generate, in fact, recommendations. In this project, we have developed a collaborative filtering recommender system for recommending movies. The basic idea of CFR systems is that, if two users share the same interests in the past, e.g. they liked the same book or the same movie, they will also have similar tastes in the future. If, for example, user A and user B have a similar purchase history and user A recently watched a movie that user B has not yet seen, the basic idea is to propose this movie to user B. 

![Capture](https://user-images.githubusercontent.com/30519294/58002595-c768ab80-7aac-11e9-9adc-d06391656228.PNG)

## Objective
To develop a collaborative filtering recommender (CFR) system for recommending movies with the main objective of recommending relevant movies to the users. In the era of competitors like Amazon Prime, Netflix, Hulu, companies want maximum users to stick to their product which will result in higher profits. So, this recommender system plans to provide optimized recommendation of movies to increase viewership on our product. This project plans to give vital information to marketing department so that they can market a movie in order to make profits. Also, the PR team and Design team will use the information generated from this project to place movies efficiently on the website and target specific segment of customers. 
There are two approaches develop a recommender system: 
* Collaborative filtering: Collaborative filtering approaches build a model from user’s past behavior (i.e. items purchased or searched by the user) as well as similar decisions made by other users. This model is then used to predict items (or ratings for items) that user may have an interest in. 
* Content-based filtering: Content-based filtering approaches uses a series of discrete characteristics of an item in order to recommend additional items with similar properties. Content-based filtering methods are totally based on a description of the item and a profile of the user’s preferences. It recommends items based on user’s past preferences. 

## Dataset
https://grouplens.org/datasets/movielens/latest/

* 105339 ratings 
* 6138 tag applications 
* 10329 movies
* 668 users 

## Logic & Reasoning
![Capture](https://user-images.githubusercontent.com/30519294/58003412-b6b93500-7aae-11e9-83b0-729af307ea76.PNG)

## Conclusion:
## Item-Based Collaborative Filtering: 
* Strengths: Content-based recommender systems don’t require a lot of user data.  We just need item data and we are able to start giving recommendations to users.  Also, our recommendation engine does not depend on lots of user data, so it is possible to give recommendations to even our first customer as long as we have adequate data to build his user profile. 
 
* Weakness: Our item data needs to be well distributed. It won’t be effective to have a content-based recommender if 80% of our movies are of same genre.  Also, the recommendations we get will likely be direct substitutes, and not complements, of the item the user interacted with. Complements are more likely discovered through collaborative techniques. 
 
## User-Based Collaborative Filtering: 
* Strengths: User-based Collaborative Filtering gives recommendations that can be complements to the item the user was interacting with. This might be a stronger recommendation than what an item-based recommender can provide as users might not be looking for direct substitutes to a movie they had just viewed or previously watched. 
* Weakness: User-based Collaborative Filtering is a type of Memory-based Collaborative Filtering that uses all user data in the database to create recommendations. Comparing the pairwise correlation of every user in our dataset is not scalable. User-based collaborative filtering relies on past user choices to make future recommendations. The implications of this is that it assumes that a user’s taste and preference remains more or less constant over time, which might not be true and makes it difficult to pre-compute user similarities offline.

## Learning:
In the era of competitors like Amazon Prime, Netflix, Hulu, companies want maximum users to stick to their product which will result in higher profits. So, this recommender system plans to provide optimized recommendation of movies to increase viewership on our product. This project plans to give vital information to marketing department so that they can market a movie in order to make profits. Also, the PR team and Design team will use the information generated from this project to place movies efficiently on the website and target specific segment of customers. 
In this project, we learn how companies like Amazon, Netflix suggests us products based on our purchases and how they target more customers. For ex: If I watched Avengers endgame and Thor Ragnarok on Netflix, the company will be pretty sure that I will be watching some superhero movie so they will recommend me similar type of movies and make money out of me. Understanding how these companies recommend products based on our liking and history was the biggest take away from this project.
