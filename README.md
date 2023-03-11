# DataScienceMP2

#### Which methods and algorithms have you applied and why?
In this assignment we were tasked to create two machine learning models:

1. The first model was to predict the financial results of 2022 based on the financial results of 2021 and 2020.
    - For the first model we used Linear Regression to predict the financial results of 2022. Here we could simply see the development of financial results from 2020 to 2021 and apply the same development to 2022 so we get a prediction based on the linear connection.

2. The second model was to predict the new location of a company in the 'small' category based on features such as financial results and number of employees
    - For this approach we wanted to try classificaton. Instead of finding an exact location of each company based on latitudes and longitudes we decided to explore what municipality a potential new company would belong to based on its financial results and number of employees.
    - Therefore we added a new column 'municipality' to our company dataframe so we could use this in our model as y value.
    - Then we could apply classification based on the features: Income and Employees to predict the label 'municipality_code' to see which municipality the new company would be located in.

#### What challenges did you experience?
Initially we tried to use multiple linear regression to predict a set of coordinates (latitude, longitude) to find the location of a potential new company. The given dataset made ground for some challenges especially with y being a tuple of latitudes and longitudes made us go with a different approach.

#### How accurate is your solution?

We got an accuracy score of 0.0 for the test set, which means that the model did not correctly predict any of the municipalities of the test companies based on their income and number of employees. This would suggests that the model is not performing well, but when we observe the predictions made by our model, we can see that it works as intended. As shown when using seed=2, the two companies with the highest income are used as our test set. Therefore, our model predicts that these companies belong to Ballerup, which now has the highest income in the training set.

#### What else needs to be done for improvement of the accuracy of the solution?

To create a more accurate model in the future, we would need a much larger dataset to train it on.
