# engage-movie-recommender-system
# Movie recommendation system:
This system recommends movie to the user on the basis of their interests. This recommendation engine uses content based filtereing for recommending.

# Content based filtering:
The idea behind Content-based (cognitive filtering) recommendation system is to recommend an item based on a comparison between the content of the items and a user profile.In simple words,I may get recommendation for a movie based on the description of other movies.

# Movie Recommendation Model Using Cosine_Similarity and CountVectorizer: Scikit-Learn-

Similarity analysis is a common task in Natural Language Processing(NLP). YouTube or Netflix use similar techniques to recommend to their customers. They analyze the previous behavior of their customers and based on that, they recommend similar material for them. This movie recommendation model is developed by using the scikit-learn library in python. I have used similarity analysis technique. It involves a lot of complex mathematics. But the scikit-learn library has some great in-built functions that will take care of most of the heavy lifting. 

# Count Vectorizer:
CountVectorizer is a great tool provided by the scikit-learn library in Python. It is used to transform a given text into a vector on the basis of the frequency (count) of each word that occurs in the entire text. This is helpful when we have multiple such texts, and we wish to convert each word in each text into vectors (for using in further text analysis).

# Cosine similarity:
Use ‘cosine_similarity’ to find the similarity. This is a dynamic way of finding the similarity that measures the cosine angle between two vectors in a multi-dimensional space. In this way, the size of the documents does not matter. The documents could be far apart by the Euclidean distance but their cosine angle can be similar.

# Tools used:
1.Numpy
2.Pandas
3.Pickle
4.Streamlit
5.Pathlib
6.streamlit_authenticator
7.requests

# Dataset:
For this model , i have used movie dataset of around 5000 movies from tmdb. 
