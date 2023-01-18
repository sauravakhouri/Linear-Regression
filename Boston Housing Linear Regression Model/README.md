# Linear Regression Model built using Boston Housing dataset from github.

The data can be downloaded and used in a pandas dataframe or it can directly be loaded using wget third party program using a bash command

Steps:

1)Loading the data set
2)Identifying the Independent(Predictor) and Dependent(Target) variables
3)Creating X and Y matrices using Predictor and Target Variables
4)Splitting the data into Train and Test and deciding the train and test size
5)Instantiating and creating a Linear Regression model and creating a best fit line using the X and Y train data
6)Applying the trained model to make prediction for Y using X_test data
7)Find out the prediction results slope, intercept, mse, r_square
8)More the r_square, more will be the accuracy of the model, so based on that make changes on train and test size of split
9)Find Adjusted R Square, using which we can eliminate features and decide which ones are helpul for the model accuracy
10)Creating a scatterplot to plot of the Y actual/Y test with Y predicted data
