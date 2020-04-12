## i2i-datascience-lab

Welcome to the Data Science Experiments Repository of Ideas2IT. We at Ideas2IT, adopt the latest practices and methodologies in Machine Learning. We are a bunch of enthusiastic folks who dabble with the latest ML / AI Developments in the Industry.




### ML Ops using SageMaker

This Experiment was carried out keeping in mind the complexity behind managing multiple ML Models in production and a rationale behind how MLOps helps solve this problem . The code will help you to get started with how to implement the MLOps process in SageMaker. The implementation part  can be done through the AWS console as well as the Jupyter Notebook inside of the SageMaker Environment. In the blog, however, we have demonstrated both modes of implementation.


The Problem Statement is to predict whether a Video Games Sales will be a hit or miss - the dataset was sourced from Kaggle. 3 variants of SageMaker native XGBoost Algorithm were used and the best model was chosen based on the AUC Metric - this was done by making use of the Search API of SageMaker. The best model was then deployed, there-in creating an Endpoint.


