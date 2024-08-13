# Weather_Prediction_Model


This repository contains a Jupyter Notebook for a weather prediction model that uses machine learning techniques to predict weather conditions based on historical data. The model is built using Python's scikit-learn library and is trained on the seattle-weather.csv dataset.
Features

    Data Preprocessing: The dataset is preprocessed using techniques like quantile transformation to prepare it for modeling.
    Model Training: The model is built using a RandomForestClassifier, a robust ensemble learning method.
    Hyperparameter Tuning: Grid Search Cross-Validation (GridSearchCV) is utilized to optimize model parameters for better accuracy.
    Model Evaluation: The performance of the model is assessed using a detailed classification report.

Installation

To run this notebook, you need to have Python installed along with the following packages:

    pandas
    scikit-learn
    matplotlib

You can install these dependencies using pip:

bash

pip install pandas scikit-learn matplotlib

Usage

Clone the repository:

    git clone https://github.com/Kaushik-Space/weather_prediction_model.git

Navigate to the repository directory:


    cd weather-prediction-model

Run the Jupyter Notebook:


    jupyter notebook weather_model.ipynb

Dataset

The model uses the seattle-weather.csv dataset, which contains historical weather data. Ensure that this dataset is in the same directory as the notebook or provide the correct path in the data loading cell.
Model Description

The model is a Random Forest Classifier, which is an ensemble method that constructs multiple decision trees and merges them to get a more accurate and stable prediction.
Hyperparameters Tuned

    max_depth: Controls the depth of the tree.
    min_samples_split: The minimum number of samples required to split an internal node.
    min_samples_leaf: The minimum number of samples required to be at a leaf node.
    n_estimators: The number of trees in the forest.

Evaluation

The model's performance is evaluated using a classification report, which provides metrics such as precision, recall, and F1-score.
Contributing

Contributions are welcome! Please feel free to submit a Pull Request or open an Issue if you have any suggestions or improvements.
