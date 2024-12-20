# Breast Cancer Prediction Streamlit App

This is a simple Streamlit application that predicts whether a breast cancer tumor is benign or malignant based on input data. The app uses a **Logistic Regression** machine learning model trained on the **Breast Cancer Wisconsin dataset** to classify tumors based on various features related to cell nuclei measurements.

## Features

- **Input Sliders**: The user can input different measurements related to cell nuclei via sliders.
- **Model Predictions**: The app predicts whether the tumor is benign or malignant based on the input features.
- **Visualization**: The app includes a radar chart that visualizes the input features and their relationship to benign and malignant tumor classification.

## Dataset

The dataset used for this project is the **Breast Cancer Wisconsin (Diagnostic) Data** available from Kaggle. You can download it from the following link:

- [Breast Cancer Wisconsin Data](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data)

This dataset contains various features related to cell nuclei measurements that help in predicting whether a breast cancer tumor is benign or malignant.

## Technologies Used

- **Streamlit**: For creating the web application interface.
- **Scikit-learn**: For creating and training the machine learning model (Logistic Regression).
- **Pandas**: For data manipulation and handling.
- **Plotly**: For generating the radar chart for feature visualization.
- **Pickle**: For saving and loading the trained model and scaler.

## Installation

To run this project locally, follow the steps below:

### 1. Clone the Repository

```bash
git clone https://github.com/Ayantanu2002/streamlit-cancer-predict.git
cd streamlit-cancer-predict
