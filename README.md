# House-Price-Prediction

Libraries Used:

1. numpy as np
2. pandas as pd
3. matplotlib.pyplot as plt
4. seaborn as sns
5. train_test_split
6. XGBRegressor
7. metrics

# Importing the Boston House Price Dataset

1. Import the Boston House Price Dataset which the datasets is already available in the sklearn we can import the datsets using sklearn.datasets.load_boston()
2. The Data is Unstructured So we are Loading the dataset to a Pandas DataFrame to make them structured . 
3. Then we need to add the target (price) column to the DataFrame

# No Of Rows and Columns
   Checking the number of rows and Columns in the data frame using 'shape'

# Missing values
   Checking for missing values using 'isnull'

# Correlation
1.  Checking the statistical measures of the dataset using 'describe' for the correlation
2.  Constructing a heatmap to understand the correlation using seaborn library

# Splitting the data and Target
1. X = Indepedent 
2. Y = Dependent

# Splitting the data into Training data and Test data

1. Here We will do Train Test Split . we will Mention 4 Variables X_train, X_test, Y_train, Y_test and 20% of data assigned for testing
2. Then We use 'Shape' For Knowing How Much data is been there in training and testing

 # Model Training
 
   XGBoost Regressor
   
# training the model with X_train

   model.fit(X_train, Y_train)
   
## Evaluation
### Prediction on training data
#### accuracy for prediction on training data

   The  model will predict X_train and stored in training_data_prediction
   
## For evaluation metrics we use R squared error and Mean Absolute Error
 
   here the model performs well both are having values near to zero

# Visualizing the actual Prices and predicted prices 
 
   Visualizing the actual Prices and predicted prices using matplotlib

# Prediction on Test Data
## accuracy for prediction on test data 

    The  model will predict X_test and stored in test_data_prediction
    
## For evaluation metrics we use R squared error and Mean Absolute Error
 
    Here the model performs well both are having values near to zero
 


