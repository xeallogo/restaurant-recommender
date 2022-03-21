# Restaurant Recommender
This recommendation system uses data from the Yelp Open Dataset, available for download here. It is also available as a dataset on Kaggle.

In order to trainin the recommendation system, I filtered the dataset to only include restaurant reviews, and only include users who wrote at least 10 reviews:
The final dataset used with the model includes 2,295,089 reviews for 73,100 businesses by 81,416 users.

SVD and GridSearch are used to train the model to efficiently predict restaurants for users with a mean error of 0.85 stars.
Histograms show yhr number of reviews per business, number of reviews per user, and star count.

Used Dash Python package to quickly get the dashboard up and running.
Dash uses Flask as its Python web framework. 
