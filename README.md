# Parkinson's Disease Severity Predictor

**Project Overview:** A machine learning model built using Random Forest Regressor to predict Motor UPDRS and Total UPDRS scores to determine the severity of Parkinson's Disease in a person.

**Dataset:** https://www.kaggle.com/datasets/thedevastator/unlocking-clues-to-parkinson-s-disease-progressi (Contains 5874 instances and 23 features)

**Features Used:** age, sex, jitter(%), jitter(abs), shimmer, shimmer(dB), NHR, HNR, RPDE, DFA, etc.

**Tech Stack:**
- **Python**
- **Scikit-learn**
- **Pandas**
- **NumPy**
- **Seaborn**
- **Matplotlib**

**Model:**
- Algorithm: Random Forest Regressor
- Evaluation Metrics:
  - **Mean Squared Error (MSE)**
  - **Mean Absolute Error (MAE)**
  - **Root Mean Squared Error (RMSE)**
  - **R² Score**
 
**Results:**
- **Model Evaluation - Motor UPDRS**
    - Mean Absolute Error (MAE): 0.5699
    - Mean Squared Error (MSE): 1.6516
    - Root Mean Squared Error (RMSE): 1.2852
    - R² Score: 0.9741
- **Model Evaluation - Total UPDRS**
    - Mean Absolute Error (MAE): 0.6791
    - Mean Squared Error (MSE): 2.4926
    - Root Mean Squared Error (RMSE): 1.5788
    - R² Score: 0.9775
