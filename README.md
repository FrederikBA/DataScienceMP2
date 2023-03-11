# DataScienceMP2

#### Which methods and algorithms have you applied and why?
In this assignment we were tasked to create two machine learning models:

1. The first model to predict the financial results of 2022 based on the financial results of 2021 and 2020.
    - For the first model we used Linear Regression to predict the financial results of 2022. Here we could simply see the development of financial results from 2020 to 2021 and apply the same development to 2022 so we get a prediction based on a linear connection.

2. The second model to predict the new location of a company in the 'small' category based on features such as financial results and number of employees
    - TestyMacTest

#### What challenges did you experience?

#### How accurate is your solution?

We got an accuracy score of 0.0 for the test set, which means that the model did not correctly predict any of the municipalities of the test companies based on their income and number of employees. This would suggests that the model is not performing well, but when we observe the predictions made by our model, we can see that it works as intended. As shown when using seed=2, the two companies with the highest income are used as our test set. Therefore, our model predicts that these companies belong to Ballerup, which now has the highest income in the training set.

#### What else needs to be done for improvement of the accuracy of the solution?

To create a more accurate model in the future, we would need a much larger dataset to train it on.
