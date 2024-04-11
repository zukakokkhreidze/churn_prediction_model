# Churn Prediction Model

## Project Overview
This repository hosts predictive models using the Telecom Churn Dataset, which features customer activity and churn labels. The dataset is divided into two segments: `churn-bigml-80.csv` for training (80% of the data) and `churn-bigml-20.csv` for testing (20%). The goal is to predict customer churn based on activity patterns.

## Dataset
The project uses two main files:
- `churn-bigml-80.csv`: Contains 80% of the customer data for training the models.
- `churn-bigml-20.csv`: Contains 20% of the customer data, used for testing the models.

## Prerequisites
Before running the notebook, ensure you have the following Python libraries installed:
- NumPy
- pandas
- Matplotlib
- seaborn
- SciPy
- scikit-learn
- XGBoost
- LightGBM
- CatBoost
- eli5


## Installation
1. **Clone the repository:**
   ```bash
   git clone https://github.com/zukakokkhreidze/churn_prediction_model.git

2. Install the required libraries:
   ```bash
   pip install numpy pandas matplotlib seaborn scipy scikit-learn xgboost lightgbm catboost eli5


## Usage
1. Open the terminal and navigate to the project directory.

2. Launch Jupyter Notebook:
   ```bash
   jupyter notebook

3. Open churn.ipynb and run the cells to see the analysis and model-building steps.
