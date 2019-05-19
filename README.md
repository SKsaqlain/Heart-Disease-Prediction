# Description
The mini-project was carried out as a part of the ML-LAB at PES University 2019.<br/>
Various models were tried to predict whether the individual has a heart disease or not based on the attributes listed in the dataset, and accuracies were compared and it was found that logistic regression gave the highest accuracy.
 * #### K-NN <br/>
K-Nearest Neighbors is one of the most basic yet essential classification algorithms in Machine Learning. It belongs to the supervised learning domain. It is very much used in real-life scenarios since it does not make any underlying assumptions about the distribution of data. A K-nn model was trained with varing number of neighbours, and it was found that with 4 neighbours the accuracy was around 71%.

* #### Logistic Regression <br/>
Logistic regression is similar to that of the regression but the only difference between these two is that the output of the regression function  is passed to a logit function. PCA was used in order to reduce the dimensions of the data and then the regression model was trained and it was found that the model gave an accuracy of around 84%  with number of components being 9 (9 components as a linear combination of 14 attributes)
 
 * #### Decision Tree <br/>
Decision tree is the most powerful and popular tool for classification and prediction. A Decision tree is a flowchart like tree structure, where each internal node denotes a test on an attribute, each branch represents an outcome of the test, and each leaf node indicates the label. Thus a path from the root to a leaf forms a hypothesis. The decision tree model was trained with the given dataset with _Entropy_ as criteria to split a node, thus an accuracy of around 73 % was obtained.

* #### SVM <br/>
A Support Vector Machine (SVM) is a supervised discriminative classifier formally defined by a separating hyperplane. In other words, given labeled training data, the algorithm outputs an optimal hyperplane which acts like a decision boudry between the classes and also categorizes new examples when supplied with query instance. In two dimentional space this hyperplane is a line dividing a plane in two parts where in each class lay in either side. Thus a SVM model was trained with a linear kernel and a accuracy of around 81% was obtained.

* #### AdaBoost <br/>
Ensemble learning methods combine several decision trees classifiers to produce better predictive performance than a single decision tree classifier. The main principle behind the ensemble model is that a group of weak learners are combined together to form a strong learner, thus increasing the accuracy of the model. AdaBoost is one of the Ensemble learning techniques.
An AdaBoostClassifier was trained with the main model being a _DecisionTreeClassifier_ and the criteria being _entropy_ , with 10 estimators it an accuracy of around 76% was obtained.

# Requirements
* Python 
* Jupyter notebook
# Dataset
The data set was obtained from kaggle. This database contains 15 attributes including the target.
```
https://www.kaggle.com/ronitf/heart-disease-uci
```
# Usage
To clone this repository run the below command
```
$ git clone https://github.com/SKsaqlain/Heart-Disease-Prediction.git
```
Open the V3.ipynb file using jupyter notebook 
