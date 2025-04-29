# Microservices Architecture Design

## Context
Designing a microservices architecture requires careful consideration of service boundaries, communication patterns, and operational concerns.

## Prompt
```
I need to design a microservices architecture for a [type of application] with the following requirements:

Business domain:
- [Describe the business domain and key entities]
- [Mention expected scale and growth projections]

Current challenges or constraints:
- [List technical constraints or challenges]
- [Note any legacy systems that need integration]

Technical requirements:
- [List specific technical requirements]
- [Note any required technology choices]

Please provide:
1. A recommended service decomposition with clear boundaries
2. Data management strategy (database per service, shared DB, etc.)
3. Service communication patterns (sync vs async, event-driven, etc.)
4. API gateway and service discovery recommendations
5. Deployment and DevOps considerations
6. Monitoring and observability strategy
7. Potential challenges with this architecture and mitigation strategies
8. Implementation roadmap (if moving from monolith to microservices)

Please include a high-level architecture diagram description that I can use to create a visual representation.
```

## Notes
- For complex domains, consider Domain-Driven Design principles
- If moving from a monolith, request specific guidance on incremental migration
- Consider requesting additional focus on specific areas like resilience, scalability, or security
