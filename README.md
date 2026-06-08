# IN THE NAME OF ALLAH

# 🌦️ Weather Prediction using BOM Dataset

## Overview

This project focuses on weather prediction using the  BOM dataset. Two machine learning algorithms were implemented and evaluated:

* K-Nearest Neighbors (KNN)
* Decision Tree

## Model Comparison

Both models were trained and tested on the same dataset to compare their performance and prediction capabilities.

### K-Nearest Neighbors (KNN)

* Simple and effective classification algorithm.
* Requires calculating distances to training samples during prediction.
* Prediction time increases as the dataset grows.

### Decision Tree

* Fast prediction speed after training.
* Efficient for real-time inference and deployment scenarios.
* Easier to interpret and visualize compared to KNN.

## Results

Experimental results showed that the Decision Tree model achieved significantly faster prediction times than the KNN model. Due to its lower inference latency, the Decision Tree is a more suitable choice for real-time weather prediction applications.

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-Learn
* Matplotlib
* Jupyter Notebook


## Future Work

* Hyperparameter optimization
* Ensemble learning methods
* Model deployment with Flask/FastAPI
* Real-time weather prediction API
