# Customer Churn Prediction

## Project Overview
A machine learning project to predict customer churn for a telecom company. The model achieves 80%+ accuracy and identifies key factors that drive customer attrition.

## Key Features
- **Data Cleaning & Preprocessing**: Handled missing values, encoded categorical variables
- **Exploratory Data Analysis**: Visualized churn patterns across different customer segments
- **Feature Engineering**: Created new features (tenure groups, service counts, average spend)
- **Model Building**: Implemented Logistic Regression and Random Forest
- **Model Evaluation**: Compared models using Accuracy, Precision, Recall, F1-Score, and AUC-ROC
- **Business Insights**: Identified top churn drivers and actionable recommendations

## Results
- **Best Model**: Logistic Regression
- **Accuracy**: 80%
- **Precision**: 64% 
- **Recall**: 56%
- **F1-Score**: 60%
- **AUC-ROC**: 84%

## Key Business Insights
- **Top Churn Drivers**: Contract type, tenure, internet service type, payment method
- **High-Risk Segments**: Month-to-month contracts, fiber optic users, customers with no tech support
- **Recommendations**: Target new customers with loyalty programs, offer contract incentives, improve support for fiber optic users

## Technologies Used
- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Scikit-learn (Logistic Regression, Random Forest, preprocessing)
- Google Colab
- Jupyter Notebook

## How to Use
1. Clone this repository
2. Open the notebook in Google Colab or Jupyter
3. Run all cells to see the analysis
4. Use the prediction function to test new customers

## Future Improvements
- Implement XGBoost and neural networks
- Add customer lifetime value analysis
- Create a web app for real-time predictions
- Deploy as API using Flask
