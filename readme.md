01. Linear Regression and Gradient Descent
    Things I learned in this
    - EDA
        Power law, Gaussian Distribution
        scatter plot, histogram, Box plot, Violin plot
        correlation ( where it's good or bad dependent and independent variable)
    - Linear Regression
        Manually without library
            write the linear regression function
            Find the value of w and b parameters, on my mind and graphs to understand the concept
            write the Loss Function ( RMSE )
        Using sckit-learn
            logistic regression (basically OLSE)
                Calculated loss using RMSE
                checked that from model.fit w and b actually fit the line on graph
            Switched with SGDRegressor to see the output, using RMSE and Graph ( No change, even logistic regression worked fine )
            Linear Regression with multiple features and computed loss error
            Using Categorical features
                Binary Categories
                One Hot Encoding
                Ordinals ( Didn't write code, not efficient value in dataset)
            Standarization | Normalization

02. Logistic Regression for Classification
    Things I learned in this
    - EDA
        Normalization, removing null values with respect to target and important features
        Uniform Distribution, Class imbalance
    - Splitting Training set, Validation set, Test set 
        according to Date format 
        fixing categorical columns, one hot encoding
        normalization, removing null and afterwards applying min max scaling
        Saved processed data to disk (parquet)
    - Logistic Regression
        Applied logistic regression
        Make confusion matrix
        Saved the model

03. Deccision Trees and Random Forrest
    Things I learned
    - Decision Trees
      - Splitting the dataset into training, validation and testing
      - Imputing missing values and Scaling numerical features
      - OneHotEncoding Numerical + Categorical Columns
      - DecisionTreeClassifier
      - Underfitting VS Overfitting
      - How to handle Overfitting 
        - Controlling HyperParameters ( Max Depth & Max Leaf Nodes )
    - Random Forest
      - Simple, Fine tuned and then ensemble method
      - different CPUs to run parallel to make job faster