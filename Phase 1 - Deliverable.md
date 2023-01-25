Phase 1 : Deliverables

## Finalize a project idea including a dataset
-  Car Insurance Claim Prediction
-  The Dataset contains information on policyholders having the attributes like policy tenure, age of the car, age of the car owner, the population density of the city, make and model of the car, power, engine type, etc, and the target variable indicating whether the policyholder files a claim in the next 6 months or not.
-  Kaggle link:https://www.kaggle.com/datasets/ifteshanajnin/carinsuranceclaimprediction-classification

## Create a mockup of your machine learning models e.g. what will be the inputs and what will be the outputs
### Introduction to Machine Learning:

Machine learning is the use of statistical algorithms to perform tasks such as learning from data patterns and making predictions. Machine learning can be divided into three learning categories: supervised, unsupervised, and deep.
Basic pattern:
•	A machine learning model is presented with a dataset.
•	The model algorithms analyze the data and attempt to identify patterns.
•	Based on these patterns, the model makes predictions on new data.

#### Supervised learning: 
Supervised learning deals with labeled data, the labels provide the correct answers. An example of supervised learning might be to predict, based on data from previous patients, whether a new patient has diabetes. Supervised learning can be broadly divided into regression and classification.

       Regression: is used to predict continuous variables. Example: Predicting the sale price of a house.
       
       Classification:  is used to predict discrete outcomes. The classification model's algorithms would attempt to learn patterns from the data, and if the model        is successful, gain the ability to make accurate predictions. Example: Predicting if a transaction is fraud or not.
       
In both classification and regression problems, a dataset is divided into features and target. Features are the variables used to make a prediction. Target is the predicted outcome.

#### Unsupervised learning: 
Machine learning algorithms work with datasets without labeled outcomes. In unsupervised learning, such correct answers, or labels, aren't provided. An example of unsupervised learning might be to task a machine learning algorithm with grouping a bag of objects as it sees fit. The algorithm isn't given labels, so it's on its own to find patterns. In this case, it might group them based on shapes, colors, or perhaps both




## Create an outline/mockup of what will your final dashboard present?
## Perform Data Exploration on your dataset in Python
- View File: data_exploration.ipynb </br>
For data exploration, we performed the following steps:
- Load the cvs file into a data frame
- Get the number of rows and columns in the dataset
   - there are 58592 rows and 44 columns
- Viewing the first 5 rows of the data
- View basic statistics of the data
- Get information about the columns to see the data type for each column and if there are any null values
- Plot histograms for all numerical values
- Visualize the relationship between all numerical columns (using scatter plots)
- Get the correlation matrix to see if there is any correlation between variables
- Plot boxplots for all numeric columns

