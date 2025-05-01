# **Restaurant Data Analysis and Visualization**

---

## Overview

This project involves analyzing restaurant datasets using various machine learning and visualization techniques. The tasks focus on predicting restaurant ratings, identifying key features, user preference analysis, model optimization, and visualizing restaurant data geographically and statistically.

---

## Table of Contents

1. [Dataset Description](#dataset-description)
2. [Tasks Overview](#tasks-overview)
   - [Task 1: Feature Importance with Decision Tree Regressor](#task-1-feature-importance-with-decision-tree-regressor)
   - [Task 2: Predict Ratings Based on Cuisine Preferences](#task-2-predict-ratings-based-on-cuisine-preferences)
   - [Task 3: Logistic Regression with Hyperparameter Tuning](#task-3-logistic-regression-with-hyperparameter-tuning)
   - [Task 4: Geographic Visualization of Restaurant Data](#task-4-geographic-visualization-of-restaurant-data)
3. [Requirements](#requirements)
4. [How to Run](#how-to-run)
5. [Results and Insights](#results-and-insights)
6. [Future Enhancements](#future-enhancements)

---

## Dataset Description

The dataset contains restaurant-related information, including:

- **Restaurant Name**
- **Cuisines**
- **City**
- **Locality**
- **Latitude**
- **Longitude**
- **Aggregate Rating**

---

## Tasks Overview

### Task 1: Feature Importance with Decision Tree Regressor

- **Objective**: Identify the most influential features impacting restaurant ratings.
- **Steps**:
  1. Load the dataset and identify non-numeric columns.
  2. Perform one-hot encoding for categorical features.
  3. Train a Decision Tree Regressor to predict the `Aggregate rating`.
  4. Calculate feature importance and identify the most influential features.
- **Output**:
  - Feature importance ranking.
  - Performance metrics: Mean Squared Error (MSE) and R-squared (R²).

---

### Task 2: Predict Ratings Based on Cuisine Preferences

- **Objective**: Predict restaurant ratings based on user-provided cuisine preferences.
- **Steps**:
  1. Encode cuisine types using `LabelEncoder`.
  2. Train a Decision Tree Regressor with cuisine data.
  3. Predict ratings for specific cuisine preferences.
- **Output**:
  - Predicted rating for user preferences.
  - Model performance metrics: MSE and R².

---

### Task 3: Logistic Regression with Hyperparameter Tuning

- **Objective**: Optimize a Logistic Regression model to predict binary outcomes.
- **Steps**:
  1. Generate synthetic data with random features and labels.
  2. Perform hyperparameter tuning using `GridSearchCV`.
  3. Evaluate the model using metrics like accuracy, precision, recall, F1 score, and confusion matrix.
- **Output**:
  - Best hyperparameters.
  - Evaluation metrics and confusion matrix.

---

### Task 4: Geographic Visualization of Restaurant Data

- **Objective**: Visualize restaurant distribution and ratings using interactive maps and plots.
- **Steps**:
  1. Create a Folium map to visualize restaurant locations.
  2. Display popups with restaurant details.
  3. Analyze and visualize restaurant count and average ratings by city using Seaborn and Matplotlib.
- **Output**:
  - Interactive HTML map (`restaurant_map.html`).
  - Box plot of rating distribution by city.

---

## Requirements

- Python 3.x
- Libraries:
  - `pandas`
  - `scikit-learn`
  - `numpy`
  - `folium`
  - `seaborn`
  - `matplotlib`

---

## How to Run

1. Install required libraries using:
   ```bash
   pip install pandas scikit-learn numpy folium seaborn matplotlib  
   ```
2. Run each task script sequentially for analysis and visualization.
3. For Task 4, open the generated `restaurant_map.html` file in a web browser to view the interactive map.

---

## Results and Insights

- **Task 1**: Identified top features influencing ratings.
- **Task 2**: Predicted restaurant ratings based on user preferences.
- **Task 3**: Optimized Logistic Regression for classification with high accuracy.
- **Task 4**: Visualized restaurant locations, ratings, and distribution by city.

---

## Future Enhancements

1. Extend analysis to include advanced models like Random Forest and Gradient Boosting.
2. Incorporate user feedback and reviews into the dataset for sentiment analysis.
3. Enhance visualization with dynamic graphs and filters.
4. Automate the preprocessing pipeline for scalability.

---

**Author**: Yogesh G
Feel free to reach out for collaboration or queries!

