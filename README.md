# BYOP-2024-DSG-
Contains the Python Code(along with readme file) and the csv file of the dataset used for my content based music recommender model
Import necessary libraries, including pandas for data manipulation, TfidfVectorizer for text feature extraction, and linear_kernel for calculating cosine similarity.
Create a new column in the DataFrame called 'content'. Combine the 'Title', 'Artist', and 'Top Genre' features into a single string for each song using the apply (LAMBDA)function.
Use the TF-IDF Vectorizer to convert the content strings into a numerical format (TF-IDF matrix). This matrix represents the importance of words in each content string.
Calculate the cosine similarity between items (songs) based on their content using the linear_kernel function. This results in a matrix where each entry (i, j) represents the cosine similarity between songs i and j.
Create a function that takes a song title, DataFrame, and cosine similarity model as input and returns a list of top recommendations(top 10 recommendations in my case) for that song based on content similarity.
Provide an input song title and print the top 10 recommendations for that son g using the function created
The input song must be from the dataset itself and for this model we have to give the exact input name of the song as it is written in the dataset for the output to be shown without any error
