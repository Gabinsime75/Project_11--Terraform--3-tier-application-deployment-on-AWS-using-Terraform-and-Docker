### 3-tier application deployment on AWS using Terraform and Docker

![alt text](https://github.com/Gabinsime75/Project_11--Terraform--3-tier-application-deployment-on-AWS-using-Terraform-and-Docker/blob/main/architecture/Project_11--Terraform--3-tier-application-deployment-on-AWS.jpg)

Before the infrastructure deployment, we will build images for these applications and push them to separate ECR (Amazon Elastic Container Registry) repositories. In order to do that,
we need to authenticate Docker to an ECR repository by running the "aws ecr get-login-password" command.

##1- Login to ECR
