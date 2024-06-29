# Loan_default_prediction
## Introduction
This project aims to predict loan defaults using machine learning techniques. It leverages historical loan data to identify patterns and features that are indicative of default risk, allowing financial institutions to make better lending decisions.

## Project Structure
data/: Directory containing the dataset.
notebooks/: Jupyter notebooks used for data exploration and model development.
src/: Source code for data preprocessing, feature engineering, and model training.
models/: Trained machine learning models.
results/: Directory for storing evaluation results and plots.
README.md: This file.
requirements.txt: List of dependencies needed to run the project.
## Data
The dataset contains historical information on loans, including features such as:

Age
Gender
Income
Employment_Status
Location
Credit_Score
Debt_to_Income_Ratio
Existing_Loan_Balance
Loan_Status
Loan_Amount
Interest_Rate
Loan_Duration_Months
## Setup
Prerequisites
Ensure you have the following installed:

Python 3.8+
Jupyter Notebook
Git
## Installation
1. Clone the repository:
git clone https://github.com/yourusername/loan-default-prediction.git
cd loan-default-prediction
2. Create a virtual environment:
python3 -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
3. Install the required dependencies:
pip install -r requirements.txt
## Usage
## Data Preprocessing
Run the data preprocessing script to clean and prepare the data for modeling:
python src/preprocess_data.py
## Model Training
Train the machine learning models using the preprocessed data:
python src/train_model.py
## Conclusion
In this project, we developed a machine learning model to predict loan defaults. The goal was to use historical loan data to identify patterns and features indicative of default risk, thereby enabling financial institutions to make better-informed lending decisions.
