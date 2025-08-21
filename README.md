#Forest Cover Type Classification
##Overview

Built a Random Forest Classifier on the UCI Forest Cover Type dataset to predict forest cover classes based on cartographic features (elevation, slope, aspect, soil type, etc.).

Accuracy: 95%

Classes: 7 types of forest cover

#Dataset Size: ~581k rows, 54 features

Key Steps

Cleaned dataset (duplicates, low variance features)

Performed EDA (feature distributions, target imbalance analysis)

Trained Random Forest

Evaluated using classification report, confusion matrix, and feature importance

#Results

Accuracy: 95%

Strong performance across all 7 classes

Top features: Elevation, Horizontal Distance to Hydrology, and Soil Type indicators

#Visuals

Confusion Matrix (per-class accuracy)

Feature Importance Plot

Cover Type distribution

#Future Improvements

Hyperparameter tuning (GridSearchCV)

Experiment with XGBoost/LightGBM

Deployment using Streamlit
