# Movie-Recommedation-App
A movie recommendation system attempts to anticipate preferences based on the user's selections. The Web-App created for this project using Python suggests movies based on the user's liked movies.

<h1>OVERVIEW</h1>
<b> One significant category of machine learning algorithms that provides consumers with "appropriate" choices is the recommender system. All three sites—YouTube, Amazon, and Netflix—have systems that suggest videos or products to you based on your past behavior (called content-based filtering) or on the behaviors and preferences of other users who have your interests (Collaborative Filtering).

Recommendation Systems work based on the similarity between either the content or the users who access the content.There are several ways to measure the similarity between two items. The recommendation systems use this similarity matrix to recommend the next most similar product to the user.

In this project, we will build a machine learning model that would recommend movies based on a movie the user likes. This Machine Learning model would be based on Cosine Similarity.</b>

There are several ways to create a movie recommendation system:
- Simple Recommender: This method rates all films according to predetermined standards, such as popularity, accolades, and/or genre, and then suggests the best films to users without taking into account their personal tastes. "Top 10 in the U.S. Today" on Netflix could serve as an illustration.
- Collaborative Filtering Recommender: This method makes use of user history to anticipate products that users may be interested in. It takes into account the movies a user has already viewed, the numerical ratings provided to those materials, and previously viewed movies by people who are similar to them.
- Content-based Filtering Recommender: This method makes suggestions for related items based on the attributes and metadata of a particular item. For instance, a recommender may consider a film's genre and director before making further recommendations.

<h2> How the App works? </h2>
For this Movie-Recommendation app, I have used Content based Filtering.The movies are suggested based on the movies you choose from the list provided.The movie's specifics, including title, genre, runtime, rating, poster, cast members, etc., are retrieved from TMDB.The key factors taken into account when making suggestions are:
- The genre
- The director 
- The top 3 casts 

The Frontend of this app has been built using streamlit and python. Please take a preview of this app:
![image](https://github.com/priyankac15/Movies-Recommedation-App/blob/main/MovieRecommendation_AppImage.jpg)

