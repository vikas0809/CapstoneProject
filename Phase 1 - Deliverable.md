Phase 1 : Deliverables

## Finalize a project idea including a dataset
-  Car Insurance Claim Prediction
-  The Dataset contains information on policyholders having the attributes like policy tenure, age of the car, age of the car owner, the population density of the city, make and model of the car, power, engine type, etc, and the target variable indicating whether the policyholder files a claim in the next 6 months or not.
-  Kaggle link:https://www.kaggle.com/datasets/ifteshanajnin/carinsuranceclaimprediction-classification

## Create a mockup of your machine learning models e.g. what will be the inputs and what will be the outputs

### Introduction to Machine Learning:

Machine learning is the use of statistical algorithms to perform tasks such as learning from data patterns and making predictions. Machine learning can be divided into three learning categories: supervised, unsupervised, and deep.
Basic pattern:

       • A machine learning model is presented with a dataset.
       • The model algorithms analyze the data and attempt to identify patterns.
       • Based on these patterns, the model makes predictions on new data.

#### Supervised learning: 
Supervised learning deals with labeled data, the labels provide the correct answers. An example of supervised learning might be to predict, based on data from previous patients, whether a new patient has diabetes. Supervised learning can be broadly divided into regression and classification.

       Regression: is used to predict continuous variables. Example: Predicting the sale price of a house.
       
       Classification:  is used to predict discrete outcomes. The classification model's algorithms would attempt to learn patterns from the data, and if the model        is successful, gain the ability to make accurate predictions. Example: Predicting if a transaction is fraud or not.
       
In both classification and regression problems, a dataset is divided into features and target. Features are the variables used to make a prediction. Target is the predicted outcome.

#### Unsupervised learning: 
Machine learning algorithms work with datasets without labeled outcomes. In unsupervised learning, such correct answers, or labels, aren't provided. An example of unsupervised learning might be to task a machine learning algorithm with grouping a bag of objects as it sees fit. The algorithm isn't given labels, so it's on its own to find patterns. In this case, it might group them based on shapes, colors, or perhaps both

### Overview:
In this Analysis, we will be using be using supervised learning and follows basic pattern:

      1. Split the data into input (X) and output (y).
      2. Create an instance of the model.
      3. Train the model with the dataset with model.fit(X,y)
      4. Create predictions with model.predict()
      5. Validate the model with accuracy_score().
    
### How does machine learning work on car insurance?
As there is continuous increase in the necessity of the automobile, the car insurance also become more and more prosperous for auto insurance companies. In the past, car insurance companies have relied on historical data to set premiums. However, Machine learning has enabled insurers to better predict risk and price insurance policies more accurately. Machine learning helps in extracting critical knowledge and information from massive customer data to improve goods and services.

### Definition of the Problem
The initial step is to use the existing data to train the models, which will further help in decision making for the new customers whether they will claim or not according to the provided features.

### Dataset

Link to the dataset: https://www.kaggle.com/datasets/ifteshanajnin/carinsuranceclaimprediction-classification. 

         The training dataset has all the independent and target features. It contains all the information of the customers such as policy tenure, age of the          car owner,age of the car, the population density of the city, make and model of the car and the target variable which will help to predict whether a                policyholder will get the claim or not
         The test dataset contains all the independent features except the target variable. 

### Proposed model:

![Test Image](/Resources/ProposedModel.png)

### Data Description:

![Test Image](/Resources/data1.png)
![Test Image](/Resources/data2.png)

### The Approach to work on the dataset:
     1. Importing the required libraries
     2. Data Pre-processing: 
               In order to understand the basic description of data, figure out the summary, data types of the data.
	           Disregarding the irrelevant and handling the missing data.
	           Variables encoding: converting categorical variables into numerical values so that it could be easily fitted to a machine learning model. We will  use LabelEncoder to encode target values
     3. Splitting Data
               A dataset is split into training and testing sets in supervised learning. The model uses the training dataset to learn from it. It then uses the      testing dataset to assess its performance. If you use your entire dataset to train the model, you won't know how well the model will perform when it                 encounters unseen data. That is why it's important to set aside a portion of your dataset to evaluate your model.
     4. Scale the Testing and Training dataset
               We used StandardScalar to scale the data, fir the instance scaler with the training data and further scaling the features with the transform ()        method.
     5. Machine Learning Techniques used and accuracy results:
              LightGBM Algorithm: LightGBM is a Supervised Machine Learning Algorithm. It had the best presentation with the accuracy of 0.936
              We tried other different models as well BalancedRandomForest Classifier with an accuracy rate of 0.603, EasyEnsembleClassifier, RandomOverSampler,      LogisticRegression, SMOTE, SMOTEENN but these models may not be the best ones to predict the claim applications because of low accuracy rates along                 with the low  precision and recall scores.


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

