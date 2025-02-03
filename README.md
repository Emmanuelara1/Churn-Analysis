# Churn-Analysis
Customer Churn Analysis
This project focuses on analyzing customer churn in an e-commerce environment. The goal is to understand customer behavior, identify characteristics of churned customers, and provide actionable insights for reducing churn. The project leverages data analysis, machine learning models, and visualizations to help businesses understand the factors influencing churn and devise strategies to retain valuable customers.

Table of Contents
Project Overview
Dataset
Data Analysis
Modeling
Model Evaluation
Key Insights
Recommendations
Installation
Usage
License
Project Overview
Customer churn refers to the percentage of customers who discontinue their service or subscription within a given time frame. High churn rates can significantly impact business growth and profitability, making it crucial for companies to understand the causes of churn and develop strategies to retain customers.

This project explores the factors contributing to churn and builds predictive models using Logistic Regression and Decision Trees. Additionally, visualizations such as churn distribution and correlation heatmaps are generated to provide insights into customer behavior.

Dataset
The dataset used for this analysis includes various customer features, such as:

Tenure
Satisfaction Score
Order Count
Preferred Login Device
Order Amount Hike from last year
Marital Status
Gender
Payment Mode
Day Since Last Order
And more...
The dataset contains both numerical and categorical features, and some columns contain missing values that were handled during the data cleaning process.

Data Analysis
Exploratory Data Analysis (EDA)
In the EDA phase, we:

Cleaned the data to handle missing values and outliers.
Explored the relationships between features using correlation analysis.
Visualized customer churn distribution and key feature distributions.
Key Features
Satisfaction Score: Higher satisfaction scores are linked to lower churn rates.
Order Count: Customers with higher order counts are less likely to churn.
Tenure: Longer customer tenure correlates with lower churn rates.
Modeling
Logistic Regression
We trained a Logistic Regression model to predict churn based on customer features. Logistic Regression is a binary classification algorithm that is suitable for predicting whether a customer will churn or not.

Decision Tree
A Decision Tree model was also implemented, which helps in understanding how decisions are made at each node based on different feature values (e.g., Order Count and Satisfaction Score).

Model Evaluation
The performance of the models was evaluated using:

Accuracy: The proportion of correct predictions.
Confusion Matrix: To assess how well the models are predicting churn vs non-churn customers.
Precision and Recall: To understand the models' ability to identify churned customers accurately.
Confusion matrix and other evaluation metrics can be visualized in the PowerPoint presentation generated in this project.

Key Insights
Satisfaction Score and Order Count are the most significant features influencing customer churn.
Customers with low satisfaction and fewer orders tend to churn more.
Logistic Regression and Decision Tree models performed well in predicting churn.
Recommendations
Targeted Retention Strategies: Use predictive models to identify high-risk customers and implement retention strategies such as personalized offers or loyalty programs.
Data Quality Improvement: Further clean the data and handle missing values to improve model accuracy.
Customer Segmentation: Use the models to segment customers based on churn risk and design specific retention plans for each group.
Installation
To run this project locally, follow these steps:

Clone the repository:
bash
Copy
git clone https://github.com/yourusername/customer-churn-analysis.git
Navigate to the project directory:
bash
Copy
cd customer-churn-analysis
Install the required dependencies:
bash
Copy
pip install -r requirements.txt
Usage
Run the data cleaning and analysis script:

bash
Copy
python churn_analysis.py
The results will be saved as output files and charts in the project directory.

The PowerPoint presentation will be generated automatically with visualizations and insights based on the churn analysis.

License
