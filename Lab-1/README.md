# Train and deploy a heart disease prediction model using XGBoost and IBM Watson Machine Learning APIs

## Introduction:

[<img src="https://raw.githubusercontent.com/Davin-IBM/Proof-of-Technology/master/DSX/images/DSX.png" height="150"/>](http://datascience.ibm.com/) [<img src="https://raw.githubusercontent.com/Davin-IBM/Proof-of-Technology/master/DSX/images/jupyter.png" height="150"/>](http://jupyter.org/index.html)

In this lab, you will use a Jupyter Notebook and the XGBoost library for heart disease detection. In addition to training, the notebook also explains how to persist a trained model to IBM Watson Machine Learning repository, deploy the model as a REST service and to predict using the deployed model using the REST APIs.

In order to train and test the heart disease prediction model, you will be using an open source data set published in the University of California, Irvine (UCI) Machine Learning Repository.

The notebook uses Python 3.5 runtime, XGBoost 0.6 and Scikit-Learn 0.17.

## Objectives:

Upon completing the lab, you will know how to:

1. Load a CSV file into Pandas DataFrame.
1. Prepare data for training and evaluation.
1. Create DMatrix from a Pandas DataFrame.
1. Create, train and evaluate a XGBoost model.
1. Vizualize a decision trees used by the model.
1. Vizualize the importance of features that were used to train the model.
1. Persist a model in Watson Machine Learning repository using Python client library.
1. Deploy a model for online scoring using the Watson Machine Learning's REST APIs
`. Score a sample scoring data using the Watson Machine Learning's REST APIs.

## Instructions:

### Step 1.  Log into your [DSX](http://datascience.ibm.com/) account, then select `View All Projects`, then select the project you created at the beginning of this proof of technology.

> <img src="https://raw.githubusercontent.com/jpatter/Proof-of-Technology/master/DSX/Lab-1/images/DSX-open-project.png"/>

### Step 2.  Click the `add notebooks` link in the top right of your project pane.

> <img src="https://raw.githubusercontent.com/Davin-IBM/Proof-of-Technology/master/DSX/Lab-1/images/DSX-add-notebook.png"/>

### Step 3.  Create the notebook.

> <img src="https://github.com/jpatter/ML-POT/blob/master/Lab-1/images/DSX-ML-CreateNotebook.PNG"/>

1. Click the `From URL` tab under `Create Notebook`.
1. Give the notebook a name in the `Name` field, for example `Titanic` and optionally you can give it a description.
1. In the Notebook URL field, use `https://raw.githubusercontent.com/jpatter/ML-POT/master/Lab-1/TitanicStudent.ipynb`.
1. Ensure that there is a `Spark Service` selected, then click the `Create Notebook` button on the bottom right of the screen.

### Step 4.  Follow the instructions in the notebook.

> <img src="https://github.com/jpatter/ML-POT/blob/master/Lab-1/images/DSX-ML-Lab-1.PNG"/>
