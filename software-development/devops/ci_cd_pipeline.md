# CI/CD Pipeline Configuration

## Context
Continuous Integration and Continuous Deployment (CI/CD) pipelines are essential for modern software development, enabling automated testing, building, and deployment of applications. This prompt helps create a well-structured CI/CD pipeline configuration.

## Prompt
```
I need to set up a CI/CD pipeline for a [type of application] project using [CI/CD platform: GitHub Actions, GitLab CI, Jenkins, etc.]. 

Project details:
- Repository: [Git platform and structure]
- Programming language(s): [languages used]
- Build system: [Maven, Gradle, npm, etc.]
- Deployment target: [Kubernetes, cloud provider, on-premises, etc.]
- Testing requirements: [unit tests, integration tests, etc.]

Pipeline requirements:
- [List specific requirements, e.g., branch protection, approval workflows]
- [Note any compliance or security requirements]

Please provide:
1. A complete CI/CD pipeline configuration file with the following stages:
   - Build
   - Test (unit and integration)
   - Security scanning (SAST, dependency checks)
   - Artifact creation and storage
   - Deployment to different environments (dev, staging, production)
2. Explanation of each stage and its purpose
3. Recommendations for environment-specific configurations
4. Strategies for handling secrets and sensitive information
5. Suggestions for optimizing pipeline performance
6. Monitoring and notification setup
7. Rollback procedures in case of failed deployments

Include best practices for the specific CI/CD platform chosen.
```

## Notes
- For monorepo setups, specify if you need separate pipelines for different components
- Consider requesting specific security scanning tools integration (SonarQube, Snyk, etc.)
- For complex deployments, you may want to request canary or blue-green deployment strategies
- If working with containers, request Dockerfile optimization suggestions alongside the CI/CD configuration