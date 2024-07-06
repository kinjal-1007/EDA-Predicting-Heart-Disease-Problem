# Heart Disease Classification Project

This project aims to classify heart disease using various machine learning models.
The following models are used and their score is compared:

- Logistic Regression
- Random Forest Classifier
- K Nearest Neighbours
- CatBoost Classifier

The GridSearchCV Logistic Regression model achieves a maximum accuracy of 88.52%.
The CatBoost Classifer provides accuracy of 85.25%.

## Project Structure

- `data/`: Folder containing the dataset (CSV file)
- `heart-disease-classification.ipynb`: Jupyter notebook with the code
- `gs_logistic_regression_model_1.pkl`: Pickle file of the logistic regression model
- `requirements.txt`: File containing all dependencies

## Setup Instructions

1. Clone the repository:
   ```sh
   git clone https://github.com/kinjal-1007/EDA-Predicting-Heart-Disease-Problem.git
   cd EDA-Predicting-Heart-Disease-Problem

2. Create and activate the conda environment:
   ```sh
   conda create --name your-env-name python=3.8
   conda activate your-env-name

3. Install dependencies from requirements.txt:
   ```sh
   pip install -r requirements.txt

4. pip install -r requirements.txt:
   ```sh
   jupyter notebook heart-disease-classification.ipynb
