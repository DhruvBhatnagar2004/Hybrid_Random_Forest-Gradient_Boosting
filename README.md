# Hybrid Random Forest and Gradient Boosting Classifier with Comparative Analysis

This project implements a hybrid classifier that combines Random Forest and Gradient Boosting models to improve prediction quality using weighted voting. Additionally, it conducts a comparative analysis of four machine learning models to benchmark performance.

## Features
- **Hybrid Model**: Combines Random Forest and Gradient Boosting predictions using customizable weights.
- **Comparative Analysis**: Evaluates Logistic Regression, SVM, Random Forest, and Gradient Boosting models to identify strengths and weaknesses.
- **Cross-Validation**: Compares hybrid model performance with base models and other classifiers.
- **Feature Importance Analysis**: Identifies key features influencing model decisions.
- **Visualization**: Includes confusion matrices, cross-validation boxplots, feature importance bar charts, and accuracy comparisons.

## Key Files
- `Comparative_analysis.ipynb`: Contains the implementation of all the models and their visualization with the implementation of the `HybridForestBoostingClassifier` class which includesfunctions for training, evaluating, and comparing models. It determines how to use the hybrid classifier and conduct a comparative analysis on a sample dataset

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/your_username/hybrid-model.git
   cd hybrid-model
