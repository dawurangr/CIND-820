# CIND-820---Predicting-Movie-Success-with-a-Random-Forest-Regressor

Written by: Rinji Dawurang
<br />
Supervisor : Ceni Babaoglu PhD
<br />
The dataset that was used for this project was retreived from:
https://www.kaggle.com/rounakbanik/the-movies-dataset 

## Description-of-Project: 

Using the CRISP-DM approach, a Random Forest Regressor model is developed using a dataset with 45,000 movies to predict what makes a movie successful.

This repository contauins the coding file for the project which is the movie_success_model.ipynb file and a readme file explaining the project.

## Project-Stages
* Business Understanding: This business problem is a predictive analytics problem. It was understood from the literature that not only financial metrics could be used to predict the success of a movie.
* Data Exploration: sourced data on a large amount of movies and decided to go with the dataset I found on Kaggle. Various columns like 'original_language' and 'popularity' were dropped for the initial data analysis and rows and columns with missing values were dropped.
* Modeling: This is a predictive anlytics problem in which the independent variable is a continuous variable so this approach was preferred over classification algorithms. For the predicitive algorithm, there were 3 choices: K-Nearest Neighbor, Linear Regression and Random Forest an I decided to go with a Random Forest Regressor because of the ability of decision trees to make predicitions individually and group the predicition to generate results after each tree votes its prediction.
* Results: Increasing the number of decision trees and random state improved the performance of the model. Adopting the proposed model's a better predictor of revenue in the movie industry as it integrates many attributes implying that it can be reasonably assumed that cumulative variation in revenue prediction using the model was solely attributed to the variations in the causal variables. 
