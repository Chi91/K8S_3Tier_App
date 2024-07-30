
# Kubernetes Deployment for Sample 3-Tier Web Application

This project involves containerizing a sample 3-tier web application and deploying it on Kubernetes. The application consists of a backend built with .NET Core, a frontend built with HTML, CSS, and JavaScript, and a PostgreSQL database.

## Application Overview

The sample application includes the following components:

- **Backend Application**: Built with .NET Core.
- **Frontend Application**: Built with HTML, CSS, and JavaScript.
- **Database**: PostgreSQL.

- **Application Link**: [3-Tier Web Application](http://example.com)

- **Backend Application Code**: Available in the [Basic3Tier.API repo](https://github.com/your-username/Basic3Tier.API)
- **Frontend Application Code**: Available in the [Basic3Tier.UI repo](https://github.com/your-username/Basic3Tier.UI)
- **Database**: PostgreSQL

## Prerequisites

- [Kubernetes](https://kubernetes.io/docs/setup/) cluster set up and accessible
- [kubectl](https://kubernetes.io/docs/tasks/tools/) command-line tool installed and configured to interact with the Kubernetes cluster
- Docker installed and configured
- Access to the source code repositories for the frontend and backend applications
- Docker images for the frontend, backend, and PostgreSQL services, available in a container registry
- Kubernetes manifests (YAML files) for deploying and managing the frontend, backend, and PostgreSQL services

## Kubernetes Resources

- **PostgreSQL Deployment**: Deploys the PostgreSQL database required by the application.
- **Backend Deployment**: Deploys the .NET Core backend application.
- **Frontend Deployment**: Deploys the HTML, CSS, and JavaScript frontend application.
- **Services**: Define the services for each deployment to enable communication between components and expose them as needed.
