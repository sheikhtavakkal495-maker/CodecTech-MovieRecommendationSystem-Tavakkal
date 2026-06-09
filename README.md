Overview

This project recommends movies to users based on movie genres. It uses Content-Based Filtering and Cosine Similarity to identify movies that are similar to a movie selected by the user.

Objective

The objective of this project is to build a recommendation system that helps users discover movies with similar characteristics and genres.

Technologies Used
Python
Pandas
Scikit-learn
Dataset

The project uses the MovieLens dataset containing:

Movie ID
Movie Title
Genres

Dataset Source: Kaggle

Project Workflow
Data Collection
Data Cleaning
Feature Extraction using CountVectorizer
Similarity Calculation using Cosine Similarity
Movie Recommendation Generation
Features
Genre-based movie recommendations
Content-Based Filtering
Fast recommendation generation
User-friendly implementation
How It Works

The user enters a movie name. The system analyzes the genres of the selected movie and compares them with other movies in the dataset. It then recommends the most similar movies based on similarity scores.

Output

The system displays the top recommended movies related to the movie entered by the user.
Input:

Toy Story (1995)

Output:

Toy Story 2 (1999)
A Bug's Life (1998)
Monsters, Inc. (2001)
Finding Nemo (2003)
Cars (2006)

Conclusion

This project demonstrates the implementation of a basic recommendation engine using Content-Based Filtering. It helps users discover movies that match their interests and provides a foundation for building advanced recommendation systems.
