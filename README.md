- E-Commerce Customer Churn Analysis 📊

This project analyzes customer churn in an e-commerce platform using Python. The goal is to understand the reasons behind customer departures and provide recommendations to improve retention.

- Overview
Customer churn is a major challenge in e-commerce, affecting profitability and growth. By analyzing churn data, we can identify trends and take actions to retain customers.

Dataset
- Source: Kaggle, titled "E-commerce Customer Churn Analysis"
- Contains customer demographics, subscription details, spending, and churn status.

- Analysis Steps

1. Data Loading
   - Loaded CSV data into Python using Pandas.
   
2. Data Cleaning
   - Checked for missing values using `.isnull().sum()`.
   - Dropped rows with missing values in the target column `Churn`.
   - Checked for duplicates using `.duplicated().sum()` and removed if any.

3. Exploratory Data Analysis (EDA)
   - Subscription duration ranged from 3–36 months.
   - Gender distribution: 4 males, 3 females.
   - Churned: 4, Retained: 3.
   - Churned customers spent less than 300 SAR.
   - Total spending ranged 90–2000 SAR.
   - Average spending: 520 SAR.
   - Average spending of retained customers: 1000 SAR.
   - Average spending of churned customers: 160 SAR.

4. Data Visualization
   - Created charts to visualize distributions and relationships between variables.

- Insights
- Churned customers spent significantly less than retained ones.
- Short subscriptions (3–8 months) were linked to higher churn.
- Females formed the majority among churned customers.
- Higher spending correlated with retention.
- No significant differences in subscription duration between genders.

- Recommendations
- Regularly check data quality to prevent missing or duplicate entries.
- Periodically analyze customer behavior for early churn prediction.
- Improve user experience with an intuitive interface and responsive support.
- Implement alerts for customers at risk of churn using predictive models.
- Convert customer feedback into actionable improvement plans.


- Link
[View Full Analysis on Google Colab](https://colab.research.google.com/drive/1TpWIIdeEgK8TDKp0XvH7uAFJ0ioYR9g6?usp=sharing)


 Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
