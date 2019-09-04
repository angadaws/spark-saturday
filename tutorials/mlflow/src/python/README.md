
## MLflow Tutorial for Start Conference New York, 2019

### Agenda
 * Introduction
 * MLflow: What, Why, and How
  * MLflow Concepts: 
    * Tracking, Projects & Models
    * Deployment
  * Road Map 1.x
  * Community and Adoption
  * Get Involved!
 * Q & A
 * Break
 * Setting up your environment
 * Hands-on Tutorials
 
### Prerequisites 
1. Knowledge of Python 3 and programming in general
2. Preferably a UNIX-based, fully-charged laptop with 8-16 GB, with a Chrome or Fixfox brower
3. Familiarity with GitHub, git, and account on Github
4. Some Knowledge of some Machine Learning Concepts, Libraries, and Frameworks 
     * scikit-Learn
     * pandas and Numpy
     * Apache Spark MLlib
     * TensorFlow/Keras
5. PyCharm/IntelliJ or Choice of sytnax-highligted Python Editor
6. pip/pip3 and Python 3 installed
7. Loads of laughter, curiosity, and sense of humor... :-)

### Installation and Setup environment

1. Load MLflow [docs](https://mlflow.org) in your browser
 * Click on Documentation (and keep this tab open)
2. `git@github.com:dmatrix/spark-saturday.git`
3. `cd <your_cloned_directory>/tutorials/mlflow/src/python`
4. Install MLflow and the required Python modules 
    * `pip install -r req.txt` or `pip3 install -r req.txt`
5. `cd labs`
6. If using PyCharm, create a project and load these files in the project

### Lab 1: Sckit-Learn Regression with RandomForestRegressor 
 * _petrol_regression_lab_1.py_
 
 Objectives of this Lab: 
 
 * Use RandomForestReqgressor Model
 * Understand MLflow Tracking API
 * How to use the MLflow Tracking API
 * Use the MLflow API to experiment several Runs
 * Interpret and observer runs via the MLflow UI
 
#### Lab Excercises: 

 1. Consult RandomForestRegressor documentation
 2. Change or add parameters, such as depth of the tree or random_state: 42 etc.
 3. Change or alter the range of runs and increments of n_estimators
 4. Check in MLfow UI if the metrics are affected
 
 *challenge-1:* Create mean square error and r2 artifacts and save them for each run
 
 *challenge-2:* Use linear regression model and see if it makes a difference in the evaluation metrics

### Lab 2: Sckit-Learn Classification with RandomForestClassifier
 * _banknote_classification_lab_2.py_
 
Objectives of this lab:
 * Use a RandomForestClassification Model
 * Understand MLflow Tracking API
 * How to use the MLflow Tracking API
 * Use the MLflow API to experiment several Runs
 * Interpret and observer runs via the MLflow UI
 
#### Lab Excercises: 
  * Consult RandomForestClassifier documentation
  * Change or add parameters, such as depth of the tree or random_state: 42 etc.
  * Change or alter the range of runs and increments of n_estimators
  * Check in MLfow UI if the metrics are affected
  * Log confusion matrix, recall and F1-score as metrics
  
 [Nice blog to read.](https://joshlawman.com/metrics-classification-report-breakdown-precision-recall-f1/)
 
### Lab 3: Sckit-Learn Regression Base with RandomForestRegressor 
 * _airbnb_base_lab_3.py_
### Lab 4: Sckit-Learn Regression Experimental with RandomForestRegressor 
 * _airbnb_exp_lab_4.py_
### Lab 5: Deep Learning Neural Networks for Classification
* _boston_housing_tensorflow_lab_5.py_
### Lab 6: Deep Learning Neural Networks for Classification
* _imdb_keras_tensorflow_lab_6.py_
### Lab 7: Deploying, loading, and predicting an existing model 
* _loading_predicting_model_lab_8.py_
### Lab 8: Experiment your own model of choice

Let's Have Loads of Fun!

Cheers

Jules