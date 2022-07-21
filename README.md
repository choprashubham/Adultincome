# Adultincome
<!-- markdownlint-disable -->
<h1 align="center">
  # DAB402: Bank Marketing Data Analysis (EDA & Modelling)
    <br>
</h1>
<p align="center">
<strong>🏆&nbsp; My goal was to perform EDA on Bank Marketing Dataset from UCI Repository and use multiple classifiers in modelling the data and then compare the performance of each of the classifiers.</strong>
</p>

## Objective of Project:
This is the classic marketing bank dataset uploaded originally in the UCI Machine Learning Repository. The dataset gives you information about a marketing campaign of a financial institution.
Analyze data in order to find ways to look for future strategies in order to improve future marketing campaigns for the bank.

## Research Objectives:
The following are the business objective of this application,
1. Identify the performance/accuracy score of Classifier Models.
2. Identify the factors that affect the customer acceptance of banking products via telephone marketing.
3. Summarize and provide future recommendations (if any)

---

<p align="center">
     🧙‍♂️&nbsp; Click here to access the Project Notebook <a href="Paste your python file Link Here">Complete EDA and modelling</a> <br>
</p>

---

## Table of Contents:

[Jupyter Notebook Link]( Paste Your Python file link here )
>**Data Sourcing**

>**Data Importing**

>**Data review, Descriptive Statistics, Null checks, Cleaning and handling outliers**

>**Descriptive Statistics (after missing values imputation)**

>**Graphical Representation: Univariate, Bivariate and Correlation Matrix**

>**EDA - Conclusion & Outcomes.**

>**Classification Models & Machine learning techniques**

>**One- Hot Encoding & Correlation Plot**

>**Applying Various Models**

>**MODEL 1 : With Imbalanced Target Variable**
   > Data Scaling
    
   > logistic regression > Evaluating Metrics
    
   > K-Nearest Neighbors Classifier > Evaluating Metrics
   
   > Support Vector Machines(SVMs) > Evaluating Metrics
   

>**MODEL 2: With Balanced Target Variable**
   >Balancing our data using SMOTEENN
   
   >Data scaling
   
   >logistic regression > Evaluating Metrics
   
   >K-Nearest Neighbors Classifier > Evaluating Metrics
   
   >Support Vector Machines(SVMs) > Evaluating Metrics
   
  
>**Conclusion from Modelling & Research answers.**

## Technologies:
This project is created with:
* Jupyter Notebook
* Python
* Python Libraries: Pandas, NumPy, matplotlib, SciPy, Seaborn, Scikit Learn

## Classification & Modelling:

Due to heavily imbalanced data in our target variable (Response/Subscribed), I've distributed my analysis in two parts:

> In First model, I've tried to predict on same data and on the Second model, I've tried to predict by balancing the target variable using various balancing techniques.

### **Steps: Here is what I have done in both of my models:**

1.Split the data into X(independent features), y(dependent features)

2.Using sklearn split X and y into Train and test set

3.Scaling our data using StandardScaler

4.Applying various machine learning algorithms such as LogisticRegression, K-nearest Neighbours, Support vector machines ,XGBoost classifier

5.Checking best accuracy and evaluation metrics of each algorithms


## EDA - Results:

The analysis are the recommendations for future marketing campaigns:

* Future campaigns should be targeted on customers from age categories below 30 years old and above 50 years old. Student and Senior citizen are more responded.
* The number of contacts with the customer shouldn't exceed 3.
* Mode of contact should be cellular and telephone.
* The month of highest level of marketing activity was the month of May. But high response rate of customers is in (March, September and October). Campaign highly active in summer time. So, for future campaign marketing activity should be increase in winter season.
* Call duration highly effect the response rate. Response rate and call duration is directly personal. So, when increase call duration response rate also increase.
* Married people are more positive response.
* House loan demand more in customers than personal loan. People wo preferred housing loan and not default are best to target.
* People who have management, technician and blue-collar related jobs are best to target.
* People who have completed their secondary education respond more. Students come under this category most.
* Low salary customers have more “yes” response.

## Classification & Modelling - Results:

* In comparison with all 3 classification algorithms ‘Support Vector Machines (SVMs)’ and 'logistic regression' performed well with accuracy of around 90.58 % and 90.39% in model 1 and with an accuracy of around 95.56% and 95.44% in model 2.
* But Support Vector Machines (SVMs) outperformed Logistic Regression in both the model by achieving highest accuracy among all of the three classification algorithms.
* From the Correlation Matrix we find out that "Duration" ,"Balance" and "previous_campaign_outcome_success" are the imporatant features that drive the decision of the customer to purchase the term deposit or not.
* Overall we can say bank should try to launch more campaigns and should focus on customers with high bank balance, also they should try to connect more with people through cellular calls.

## Content:

- Final Bank Marketing EDA & Classification Report.pdf # PDF Report / summary of the final assignment.

- Final Bank Marketing EDA & Classification Report.docx # Report in Doc Format.

- EDA and Classification Complete.ipynb # Jupyter notebook with coding.

- Bank_Marketing_Analysis.csv # Bank Marketing Dataset CSV File.

- README.md # this readme file
