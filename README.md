# AIPrompts

A repository for organizing and storing prompts for various AI contexts.

## Purpose

This repository serves as a centralized collection of prompts for different AI systems and use cases, including:

- Chat-based AI systems (ChatGPT, Claude, etc.)
- Code generation tools (Windsurf, Claude Opus, etc.)
- Image generation prompts
- Specialized task prompts

## Repository Structure

```
├── software-development/  # Software and coding related prompts
│   ├── code-generation/   # Generating code snippets or full programs
│   ├── debugging/         # Fixing issues and troubleshooting
│   ├── architecture/      # System design and architecture
│   ├── devops/            # CI/CD, infrastructure as code, and deployment
│   └── code-quality/      # Code reviews, testing, and quality assurance
├── creative/              # Creative content generation
│   ├── writing/           # Story, essay, and content writing
│   ├── visual/            # Image generation guidance
│   └── brainstorming/     # Idea generation and creative thinking
├── business/              # Business and professional contexts
│   ├── marketing/         # Marketing copy and strategy
│   ├── communication/     # Professional emails and communications
│   └── analysis/          # Business analysis and reporting
├── research/              # Academic and research contexts
│   ├── literature-review/ # Research summaries and reviews
│   ├── data-analysis/     # Data processing and visualization
│   └── methodology/       # Research design and methodology
└── personal/              # Personal assistant contexts
    ├── productivity/      # Time management and organization
    ├── learning/          # Educational assistance
    └── lifestyle/         # Health, wellness, and day-to-day assistance
```

## Usage

Each prompt is stored as a markdown file with the following structure:

- **Title**: Brief description of the prompt's purpose
- **Context**: Background information and use case
- **Prompt**: The actual prompt text
- **Notes**: Optional tips, variations, or expected outcomes

## Best Practices for AI Prompts

When working with AI systems, especially for software development and DevOps tasks, consider these best practices:

1. **Be specific and detailed**: The more context and specifics you provide, the better the AI's response will be.
2. **Use examples**: When possible, include examples to illustrate what you're looking for.
3. **Break down complex tasks**: For complex problems, break them into smaller, more manageable prompts.
4. **Iterate and refine**: Start with a basic prompt and refine it based on the responses you receive.
5. **Provide context**: Include relevant background information, constraints, and requirements.
6. **Specify format**: Clearly indicate the desired format for the response (code, explanation, list, etc.).
7. **Review and validate**: Always review AI-generated code or content before implementing it.
8. **Use placeholders consistently**: Use the [placeholder] format consistently for parts that need to be replaced.
9. **Include error handling**: For code generation, specify how errors should be handled.
10. **Consider security implications**: Be explicit about security requirements, especially for infrastructure and authentication code.

## Contributing

Feel free to add new prompts or refine existing ones. Please follow the established structure and provide clear documentation for each prompt.

### Creating New Prompts

1. Use the template in `_templates/prompt_template.md` as a starting point
2. Place your prompt in the appropriate category directory
3. Follow the established format with Title, Context, Prompt, and Notes sections
4. Use clear, descriptive language and include helpful examples
5. Test your prompt with an AI system before submitting if possible
