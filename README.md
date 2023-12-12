# Disneyland Review Analysis

## Introduction
This project develops a Deep Neural Network (DNN) model to analyze reviews of Disneyland parks around the world and predict their sentiment. Using a dataset of 42,656 reviews, the model leverages both Multi-Layer Perceptron (MLP) and Bidirectional LSTM to understand and classify review sentiments.

## Features
- Analysis of 42,656 reviews from Disneyland parks (California, Paris, Hong Kong).
- Combination of MLP for categorical features and Bidirectional LSTM for text analysis.
- Focus on sentiment prediction, classifying reviews as positive or negative.

## Dataset
- 6 features: Year_Month, Reviewer_Location, Branch, and Review_Text.
- Target feature: Rating, indicating positive or negative sentiment.
- Addressing missing values and varied data types.

## Model Details
- MLP: Parses 'Year_Month', 'Reviewer_Location', 'Branch'.
- Bidirectional LSTM: Analyzes 'Review_Text'.
- Output concatenation and classification in the final layer.

## Installation
To set up the project environment:
git clone https://github.com/PatrizioAcquadro/Disneyland-Review-Analysis.git
cd Disneyland-Review-Analysis
pip install -r requirements.txt

## Usage
To run the analysis:
jupyter notebook Acquadro_502311_MLP_DL_Exam.ipynb


## Contributing
Contributions are welcome. Please send your pull requests to the 'develop' branch for review.

## Authors
- Acquadro Patrizio
