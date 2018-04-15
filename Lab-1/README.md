# Train and deploy a heart disease prediction model using XGBoost and IBM Watson Machine Learning APIs

## Introduction:

[<img src="https://raw.githubusercontent.com/Davin-IBM/Proof-of-Technology/master/DSX/images/DSX.png" height="150"/>](http://datascience.ibm.com/) [<img src="https://raw.githubusercontent.com/Davin-IBM/Proof-of-Technology/master/DSX/images/jupyter.png" height="150"/>](http://jupyter.org/index.html)

In this lab, you will use a Jupyter Notebook to train a model using the XGBoost library to classify whether a person has heart disease or not In addition to training, the notebook also explains how to persist a trained model to the IBM Watson Machine Learning repository, deploy the model as a REST service and to predict using the deployed model using the REST APIs.

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
1. Score sample data using the Watson Machine Learning's REST APIs.

## Instructions:

### Step 1.  Log into your [Watson Studio](http://datascience.ibm.com/) account, then select `View All Projects`.

> <img src="https://github.com/bleonardb3/ML-POT/blob/master/Lab-1/images/View%20All%20Projects.png"/>

### Step 2.  Select the project you created at the beginning of this proof of technology.

> <img src="https://github.com/bleonardb3/ML-POT/blob/master/Lab-1/images/Select%20Watson%20Studio%20Labs.png"/>

The labs in this Proof of Technology will require the following services to be created and associated with your project. 
•	Object Storage
•	Watson Machine Learning
•	Apache Spark  

The Object Storage service instance should already exist, having been created when the Watson Studio Labs (or whatever you named it) project was created. Both the Watson Machine Learning service, and the Apache Spark service need to be created and then associated with the project.  

### Step 3.  Click on the project `Settings` tab

> <img src="https://github.com/bleonardb3/ML-POT/blob/master/Lab-1/images/Select%20Settings.png"/>

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
