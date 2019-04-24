# Automatic Labelling and Model Tuning with Amazon SageMaker

This repository contains resources required for a workshop.

Developing machine learning models requires a lot of effort which often needs to be repeated over time as data distributions change. In this session you will learn about some of the latest concepts in Automatic Machine Learning including how to apply them to speed up development and achieve robust models over time. You will learn how to run a custom labelling job using Amazon SageMaker GroundTruth to build a data set to fine-tune your model. You will also learn how to tune your model’s hyperparameters using SageMaker’s Automatic Model Tuning capabilities and understand the theory of how Bayesian Optimisation is automatically applied for more accurate results and faster tuning.
 
## Prerequisites
### AWS Account

In order to complete this workshop you'll need an AWS Account with access to create AWS IAM, S3 and SageMaker resources. The code and instructions in this workshop assume only one student is using a given AWS account at a time. If you try sharing an account with another student, you'll run into naming conflicts for certain resources. You can work around these by appending a unique suffix to the resources that fail to create due to conflicts, but the instructions do not provide details on the changes required to make this work.

Some of the resources you will launch as part of this workshop are eligible for the AWS free tier if your account is less than 12 months old. See the AWS Free Tier page for more details. For other resources AWS credit vouchers are supplied.

## AWS Region

SageMaker is not available in all AWS Regions at this time. Accordingly, we recommend running this workshop in one of the following supported AWS Regions: N. Virginia, Oregon, Ohio, or Ireland.
Once you've chosen a region, you should create all of the resources for this workshop there, including a new Amazon S3 bucket and a new SageMaker notebook instance. Make sure you select your region from the dropdown in the upper right corner of the AWS Console before getting started.

## Outline

This workshop is divided into multiple labs. Lab 1 must be completed first, followed by Lab 2:

1.	Automatic Labelling
2.	Private Workforce Labelling 
3.	Automatic Model Tuning 

Be patient as you work your way through the notebook-based modules. After you run a cell in a notebook, it may take several seconds for the code to show results. For the cells that start training jobs, it may take several minutes. In particular, the last two modules have training jobs that may last up to 10 minutes.
