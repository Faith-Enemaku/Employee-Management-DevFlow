# Employee Management Application – Secure Cloud CI/CD Project

## Overview
This project demonstrates a secure cloud CI/CD pipeline for an Employee Management Application using Azure DevOps, Terraform, and SonarQube. It showcases automation, infrastructure as code, code quality, and cloud security best practices.

## Tools & Technologies
- Azure DevOps (Repos, Pipelines)
- Terraform (IaC for secure cloud infrastructure)
- SonarQube (Static code analysis & quality gates)
- Azure Cloud (compute and supporting resources)
- Git & GitHub

## CI/CD Workflow
1. Code pushed to the repo triggers Azure DevOps pipeline  
2. Build and test stages run automatically  
3. SonarQube scans code for quality and security issues  
4. Terraform provisions secure cloud infrastructure 
5. Application is deployed automatically  

## Security & Quality
- Secrets stored securely, RBAC applied in cloud resources  
- SonarQube ensures code quality and identifies vulnerabilities early  
- Infrastructure is modular and auditable

## Next Steps
- Add full application code  
- Implement Dev/Test/Prod environments  
- Enhance security scanning and monitoring  
- Expand Terraform modularization
