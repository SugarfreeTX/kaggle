# kaggle

Some attempts at Kaggle datasets in order to apply what I've learned through "here and there" techniques and apply my understanding of algorithms and techniques that were taught/explained through: 
* <ul>Hands-on Machine Learning with Scikit-Learn, Keras & TensorFlow</ul>

Kaggle Data set Projects:

* Titanic data set 
* ieee-fraud-detection data set 

Approach: 

* The titanic_survival.ipynb I used the models SVC and RandomForestClassifier. The SVC scored better than both models of the RandomForestClassifier. The second RandomForestClassifier was built using hyperparameter combinations output by (scikit version 0.24.1) HalvingRandomSearchCV.
* The cabin_classification.ipynb is an attempt to use classifiers to classify the Cabins since there were such a large number of NaN for that column. It didn't score high enough to continue with finding the best parameters for the models. Data Science Exchange members also told me the data set is too small. 

* For ieee-fraud-detection, is using the a binary classifier (Logistic Regression model) to predict if a transaction will be fraud or not (0, 1). 


