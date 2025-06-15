# Real-Estate-House-Price-Prediction-MLP

This repository contains a machine learning project focused on predicting house prices in Paris. The project explores and compares the effectiveness of Linear Regression and Multi-layer Perceptron (MLP) models to determine the optimal approach for accurate real estate valuation.

## Project Goal

The primary goal of this project is to build and evaluate predictive models to accurately forecast house prices in Paris. The focus is on developing a robust model that can capture complex, non-linear relationships within the real estate data and generalize well to new market data, avoiding overfitting.

## Files Overview

* **`house_price_prediction_mlp.ipynb`**: This Jupyter notebook details the entire predictive modeling pipeline:
    * **Data Preprocessing**: Includes steps for loading, exploring, and preparing the house sales data, such as handling missing values, scaling numerical features, and dropping irrelevant columns.
    * **Predictive Modeling**: Implementation and training of both Linear Regression and several Multi-layer Perceptron (MLP) models with varying architectures.
    * **Experiments Report**: Comprehensive evaluation of each model's performance using metrics like Mean Absolute Error (MAE) and correlation, comparing training and testing errors to assess overfitting.
    * **Model Selection**: Identifies the "MLP 3" model (with 2 hidden layers: 80 and 120 nodes) as the best performer, citing its low MAE difference between training and testing, and high correlation.

## Dataset

This project utilizes a dataset of 10,000 house sales in Paris (`Part1_house_price.csv`). **Please note: This data file is not included in this repository.** The Jupyter notebook is configured to load this dataset from a Google Drive path (`/content/drive/MyDrive/Part1_house_price.csv`). To run the notebook, you will need to obtain this dataset and ensure it is accessible at the specified path or modify the notebook to load your own real estate data.

## Technologies Used

* Python
* Pandas (for data manipulation)
* NumPy (for numerical operations)
* Matplotlib (for data visualization)
* Scikit-learn (for data splitting, scaling, and metrics)
* TensorFlow/Keras (for building and training MLP models)

## Getting Started

To explore or run the analysis:

1.  Clone this repository.
2.  Ensure you have Python installed along with the necessary libraries (you can install them via `pip install pandas numpy matplotlib scikit-learn tensorflow`).
3.  **Provide the `Part1_house_price.csv` dataset**: You will need to obtain this dataset and ensure it is accessible to the notebook (e.g., by uploading it to your Google Drive at the path `/content/drive/MyDrive/Part1_house_price.csv` if using Google Colab, or placing it in an appropriate local directory and updating the notebook's file path).
4.  Open `house_price_prediction_mlp.ipynb` in a Jupyter environment (e.g., Jupyter Lab, VS Code with Jupyter extension, or Google Colab).
5.  Run the cells sequentially to execute the data loading, preprocessing, model training, and evaluation steps.

## Contact

For any questions or further information, please contact [Jeremiyah/jeremypeter016@gmail.com].
