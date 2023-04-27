
# Ensemble Classification using Balanced Data to Predict Customer Churn: A Case Study on the Telecom Industry

we use data mining classification methods, such as neural network, K-nearest neighbor, support vector machine, logistic regression, decision tree, and random forest. The results are analyzed using various criteria such as accuracy, precision, recall, F1-score, and ROC curve.
The contribution of this project is to examine the performance of classifiers before and after data balancing. After determining the successful classifiers, we combine them with the AdaBoost and XGBoost methods.The most effective combinations are identified according to all evaluation criteria. Our results show that the use of a hybrid classifier with the help of AdaBoost and XGBoost significantly improves performance.


## Prerequisites

* Install Anaconda
   * make sure you dont have python in your system.
   * https://docs.anaconda.com/free/anaconda/install/index.html
   
* Instal Tensorflow
   
   * Open Git Bash and write command below
   
```bash
  pip install tensorflow
  pip install pandas
  pip install numpy
  pip install seaborn
```
   * Now open file in the Jupyter Notebook
   

## The topics investigated in this project

* Data Preprocessing
for data preprocessing, the missing values and duplicate fields were first deleted.Some dataset features have Yes/No values.We converted the values of such features to 0/1.Another important preprocessing is for multi-value features.

* Data Balancing

Data imbalance is one of the most common problems in classification. It occurs when the proportions of the samples belonging to the classes are significantly different from each other. For example, if 90% of the data belongs to the class of loyal customers (class 0) and 10% belongs to the class of churned customers (class 1), then the dataset is unbalanced. One general method for data balancing is oversampling. Replacement of minority class samples is used here. It does not require additional information and uses the existing data to balance the training set. One of the disadvantages of this method is the increase in the size of the training set, which leads to an increase in the learning time of the classifier.

* Baseline Classification Methods

  * Neural Network
  * K-nearest Neighbors
  * Support Vector Machines
  * Logistic Regression
  * Decision Tree
  * Random Forest
  * AdaBoost
  * XGBoost
  * Ensemble learning

* Analysis of results

  * Precision
  * Recall
  * Accuracy
  * F-measure
  * ROC Curve



## Authors

- [Omid Soleiman Garmabaki](https://www.linkedin.com/in/omid-sg/)
- [Mohammad Hossein Rezvani](https://www.linkedin.com/in/mohammad-hossein-rezvani-1b708158/)

<h3 align="left">Languages and Tools:</h3>
<p align="left"> <a href="https://opencv.org/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/opencv/opencv-icon.svg" alt="opencv" width="40" height="40"/> </a> <a href="https://pandas.pydata.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/2ae2a900d2f041da66e950e4d48052658d850630/icons/pandas/pandas-original.svg" alt="pandas" width="40" height="40"/> </a> <a href="https://www.python.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> </a> <a href="https://scikit-learn.org/" target="_blank" rel="noreferrer"> <img src="https://upload.wikimedia.org/wikipedia/commons/0/05/Scikit_learn_logo_small.svg" alt="scikit_learn" width="40" height="40"/> </a> <a href="https://seaborn.pydata.org/" target="_blank" rel="noreferrer"> <img src="https://seaborn.pydata.org/_images/logo-mark-lightbg.svg" alt="seaborn" width="40" height="40"/> </a> <a href="https://www.tensorflow.org" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/tensorflow/tensorflow-icon.svg" alt="tensorflow" width="40" height="40"/> </a> </p>
