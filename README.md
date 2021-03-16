# Machine Learning - The Boolean Pandemic 
### What are the people more likely to survive to the boolean pandemic? Which patients will survive?

On January 1st, 2020, an epidemy was originated in Albuquerque, in New Mexico state, and spread on the following days to Santa Fe and Taos. 
While the conditions of the virus transmission were still unknown and there were no certainties of what led a patient to survive or not to the virus, it seems there were some groups of people more prone to survive than others.

In this challenge, our goal was to build a predictive model that answers the question “What are the people more likely to survive to the boolean pandemic?” using the small quantity of data accessible of the patients – name, birthday date, severity of the disease, money of expenses associated to the treatment of each family, city and others.

As data scientists, our team was asked to analyze and transform the data, and apply different predictive models in order to answer the defined question in the more accurate way.

Our project can be divided in the following steps:
- #### 1. Data Exploration
 Performing descriptive statistics for numerical and categorical variables, checking data types, and analyzing univariate and multivariate correlations.
- #### 2. Data Cleaning
 Outliers removal, missing values imputation applying different criteria depending on their nature (KNN Imputer for example) and scalling
- #### 3. Feature Engineering
 In ML, feature engineering is one of the most powerful ways to find patterns and boost the model's performance. In this step, we combined different variables and information to retrieve the most from the data.
- #### 4. Modelling
 For the modelling phase, we built our custom sklearn Pipeline using a grid search to integrate different types of models in order to find the best hyperparameters according to the model accuracy, selecting the most appropriate classifier algorithm.
- #### 5. Results
 Our best model got, while being tested inside GridSearchCV, showed a mean accuracy of 0.83111 on the test set, with a standard deviation of 0.0245. When it comes to the train set, it showed a mean accuracy of 0.89028, with a standard deviation of 0.00448.
 
 To get more details on how we performed the predictive modelling and the analysis, visit our fully detailed jupyter notebook.
 Final grade was 19/20
 
