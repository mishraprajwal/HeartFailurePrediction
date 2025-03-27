# Heart Failure Prediction

This project uses machine learning techniques to predict the likelihood of heart failure based on patient data. The analysis is presented as a Jupyter Notebook (`HeartFailurePrediction.ipynb`) that covers data exploration, feature engineering, model training, evaluation, and visualization.

## Project Overview

The objective of this project is to:

- Explore and preprocess a dataset containing patient health metrics.
- Analyze the relationships between different features and heart failure outcomes.
- Build and evaluate machine learning models (such as XGBoost) to predict heart failure risk.
- Visualize results and interpret model performance.

## Features

- **Data Exploration:** Detailed EDA to understand feature distributions and correlations.
- **Preprocessing:** Data cleaning and preparation steps to ready the dataset for modeling.
- **Modeling:** Implementation of classification models (e.g., XGBoost) with cross-validation.
- **Evaluation:** Model evaluation using metrics such as ROC-AUC, accuracy, and classification reports.
- **Visualization:** Graphical representation of model outputs and feature correlations using tools like Graphviz.

## Requirements

- Python 3.x
- Jupyter Notebook

### Python Libraries

Install the necessary packages using pip:

```bash
pip3 install pandas numpy matplotlib scikit-learn xgboost graphviz
```

```bash
brew install libomp
```

Clone the repository

```bash
git clone https://github.com/mishraprajwal/HeartFailurePrediction.git
```

cd to the directory

```bash
cd HeartFailurePrediction
```

launch jupyter notebook

```bash
jupyter notebook HeartFailurePrediction.ipynb
```