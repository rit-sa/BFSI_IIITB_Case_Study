# BFSI_IIITB_Case_Study


**Business Understanding**

CredX is a leading credit card provider that gets thousands of credit card applications every year. But in the past few years, it has experienced an increase in credit loss. The CEO believes that the best strategy to mitigate credit risk is to acquire the right customers.

In this project, your task is to help CredX identify the right customers using predictive models. Using past data of the bank&#39;s applicants, you need to determine the factors affecting credit risk, create strategies to mitigate the acquisition risk and assess the financial benefit of your project


**Understanding the Data**

There are two data sets in this project: demographic and credit bureau data.

Demographic/application data: This is obtained from the information provided by the applicants at the time of credit card application. It contains customer-level information on age, gender, income, marital status, etc.

Credit bureau: This is taken from the credit bureau and contains variables such as &#39;number of times 30 DPD or worse in last 3/6/12 months&#39;, &#39;outstanding balance&#39;, &#39;number of trades&#39;, etc.


**Data Cleaning and Preparation**

Create a master file with all the relevant variables and perform the necessary data quality checks and cleaning. In credit risk analytics, the weight of evidence (WOE) (and, equivalently, information value analysis) is often used to identify the important variables. Apart from assessing variable importance, WOE is also used to impute missing values from the data. You&#39;ll note that some variables contain a significant number of missing values. Replace the actual values of all the variables by the corresponding WOE value and store the data in a separate file (e.g. woe\_data) for further analysis.

You can read about WOE and information value analysis from the links provided in the additional resources section.


**Model-Building**

The two types of models you need to build are as follows:

Demographic data model: Build a model to predict the likelihood of default using only the demographic data. This will give you a good idea about the predictive power of the application data. Obviously, the final model will use the credit bureau data as well, though this model is an important part of understanding the predictive power of application data.

Model using both demographic and credit bureau data: Build a model to predict default using both the data sets. You may choose any type of model, though it is recommended to start with a logistic regression model first. Further, you can choose any type of model.


**Model Evaluation**

Evaluate the models using relevant metrics and report the results. As part of model validation, predict the likelihood of default for the rejected candidates and assess whether the results correspond to your expectations.


**Assessing the Financial Benefit of your Project**

- The implications of using the model for auto-approval or rejection, i.e., how many applicants on an average would the model automatically approve or reject
- The potential credit loss avoided with the help of the model
- Assumptions based on which the model was built
