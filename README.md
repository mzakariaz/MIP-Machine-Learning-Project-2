<h1><b>MIP-Machine-Learning-Project-2</b></h1>

<h2><b>Contents</b></h2>

- [**Introduction**](#introduction)
- [**Details**](#details)
- [**Credits**](#credits)

## **Introduction**
This project is my attempt at Project 2 of the Machine Learning Engineer internship at Mentorness.

## **Details**
* **<u>Project Title:</u>** *FasTag Fraud Detection*
* **<u>Project Description:</u>** This project focuses on leveraging machine learning classification techniques to develop an effective fraud detection system for FasTag transactions. The dataset comprises key features such as transaction details, vehicle information, geographical location, and transaction amounts. The goal is to create a robust model that can accurately identify instances of fraudulent activity, ensuring the integrity  and security of FasTag transactions.
* **<u>Project Submission:</u>** All of the work to be evaluated in this project is to be found in the `fastag-fraud-detection.ipynb` file, located in the current directory.
* **<u>Libraries Used:</u>** The following libraries were used for the stated purposes:
  * `numpy`, for numerical calculations;
  * `pandas`, for data analysis;
  * `matplotlib.pyplot`, for data visualisation;
  * `seaborn`, for data visualisation;
  * `sklearn.preprocessing`, for preprocessing the dataset, especially via the `StandardScaler` module;
  * `sklearn.model_selection`, for model selection, specifically via the `train_test_split` module;
  * `sklearn.linear_model`, for using linear models, especially via the `LogisticRegression` module;
  * `sklearn.tree`, for using tree models, especially via the `DecisionTreeClassifier` module;
  * `sklearn.ensemble`, for using ensemble methods, especially via the `RandomForestClassifier`, `VotingClassifier` and `BaggingClassifier` modules;
  * `sklearn.svm`, for using support vector machines, especially via the `SVC` module, and;
  * `sklearn.metrics`, for model evaluation, especially through the `accuracy_score`, `f1_score`, `precision_score` and `recall_score` modules.

## **Credits**
All of the sources (e.g. videos, images, articles) used to help build this project are cited in the links below:
- https://www.youtube.com/watch?v=_PwhiWxHK8o
- https://www.youtube.com/watch?v=ZVR2Way4nwQ
- https://www.youtube.com/watch?v=v6VJ2RO66Ag
- https://scikit-learn.org/stable/modules/svm.html
- https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.VotingClassifier.html#sklearn.ensemble.VotingClassifier
- https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LogisticRegression.html#sklearn.linear_model.LogisticRegression
- https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestClassifier.html#sklearn.ensemble.RandomForestClassifier
- https://scikit-learn.org/stable/api/sklearn.metrics.html#module-sklearn.metrics
- https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.GridSearchCV.html#gridsearchcv
- https://www.statology.org/plot-logistic-regression-in-python/