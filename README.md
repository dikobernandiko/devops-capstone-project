# devops-capstone-project

This repository contains the capstone project for the **IBM DevOps and Software Engineering Professional Certificate** on Coursera. The primary goal of this project is to develop, test, secure, and deploy a fully functional, cloud-native **Customer Accounts Microservice** using modern DevOps practices and tools.

## Project Overview
The Customer Accounts Microservice is a Python Flask-based RESTful API designed to manage customer names and addresses for an e-commerce platform. Over the course of multiple sprints, this project demonstrates the practical application of the end-to-end DevOps lifecycle—from initial planning to automated cloud deployment.

## Key Features & Technologies
- **Agile Planning:** Project management conducted using a GitHub Kanban board, user story templates, and sprint backlogs.
- **RESTful API & TDD:** Built with Python and Flask, utilizing Test-Driven Development (TDD) principles with `nosetests` to ensure a minimum of 95% code coverage.
- **Continuous Integration (CI):** Automated workflows via GitHub Actions to handle code linting (Flake8), unit testing, and security compliance.
- **Application Security:** Implementation of secure coding practices using `Flask-Talisman` for security headers and `Flask-CORS` for Cross-Origin Resource Sharing.
- **Containerization & Deployment:** Packaging the microservice into a Docker container and deploying it manually to an OpenShift/Kubernetes cluster using custom YAML manifests.
- **Continuous Delivery (CD):** Automation of the entire deployment pipeline using Tekton to achieve hands-free, continuous deployment to the cloud environment.

---
*"You build it, you run it."*
