# House-Price-Analysis-using-Regression-Model
What is Regression Analysis?

  Regression analysis is a predictive modelling technique that analyzes the relation between the target or dependent variable and independent variable in a dataset. The different types of regression analysis techniques get used when the target and independent variables show a linear or non-linear relationship between each other, and the target variable contains continuous values. The regression technique gets used mainly to determine the predictor strength, forecast trend, time series, and in case of cause & effect relation. 

Types of Regression Analysis Techniques
  There are many types of regression analysis techniques, and the use of each method depends upon the number of factors. These factors include the type of target variable, shape of the regression line, and the number of independent variables. 

  > Linear Regression:
     
    Linear regression is one of the most basic types of regression in machine learning. The linear regression model consists of a predictor variable and a dependent variable related linearly to each other. In case the data involves more than one independent variable, then linear regression is called multiple linear regression models. 
    
    There are different types of linear regression. The two major types of linear regression are simple linear regression and multiple linear regression.

 
> Simple linear regression can be used:

  A simple linear regression model is susceptible to outliers. Therefore, it should not be used in case of big size data.
  * To find the intensity of dependency between two variables. Such as the rate of carbon emission and global warming. 
  * To find the value of the dependent variable on an explicit value of the independent variable. For example, finding the amount of increase in atmospheric temperature with a certain amount of carbon dioxide emission.    

  Multiple linear regression can be used:

  In multiple linear regression, a relationship is established between two or more independent variables and the corresponding dependent variables.
  * To estimate how strongly two or more independent variables influence the single dependent variable. Such as how location, time, condition, and area can influence the price of a property.
  * To find the value of the dependent variables at a definite condition of all the independent variables. For example, finding the price of a property located at a certain place, with a specific area and its condition.

 > Ridge Regression:

  This is another one of the types of regression in machine learning which is usually used when there is a high correlation between the independent variables. This is because, in the case of multi collinear data, the least square estimates give unbiased values. But, in case the collinearity is very high, there can be some bias value. Therefore, a bias matrix is introduced in the equation of Ridge Regression. This is a powerful regression method where the model is less susceptible to overfitting.

 > Lasso Regression:

  Lasso Regression is one of the types of regression in machine learning that performs regularization along with feature selection. It prohibits the absolute size of the regression coefficient. As a result, the coefficient value gets nearer to zero, which does not happen in the case of Ridge Regression.
  
  Due to this, feature selection gets used in Lasso Regression, which allows selecting a set of features from the dataset to build the model. In the case of Lasso Regression, only the required features are used, and the other ones are made zero. This helps in avoiding the overfitting in the model. In case the independent variables are highly collinear, then Lasso regression picks only one variable and makes other variables to shrink to zero.
  

  

