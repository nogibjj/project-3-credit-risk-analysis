[![CI](https://github.com/nogibjj/python-template/actions/workflows/cicd.yml/badge.svg)](https://github.com/nogibjj/python-template/actions/workflows/cicd.yml)

## IDS721 Project 3: Credit Risk Analysis with XGboost in SageMaker

This project is Cloud based Big Data Systems Project, which is designed to to apply a major Big Data system to perform a Data Engineering related task. 
Example systems could be: (AWS Athena, AWS Spark/EMR, AWS Sagemaker, Databricks, Snowflake).

### Intro
In this project, I explore a common business problem faced by banks and financial institutions - predicting credit risk. I build an XGBoost model to predict whether a loan applicant is likely to default on their loan or not. I use Amazon SageMaker to train and deploy our model.

### Data
The credit risk dataset contains information about loan applicants, including their age, sex, income, loan amount, and whether they defaulted on their loan or not. It could be a good resource for building and testing credit risk models.

### Demo
![image](imgs/s3.png)
![image](imgs/notebook.png)


### Sagamaker and S3 Steps:
1. Prepare your data: You will need to make sure your data is in a suitable format for SageMaker and upload it to an S3 bucket.
2. Set up a SageMaker notebook instance: This will allow you to write and run your machine learning code using Jupyter notebooks in a SageMaker environment.
3. Load and preprocess the data in SageMaker: Once your data is uploaded to S3, you can load it into your notebook instance and preprocess it as necessary for training.
4. Train the model with SageMaker: You can use the ML algorithm provided by SageMaker to train your model on the preprocessed data.
5. Deploy the model: Once your model is trained, you can deploy it using SageMaker's hosting services.
6. Test the model using Batch Transform: You can use SageMaker's Batch Transform functionality to test your model on a large dataset, and compare the predicted results with the actual results.
7. Store the data securely in S3: Throughout the process, you can store your data securely in S3, which provides durable, scalable, and secure storage for your data.

###


1. First thing to do on launch is to open a new shell and verify virtualenv is sourced.

Things included are:

* `Makefile`

* `Pytest`

* `pandas`

* `Pylint`

* `Dockerfile`

* `GitHub copilot`

* `jupyter` and `ipython` 

* A base set of libraries for devops and web

* `githubactions` 

