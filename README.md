# Sentiment Analysis and Prediction: A Hybrid Approach

This is a sentiment analysis and prediction model that uses a hybrid approach with feature extraction.The model combines deep learning and classical machine learning: a deep learning model extracts features from movie reviews, and a logistic regression model uses these features to analyze the sentiment (positive or negative) in reviews. The dataset used was the IMDb Dataset of 50K Movie Reviews.

https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews

## Table of Contents
- [Features](#features)
- [Installation](#installation)
- [Data](#data)
- [License](#license)

## Features

I was working on a project where I needed to create a pure hybrid model using feature extraction, where features extracted from a deep learning model are used in a classical machine learning model. But because I couldn't find solid examples and a concrete solution, I decided to give it a try and develop one myself after studying the concept in depth. This model serves as an example, rather an experiment, in cases where combining deep learning with classical machine learning models together in sequence might improve overall model performance. Here’s the basic framework:

- Applied feature extraction as the core conecpt for the project
- Performed basic preprocessing on the text data to prepare for machine learning
- Developed a complex deep learning model with scaled self-attention layer to get the best results
- Adjusted parameters like learning rate, batch size, and number of epochs after thorough experimentation
- Implemented a loop to evaluate and compare different classification algorithms to choose the best option based on various metrics
- Implemented SVM Classifier on the feature-extracted data to improve the final model
- Evaluated the final model's performance using learning curves and a confusion matrix
- Tested the model on real-world data to ensure its accuracy and reliability

## Installation

Use any Python >= 3.11 version along with the requirements.txt file in the repository. I used 3.12 with the latest versions of all libraries.

```bash
# Installing using repo file
pip install -r requirements.txt
```

## Data
Link to the original dataset on Kaggle:
https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews

## License

Sentiment Analysis and Prediction: A Hybrid Approach © 2024 by Reshail Naeem is licensed under Attribution-NonCommercial-ShareAlike 4.0 International 
