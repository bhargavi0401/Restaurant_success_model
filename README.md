# Restaurant Closure Prediction Model

## Project Description

The goal of this project was to build a predictive model that can determine whether a restaurant is likely to close within a 4-year period. The model aims to provide valuable insights for restaurant lenders (such as banks) and investors, helping them make informed decisions based on the predicted likelihood of closure.

## Table of Contents

- [Overview](#overview)
- [Data](#data)
- [Methodology](#methodology)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Overview

In the dynamic and competitive restaurant industry, understanding the factors that contribute to the likelihood of closure is crucial for making strategic decisions. This predictive model leverages machine learning algorithms to analyze relevant features and predict the probability of a restaurant closing within the next 4 years.

## Data

The model utilizes a dataset containing information about various restaurants, including features such as business metrics, location, and other relevant factors. The dataset was preprocessed to handle missing values, encode categorical variables, and prepare the data for training the machine learning models.

## Methodology

The project employs several machine learning classifiers, including Logistic Regression, Gaussian Naive Bayes, Decision Tree, Gradient Boosting, and Random Forest. The models were trained on a carefully split dataset, and their performance was evaluated using metrics such as accuracy, precision, recall, and F1 score.

## Usage

To use the predictive model, follow these steps:

1. [Install dependencies](#dependencies): Ensure that the required libraries and packages are installed.
2. [Data Preparation](#data-preparation): Prepare your dataset in a format suitable for input into the trained model.
3. [Model Inference](#model-inference): Use the provided scripts or APIs to obtain predictions for restaurant closure likelihood.

## Results

The model's performance on the test dataset and its ability to predict restaurant closures are summarized in the results section. The ROC curves provide insights into the trade-off between true positive and false positive rates for each classifier.

## Contributing

If you'd like to contribute to the project, please follow the guidelines outlined in the [CONTRIBUTING.md](CONTRIBUTING.md) file.

## License

This project is licensed under the [MIT License](LICENSE).

