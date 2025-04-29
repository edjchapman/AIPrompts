# Performance Optimization Analysis

## Context
When applications encounter performance issues, a systematic approach to debugging and optimization is necessary. This prompt helps identify bottlenecks and suggest improvements.

## Prompt
```
I'm experiencing performance issues with my [language/framework] application. Please help me analyze potential bottlenecks and suggest optimization strategies.

Application details:
- Technology stack: [list technologies used]
- Type of application: [web app, API, data processing, etc.]
- Current performance metrics: [describe current performance]
- Expected performance: [describe desired performance]

Performance symptoms:
- [Describe specific issues you're seeing]
- [Include any error messages or logs if relevant]
- [Note when/where the issues occur]

Areas where I suspect bottlenecks:
- [List any components you suspect]

Please provide:
1. A systematic approach to diagnose the performance issues
2. Potential bottlenecks to investigate first
3. Specific optimization techniques relevant to my stack
4. Tools or profilers I should consider using
5. Code patterns that might be causing the slowdown
6. Architectural changes that might improve performance
```

## Notes
- Including specific error messages or metrics makes the analysis more accurate
- For database-related performance issues, include information about your schema and query patterns
- Consider including sample code of suspect areas if available
