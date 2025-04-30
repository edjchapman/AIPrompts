# Navigating Large Codebases with Agentic Editors

## Context
Working with large codebases can be challenging, even for experienced developers. Agentic code editors like Claude Code and Windsurf offer powerful capabilities to help understand, navigate, and modify complex codebases more efficiently. This guide provides strategies for leveraging these tools when working with large software projects.

## Prompt
```
I'm working with [agentic code editor: Claude Code, Windsurf, etc.] on a large [language/framework] codebase. I need help with [understanding the architecture, finding relevant code, implementing a feature, fixing a bug, etc.].

Codebase details:
- Size: [approximate lines of code or number of files/modules]
- Architecture: [brief description of the architecture pattern]
- Key components: [list major subsystems or modules]
- My current understanding: [what you already know about the codebase]

Specific task:
- [Describe what you're trying to accomplish]
- [Mention any error messages or unexpected behavior]
- [Note any constraints or requirements]

Please help me by:
1. Suggesting an approach to navigate this codebase efficiently
2. Identifying the most relevant files/modules to examine
3. Explaining how the components likely interact
4. Providing search strategies to find relevant code
5. [Any other specific assistance needed]

I've already looked at [files or components you've already examined].
```

## Notes
- **Start with high-level understanding**: Ask the AI to help you understand the overall architecture before diving into specific components.
- **Use incremental exploration**: Work with the AI to progressively explore the codebase, starting from entry points or main components.
- **Leverage search capabilities**: Have the AI suggest effective search terms to find relevant code across the codebase.
- **Request relationship mapping**: Ask the AI to help identify relationships between components and how data flows through the system.
- **Focus on one component at a time**: For very large codebases, focus your exploration on one subsystem or feature area at a time.
- **Use the AI as a guide**: Let the AI suggest which files to examine next based on your current focus.
- **Document as you go**: Ask the AI to summarize what you've learned about the codebase to reinforce your understanding.

### Effective Strategies

#### For Understanding Existing Code
- Ask the AI to explain complex functions or classes
- Request simplified diagrams or explanations of data flow
- Have the AI identify design patterns in use

#### For Making Changes
- Ask the AI to identify all places that might be affected by your change
- Request suggestions for test cases to verify your changes
- Have the AI review your changes for consistency with the existing codebase