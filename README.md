# YouTube Adview Prediction Project

This project aims to predict the number of adviews for YouTube videos based on various metrics using machine learning regression techniques.
_____________________________________________________________________________________________________________________________________________________

# Dataset

The dataset (train.csv) contains metrics and details of approximately 15,000 YouTube videos. 

The attributes include:
•	vidid: Unique identification ID for each video
•	adview: Number of adviews for each video (target variable)
•	views: Number of unique views for each video
•	likes: Number of likes for each video
•	dislikes: Number of dislikes for each video
•	comment: Number of unique comments for each video
•	published: Date of uploading the video
•	duration: Duration of the video (in minutes and seconds)
•	category: Category niche of each video

_____________________________________________________________________________________________________________________________________________________

# Project Overview
The goal of this project is to build a regression model to predict the adview counts based on the aforementioned metrics. Various machine learning algorithms were explored and evaluated to determine the best-performing model.

_____________________________________________________________________________________________________________________________________________________

# Steps and Tasks Completed

1.	Data Import and Exploration
  -Imported the dataset and checked its shape and data types.
  -Visualized data distributions using histograms, line plots, and a heatmap.  	
2.	Data Cleaning and Transformation
  -Removed rows with missing values ('F') in views, likes, dislikes, and comments.
  -Converted categorical 'category' feature to numerical values.
  -Converted 'duration' from string format to seconds.
3.	Modeling and Evaluation
   Trained and evaluated the following regression models:
  -	Linear Regression
  - Support Vector Regressor (SVR)
  - Decision Tree Regressor
  - Random Forest Regressor
  - Artificial Neural Network (ANN) using Keras
4.	Model Selection
   Selected the best model based on Mean Squared Error (MSE) on the test set.
5.	Final Predictions and Model Saving
  	Saved the best model (based on MSE) for future predictions.

_____________________________________________________________________________________________________________________________________________________

# How to Use

1.	Setup
  - Ensure Python 3.x is installed.
  - Install required libraries using pip install -r requirements
2.	Running the Code
  - Clone the repository: git clone https://github.com/Ghanasree-S/youtube-adview-prediction.git
  - Navigate to the project directory
  - Run the main script: YouTube_Adview_Predictions.ipynb
3.	Output
  - After running the script, check the console for model evaluation metrics and predictions.


