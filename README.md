# car_evaluation

The dataset consists of 6 features and one class label column.

Each feature is a categorical variable. It is a multiclass classification problem.

There are 1728 datapoints, so it is a fairly small dataset. It is good enough for practice of wide variety of skills like data manipulation to convert categorical data into numerical values, data visualization to understand the relationship of each feature with the dependent variable and data modelling to understand which algorithm suits best to the data.

I have done extensive data analysis by using basic statistical techniques and plotting the same using matplotlib Bar plots.

I have used functional programming technique wherein I have created a generic function to do the repetitive task. This improves the code readability and makes the code clean and easy to understand apart from saving a lot of time.

I have used TSNE plot to  understand the distribution of data in high dimensional space. The data is well separable, therefore, easy to work with.

Scikit learn's inbuilt function of train_test_split has been used to split the date in 70:30 ratio.

We need large amount of data to use cross validation data to find the optimal hyperparameter. As this problem is very simple(in terms of separability of the data) and the dataset is very small, therefore, I didn't used cross validation data to select optimal hyperparameter. Instead I used GridSearchCV to find the optimal hyperparameters. 

I used almost all of major machine learning models to find out which model performs better.

I used heatmap to understand the contribution of each hyperparameter in the final score.

When there are multiple hyperparameters, GridSearchCV comes in handy, and that is what I used in this project to find the optimal combination of hyperparameters. 

At the end I summarized the results using prettytable library to represent the results in tabular format.

I also wrote the summary of results to culminate the notebook.
