# sagemaker_ML
To test the sagemaker for ML model

Using Amazon sagemaker for classification task of Loan prediction for online hackathon problem.
https://datahack.analyticsvidhya.com/contest/practice-problem-loan-prediction-iii/

Train file has been spilt into Train and Validation dataset in 80:20 split.
XGBoost has been used as a built-in ML algorithm.

Steps:
1) Creating a Notebook instance (EC2) which creates EBS along with it. (EBS is the Amazon Elastic Block Store)
2) Loading the datasets into local instance
3) Uploading data into Amazon s3 bucket
4) Training the model (using Sagemaker in built algorithm)
5) Deploying model and creating endpoint.

 
