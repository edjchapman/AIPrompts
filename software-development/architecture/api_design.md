# API Design Guide

## Context
Designing robust, scalable, and developer-friendly APIs is crucial for modern software systems. This prompt helps create well-structured API designs following best practices.

## Prompt
```
I need to design a RESTful API for a [type of system/application] that will be used by [target users/clients].

Business requirements:
- Purpose: [describe what the API will be used for]
- Key functionality: [list main functions the API should support]
- Data entities: [list main data entities involved]
- Access control requirements: [describe authentication/authorization needs]
- Scale expectations: [describe expected traffic/load]

Please provide a comprehensive API design including:

1. Resource identification and naming conventions
   - URI structure and hierarchy
   - Resource naming (plural vs singular, etc.)
   
2. HTTP methods usage
   - Appropriate use of GET, POST, PUT, PATCH, DELETE
   - Handling bulk operations
   
3. Request/response formats
   - JSON schema for key resources
   - Standard error response format
   - Pagination approach
   - Filtering, sorting, and search capabilities
   
4. Authentication and authorization
   - Recommended auth mechanism (OAuth, API keys, etc.)
   - Permission model
   
5. Versioning strategy
   - How to handle API evolution
   - Backward compatibility considerations
   
6. Documentation approach
   - OpenAPI/Swagger recommendations
   - Example requests and responses
   
7. API security considerations
   - Rate limiting approach
   - Data validation strategies
   - Protection against common vulnerabilities

8. Performance optimization recommendations

Please include example requests and responses for key endpoints.
```

## Notes
- For public APIs, consider adding guidance on developer onboarding and API keys management
- For complex domains, request specific guidance on resource relationships and navigation
- If you have specific technology constraints (language, framework, etc.), mention them
- For microservices architectures, consider requesting guidance on API gateway patterns
- If you need GraphQL instead of REST, specify this in your request