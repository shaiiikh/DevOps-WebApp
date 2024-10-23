# DevOps Web Application

This project sets up containerized development and production environments for a web application using Docker, Docker Compose, and Kubernetes.

# Getting Started
Prerequisites
- Docker and Docker Compose
- Kubernetes (Minikube, GKE, EKS, etc.)
- Helm for Kubernetes package management

Development Setup
1. Clone the Repository:
   git clone <repository_url>
   cd <repository_directory>

2. Run the Development Server:
   docker-compose up

Access the app at [http://localhost:3000](http://localhost:3000).

3. Edit Files for Auto-Reloading: Modify the code in the project files (e.g., app/page.tsx), and the app will auto-update.

# Deployment
Kubernetes Deployment with Helm
1. Build Docker Images:
   docker build -t <image_name> .

2. Deploy with Helm:
   helm install <release_name> ./helm

3. Access the Application: Use the configured Ingress to access the services.

Learn More
For more information:

[Next.js](https://nextjs.org) Documentation - Learn about features and API.
[Kubernetes](https://kubernetes.io/) Documentation - Explore Kubernetes deployment options.
[Helm](https://helm.sh/) Documentation - Learn how to manage your Kubernetes deployments.      
