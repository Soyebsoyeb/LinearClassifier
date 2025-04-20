# Dog vs. Cat Classification System

A machine learning project comparing different evaluation approaches for a linear classifier using Ear Flappiness Index and Whisker Length.

## Notebook Structure

1. **Basic Training** [`Classification.ipynb`]
   - Implements logistic regression from scratch
   - Trains on complete dataset
   - Visualizes decision boundary

2. **Train-Test Split** [`Classification_Train_Test.ipynb`]
   - 80/20 split of dataset
   - Performance evaluation on unseen data
   - Confusion matrix visualization

3. **Cross-Validation** [`Classification_Train_Test_cross.ipynb`]
   - 5-fold cross-validation implementation
   - Learning curve analysis
   - Hyperparameter tuning

## Key Features

- Biological Metrics:
  - 🐶 Ear Flappiness Index
  - 🐱 Whisker Length 
- Three Evaluation Methods:
  - Simple training accuracy
  - Hold-out validation
  - k-Fold cross-validation
- **Visualizations**:
  - Decision boundaries
  - Learning curves
  - Error analysis

## Installation

# bash

git clone https://github.com/Soyebsoyeb/ML.git
pip install -r requirements.txt
jupyter lab  # or jupyter notebook
