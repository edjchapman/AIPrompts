# Python REST API Generator

## Context
When building microservices or backend applications, having a well-structured REST API following best practices is essential.

## Prompt
```
Create a Python FastAPI application that implements a RESTful API for a [describe resource type] management system. 

The API should:
- Follow REST principles with proper HTTP methods
- Include proper validation for inputs
- Implement error handling with appropriate status codes
- Include Swagger/OpenAPI documentation
- Use SQLAlchemy for database interactions
- Implement authentication using JWT tokens

The [describe resource type] should have the following attributes:
- [List attributes]

Please include:
1. Project structure
2. Requirements.txt
3. Database models
4. API route implementations
5. Authentication middleware
6. Example usage with curl commands
```

## Notes
- Replace [describe resource type] with your specific entity (users, products, events, etc.)
- Adjust the attributes section based on your specific needs
- Consider adding Docker configuration for easier deployment
