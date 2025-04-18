Introduction

Problem Statement: Build a classification model to predict whether an employee is likely to leave the company based on features like job satisfaction, salary, work environment, and years of experience. The prediction can help companies focus their efforts on employee retention strategies.

Employee attrition poses a significant challenge for businesses, as it leads to higher recruitment costs and a loss of experienced talent. Predicting employee turnover can help organizations take proactive steps in retaining valuable employees, optimizing recruitment efforts, and improving overall workforce stability. This project aims to build a predictive machine learning model to identify employees who are at risk of leaving the company based on various factors, including job satisfaction, salary, work environment, and years of experience. By doing so, companies can implement targeted interventions to retain top talent and reduce attrition rates.

Methodology

The approach to solving this problem involves several key steps, as outlined below:

1.	Data Collection
The dataset used in this project contains various features that describe employee characteristics, including job satisfaction, monthly income, work environment satisfaction, and tenure with the company. This data was uploaded in CSV format and serves as the foundation for the predictive model.

2.	Data Preprocessing
o	Handling Irrelevant Features: Certain columns, such as 'EmployeeCount', 'EmployeeNumber', 'Over18', and 'StandardHours', were dropped from the dataset, as they were not relevant to predicting employee attrition.
o	Encoding Categorical Data: Categorical variables, including job roles and departments, were encoded into numerical values using LabelEncoder. This transformation enables the use of these variables in machine learning models.

3.	Feature Selection
Key features that are likely to influence employee attrition were selected for the model. These include:
o	Job satisfaction
o	Monthly income
o	Environment satisfaction
o	Work-life balance
o	Total working years
o	Years at the company
These features were chosen based on their relevance and potential impact on employee turnover.
4.	Model Selection and Training
A Random Forest Classifier was chosen due to its ability to handle both numerical and categorical data efficiently. Random Forests are robust, capable of capturing complex patterns, and provide reliable performance with minimal parameter tuning. The dataset was split into an 80% training set and a 20% testing set to train the model and evaluate its performance.

5.	Model Evaluation
o	The model's performance was assessed using several evaluation metrics:
	Accuracy: The percentage of correct predictions.
	Precision: The proportion of true positives among the predicted positives.
	Recall: The proportion of true positives among all actual positives.
o	Additionally, a confusion matrix was generated to visualize the model's performance, showing the number of true positives, true negatives, false positives, and false negatives.

OUTPUT -
![Screenshot 2025-04-18 145801](https://github.com/user-attachments/assets/afd99b71-cf28-4fd1-b526-4da4a418448b)

