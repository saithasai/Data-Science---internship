### TSF SUPERVISED MACHINE LEARNING

### Task
1) To predict the percentage of a student based on the number of study hours.
2) Based on that what will be predicted score if a student studies for 9.25 hrs/ day?

### Libraries used
pandas,numpy,matplotlib.pyplot

### Approach used
Supervised Machine Learning (Linear regression)

### Performed Action:
- Imported pandas, numpy and matplotlib.       
- The data containing hours and scores is kept in a dataframe df.       
- Visualized the data as number of study hours v/s Percentage_Score.           
- Divided the data into inputs and outputs using .iloc[] indexer.         
- Splitted the data into training data and test data using Scikit-Learn's built-in train_test_split() method   
- Created an instance of LinearRegression.   
- Trained the model using X_train (input features) and Y_train (target values).   
- After training, the model (regressor) is made ready to predictions on new data.     
- Calculated the regression line based on the slope (regressor.coef_) and intercept (regressor.intercept_) learned during training.    
- Returned test data and predicted y_pred when passing X_test to the model.        
- Compared tested data (Y_test) and predicted data (y_pred).       
- Predicted score if a person studies for 9.25 hours/day using regressor object.      
- To evaluate the performance of algorithm, mean absolute error is computed.

### Result:
- Study hours and scores have a linear relationship.        
- The predicted score if a person studies for 9.25 hours/day is 93.69173248737539.     
- Mean Absolute Error: 4.183859899002982.
