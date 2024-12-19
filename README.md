# FIFA Player Stats Analysis and Prediction
Data from https://www.kaggle.com/datasets/bryanb/fifa-player-stats-database?resource=download

This project involves analyzing and predicting FIFA player stats using a dataset from Kaggle. The dataset contains various attributes of FIFA players, including their age, overall rating, potential, special skills, and more.

## Purpose
The purpose of this project is to build a machine learning model that can predict whether a player is 'Good' (Best Overall Rating >= 75) based on their attributes. This can help in identifying promising players and making informed decisions in team management and player scouting.

## Workflow
1. **Load Data**: Load the dataset into a pandas DataFrame.
2. **Preprocessing and Data Cleaning**: Handle missing values by filling them with the mean or dropping columns with too many missing values.
3. **Feature Selection**: Select relevant features for the machine learning model.
4. **Data Splitting**: Split the data into training and test sets.
5. **Feature Scaling**: Scale the features using StandardScaler.
6. **Model Building**: Build a logistic regression model to predict whether a player is 'Good' (Best Overall Rating >= 75).
7. **Model Training**: Train the model using the training data.
8. **Model Evaluation**: Evaluate the model using accuracy and F1 score metrics.

## Results
- **Accuracy**: 0.9869
- **F1 Score**: 0.9868

The project demonstrates the process of data cleaning, feature selection, model building, and evaluation using a real-world dataset. The high accuracy and F1 score indicate that the model performs well in predicting whether a player is 'Good' based on their attributes.
