### TSF SUPERVISED MACHINE LEARNING

### Task
1) To predict the percentage of a student based on the number of study hours.
2) Based on that what will be predicted score if a student studies for 9.25 hrs/ day?

### Libraries used
pandas,numpy,matplotlib.pyplot

### Approach used
Supervised Machine Learning (Linear regression)

### Performed:
Imported pandas, numpy and matplotlib.       
The data containing hours and scores is kept in a dataframe df.
Visualized the data as number of study hours v/s Percentage_Score.
Dividing the data into inputs and outputs using .iloc[] indexer.        
Splitted the data into training data and test data using Scikit-Learn's built-in train_test_split() method   
Creates an instance of LinearRegression.
Fits (trains) the model using X_train (input features) and Y_train (target values).   
After training, the model (regressor) is ready to make predictions on new data.     
Calculated the regression line based on the slope (regressor.coef_) and intercept (regressor.intercept_) learned during training.

### Conclusion:
Study hours and scores have a linear relationship.
