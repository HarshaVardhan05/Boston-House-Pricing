# Boston-House-Pricing Prediction


Project Description

You want to be the best real estate agent out there. In order to compete with other agents in your area, you decide to use machine learning. You are going to use various statistical analysis tools to build the best model to predict the value of a given house. Your task is to find the best price your client can sell their house at. The best guess from a model is one that best generalizes the data.


Loading the dataset:

 Data set is loaded as:
 
 boston=load_boston()




Let us know begin with the exploration of data using numpy

      This dataset was taken from the StatLib library which is maintained at Carnegie Mellon University.

Number of data points (houses)?

number of houses: 506


Number of features?

number of features: 13

Boston house prices dataset
---------------------------

**Data Set Characteristics:**  

    :Number of Instances: 506 

    :Number of Attributes: 13 numeric/categorical predictive. Median Value (attribute 14) is usually the target.

    :Attribute Information (in order):
        - CRIM     per capita crime rate by town
        - ZN       proportion of residential land zoned for lots over 25,000 sq.ft.
        - INDUS    proportion of non-retail business acres per town
        - CHAS     Charles River dummy variable (= 1 if tract bounds river; 0 otherwise)
        - NOX      nitric oxides concentration (parts per 10 million)
        - RM       average number of rooms per dwelling
        - AGE      proportion of owner-occupied units built prior to 1940
        - DIS      weighted distances to five Boston employment centres
        - RAD      index of accessibility to radial highways
        - TAX      full-value property-tax rate per $10,000
        - PTRATIO  pupil-teacher ratio by town
        - B        1000(Bk - 0.63)^2 where Bk is the proportion of blacks by town
        - LSTAT    % lower status of the population
        - MEDV     Median value of owner-occupied homes in $1000's
        
   
   
   
   
        
  Concatinating features and target to get a better view.
  
  df=pd.concat([features,target],axis=1)
  
  
  
   Stage 1: CORRELATION

   correlation between every feature with target values 
 
 
 
   stage 2: Splitting the data 
        
        
   Importance of splitting the data
   
                 One of the biggest problems that could occur is overfitting or underfitting. If we were to not split the dataset, it would imply that we have used all our data        for training and there is a high chance that our algorithm becomes tailor made to the given dataset. Thus, there could be a huge dip in the performance of the algorihtm          on the test dataset.

    Some of the advantages that splitting the dataset gives us are as follows:

                It allows us to check if we have undefit or overfit the data.
                It provides a sense of validation for our model.
                It suggests the level of performance measure one would expect from the test data. Thus, we are better prepared for the unknown data.

        
   step:3
   
   Gradient Descent
   update function     
        
        
        
   STEP:4

   MODEL VISUALISATION    
   
   
   
   VISUALISATION OF LEARNING PROCESS

   Plotting regression line
   
   
   
   STEP :5

   PREDICTION

   Calculating the prediction

        
