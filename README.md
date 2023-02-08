# Movie-Recommedation-App
A movie recommendation system attempts to anticipate preferences based on the user's selections. The Web-App created for this project using Python suggests movies based on the user's liked movies.

<h1>OVERVIEW</h1>
<b> One significant category of machine learning algorithms that provides consumers with "appropriate" choices is the recommender system. All three sites—YouTube, Amazon, and Netflix—have systems that suggest videos or products to you based on your past behavior (called content-based filtering) or on the behaviors and preferences of other users who have your interests (Collaborative Filtering).

Recommendation Systems work based on the similarity between either the content or the users who access the content.There are several ways to measure the similarity between two items. The recommendation systems use this similarity matrix to recommend the next most similar product to the user.

In this project, we will build a machine learning model that would recommend movies based on a movie the user likes. This Machine Learning model would be based on Cosine Similarity.</b>

There are several ways to create a movie recommendation system:
- <b>Simple Recommender</b>: This method rates all films according to predetermined standards, such as popularity, accolades, and/or genre, and then suggests the best films to users without taking into account their personal tastes. "Top 10 in the U.S. Today" on Netflix could serve as an illustration.
- <b>Collaborative Filtering Recommender</b>: This method makes use of user history to anticipate products that users may be interested in. It takes into account the movies a user has already viewed, the numerical ratings provided to those materials, and previously viewed movies by people who are similar to them.
- <b>Content-based Filtering Recommender</b>: This method makes suggestions for related items based on the attributes and metadata of a particular item. For instance, a recommender may consider a film's genre and director before making further recommendations.

<h2> How does it determine which item is most comparable to the one the user loves (or chooses, in this case)? </h2>

The similarity scores are now presented.It is a numerical value that runs from 0 to 1, used to assess how much two items resemble one another on a scale from 0 to 1. This similarity score is calculated by comparing how closely the text details of the two items match. Therefore, the similarity score is a metric used to compare two things' given textual descriptions. Cosine-similarity can be used to achieve this.

Cosine similarity is a metric used to measure how similar two items are. Mathematically, it measures the cosine of the angle between two vectors projected in a multi-dimensional space. The output value ranges from 0–1.0 means no similarity, where as 1 means that both the items are 100% similar.Here, to build this recommenders system i have used the Cosine Similarity from Sklearn, as the metric to compute the similarity between two movies.
 
<h2> How the App works? </h2>

For this Movie-Recommendation app, I have used Content based Filtering.The movies are suggested based on the movies you choose from the list provided.The movie's specifics, including title, genre, runtime, rating, poster, cast members, etc., are retrieved from TMDB.The key factors taken into account when making suggestions are:

- The genre
- The director 
- The top 3 casts 

The Frontend of this app has been built using streamlit and python. Please take a preview of this app:

![image](https://github.com/priyankac15/Movies-Recommedation-App/blob/main/MovieRecommendation_AppImage.jpg)


<b>Sources:</b>
[IMDB-5000-Movies-Dataset](https://www.kaggle.com/datasets/carolzhangdc/imdb-5000-movie-dataset)
[TMDB-API-Guide](https://www.themoviedb.org/documentation/api)


