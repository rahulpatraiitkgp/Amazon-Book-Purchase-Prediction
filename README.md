# Amazon-Book-Purchase-Prediction
Machine Learning Engineer Nanodegree Project Udacity

### Project Summary:
Recommender Systems are to help people discover new content, find the content we were already looking for, discover which things go together, personalize user experiences in response to user feedback, recommend incredible products that are relevant to our interests and identify things that we like, which are basically to model people’s preferences, opinions and behavior. My recommender system model in this project can be used for evaluating users’ purchase habits, predicting whether or not users may buy some items. Then we can recommend book items to users. If you have used services like Amazon, Job Board or Netflix, it is often to find some recommendations suggesting items for you to buy, jobs you may be interested or movies to watch. We will use this idea to build a similar application like them.

In this project, I have built a recommender system to make predictions related to reviews of Books on Amazon. The dataset is 2,000,000 Amazon Book Reviews, which provided me purchase information. My target was to predict whether the user purchased the item based on these reviews.

## Disclaimer:

As a CS minor student of IIT Kharagpur and a long-time self-taught learner, I have completed many CS related MOOCs on Coursera, Udacity, Udemy, and Edx. I do understand the hard time you spend on understanding new concepts and debugging your program. Here I released these solutions, which are **only for your reference purpose**. It may help you to save some time. And I hope you don't copy any part of the code (the programming assignments are fairly easy if you read the instructions carefully), see the solutions before you start your own adventure. This Project is almost one of the simplest Machine Learning Project I have ever taken, but the simplicity is based on the fabulous course content and structure. It's a treasure given by Udacity team.


### Data
Assignment data is available on:
http://jmcauley.ucsd.edu/data/assignment1.tar.gz
- itemID: The ID of the item. This is a hashed product identifier from Amazon.
- reviewerID: The ID of the reviewer. This is a hashed user identifier from Amazon.
- helpful: Helpfulness votes for the review. 
- reviewText: The text of the review.
- summary: Summary of the review.
- unixReviewTime: Time of the review in seconds since 1970.
- reviewTime: Plain-text representation of the review time.
- category: Category labels of the product being reviewed.

### Tasks:
Purchase prediction: predict given a (user,item) pair from ‘pairs_Purchase.txt’ whether the user purchased the item (really, whether it was one of the items they reviewed). Predictions should be labeled 1 (purchased) or 0 (not purchased). Accuracy will be measured in terms of the classification accuracy.

### Techiniques used in project:
- Python
- Pnadas
- Sklearn
- Machine Learning
- Collaborative Filtering
