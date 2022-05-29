# Recommendation-Engine
The following project is a recommendation engine for movies.

The recommendation system filters the movie on the basis of its properties.

CONTENT-BASED FILTERING

Content-based filtering recommendation, also known as Cognitive filtering, uses item features to recommend other items similar to what the users like on their previous actions or feedback.
It works by the data that is taken from the user either explicitly or implicitly.

Advantages:
1) The model doesn't need any data about other users, since the recommendations are specific to  this user.
2) This makes it easier to scale to a large number of users.
3) The model can capture the specific interests of a user, and can recommend niche items that very few other users are interested in.

COLLABORATIVE FILTERING 

Collaborative Based Filtering will overcome the Disadvantage of Content Based Filtering as it is going to use the User Interactions Instead of the Content from the Items used by the Users.
Collaborative Filtering doesn’t need anything else except the user’s historical preference on a set of items. 
It is based on historical data, the core assumption here is that the users who have agreed in the past tend to also agree in the future.

Advantages:
1) It works Really well, even if the data is small.
2) The model can help users discover new interests. In isolation, the ML system may not know the user is interested in a given item, but the model might still recommend it because similar users are interested in that item.
3) No Need for Domain Knowledge.

This recommendation system explains the working of both, Content Based and Collaborative Filtering.
