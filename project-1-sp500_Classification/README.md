# S&P 500 Classification with Different Methods  
(Logistic Regression, KNN, SVM, Gradient Boosting)

## Overview
This project aims to classify **S&P 500 stock movements** using various classification models.  
We analyze **historical macroeconomic data** and apply predictive modeling techniques to forecast market trends.

## Dataset
- **File:** [`LRM_final_project_backdata(v0.2)_20241210.xlsx`](./LRM_final_project_backdata(v0.2)_20241210.xlsx)
- **Features Used (Source):**
  - **S&P 500 prices & volume** *(Investing.com)*
  - **Macroeconomic Indicators:**
    - **CPI** *(US Bureau of Labor Statistics)*
    - **EFFR (Federal Reserve Rate)** *(Federal Reserve Bank of NY)*
    - **GDP (%)** *(Bureau of Economic Analysis)*
    - **Unemployment Rate** *(US Bureau of Labor Statistics)*
    - **WTI Crude Oil Price** *(US Energy Information Administration)*
    - **FX Rates (EUR & CNY)** *(Investing.com)*

---

## Methodology
1. **Data Preprocessing:**  
   - Cleaned and normalized macroeconomic variables.  
   - Built a classification model to predict **next month's S&P 500 movements** based on **previous month's macro data**.

2. **Feature Engineering:**  
   - Created relevant macroeconomic financial indicators.

3. **Modeling:**  
   - Applied multiple classification models:  
     ✅ **Logistic Regression**  
     ✅ **K-Nearest Neighbors (KNN)**  
     ✅ **Support Vector Machine (SVM)**  
     ✅ **Gradient Boosting**  

4. **Evaluation:**  
   - **Accuracy Score** was used to measure model performance.

## 🔍 Results
- **Achieved 69.7% accuracy** in predicting S&P 500 movements using only macroeconomic indicators.
- **Gradient Boosting performed the best**, outperforming Logistic Regression, KNN, and SVM.
- Below is a visualization of prediction vs actual market trends:
![image](https://github.com/user-attachments/assets/228518d1-9a25-45cc-8ad0-16cf562d5d97)

## Next Steps
- Test with **Random Forest & XGBoost** to compare performance.
- Improve **feature selection** for better accuracy.
- Deploy as a **web application** for real-time market predictions.

## 📂 Files in This Project
**Main Files:**  
- [`S&P500_Classification(v0.2).ipynb`](./S&P500_Classification(v0.2).ipynb) → Jupyter Notebook with data analysis & model training  
- [`LRM_final_project_backdata(v0.2)_20241210.xlsx`](./LRM_final_project_backdata(v0.2)_20241210.xlsx) → Raw dataset  
- [`Linear_Regression_Project.pdf`](./Linear_Regression_Project.pdf) → Final project report  


## 🏆 Author
👤 **Youngshin Park**  
📧 [Email Me](mailto:yp2691@gmail.com)  
🔗 [LinkedIn Profile](https://www.linkedin.com/in/youngshin-jordan-park/)  



