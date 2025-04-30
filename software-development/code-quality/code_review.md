# Code Review Guide

## Context
Code reviews are a critical part of the software development process, helping to ensure code quality, knowledge sharing, and early bug detection. This prompt helps generate comprehensive code review feedback.

## Prompt
```
I need to conduct a thorough code review for a [language] [type of code: feature, bug fix, refactoring] that implements [brief description of functionality].

Code details:
- Programming language: [language]
- Framework/libraries: [list relevant frameworks]
- Lines of code: [approximate size]
- Purpose: [what the code is intended to do]

Please review the following code and provide feedback:

```
[Paste code here]
```

Please provide a comprehensive code review that includes:

1. Overall assessment
   - Code quality and readability
   - Adherence to best practices and design principles
   - Potential bugs or edge cases
   
2. Specific feedback on:
   - Architecture and design choices
   - Performance considerations
   - Security vulnerabilities
   - Error handling and edge cases
   - Test coverage and quality
   - Documentation and comments
   
3. Suggestions for improvement with specific examples
   - Alternative approaches or patterns
   - Simplifications or optimizations
   - Better naming conventions if applicable
   
4. Positive aspects of the code that should be maintained

Please be constructive, specific, and educational in your feedback.
```

## Notes
- For larger codebases, consider focusing the review on specific components or aspects
- Request feedback on specific concerns if you have particular areas of interest
- For team contexts, you can ask for feedback that aligns with your team's established coding standards
- Consider including context about the codebase's maturity and constraints