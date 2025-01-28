# Movie-Recommendation-System:-
*This project is a movie recommendation system that suggests movies similar to the one selected by the user. It is built using Python, Streamlit, and employs the Count Vectorizer method to calculate similarities between movies.


*FEATURES:-
1)Movie Recommendation: Input a movie title, and the system suggests five similar movies.
2)Poster Fetching: Displays the posters of recommended movies for better user experience.
3)Interactive UI: Uses Streamlit to provide a user-friendly interface


*TECHNOLOGIES USED:-
1)Frontend: Streamlit
2)Backend: Python
3)Libraries/Tools:-
   pandas for data manipulation
   sklearn for Count Vectorizer
   joblib for model storage/loading
   requests for fetching movie posters from TMDB API

   
*WORKING OF THE PROJECT:-
1)The Count Vectorizer is used to calculate the similarity between movies based on textual metadata (e.g., genres, descriptions).
2)Movie similarity is represented using a similarity matrix.
3)For a given movie, the model identifies the top 5 most similar movies based on the similarity matrix.
4)Movie posters are fetched using TMDB API.
