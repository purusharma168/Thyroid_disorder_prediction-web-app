Thyroid disorder prediction
==============================
Thyroid disease is a common cause of medical diagnosis and prediction, with an onset that is difficult to forecast in medical research. The thyroid gland is one of our body's most vital organs. Thyroid hormone releases are responsible for metabolic regulation. Hyperthyroidism and hypothyroidism are one of the two common diseases of the thyroid that releases thyroid hormones in regulating the rate of body's metabolism. 

The main goal is to predict the estimated risk on a patient's chance of obtaining thyroid disease or not.

**About Dataset**

From Garavan Institute

Documentation: as given by Ross Quinlan

6 databases from the Garavan Institute in Sydney, Australia

Approximately the following for each database:

 -2800 training (data) instances and 972 test instances

 -Plenty of missing data

 -29 or so attributes, either Boolean or continuously-valued

2 additional databases, also from Ross Quinlan, are also here

 -Hypothyroid.data and sick-euthyroid.data

 -Quinlan believes that these databases have been corrupted
 
 -Their format is highly similar to the other databases

1 more database of 9172 instances that cover 20 classes, and a related domain theory

Another thyroid database from Stefan Aeberhard

 -3 classes, 215 instances, 5 attributes

 -No missing values

A Thyroid database suited for training

 -3 classes

 -3772 training instances 

Thyroid Disease Data Set from UCI Machine Learning Repository For Data Set: https://archive.ics.uci.edu/ml/datasets/thyroid+disease

 Approach:
-------------------------

Data Description : We will be using Thyroid Disease Data Set present in UCI Machine Learning Repository. This Data set is satisfying our data requirement. Total 3772 instances present in different batches of data.

Export Data from database to CSV for Training : Here we will be exporting all batches of data from database into one csv file for training.

Data Splitting  : We filter the columns for splitting the data for train and test for further uses

Data Preprocessing  : We will be exploring our data set here and do EDA if required and perform data preprocessing depending on the data set. We first explore our data set in Jupyter Notebook and decide what pre-processing and Validation we have to do such as imputation of null values, etc and then we have to write separate modules according to our analysis, so that we can implement that for training as well as prediction data.

Data Training : We trained a RandomForestClassifier model in our notebook and  was good on it. We 
trained with our processed data.

Model Evaluation : Model evaluation done by classification and report was saved to .pkl file

Model Saving : we will save our models  so that we can use them for prediction purpose.

Cloud Setup : Here We will do cloud setup for model deployment. Here we also create our
flask app and user interface and integrate our model with flask app and UI

Push app to cloud : After doing cloud setup and checking app locally, we will push our app to cloud to start the application.

Data from client side for prediction purpose : Now our application on cloud is ready for doing prediction. The prediction data which we receive from client side.

Data processing and Prediction  : Client data will also go along the same process Data pre-processing and 
according to that we will predict those data.

Export Prediction to CSV : Finally when we get all the prediction for client data, then our final task is to export prediction to csv file and hand over it to client.

**Web Deployment**
=================================================
Thyroid disease detection Web App 

URL: https://puru-thyroid-disease-app.herokuapp.com/

























