# Azure Container Registry Azure Container Apps
Azure Container Registry Azure Container Apps.

Guidance 
https://microsoftlearning.github.io/AZ-204-DevelopingSolutionsforMicrosoftAzure/Instructions/Labs/AZ-204_lab_05.html

Solution: 
https://github.com/utpal-maiti/AZ-204-DevelopingSolutionsforMicrosoftAzure/tree/master/Allfiles/Labs/05/Solution

**Azure Container Registry (ACR)** and **Azure Container Apps** are two powerful services that work together to streamline the development, deployment, and management of containerized applications. Here's a brief overview of each:

### Azure Container Registry (ACR)
**Azure Container Registry** is a fully managed Docker registry service that allows you to build, store, and manage container images and artifacts. It supports Docker and Open Container Initiative (OCI) images, providing a secure and scalable solution for container image management. Key features include:
- **Geo-replication**: Replicate your registry across multiple regions for high availability and low latency.
- **Automated Builds**: Use ACR Tasks to automate container image builds triggered by source code updates, base image updates, or timers.
- **Security**: Integrated security features like Docker Content Trust, image scanning for vulnerabilities, and Azure Active Directory authentication.
- **Integration**: Seamlessly integrates with Azure services like Azure Kubernetes Service (AKS), Azure App Service, and Azure Machine Learning.

### Azure Container Apps
**Azure Container Apps** is a serverless platform that allows you to run containerized applications without managing infrastructure. It provides automatic scaling, integrated networking, and built-in security features. Key features include:
- **Serverless Management**: Automatically manages infrastructure, scaling, and health monitoring.
- **Dynamic Scaling**: Scales based on HTTP traffic, event-driven processing, CPU or memory load, and more.
- **Integrated with Dapr**: Supports building microservices with Dapr, providing APIs for state management, messaging, and event handling.
- **Blue/Green Deployments**: Allows traffic splitting across multiple versions of an application for seamless updates and A/B testing.
- **Security**: Built-in security features, including secret management and DNS-based service discovery.

### How They Work Together
- **Build and Store Images**: Use Azure Container Registry to build and store your container images.
- **Deploy and Run**: Deploy these container images to Azure Container Apps, which will handle the orchestration, scaling, and management of your applications.
- **Integrated Workflow**: Streamline your development workflow by integrating ACR with Azure Container Apps, ensuring a smooth and efficient deployment process.
