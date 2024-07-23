# Predict-Bike-Sharing-Demand-with-AutoGluon
In this project, I trained a model using AutoGluon to predict bike sharing demand. This is part of the AWS &amp; Udacity "AWS ML Fundamentals" Certification.

Description: 
In this project, you'll use the AutoGluon(opens in a new tab) library to train several models for the Bike Sharing Demand(opens in a new tab) competition in Kaggle. You will be using Tabular Prediction(opens in a new tab) to fit data from CSV files provided by the competition. This project will demonstrate your ability to use AutoGluon to train several iterations of models and record your personal optimization of the problem.

Bike-sharing demand is highly relevant to related problems companies encounter, such as Uber, Lyft, and DoorDash. Predicting demand not only helps businesses prepare for spikes in their services but also improves customer experience by limiting delays.

In the end, you will have submitted several entries to the competition and achieved a rank within Kaggle. You will also complete a report of your findings that you can share publicly on Kaggle or your personal page, providing a way to showcase your work.

Conclusion: 
This project taught me how to use exploratory data analysis to understand data, find features that are the most meaningful for that data, and tune hyperparameters to improve models of that data. Using more features and data points can help your predictions become more accurate. Also, there are a variety of hyperparameters, like for neural network models, that greatly improve the building accurate machine learning models. The initial model was bare and ineffective. When more features were added, the model improved by 62%. My third model, regression, was just the add_features model, but with the hyperparameter problem_type="regression". This only improved the kaggle score by 1%. However, when implementing the hyperparameters available in autogluon.core, the best kaggle score was achieved: 0.4835.
