# Goal
The goal of this project was to use machine learning algorithms to correctly classify Enron employees who were known to have committed fraud from a data set that contained a general selection of employees who had committed fraud and who had not committed fraud.  The report is presented in a question and answer format and is located [here](https://github.com/ondramie/machine-learning-python-enron-employees/blob/master/enron_free_responses.markdown).  The software used for this task was Python and the library used was the [sk-learn package](http://scikit-learn.org/stable/). 

# Algorithms Used
The machine algorithms used were: 

+ Gaussian Naive Bayes 
+ Support Vector Machine
+ K-Nearest Neighbors
+ Adaboost
+ Random Forest 

Recursive elimination of features was utilized, as was Select-K-Best and Principal Component Analysis. 

# Description of Files
File Name | Description
:--| :--
References.txt | References Used
enron_free_responses.markdown | Markdown Report with Questions
my_classifier.pkl | Pickle File of Classifier
my_dataset.pkl | Pickle File of Data Set 
my_feature_list.pkl | Pickle File of Features Used
poi_id.py | Python Code With ML Algorithms
tester.py | Python Code for Cross-Validation
