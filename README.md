#Building a Logistic Regression Model to Predict Wine Quality

**Author: Darren Bansil**

**Date: June 19th, 2023**

We will be building our own logistic regression model from scratch. Logistic regression takes a set of independent variables and makes a prediction on an event happening or not. This makes it a great model for binary classification which is what we will be doing today. Our model will train on a variety of wine attributes and make a prediction on if the wine is of good quality or not.

**Dataset**

We will be working with a dataset on Portuguese "Vinho Verde" red wine pulled from UC Irvine Machine Learning Repository. The dataset can be found [here](https://doi.org/10.24432/C56S3T).



Input variables (based on physicochemical tests):
1. fixed acidity
2. volatile acidity
3. citric acid
4. residual sugar
5. chlorides
6. free sulfur dioxide
7. total sulfur dioxide
8. density
9. pH
10. sulphates
11. alcohol

Output variable (based on sensory data): 
12. quality (score between 0 and 10)
