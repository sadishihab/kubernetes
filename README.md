# Container Orchestration with Kubernetes

## Technologies used:

- Kubernetes, Docker, MongoDB, Mongo Express, Mosquitto, K8s, Helm, Helmfile, Linode LKE, Linux, AWS ECR, Redis 

## Job 1: Deploy MongoDB and Mongo Express into local K8s cluster
#### Job description:

- Setup local K8s cluster with Minikube
- Deploy MongoDB and MongoExpress with configuration and credentials extracted into ConfigMap and Secret

## Job 2: Deploy Mosquitto message broker with ConfigMap and Secret Volume Types
#### Job description:

- Define configuration and passwords for Mosquitto message broker with ConfigMap and Secret Volume types

## Job 3: Install a stateful service (MongoDB) on Kubernetes using Helm
#### Job description:

- Create a managed K8s cluster with Linode Kubernetes Engine
- Deploy replicated MongoDB service in LKE cluster using a Helm chart
- Configure data persistence for MongoDB with Linode’s cloud storage
- Deploy UI client Mongo Express for MongoDB
- Deploy and configure nginx ingress to access the UI application from browser

## Job 4: Deploy our web application in K8s cluster from private Docker registry
#### Job description:

- Create Secret for credentials for the private Docker registry
- Configure the Docker registry secret in application Deployment component
- Deploy web application image from our private Docker
- registry in K8s cluster

## Job 5: Deploy Microservices application in Kubernetes with Production & Security Best Practices
#### Job description:

- Create K8s manifests for Deployments and Services for all microservices of an online shop application
- Deploy microservices to Linode’s managed Kubernetes cluster

## Job 6: Create Helm Chart for Microservices
#### Job description:

- Create 1 shared Helm Chart for all microservices, to reuse common Deployment and Service configurations for the services

## Job 7: Deploy Microservices with Helmfile
#### Job description:

- Deploy Microservices with Helm
- Deploy Microservices with Helmfile
