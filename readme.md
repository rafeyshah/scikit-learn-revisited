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

            