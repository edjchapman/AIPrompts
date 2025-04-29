# Terraform Infrastructure as Code

## Context
Infrastructure as Code (IaC) using Terraform allows for consistent, version-controlled infrastructure deployment. This prompt helps create well-structured Terraform configurations for various cloud providers and infrastructure needs.

## Prompt
```
I need to create Terraform code to provision [type of infrastructure] on [cloud provider: AWS, Azure, GCP, etc.].

Infrastructure requirements:
- Purpose: [describe what this infrastructure will be used for]
- Components needed: [list required resources like VPC, EC2, S3, etc.]
- Environment: [production, staging, development]
- Scalability requirements: [describe scaling needs]
- Security requirements: [describe security considerations]
- Networking requirements: [describe network setup]

Please provide:
1. A complete Terraform configuration including:
   - Provider configuration
   - Resource definitions with appropriate naming conventions
   - Variables and outputs
   - Modular structure (if appropriate)
   - State management approach
   
2. Best practices implementation for:
   - Security (least privilege, encryption, etc.)
   - Cost optimization
   - Maintainability
   - Reusability
   
3. Explanation of key design decisions
4. Deployment and management instructions
5. Suggestions for CI/CD integration
6. Recommendations for monitoring and alerting
7. Disaster recovery considerations

Please structure the code following Terraform best practices with appropriate comments.
```

## Notes
- For complex infrastructures, consider requesting a modular approach with reusable modules
- Specify if you need multi-environment support (dev/staging/prod)
- For specific compliance requirements (HIPAA, PCI, etc.), mention them explicitly
- Consider requesting drift detection and remediation strategies
- For multi-cloud deployments, specify which components should go to which cloud provider