# Recommender-System
A recommender system is a simple algorithm whose aim is to provide the most relevant information to a user by discovering patterns in a dataset.

In this tutorial we are going to use the MovieLes Dataset. This dataset was put together by the Grouplens research group at the University of Minnesota. It contains 1, 10, and 20 million ratings. Movielens also has a website where you can sign up, contribute reviews and get movie recommendations. You can find more datasets for various data science task from Dataquest’s data resource.

Here, I had made a simple item similarity based recommender system. It is a form of memory based collaborative model. These systems identify similar items based on users’ previous ratings. For example if users A,B and C gave a 5 star rating to books X and Y then when a user D buys book Y they also get a recommendation to purchase book X because the system identifies book X and Y as similar based on the ratings of users A,B and C.

Here, in the histogram visualization I saw a sharp decline in number of ratings from 100.I therefore set this as the threshold, however this is a number you can play around with until you get a suitable option to overcome challenge that some of the movies have very few ratings and may end up being recommended simply because one or two people gave them a 5 star rating to some extent.
