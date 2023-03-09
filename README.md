[![CI](https://github.com/nogibjj/python-template/actions/workflows/cicd.yml/badge.svg)](https://github.com/nogibjj/python-template/actions/workflows/cicd.yml)
## IDS721- Project 3

### Intro

For my IDS721 individual project 3, I intend to apply big data techniques to perfrom analysis and machine learning to the Chicago Uber/Lyft Dataset. To evaluate the model's accuracy, I will be using SageMaker's Batch Transform feature to compare the predicted Boston house price with the actual median house price. In addition, I plan to use S3 to store the data securely in the cloud.


### Data
The Transportation Network Providers (TNP) Trips dataset on data.cityofchicago.org is a public resource that contains information on trips made by Transportation Network Providers such as Uber and Lyft in the City of Chicago. This dataset includes detailed trip-level data, such as pick-up and drop-off times, trip distances, and fares, for trips that occurred between November 2018 and February 2019. By analyzing this dataset, one can gain insights into the usage patterns of these popular ride-hailing services in Chicago, and potentially identify areas for optimization and improvement in the transportation system.

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

