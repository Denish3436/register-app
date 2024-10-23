# Registration App Deployment on Amazon EKS
---
## Overview

This project demonstrates the end-to-end process of developing and deploying a Registration App using Amazon EKS, embodying modern DevOps practices. By integrating a range of advanced tools and technologies, this project highlights how to achieve a robust, scalable, and secure application environment.

### **Key Aspects:**
- **Container Orchestration**: Amazon EKS manages and scales containerized applications efficiently, ensuring high availability and performance.
- **CI/CD Automation**: Jenkins automates the build, test, and deployment processes, facilitating rapid and reliable application updates.
- **Code Quality Management**: SonarQube continuously assesses code quality and technical debt, promoting high standards and maintainability.
- **Continuous Deployment**: ArgoCD enables GitOps-based continuous deployment, streamlining the deployment process in Kubernetes environments.
- **Security Assurance**: Trivy performs thorough vulnerability scans, securing the application from potential threats.
- **Containerization**: Docker packages the application and its dependencies into consistent, portable containers, simplifying deployment and scaling.
- **Source Code Management**: GitHub supports effective collaboration and version control, enabling smooth development workflows.

This project serves as a comprehensive example of how to leverage contemporary DevOps tools and cloud-native technologies to deliver scalable, secure, and maintainable applications.

## Key Technologies & Tools

- **Amazon EKS**: For container orchestration and management.
- **Jenkins**: Automates the CI/CD pipeline for efficient build, test, and deployment.
- **SonarQube**: Ensures continuous code quality and technical debt management.
- **ArgoCD**: Provides GitOps-based continuous deployment for Kubernetes.
- **Trivy**: Conducts vulnerability scans to enhance application security.
- **Maven**: Manages builds and dependencies.
- **GitHub**: Facilitates source code management and collaboration.
- **Docker**: Packages applications and dependencies into containers.

## Project Highlights

- **Efficient CI/CD Pipeline**: Automated build, test, and deployment with Jenkins.
- **High Code Quality**: Continuous code quality checks with SonarQube.
- **Secure Deployments**: Vulnerability scanning using Trivy to ensure application security.
- **Continuous Deployment**: Automated deployments with ArgoCD in a Kubernetes environment.
- **Scalable and Reliable**: Utilized Amazon EKS for managing and scaling containerized applications.
- **Containerization**: Leveraged Docker for consistent and portable application deployment.
- **Version Control**: Managed source code effectively with GitHub.

## Directory Structure

```plaintext
.
├── server
│   ├── src
│   │   ├── main
│   │   │   └── java
│   │   │       └── com
│   │   │           └── example
│   │   │               └── Greeter.java
│   │   ├── site
│   │   │   └── apt
│   │   │       └── index.apt
│   │   ├── test
│   │   │   └── java
│   │   │       └── com
│   │   │           └── example
│   │   │               └── TestGreeter.java
│   ├── pom.xml
├── webapp
│   ├── src
│   │   └── main
│   │       └── webapp
│   │           └── WEB-INF
│   │               └── index.jsp
├── Dockerfile
├── Jenkinsfile
├── README.md
├── test
├── pom.xml
```





