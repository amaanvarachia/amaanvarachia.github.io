## Amaan Varachia 
A variety of projects and excercises across various topics of Coding, Data Science, Machine Learning, Data Engineering etc.

### [Regression](https://github.com/amaanvarachia/Data-Science-Regression)
This project explores applying statsmodel ordinary least squares linear regression to student graduate data to determine their predicted salary. The data is also fitted with sklearns LinearRegression and a test/train split was done on the data before comparing the root mean square error between testing and training data.
Analysis such as correlation, pearsons correlation, residuals vs fitted, Q-Q plot,scale location plot(for linearity and homoskedasicity), residuals vs leverage, shapiro statistic and normality curve. 
Multiple linear regression: Variance Inflation Factor test for multicollinearity, correlation matrix for multiple variables and Durban Watson test for autocorrelation in the residuals.Multivariate regression model, ANOVA test and stepwise regression model. 

### [Trees](https://github.com/amaanvarachia/Data-Science-Trees)
This project uses the classic Titanic data set and begins by cleaning the set, one hot encoding the categorical variables. Various hyperparameters are then tested in the sklearn "DecisionTreeClassifier". Hyperparameter tuning was done using the gridSearchCV function which makes use of k folds cross validation in its methodology. The best hyperparameters are then used to model the partitioned training data set. The model performance is then evaluated by accuracy, precision, MCC,recall adn F1-score. 

[Random Forest](https://github.com/amaanvarachia/Data-Science-Trees/blob/main/Random%20Forrest.ipynb)
This short project implements Random Forest regression or the "averaging multiple deep decision trees' model to predict median value of housing in Boston.Model tuning was done using the GridSearchCV function which implements cross validation to determine the best hyperparemeters. Since this model makes use of boostraping and aggregation (bagging),an out of bag score (OOB) is an appropariate metric in junction with a validation score.  

### [Unsupervised Learning](https://github.com/amaanvarachia/Data-Science-Unsupervised-Learning)
[Clustering project](https://github.com/amaanvarachia/Data-Science-Unsupervised-Learning/blob/main/Clustering%20code.ipynb): This project explored the use of k means clustering to a data set of grocery shoppers and used clustering to group people that favor certain foods example high in dairy,grocery and fresh produce but low in detergent and deli meats. Determing the amount of clusters was done by the 'silhouette' and scree plot (elbow) methods.

Using another data set of stock prices, the data was standardized and cluster analysis was perfomed on it. Using the clusters a Random Forest regression model was fitted using the clusters as extra input features as well as a Random Forest model that used no clustering analysis with it. The results show an increase in the AUC score when using the 5 clusters as features on top of the available data.

[Principle Components Analysis (PCA) Project](https://github.com/amaanvarachia/Data-Science-Unsupervised-Learning/blob/main/PCA%20Code.ipynb): This notebook explores a breast cancer dataset that is standardized and then generating principle components (same amount as the features) which computationally handles the eigenvectors and eigenvalues. The standard deviation (eigenvalues), proportion of variance and cumulative proportion are then displayed and the number of principle components that will be chose will be based on the component that has an eigenvalue greater than 1 as well as taking into account the cumulative proporton. A screeplot technique can also be used. A projection matrix can help visualize how much weight variables have in each PC. After filtering down only the PC's that are useful a logistic regression model is fit on it with a categorical target variable of Diagnosis and compared to a logistic regression done with all 30 of the normal indpendent variables. The result shows an increase in the pseudo R-squared valued when applying the PCA compression technique.


### [Text Analytics](https://github.com/amaanvarachia/Data-Science-TextAnalytics)


```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```


### Disclaimer
All methods,data and code do not completely belong to Amaan Varachia or contain propiertary data. These are formulated from varies resources for the sole purpose of gaining hands on experience on various coding, statistical and data analytical techniques. 


