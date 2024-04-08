# NLW Unite - DevOps

## 💻 About the Project

This project was built during the "NLW Unite" event hosted by [Rocketseat](https://www.rocketseat.com.br). It is designed as a comprehensive DevOps solution for a Node.js API, which was also developed as part of the event. The aim of this project is to streamline the deployment, management, and scaling processes of the Node.js API using a variety of DevOps tools and practices.

> Please note that this project was created for personal educational purposes during the "NLW Unite" event. It is not intended for production use and may not be directly reproducible in real-world environments without modifications. Always assess and adapt the code and methodologies to meet the requirements and security standards of your specific deployment scenario.

### 🧪 Features

- **Docker Integration**: Utilizes Docker to containerize the Node.js API, ensuring consistent environments for development, testing, and production. Includes workflows for automatic Docker image generation with appropriate version tagging in Docker Hub.
- **Terraform Deployment**: Employs Terraform to provision a database cluster on DigitalOcean, automating the infrastructure setup process and ensuring a reproducible environment.
- **Kubernetes Orchestration with Helm**: Leverages Kubernetes and Helm for orchestrating the application's deployment, scaling, and management.
- **ArgoCD for Continuous Delivery**: Integrates ArgoCD to establish a continuous delivery pipeline, allowing for automatic deployment of changes with minimal manual intervention.
