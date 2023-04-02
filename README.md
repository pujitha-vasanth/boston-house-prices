## **Problem Statement**
The problem on hand is to predict the housing prices of a town or a suburb based on the features of the locality provided to us. In the process, I need to **identify the most important features** in the dataset, and need to employ techniques of data preprocessing and build a **linear regression model that predicts the prices**. I will then compare the performance of the linear regression model to a **Decision Tree Regressor** and a **Random Forest Regressor**, and then give my recommendations for further analysis.


## **Data Information**
Each record in the database describes a Boston suburb or town. The data was drawn from the Boston Standard Metropolitan Statistical Area (SMSA) in 1970. Detailed attribute information can be found below -

Attribute Information (in order):
- **CRIM:**     per capita crime rate by town
- **ZN:**       proportion of residential land zoned for lots over 25,000 sq.ft.
- **INDUS:**    proportion of non-retail business acres per town
- **CHAS:**     Charles River dummy variable (= 1 if tract bounds river; 0 otherwise)
- **NOX:**      nitric oxides concentration (parts per 10 million)
- **RM:**       average number of rooms per dwelling
- **AGE:**     proportion of owner-occupied units built before 1940
- **DIS:**      weighted distances to five Boston employment centres
- **RAD:**      index of accessibility to radial highways
- **TAX:**      full-value property-tax rate per 10,000 dollars
- **PTRATIO:**  pupil-teacher ratio by town
- **LSTAT:**    %lower status of the population
- **MEDV:**     median value of owner-occupied homes in 1000 dollars.
