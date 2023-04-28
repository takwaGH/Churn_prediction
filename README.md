# Churn_prediction
Customer Churn is also known as customer attrition refers to customer or subscriber stop doing business with company or services. 
A business typically treats a person as churned once a specific amount of time has passed since the customers last interaction with the company or service.

Customer churn is one of the major and most important problem for large companies. Especially in Telecom industry customer will not hesitate to leave if they don’t find what they are looking for. Customer want competitive pricing, high quality service and value for money.
I will create a model which predicts if a customer is likely to churn using open source Telecom data and Python.
this project aims to predict if users will leave the telecom company or no based on historical data0 To do so we should identify which customer to churn 
and assignevery one some score with probability and then target them with high score of churning.

#Justification du choix de modèle
In general, supervised models follow can be represented with this formula

![formule](https://user-images.githubusercontent.com/123807794/235086111-44a4b6b2-dc78-4428-ac5a-6fed95ce801f.PNG)

Depending on what is the type of target variable, the supervised task can be regression or classification (binary or multiclass). Binary classification tasks can have negative (0) or positive (1) target values. The output of these models is the probability of xi belonging to the positive class.

Logistic regression is similar to linear regression because both models take into account the bias term and weighted sum of features. The difference between these models is that the output of linear regression is a real number, while logistic regression outputs a value between zero and one, applying the sigmoid function to the linear regression formula.

![C2](https://user-images.githubusercontent.com/123807794/235086715-cc855eee-be72-4207-9a65-88c3d96db62f.PNG)


In this way, the sigmoid function allows transforming a score into a probability.
We can illutraste our project by the image below:

![users](https://user-images.githubusercontent.com/123807794/235089343-512a21d5-a19f-4f93-84f5-9c6962e68bc1.PNG)
