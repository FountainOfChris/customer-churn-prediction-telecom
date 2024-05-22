# Assessing Customer Churn Using Machine Learning

## Project Description

Dive into India's telecom sector to analyze customer churn. Utilize pandas and machine learning to study datasets from top telecom firms, revealing demographic and usage patterns. Predict customer retention, merging data analysis and predictive modeling to sharpen your data science expertise.

## Table of Contents

- [Project Description](#project-description)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Dataset](#dataset)
- [Data Preparation](#data-preparation)
- [Model Building](#model-building)
- [Model Training](#model-training)
- [Model Evaluation](#model-evaluation)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Prerequisites

Before starting, ensure you have the following:

- Basic understanding of Python programming and machine learning libraries (e.g., pandas, scikit-learn).
- Familiarity with data preprocessing and classification tasks.

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/yourusername/customer-churn-prediction-telecom.git
    cd customer-churn-prediction-telecom
    ```

2. Create a virtual environment and activate it:

    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. Install the required packages:

    ```bash
    pip install -r requirements.txt
    ```

## Dataset

The dataset used for this project contains demographic and usage information of customers from four major telecom partners: Airtel, Reliance Jio, Vodafone, and BSNL. The datasets include:

- `telecom_demographics.csv`: Contains customer demographic information.
- `telecom_usage.csv`: Contains customer usage patterns.

## Data Preparation

1. **Load Data:** Load the datasets using pandas.
2. **Merge Data:** Merge the demographic and usage datasets on `customer_id`.
3. **One-Hot Encoding:** Apply one-hot encoding to categorical variables.
4. **Feature Scaling:** Scale numerical features using `StandardScaler`.
5. **Data Splitting:** Split the data into training and testing sets using `train_test_split`.

## Model Building

1. **Define Models:** Define `LogisticRegression` and `RandomForestClassifier` models.
2. **Training:** Train the models on the training data.
3. **Prediction:** Predict customer churn on the test data.

## Model Training

1. **Train Logistic Regression:** Train the `LogisticRegression` model.
2. **Train Random Forest:** Train the `RandomForestClassifier` model.

## Model Evaluation

1. **Evaluation Metrics:** Evaluate the models using `classification_report` and `confusion_matrix`.
2. **Compare Models:** Compare the accuracy of the `LogisticRegression` and `RandomForestClassifier` models.

## Usage

To use the trained models for predicting customer churn, follow the instructions provided in the notebook `customer_churn_prediction_notebook.ipynb`.

1. **Load Model:** Load the trained models.
2. **Input Data:** Provide new customer data as input to the models.
3. **Predict Churn:** Generate predictions for customer churn.

## Results

Document the results of your models, including the evaluation metrics and any visualizations that help interpret the models' performance.

## Contributing

Contributions are welcome! Please fork the repository and use a feature branch. Pull requests are reviewed on a regular basis.

## License

This project is licensed under the MIT License. See the LICENSE file for more details.
