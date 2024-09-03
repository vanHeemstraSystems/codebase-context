# 500 - Coding Assistant Prompt

🤖 Using with AI Assistants

While this linter provides automated validation of CCS files, you can also use the Codebase Context Specification with AI assistants without any specific tooling. The ```CODING-ASSISTANT-PROMPT.md``` file in the root directory provides guidelines for AI assistants to understand and use the Codebase Context Specification.

To use the Codebase Context Specification with an AI assistant:

1. Include the content of ```CODING-ASSISTANT-PROMPT.md``` in your prompt to the AI assistant.
2. Ask the AI to analyze your project's context files based on these guidelines.
3. The AI will be able to provide more accurate and context-aware responses by following the instructions in the prompt.

[A UI element graphic would be inserted here, demonstrating how the Codebase Context Specification could be integrated into development environments]

Note that while this approach allows for immediate use of the specification, some features like .contextignore should eventually be applied by tooling (such as this linter) for more robust implementation.