# SockShop-project

A microservices architecture divides an application into small, independent services that communicate over a network. In this project, we'll deploy SockShop, a containerized microservices-based application, using Kubernetes for orchestration.

SockShop includes several microservices, such as the front-end, carts, catalouge, payments and shipping. Each service operates independently but share relevant data accross the deployment. Each microservice is packaged in a docker image and kubernetes is used to deploy and orchestrate the communication between the different services.

Core DevOps practices will be employed to automate the deployment of SockShop, this DevOps practices will include: - Infrastructure as a Code to automate the provisioning of our resources - Container Orchestration - Monitoring, Logging & Alerts - Continous Development and Continuous Integration - Security.


# Prerequisite:
1.  AWS account.
2.  VScode and/or gitbash with AWS CLI configured.
3.  Installed minikube and kubectl.
4.  Domain name.
5.  Terraform installed on your local machine.
6.  Choco and helm installed on your powershell.


Using terraform, deploy the EKS through
"terraform init → terraform plan → terraform apply -auto-approve."

Here, after successful deployment.

![Deployed Resources](./images/sucessfully%20deployed.jpeg)


![Port-forwarding](./images/port-forwarding.png)


![localhost](./images/1st%20image.png)


![load balancer](./images/load%20balancer.png)


![DNS mapped](./images/2nd%20image.png)
