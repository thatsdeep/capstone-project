[![CircleCI](https://circleci.com/gh/thatsdeep/capstone-project.svg?style=svg)](https://circleci.com/gh/thatsdeep/capstone-project/)

## capstone-project

Its a Udacity DevOps Capstone project to deploy an app in AWS EKS

Below are the steps performed

Build a html application

Containerize the application using Docker and push it to DockerHub

Pull the application from DockerHub into AWS-ECR

Create a EKS cluster and required nodes

Setup Load Balancer

Delete all post completion


The following environment variablesz must be set for the project on CircleCI via the project settings page, before the project can be built successfully.

Variable	Description
AWS_ACCESS_KEY_ID	          
Used by the AWS CLI
AWS_SECRET_ACCESS_KEY	  
Used by the AWS CLI
AWS_DEFAULT_REGION	
Used by the AWS CLI. 
Project value: "ap-south-1"
AWS_ECR_URL	                
Identifies the AWS ECR docker image registry that the docker image will be pushed to, in the format                   AWS_ACCOUNT_ID.dkr.ecr.AWS_DEFAULT_REGION.amazonaws.com
