Welcome to "Employee Churn Analysis Project". This is the project which I was be able to build my own classification models for a variety of business settings.

Also I learned what is Employee Churn. How it was different from customer churn, Exploratory data analysis and visualization of employee churn dataset using matplotlib and seaborn, model building and evaluation using python scikit-learn package.

I was be able to implement classification techniques in Python. Using Scikit-Learn allowing to successfully make predictions with the Random Forest, Gradient Descent Boosting , KNN algorithms.

At the end of the project, I had the opportunity to deployed my model using Streamlit.

#Determines
In this project I have HR data of a company. A study is requested from me to predict which employee will churn by using this data.

The HR dataset has 14,999 samples. In the given dataset, I have two types of employee one who stayed and another who left the company.

I could describe 10 attributes in detail as:

satisfaction_level: It is employee satisfaction point, which ranges from 0-1.
last_evaluation: It is evaluated performance by the employer, which also ranges from 0-1.
number_projects: How many of projects assigned to an employee?
average_monthly_hours: How many hours in averega an employee worked in a month?
time_spent_company: time_spent_company means employee experience. The number of years spent by an employee in the company.
work_accident: Whether an employee has had a work accident or not.
promotion_last_5years: Whether an employee has had a promotion in the last 5 years or not.
Departments: Employee's working department/division.
Salary: Salary level of the employee such as low, medium and high.
left: Whether the employee has left the company or not.
First of all, to observe the structure of the data, outliers, missing values and features that affect the target variable, must use exploratory data analysis and data visualization techniques.

Then, must perform data pre-processing operations such as Scaling and Label Encoding to increase the accuracy score of Gradient Descent Based or Distance-Based algorithms. perform Cluster Analysis based on the information obtain during exploratory data analysis and data visualization processes.

The purpose of clustering analysis is to cluster data with similar characteristics. Use the K-means algorithm to make cluster analysis. However, must provide the K-means algorithm with information about the number of clusters it will make predictions. Also, the data is applied to the K-means algorithm must be scaled. In order to find the optimal number of clusters, use the Elbow method. Briefly, try to predict the set to which individuals are related by using K-means and evaluate the estimation results.

Once the data is ready to be applied to the model, must split the data into train and test. Then build a model to predict whether employees will churn or not. Train models with train set, test the success of model with test set.

Try to make predictions by using the algorithms Gradient Boosting Classifier, K Neighbors Classifier, Random Forest Classifier. Use the related modules of the scikit-learn library. Use scikit-learn Confusion Metrics module for accuracy calculation. Use the Yellowbrick module for model selection and visualization.

In the final step, deploy model using Streamlit tool.


#Tasks

1. Exploratory Data Analysis

2. Data Visualization

3. Data Pre-Processing

4. Cluster Analysis

5. Model Building

6. Model Deployement

