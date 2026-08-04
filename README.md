# GitHub-Actions-Project
This project demonstrates a complete DevOps workflow for a Maven-based Java backend application, implementing an automated CI/CD pipeline using GitHub Actions. The application is containerized with Docker, stored in Docker Hub, and deployed to a Kubernetes cluster running on AWS.

📌 Workflow
1. Developer pushes code to GitHub.
2. GitHub Actions triggers the CI pipeline.
3. Maven builds and tests the application.
4. Docker image is created and pushed to Docker Hub.
5. CD pipeline deploys the latest image to the Kubernetes cluster.
6. AWS hosts the Kubernetes infrastructure and application workloads.
