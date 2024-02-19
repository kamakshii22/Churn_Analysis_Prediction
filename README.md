<h1 align="center">
  Customer Churn Analysis and Predictive Modeling
</h1>
<div align="center">
  <h4>Aurthor: <a href="https://www.linkedin.com/in/kamakshisharma22">Kamakshi Sharma</a></h4>
</div>

## Overview:
Customer churn prediction is a critical challenge across various industries, including banking. Losing customers can lead to reduced revenue and market share, underscoring the need for accurate churn prediction to mitigate such losses. In this project, we aimed to predict customer churn in a banking dataset using machine learning techniques. Additionally, we developed a Power BI dashboard to further analyze churn prediction results and provide interactive visualizations for stakeholders.

## Problem Statement:
The project focuses on predicting whether a bank customer will continue with their account or close it (i.e., churn). The dataset contains information on bank customers, including attributes such as credit score, geography, gender, age, tenure, balance, and more.

## Dataset Description:
- 165,034 rows and 14 columns
- Attributes include demographics, account details, and churn status (Exited = 1 for churned, 0 for active)

## Machine Learning Task:
This project employs supervised learning, specifically a classification task, to predict customer churn. Three algorithms were utilized: Logistic Regression, Random Forest, and XGBoost. Each algorithm was evaluated with and without balancing techniques, including over-sampling and under-sampling.

## Methodology:
### Data Analysis:
- Exploratory Data Analysis (EDA) to understand data distribution and patterns
- Addressing class imbalance (more active customers than churned)
- Identifying factors influencing churn

### Data Preprocessing:
- Handling missing values and outliers
- Transforming categorical variables (using encoding)
- Standard scaling numerical features

### Model Building and Evaluation:
- Training and evaluating models with and without data balancing
- Metrics used: confusion matrices, precision, recall, F1-score, accuracy

## Outcome:
XGBoost with over-sampling (SMOTE) chosen for high recall and balanced performance.

## Power BI Dashboard Development:
In addition to the machine learning model development, we also created a Power BI dashboard to further analyze the churn prediction results and provide interactive visualizations for stakeholders.
<div align="center">
  <img src="https://github.com/kamakshii22/Churn_Analysis_Prediction/blob/main/Churn_Analysis_Dashboard_Ks.JPG" alt="Power BI Logo" >
</div>

### Churn Analysis: 
- The dashboard showcases churn rates across different demographic segments: age groups, genders, and residence locations.
- Utilizing DAX measures and calculations, interactive charts offer insights into how demographic factors influence customer churn.
- Users can dynamically explore churn trends and identify high-risk segments for targeted retention strategies.
- This analysis enhances understanding of customer behavior and informs data-driven decision-making to mitigate churn risks effectively.

### Key Insights from Power BI Dashboard:
- The churn rate for credit card customers is 21.16%.
- There is a positive correlation between the number of products a customer has and their churn rate.
- Customers with a poor credit score are much more likely to churn than customers with an average credit score.
- Active customers are less likely to churn than inactive customers.

### Utilization of Power BI for Business Insights:
By leveraging Power BI, stakeholders can gain actionable insights from the churn prediction model's outputs. The interactive nature of the dashboard facilitates exploration of data trends, identification of churn drivers, and formulation of targeted retention strategies.

### Integration with Machine Learning Model:
The Power BI dashboard seamlessly integrates with the machine learning model's predictions, enabling real-time monitoring of churn prediction performance and the effectiveness of retention initiatives. This integration enhances decision-making capabilities and empowers businesses to proactively address customer churn.

## GitHub Files:
- [Power BI Dashboard File](https://github.com/kamakshii22/Churn_Analysis_Prediction/blob/main/Churn_Analysis_ks.pbix)
- [Jupyter Notebook (IPYNB)](https://github.com/kamakshii22/Churn_Analysis_Prediction/blob/main/Project_Bank_Churn_Prediction.ipynb)
- [Presentation (PPT)](https://github.com/kamakshii22/Churn_Analysis_Prediction/blob/main/PPT_Kamakshi.pptx)

## Conclusion:
The combination of machine learning models for churn prediction and Power BI dashboards for interactive analysis constitutes a powerful approach for addressing customer churn challenges in the banking sector. By leveraging these tools, organizations can gain deeper insights into customer behavior, enhance decision-making processes, and ultimately improve customer retention strategies.
