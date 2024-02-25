# Movie-Recommendation-System-
This project is an implementation of a movie recommendation system utilizing two different approaches: Collaborative Filtering and Singular Value Decomposition (SVD) combined with K-means clustering. The system suggests movies to users based on their historical preferences and similarities with other users.

## Table of Contents
- Introduction

- Approaches Used

- Dependencies

## Introduction
Movie recommendation systems play a crucial role in helping users discover new movies based on their preferences and behaviors. This project aims to provide users with personalized movie recommendations using two main approaches: Collaborative Filtering and SVD with K-means clustering.

## Approaches Used
Collaborative Filtering: This approach recommends movies by finding similar users and suggesting items that they have liked in the past. It employs user-item interaction data to identify patterns and make predictions.

Singular Value Decomposition (SVD) with K-means Clustering: SVD is a matrix factorization technique used for dimensionality reduction. By decomposing the user-item interaction matrix, it extracts latent features. These features are then clustered using K-means to group similar users together, enabling personalized recommendations.

## Dependencies
The project is implemented using Python and requires the following dependencies:

numpy

pandas
