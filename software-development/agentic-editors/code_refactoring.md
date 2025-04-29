# Code Refactoring with Agentic Editors

## Context
Refactoring code is a critical but often time-consuming task in software development. Agentic code editors like Claude Code and Windsurf can significantly accelerate and improve the refactoring process by understanding code context, suggesting improvements, and helping implement changes safely. This guide provides strategies for leveraging these tools for effective code refactoring.

## Prompt
```
I'm working with [agentic code editor: Claude Code, Windsurf, etc.] and need help refactoring [specific code: function, class, module, etc.] in my [language/framework] project.

Current code:
```
[Paste the code to be refactored here]
```

Refactoring goals:
- [Improve readability/maintainability]
- [Enhance performance]
- [Reduce complexity]
- [Fix code smells]
- [Implement design pattern]
- [Other specific goals]

Project constraints:
- [Backward compatibility requirements]
- [Performance requirements]
- [Testing availability]
- [Other constraints]

Please help me by:
1. Analyzing the current code and identifying issues
2. Suggesting refactoring approaches with pros and cons
3. Providing a refactored version that addresses the goals
4. Explaining the key changes made and why
5. Suggesting tests to verify the refactoring preserves behavior
```

## Notes
- **Start with clear goals**: Define specific refactoring objectives rather than just asking for "better code"
- **Provide context**: Include surrounding code or explain how the code fits into the larger system
- **Consider incremental refactoring**: For complex code, break the refactoring into smaller, manageable steps
- **Request explanations**: Ask the AI to explain its refactoring decisions to ensure you understand the changes
- **Verify behavior preservation**: Always request suggestions for testing the refactored code
- **Review carefully**: Manually review all AI-suggested refactorings before implementing them

### Common Refactoring Patterns to Request

#### Code Structure Improvements
- Extract method/function for code reuse
- Simplify complex conditional logic
- Replace nested conditionals with guard clauses
- Consolidate duplicate code

#### Object-Oriented Refactorings
- Extract class or interface
- Replace inheritance with composition
- Implement design patterns (Strategy, Factory, etc.)
- Improve encapsulation

#### Performance Optimizations
- Optimize algorithms
- Reduce unnecessary computations
- Improve data structure usage
- Optimize resource management

#### Modern Language Feature Adoption
- Convert to newer language features (e.g., Java streams, C# LINQ)
- Implement async/await patterns
- Use functional programming techniques where appropriate