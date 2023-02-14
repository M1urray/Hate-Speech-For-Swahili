# Hate Speech Detection

This project focuses on applying Machine Learning techniques to categorize a piece of text into three distinct categories, which are "hate speech", "offensive language" and "neither".

The predictive model is then deployed in a Web App, allowing users to enter any text they please in order to get a prediction about its category.

The app features an interpretation schema that aims to explain the given prediction applying the LIME method, that utilizes white box models in order to interpret decisions of black box models.

## To DO

- [x] Train one-vs-rest model (1 model for each label -> select the most probable prediction as the final one)
- [x] Apply above schema utilizing Logistic Regression with L2 regularization
