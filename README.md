# EMPLOYEE-ATTRITION-FORECASTING-USING-MACHINE-LEARNING


### Project Overview

The Employee Attrition Prediction project aims to predict which employees are likely to leave an organization. By analyzing factors such as job satisfaction, compensation, career growth, and work-life balance, the project identifies key drivers of attrition. With these insights, companies can take proactive measures to improve retention, such as enhancing employee engagement, offering better benefits, or creating growth opportunities. Reducing turnover can cut costs related to recruitment, training, and lost productivity. Ultimately, this project helps businesses retain top talent, maintain a stable workforce, and boost overall productivity for long-term success.

### Data Source

The dataset used in this project is the IBM HR Analytics Employee Attrition & Performance dataset.
The dataset contains 35 variables and 1470 records.

### Tools

Jupyter Notebook

### Algorithms

Random Forest
<Br>
Logistic Regresion
<Br>
Support Vector Machine

### Steps

## Data Loading and Inspection

The HR dataset is loaded, which contains employee details like age, salary, and job satisfaction. We check for missing data and analyze the basic statistics to understand the dataset.

## Data Preprocessing

The target variable (Attrition) is separated from the features (e.g., age, salary). Categorical variables (like gender, department) are converted into numerical values using one-hot encoding. Features are scaled to ensure all inputs are on a similar scale for better model performance.

## Model Training

The dataset is split into training and testing sets. Three machine learning models are trained:
Logistic Regression: A simple model for binary classification (leave or stay).
Random Forest Classifier: A more complex model that uses decision trees.
Support Vector Machine (SVM): A model that tries to separate the data into two categories with an optimal boundary.

## Model Evaluation

Predictions are made on the test data, and accuracy is calculated.
Accuracy tells us how often the model is correct. The models show around 87-88% accuracy.
Recall (how well the model identifies employees who leave) is low for all models, meaning they often miss predicting employees likely to leave.

### Conclusion

The employee attrition prediction project, using machine learning and Python, was successfully completed. It used features from the IBM HR dataset, such as employee demographics and performance data, to predict the likelihood of attrition. This helps companies develop proactive retention strategies. In conclusion, the project demonstrates the effectiveness of using machine learning and data-driven insights to predict and reduce employee turnover. It highlights how data can guide HR decisions and improve employee retention.


