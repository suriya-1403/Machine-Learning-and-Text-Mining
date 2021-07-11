# **Part 1: Machine Learning Models**

You work for an office transport company. You are in discussions with ABC Consulting company for providing transport for their employees. For this purpose, you are tasked with understanding how do the employees of ABC Consulting prefer to commute presently (between home and office). Based on the parameters like age, salary, work experience etc. given in the data set ‘Transport.csv’, you are required to predict the preferred mode of transport. The project requires you to build several Machine Learning models and compare them so that the model can be finalised. 

**Data Dictionary** 
_Age_ : Age of the Employee in Years <br>
_Gender_ : Gender of the Employee <br>
_Engineer_ : For Engineer =1 , Non Engineer =0 <br>
_MBA_ : For MBA =1 , Non MBA =0 <br>
_Work_ Exp : Experience in years <br>
_Salary_ : Salary in Lakhs per Annum <br>
_Distance_ : Distance in Kms from Home to Office <br>
_license_ : If Employee has Driving Licence -1, If not, then 0 <br>
_Transport_ : Mode of Transport <br>

The objective is to build various Machine Learning models on this data set and based on the accuracy metrics decide which model is to be finalised for finally predicting the mode of transport chosen by the employee. 

**Questions:** 
1. Basic data summary, Univariate, Bivariate analysis, graphs, checking correlations, outliers and missing values treatment (if necessary) and check the basic descriptive statistics of the dataset. 
2. Split the data into train and test in the ratio 70:30. Is scaling necessary or not? 

3. Build the following models on the 70% training data and check the performance of these models on the Training as well as the 30% Test data using the various inferences from the Confusion Matrix and plotting a AUC-ROC curve along with the AUC values. Tune the models wherever required for optimum performance :
- Logistic Regression Model <br>
- Linear Discriminant Analysis <br>
- Decision Tree Classifier – CART model <br> 
- Naïve Bayes Model <br>
- KNN Model <br>
- Random Forest Model <br>
- Boosting Classifier Model using Gradient boost. <br>
4. Which model performs the best? 
5. What are your business insights? 

# **Part 2: Text Mining** 

A dataset of Shark Tank episodes is made available. It contains 495 entrepreneurs making their pitch to the VC sharks.
 
You will ONLY use “Description” column for the initial text mining exercise. 

1. Pick out the Deal (Dependent Variable) and Description columns into a separate data frame. 
2. Create two corpora, one with those who secured a Deal, the other with those who did not secure a deal. 
3. The following exercise is to be done for both the corpora: 
- Find the number of characters for both the corpuses. 
- Remove Stop Words from the corpora. (Words like ‘also’, ‘made’, ‘makes’, ‘like’, ‘this’, ‘even’ and ‘company’ are to be removed) 
- What were the top 3 most frequently occurring words in both corpuses (after removing stop words)? 
- Plot the Word Cloud for both the corpora. 
4. Refer to both the word clouds. What do you infer? 
5. Looking at the word clouds, is it true that the entrepreneurs who introduced devices are less likely to secure a deal based on your analysis?

## WordCloud Screenshots:

![W1](https://user-images.githubusercontent.com/61049979/125207295-256a3580-e2a9-11eb-851b-bb663db1ac25.PNG)
![W2](https://user-images.githubusercontent.com/61049979/125207299-3024ca80-e2a9-11eb-8d61-bd3e4d8704fe.PNG)

