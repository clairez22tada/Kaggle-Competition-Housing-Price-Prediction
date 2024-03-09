# Kaggle-Competition-Housing-Price-Prediction
This repository contains the code and documentation for the Kaggle competition on predicting housing listing prices. The goal of this project was to develop machine learning models that accurately estimate the selling price of houses based on various features provided in the listing.

Problem Description
Predicting listing prices in the real estate market is crucial for buyers, sellers, and real estate professionals. This Kaggle competition aimed to address this common problem by leveraging machine learning techniques to predict housing prices.

Data Description
The dataset provided for the competition includes various features such as property type, location, size, number of bedrooms and bathrooms, amenities, and other relevant attributes. Additionally, it contains the actual selling prices, allowing for supervised learning approaches.

Approach
Extracted numerical features from textual descriptions using regular expressions.
Applied standard scaling to normalize numerical features.
Utilized one-hot encoding to convert categorical features into numerical representations.
Generated text embeddings for listing descriptions using a pre-trained DistilBERT model.
Experimented with different hyperparameters and optimization algorithms for both neural network and XGBoost models.
Implemented a feedforward neural network with one hidden layer and ReLU activation.
Utilized Mean Squared Error (MSE) loss function for optimization.
Employed Adam optimizer with a specific learning rate.
Ran experiments to identify the optimal ensemble method.
Combined predictions from the neural network and XGBoost models using weighted averaging.
Results
The developed models achieved a competitive performance, ranking 4th in the Kaggle competition. Model evaluation was conducted using mean squared error (MSE) loss and R-squared score on a validation set, yielding promising results.

Feel free to explore the codebase, provide feedback, and contribute to further enhancements. 
