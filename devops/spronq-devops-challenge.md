# Containerized Application Deployment Challenge

## Challenge Description
As a DevOps engineer at a software company, you are responsible for deploying a new web application to production. The application is a simple web-based service that allows users to upload and share images with others. Your task is to set up a Kubernetes environment and deploy a scalable web application using Kubernetes concepts and best practices. You will be asked to make a simple web application that needs to be containerized, deployed to Kubernetes, and scaled based on traffic demands.

### Requirements
1. Kubernetes Cluster: Set up a Kubernetes cluster using any preferred Kubernetes distribution (e.g., Minikube, Docker Desktop, GKE, EKS, AKS, etc.). Ensure that you have access to the cluster and can interact with it using kubectl.
2. Dockerize the Web Application: Containerize your web application using Docker. You will need to write a Dockerfile and any other necessary configurations to create the Docker image for the web application.
3. Kubernetes Deployment: Write a Kubernetes manifest (YAML) for deploying the Dockerized web application to the Kubernetes cluster. The manifest should include a Deployment resource that defines the desired state of the application, specifying the container image, replicas, environment variables, and any other necessary configurations.
4. Autoscaling: Implement a way to automatically scale between 2 to 5 replicas the web application based on CPU utilization.
5. Ingress Controller: Set up an Ingress resource to expose the web application to external traffic. 
6. Documentation: Provide a detailed README that includes instructions on how to set up the Kubernetes cluster, deploy the web application, and test its functionality. Include any additional notes on the design decisions you made and any other relevant information.

### Additional Considerations (optional, but a plus)
- Implement a rolling update strategy to deploy new versions of the web application without downtime.
- Use ConfigMaps and Secrets to manage application configurations securely.
- Add Prometheus monitoring and Grafana dashboard for monitoring cluster and application metrics.

## Submission
The candidate should submit the following:
1. Link to the Git repository containing the application code, IaC scripts and documentation.
2. Any additional notes or explanations to clarify design decisions may be included in the repository.

## Evaluation Criteria
Candidates will be evaluated based on their ability to:
- Successfully containerize the application and set up a functional CI/CD pipeline.
- Efficiently manage cloud resources using IaC.
- Implement monitoring and alerting for the application.
- Implement security best practices.
- Provide clear and well-documented solutions.

## Create your web app
You can use any webapp you want. If you don't know how to start you can use the following:

`npx create-next-app@latest nextjs-blog --use-npm --example 
"https://github.com/vercel/next-learn/tree/main/basics/learn-starter"`
