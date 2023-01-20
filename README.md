# Azure-Docker-Build-Python-App

In this project I deployed a containerized python flask application on to the Azure Kubernetes Service. This was done using Github Actions which created the docker image, pushed it the a acr repository, and then deployed it on to my existing Kubernetes Cluster in Azure Kubernetes Service. The Kubernetes Cluster was created using Terraform. Reference [this repo](https://github.com/rjones18/Terraform-Azure-Kubernetes-Service).
