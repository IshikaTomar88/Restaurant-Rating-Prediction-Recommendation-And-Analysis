[README .md](https://github.com/user-attachments/files/21700141/README.md)
# Restaurant-Rating-Prediction-Recommendation-And-Analysis
This repo contains the files in which I have worked during my Machine Learning internship at Cognifyz technologies. The internship was undertaken in July-Aug 2025. They provided me a large dataset of restaurants and my main role for me was to build a model to predict the ratings of restaurants and gather meaningful insights from the data. My regression model achieved an accuracy of 97% and further details are listed below.

# Task 1
Objective: Build a machine learning model to predict the aggregate rating of a restaurant based on other features.

https://colab.research.google.com/drive/1Y6mXcCrWCwAD4V_ocfSOqrVyjG9d8NMI

## Steps :
* Preprocess the dataset by handling missing values, encoding categorical variables, and splitting the data into training and testing sets.
* Select a regression algorithm (e.g., linear regression, decision tree regression) and train it on the training data.
* Evaluate the model's performance using appropriate regression metrics (e.g., mean squared error, R-squared) on the testing data.
* Interpret the model's results and analyze the most influential features affecting restaurant ratings.

# Task 2 :
Objective: Create a restaurant recommendation system based on user preferences.

https://colab.research.google.com/drive/15vwlM6fUGWjAU-7vn7X_PhPKi_vaNd1c

## Steps :
* Preprocess the dataset by handling missing values and encoding categorical variables.
* Determine the criteria for restaurant recommendations (e.g., cuisine preference, price range).
* Implement a content-based filtering approach where users are recommended restaurants similar to their preferred criteria.
* Test the recommendation system by providing sample user preferences and evaluating the quality of recommendations.

# Task 3 
Objective: Develop a machine learning model to classify restaurants based on their cuisines.

https://colab.research.google.com/drive/1PkHbJt6ar-Yhz2Xmw2g_R55SU6r2Ut0q

## Steps :
* Preprocess the dataset by handling missing values and encoding categorical variables.
* Split the data into training and testing sets.
* Select a classification algorithm (e.g., logistic regression, random forest) and train it on the training data.
* Evaluate the model's performance using appropriate classification metrics (e.g., accuracy, precision, recall) on the testing data.
* Analyze the model's performance across different cuisines and identify any challenges or biases.

# Task 4 :
Objective: Perform a geographical analysis of the restaurants in the dataset.

https://colab.research.google.com/drive/1s2NBYxKc94CV99l285_DNo1cFlNLZiFO#scrollTo=D7yAVzkjICx5

## Steps : 
* Explore the latitude and longitude coordinates of the restaurants and visualize their distribution on a map.
* Group the restaurants by city or locality and analyze the concentration of restaurants in different areas.
* Calculate statistics such as the average ratings, cuisines, or price ranges by city or locality.
* Identify any interesting insights or patterns related to the locations of the restaurants.

# Dataset
CSV file is uploaded here in the repo

# Platform
Google Colab

# Libraries
pandas, numpy, matplotlib, seaborn, scikitlearn

# Data Preprocessing and splitting
* Cuisines had 9 null values. So dropped
* Removed features that will inhibit model performance
* The target variables were balanced
* Split training data and test data in the ratio 8:2  .

# Model Evaluation
* My restaurant rating prediction model obtained a R2 score of 0.98.
* Random Forest performs better on the model than logistic regression.

# Insights from EDA
* Expensive restaurants tend to have higher ratings.
* Visualized the geospatial distribution of restaurants on the map using their co-ordinates.
* New Delhi has the highest number of restaurants.
* 'North Indian' is the most popular cuisine overall.
* endations.

# Report Summary - Key Points

*   **Location-based analysis:** Revealed restaurant geographical distribution and density.
*   **Cuisine Classification:** Demonstrated automated cuisine identification using restaurant data.
*   **Restaurant Recommendation:** Outlined methods for personalized restaurant suggestions.
*   **Restaurant Rating Prediction:** Focused on predicting restaurant ratings based on features.
*   **Future Work:** Suggests using more data, advanced models, real-time systems, and addressing ethical aspects for deeper insights.
