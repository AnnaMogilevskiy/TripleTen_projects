# Project - Machine Learning.Megaline 

##  Project description
Mobile carrier Megaline has found out that many of their subscribers use legacy plans. They want to develop a model that would analyze subscribers' behavior and recommend one of Megaline's newer plans: Smart or Ultra.

###  Project's objective
 The goal of the project was to develop a model that will pick the right plan with the highest possible accuracy.

###  Overview of the data
I had access to behavior data about subscribers who have already switched to the new plans.
Every observation in the dataset contains monthly behavior information about one user. The information given as follows:

- сalls — number of calls,
- minutes — total call duration in minutes,
- messages — number of text messages,
- mb_used — Internet traffic used in MB,
- is_ultra — plan for the current month (Ultra - 1, Smart - 0).

### The Process

First of all I investigated the data before starting to work with the models, to do this I used different methods, visualizations. I also checked correlation between the parameters and removed unnecessary parameters. 
Data preprocessing was made in a previous project, so I missed this step. 
After I split the dataset into training, validation and test sets, developed 5 models, choose the best parameters for them and checked their accuracy, confusion matrix and classification report.


### Results
I developed Decision Tree Classifier model, Random Forest Classifier model, Logistic Regression model, used AdaBoost with Decision tree and Random forest base estimators and tried Gradient Boosting Classifier, made the final evaluation of models, check the Matthews correlation coefficient and made conclusions about the best model. 

 
Please have a look at the Jupyter Notebook Full version of [Machine Learning project](https://nbviewer.org/github/AnnaMogilevskiy/TripleTen_projects/blob/main/Machine_Learning/ML_project.ipynb).

