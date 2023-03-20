# DevOps-Bootcamp--Project  By Mohamed_Ahmed_abdalrahim #

<!-- Project OverView
The Purpose of the project is to deploy python-app 
with database on a AWS cluster using Terraform  
to create the environment and ansible for configuration -->

< To run Terraform script must install Terraform and anisble first on your machine >

# 1) Building the Environment using Terraform and install jenkins by ansibly on EC2 running by terraform
# Apply the code using :
```
' terraform plan '
' terraform init '
' terraform apply '
```
# 2) Using Jenkins to build&push images
# Add the following script in the jenkins file to jenkins manually to build the docker file then push it to ecr and  apply the kubernetes files


