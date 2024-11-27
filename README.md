# Hybrid Random Forest and Gradient Boosting Classifier

This project implements a hybrid classifier that combines Random Forest and Gradient Boosting models to improve prediction quality using weighted voting. The hybrid approach is designed for binary classification tasks, particularly for datasets with imbalanced class distributions.

## Features
- **Hybrid Model**: Combines Random Forest and Gradient Boosting predictions using customizable weights.
- **Cross-Validation**: Compares hybrid model performance with base models (Random Forest and Gradient Boosting).
- **Feature Importance Analysis**: Identifies key features influencing model decisions.
- **Visualization**: Includes confusion matrices, cross-validation boxplots, and feature importance bar charts.

## Key Files
- `hybrid_classifier.py`: Contains the implementation of the `HybridForestBoostingClassifier` class.
- `model_evaluation.py`: Includes functions for model training, evaluation, and visualization.
- `example_usage.py`: Demonstrates how to use the hybrid classifier on a sample dataset.

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/your_username/hybrid-model.git
   cd hybrid-model
