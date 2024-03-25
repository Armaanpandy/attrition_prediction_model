# [Attrition Prediction Model](https://github.com/Armaanpandy/attrition_prediction_model/tree/main)

[Dataset Source](https://www.kaggle.com/datasets/mfaisalqureshi/hr-analytics-and-job-prediction)

**Overview of the Project:**
This project aims to analyze employee attrition within an organization and develop predictive models to identify factors contributing to employee turnover. By leveraging machine learning techniques, we seek to gain insights into the underlying causes of attrition and provide recommendations to mitigate its impact on organizational performance.

[ML Model Notebook](https://github.com/Armaanpandy/attrition_prediction_model/blob/main/attrition_predictor.ipynb)

*Note*: Dont run the model training section if you just want to look at results directly run the validation set sectiom

[Executive Summary](https://github.com/Armaanpandy/attrition_prediction_model/blob/main/Attrition%20Rate%20Model%20Executive%20Summary.pdf)

**Problem:**
Employee attrition poses significant challenges for organizations, leading to increased recruitment costs, loss of expertise, and reduced productivity. Identifying the factors driving attrition and implementing effective retention strategies are crucial for maintaining a stable and engaged workforce.

**Solution Suggested Using Machine Learning:**
Using machine learning algorithms such as Random Forest, logistic regression, and gradient boosting, we analyzed historical employee data to uncover patterns and relationships associated with attrition. By training predictive models on features such as satisfaction level, number of projects, and average monthly hours, we were able to accurately predict employee turnover and identify key factors contributing to attrition.

Through this approach, we gained valuable insights into the drivers of attrition and proposed data-driven recommendations to address the problem. These recommendations include monitoring employee satisfaction levels, balancing workload, reviewing compensation practices, and improving promotion processes. By implementing these solutions, organizations can proactively manage attrition and foster a positive work environment conducive to employee retention and organizational success.

## Results
**The Random Forest model achieved high performance metrics on the test set:**

- Accuracy: 98.21%
- Precision: 91.96%
- Recall: 97.08%
- F1 Score: 94.45%

**Insights from the model and data analysis include:**

- Satisfaction level was higher for employees who stayed, indicating its importance as a retention factor.
- Employees who left had higher numbers of projects and average monthly hours, suggesting potential overwork and dissatisfaction.
- Low salary types constituted 60% of employees who left, highlighting the importance of fair compensation.
- No attritions were observed for employees with a tenure of more than 6 years, indicating potential retention strategies for long-term employees.
- There was no significant correlation between promotion in the last 5 years and attrition, suggesting the need for a review of promotion practices.
- The correlation matrix provided insights into the relationships between various features, such as satisfaction level, last evaluation, number of projects, and attrition.

**Recommendations based on the model results include:**

- Monitoring employee satisfaction levels regularly to identify potential attrition risks.
- Balancing workload and work hours to prevent overwork and burnout.
- Reviewing salary structures and ensuring fair compensation practices.
- Assessing and improving promotion practices to enhance employee motivation and retention.
- Implementing strategies to support long-term employee retention and well-being.
- Conducting regular employee feedback mechanisms to address dissatisfaction and improve the work environment.

Overall, the model results provide valuable insights for strategic decision-making aimed at improving employee retention and satisfaction within the organization.
