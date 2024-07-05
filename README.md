# youtube-adview-prediction
 This repository contains a machine learning project focused on predicting YouTube adview counts based on video metrics such as views, likes, dislikes, comments, and more. Various regression models have been explored and evaluated to determine the best-performing model for predicting adviews on YouTube videos.

 This project aims to predict the number of adviews for YouTube videos based on various metrics using machine learning regression techniques.

Dataset
The dataset (train.csv) contains metrics and details of approximately 15,000 YouTube videos. The attributes include:

vidid: Unique identification ID for each video
adview: Number of adviews for each video (target variable)
views: Number of unique views for each video
likes: Number of likes for each video
dislikes: Number of dislikes for each video
comment: Number of unique comments for each video
published: Date of uploading the video
duration: Duration of the video (in minutes and seconds)
category: Category niche of each video
Project Overview
The goal of this project is to build a regression model to predict the adview counts based on the aforementioned metrics. Various machine learning algorithms were explored and evaluated to determine the best-performing model.

Steps and Tasks Completed
Data Import and Exploration

Imported the dataset and checked its shape and data types.
Visualized data distributions using histograms, line plots, and a heatmap.
Data Cleaning and Transformation

Removed rows with missing values ('F') in views, likes, dislikes, and comments.
Converted categorical 'category' feature to numerical values.
Converted 'duration' from string format to seconds.
Modeling and Evaluation

Trained and evaluated the following regression models:
Linear Regression
Support Vector Regressor (SVR)
Decision Tree Regressor
Random Forest Regressor
Artificial Neural Network (ANN) using Keras
Model Selection

Selected the best model based on Mean Squared Error (MSE) on the test set.
Final Predictions and Model Saving

Saved the best model (based on MSE) for future predictions.
How to Use
Setup

Ensure Python 3.x is installed.
Install required libraries using pip install -r requirements.txt.
Running the Code

Clone the repository: git clone https://github.com/your_username/your_repository.git
Navigate to the project directory: cd your_repository
Run the main script: python main.py
Output

After running the script, check the console for model evaluation metrics and predictions.
Files Included
train.csv: Main dataset file containing YouTube video metrics.
main.py: Main Python script for data preprocessing, modeling, and evaluation.
README.md: This file, providing an overview of the project.
Future Improvements
Implement cross-validation for more robust model evaluation.
Explore ensemble methods or deep learning architectures for further performance enhancement.
