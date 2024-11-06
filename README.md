
# PetalPredict: Iris Flower Species Classifier
PetalPredict is a machine learning project focused on classifying iris flowers into species based on petal and sepal dimensions. This project uses Logistic Regression to distinguish between species, providing an accessible entry point to data-driven botanical classification.

# Project Overview

- Objective: Develop a machine learning model to classify iris flowers into species based on petal and sepal measurements.
- Dataset: The Iris dataset, containing 150 samples across three species (Setosa, Versicolor, Virginica) with four attributes: sepal length, sepal width, petal length, and petal width.

# Key Features

1. Data Preprocessing:
   - Loads and explores the Iris dataset.
   - Splits data into training and test sets using `train_test_split()`.

2. Model Selection and Training:
   - Uses Logistic Regression with `max_iter=1000` as the classification algorithm.
   - Trains the model using the `fit()` method.

3. Evaluation and Visualization:
   - Evaluates model accuracy using `accuracy_score()`.
   - Generates a classification report and visualizes decision boundaries with 2D scatter plots.


# Usage

1. Open `Iris_Flower_Classification_PROJECT.ipynb` in Jupyter Notebook.
2. Run cells to load data, preprocess, train the model, and visualize classification results.

# Results and Discussion

- Accuracy: The Logistic Regression model accurately classified the iris flower species.
- Future Improvements: Experimenting with alternative algorithms and hyperparameter tuning may enhance performance.
