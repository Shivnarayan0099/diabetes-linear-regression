# Diabetes Prediction using Linear Regression
This project uses the Diabetes dataset from Scikit-Learn to train a Linear Regression model that predicts disease progression.
## Steps Done
- Loaded Diabetes dataset
- Performed EDA (info, describe, correlation)
- Split data into Train/Test
- Trained Linear Regression model
- Calculated R2 Score & MSE
- Plotted Actual vs Predicted
## How to Run
1. Install dependencies:
   pip install -r requirements.txt
2. Open notebook:
   jupyter notebook
3. Run notebook cells step-by-step.
## Model Performance
**R² Score:** ~0.45  
(Model explains about 45% of the variance — typical for this dataset)

- **Mean Squared Error (MSE):** ~2900  
(Dataset has high variance, so MSE remains high)
