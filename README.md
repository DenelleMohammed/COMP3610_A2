# COMP3610 Assignment 2 – Taxi Tip Prediction

Author: Denelle Mohammed  
Course: COMP3610  
Assignment: Assignment 2

## Project Overview
This project applies machine learning techniques to analyze NYC taxi trip data and predict tipping behavior. Two predictive tasks are addressed:

1. **Regression Task** – Predict the tip amount for a taxi trip.
2. **Classification Task** – Predict whether the tip exceeds 20% of the fare.

The project implements multiple machine learning models and compares their performance using appropriate evaluation metrics.

---

## Models Implemented

### Regression Models
- Linear Regression
- Random Forest Regressor

### Classification Models
- Logistic Regression
- Random Forest Classifier
- Neural Network (PyTorch)

---

## Methodology

The project follows a typical machine learning workflow:

1. **Data preprocessing and cleaning**
2. **Feature engineering**
3. **Train / validation / test split**
4. **Model training**
5. **Hyperparameter tuning using RandomizedSearchCV**
6. **Neural network training using PyTorch**
7. **Model evaluation and comparison**
8. **Feature importance and coefficient interpretation**

---

## Evaluation Metrics

### Regression Metrics
- MAE (Mean Absolute Error)
- RMSE (Root Mean Squared Error)
- R² Score

### Classification Metrics
- Accuracy
- Precision
- Recall
- F1-score
- AUC-ROC

---

## Key Findings

- Random Forest models generally performed slightly better than linear models.
- The neural network achieved comparable performance but did not significantly outperform traditional machine learning models.
- Fare-related features (especially `fare_amount`) were the strongest predictors of tip amount.
- Trip characteristics and location variables also contributed to tipping behavior.

---

## Repository Structure

COMP3610-Assignment2
│
├── assignment2.ipynb # Main notebook containing all analysis and models
├── README.md # Project description
├── requirements.txt # Python dependencies
└── .gitignore # Files ignored by Git

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- PyTorch
- Matplotlib
- Seaborn

---

# Setup Instructions

**## 1. Clone the repository**

```bash
git clone https://github.com/YOUR_USERNAME/COMP3610-Assignment2.git
cd COMP3610-Assignment2

**## 2. Create a virtual environment (recommended)**
python -m venv venv

Activate the environment:

Mac/Linux
source venv/bin/activate
Windows
venv\Scripts\activate

**## 3. Install dependencies**

Install all required Python packages:

pip install -r requirements.txt

**## 4. Running the Notebook**
1. Start Jupyter Notebook:

jupyter notebook

2. Then open:

assignment2.ipynb

3. Run the notebook from top to bottom to reproduce the results.
