
# Title of Project

## Census income Prediction
# Description
The census income data set was extracted from 1994 US Census bureau database.
The data set contains lots of feaures like age, workclass, education etc. The data set contains one target columns that is income.
Here our main goal is to predict the income of person based on the features whether the perosn makes less tha or equal to 50K or greater than 50K by using classification algorithm.
SO it is classification problem.


## Dataset
The data set is downloaded form the UCI Machine Learning Repository.

To downlad the data set you can refer to this link:-

https://archive.ics.uci.edu/ml/datasets/census+income




## Importance or Use case

Census data set is prepared every decade in every country. It present a full and reliable picture of population of a country, it represent the dmographic condition, economic condition etc.
It contains information about gender, age, workclass, education etc.

This information is very important in improving the life quality, makijng the future plan to develope the country or help to sove the existing problems etc.

The model that we are creating it classify the person based on feaures whether he earns less than or equal to 50K or earns more than 50K

If we are able to classify the person then easily government can provide the faccislities based on income classes

Example- In india we can easily find out out whether this person belongs to Below Poverty Line(BPL) or not and on the basis of his condition governmenmt can provide the facilities
## Lab Environment
We have used Google colab to create this project

Link for google colab :-

https://colab.research.google.com/
## Task Done

### 1) Data Preprocessing and Data manipulation
- Data set contains some isleading values like ? and whitespace
- We have removed these misleading values and whitespaces

### 2) Exploratory Data Analysis
- We have done EDA to find out the some insight from data set
#### a) Statistical analysis
- We done statistical analysis for categorical and numerical columns
- We find out that the average age is 38 year and the mean hours spent per week are 40.4

#### b) Graphical analysis
- We have ploted lots of graph to visualize the data set and find the pattern of data set

- We have ploted bar graph, countplot,histogram, distplot, heatmap etc.
- We found out About 69.70 % of people belongs to Private workclass,
- 32.25% of the people done Hs-grad in education that is maximum
- Maximum number of people (approximate 85 %) belongs to White class etc.

 ### 3) Fetaure selection
- We have done some hypothesis testing to select the features
- We have t-test for numerical columns and Chi-Square test for categorical columns

### 4) Spiting and scaling 
- we split the data set into training and testing dataset
- After spliting the data set we scaled the training and testing data set

### 5) Model Building 
- We have build mutiple models on training data set.
- We compared the performance of models on the basis of ROC Curve and Classification Report
- Cross_validation_score of Log_reg is 0.80674
- Cross_validation_score of decision_tree is 0.8256
- Cross_validation_score of random_forest is 0.84179
- Cross_validation_scoreof xgb is 0.85845
-  We finalize XGB Classifier as best model which is giving us best accuracy among other models that are used here.



## Future work

- We can also do hyperparameter tuning by using Grid Search CV or Random Search CV to find out best parameters
- We can also apply deep learning algorithm hyperparameter
- We will test our model
- After testing we will deploy the model