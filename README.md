 Customer Churn Analysis

This project analyzes customer churn behavior in a telecom company using the **Telco Customer Churn Dataset**.

 Dataset

- Source: [Kaggle - Telco Customer Churn](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)
- Size: ~7k records

 Objective

To identify patterns behind customer churn using data visualization and build a basic churn prediction model.

 Tools & Libraries

- Python 🐍
- Pandas, NumPy
- Seaborn, Matplotlib
- Scikit-learn (Logistic Regression)

 Exploratory Data Analysis (EDA)

 Churn Distribution

![Churn Count](images/churn_pie.png)

 Churn by Contract Type

![Contract](images/churn_by_contract.png)

Correlation Heatmap

![Heatmap](images/correlation_heatmap.png)

 Machine Learning (Optional)

Used Logistic Regression to predict customer churn:
- Accuracy: 79%
- Key Factors: Contract type, Monthly Charges, Tenure

 Key Insights

- Month-to-month contract customers are more likely to churn.
- Customers with higher monthly charges and short tenure churn more often.
- One-year and two-year contracts reduce churn risk.

 How to Run

1. Open `churn_analysis.ipynb` in Google Colab or Jupyter Notebook
2. Upload the dataset from Kaggle
3. Run cells step-by-step to explore and train the model

 Author

Saloni Sangode • [@codewithsaloni0506](https://github.com/codewithsaloni0506)

---

 ⭐ Star this repo if you like it!
