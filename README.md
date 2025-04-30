# Delivery Time Prediction Using Linear Regression

This project predicts delivery time using a linear regression model built with Python (scikit-learn). It includes data preprocessing, exploratory data analysis, feature selection, model building, and residual diagnostics.

## 📁 Project Structure
LR_Delivery_Time_Prediction_Prasoon_Kumar_Jha.zip
├── LR_Delivery_Time_Prediction_Prasoon_Kumar_Jha.ipynb   # Jupyter notebook with full code and analysis
├── LR_Delivery_Time_Prediction_Prasoon_Kumar_Jha.pdf     # Final project report

## 📌 Key Highlights

- **Data Cleaning & Filtering**
  - Removed features with weak correlation (|r| < 0.15)
  - Handled outliers using the IQR method

- **Feature Selection**
  - Used Recursive Feature Elimination (RFE) to choose the top 10 features

- **Model Performance**
  - R² (Training): ~0.86
  - R² (Testing): ~0.86

- **Tools Used**
  - Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

## 📊 Residual Analysis
- Visual diagnostics include:
  - Histogram of Residuals
  - Q-Q Plot
  - Residuals vs Predicted Plot

## 📄 Report
Detailed explanation of assumptions, methodology, model diagnostics, and performance metrics included in:
- `LR_Delivery_Time_Prediction_Prasoon_Kumar_Jha.pdf`

## 🙋‍♂️ Author
**Prasoon Kumar Jha**
