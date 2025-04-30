# Agentic Code Editor Best Practices

## Context
Agentic code editors like Claude Code and Windsurf combine AI capabilities with traditional code editing, allowing for more interactive and intelligent coding experiences. These tools can understand code context, suggest improvements, generate implementations, and help debug issues. This guide provides best practices for effectively working with these powerful tools.

## Prompt
```
I'm working with [agentic code editor: Claude Code, Windsurf, etc.] on a [language/framework] project. I need help with [specific task: implementing a feature, debugging an issue, refactoring code, etc.].

Project context:
- Repository structure: [brief description of key directories/files]
- Technologies used: [languages, frameworks, libraries]
- Current implementation: [brief description of relevant existing code]

Specific requirements:
- [Describe what you're trying to achieve]
- [Mention any constraints or requirements]
- [Note any performance or security considerations]

Please help me by:
1. [Understanding the current code structure]
2. [Suggesting an implementation approach]
3. [Providing code snippets or full implementations]
4. [Explaining your reasoning and alternatives considered]
5. [Identifying potential edge cases or issues]

I prefer [code style preferences, documentation level, etc.].
```

## Notes
- **Be specific about context**: Agentic editors work best when they understand the broader context of your codebase. Provide information about your project structure, dependencies, and existing patterns.
- **Use incremental steps**: For complex tasks, break them down into smaller steps and work through them sequentially with the AI.
- **Leverage code references**: When discussing existing code, reference specific files and functions to help the AI understand the context.
- **Request explanations**: Ask the AI to explain its reasoning, especially for complex solutions, to ensure you understand the implementation.
- **Iterate on solutions**: Don't hesitate to refine the AI's suggestions by asking for improvements or alternatives.
- **Combine with traditional coding**: Use the AI for initial implementations, complex algorithms, or boilerplate, but maintain control over the final code.
- **Verify generated code**: Always review and test AI-generated code before integrating it into your project.

### Editor-Specific Tips

#### Claude Code
- Use the "explain this code" feature to understand complex sections
- Leverage the ability to reference specific lines or functions
- Use the "improve this code" feature for refactoring suggestions

#### Windsurf
- Take advantage of the inline code generation capabilities
- Use the context-aware code completion for faster development
- Leverage the debugging assistance features for troubleshooting