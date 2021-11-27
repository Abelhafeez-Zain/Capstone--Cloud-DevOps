# Capstone--Cloud-DevOps

About The Project

This project is a part from Udacity Nanodegree. In this project, it is required to apply the skills and knowledge obtained from the program, which includes:

Worked with AWS
Used Jenkins to implement Continuous Integration and Continuous Deployment (CI/CD)
Built pipelines in Jenkins
Used Ansible and CloudFormation to deploy clusters
Built Kubernetes clusters (AWS EKS)
Built Docker containers in pipelines (Dockerhub)
The CI/CD pipeline for microservices applications is developed with rolling deployment. Linting is also done to check typographical errors.

Getting Started

To get a local copy up and running follow these simple example steps.

Prerequisites

Create an AWS account
Create an EC2 instance with Amazon Linux and install Jenkins.
Then, install necessary plugins such as AWS SDK, Blue Ocean, Pipeline and GitHub clients.
Create a Docker account.
EKS can be created manually by using the command below.
eksctl create cluster --name <cluster-name> --version 1.16 --nodegroup-name standard-workers --node-type t2.medium --nodes 3 --nodes-min 1 --nodes-max 4 --node-ami auto --region us-west-2
Setup the credentials in Jenkins for AWS credentials and dockerhub credentials
  
  
