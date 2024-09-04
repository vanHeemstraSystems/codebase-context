# 500 - Coding Assistant Prompt

🤖 Using with AI Assistants

While this linter provides automated validation of CCS files, you can also use the Codebase Context Specification with AI assistants without any specific tooling. The ```CODING-ASSISTANT-PROMPT.md``` file in the root directory provides guidelines for AI assistants to understand and use the Codebase Context Specification.

To use the Codebase Context Specification with an AI assistant:

1. Include the content of ```CODING-ASSISTANT-PROMPT.md``` in your prompt to the AI assistant.
2. Ask the AI to analyze your project's context files based on these guidelines.
3. The AI will be able to provide more accurate and context-aware responses by following the instructions in the prompt.

[A UI element graphic would be inserted here, demonstrating how the Codebase Context Specification could be integrated into development environments]

Note that while this approach allows for immediate use of the specification, some features like .contextignore should eventually be applied by tooling (such as this linter) for more robust implementation.

## 100 - Use Cody for Prompting

After having entered the Access Token from Sourcegraph Cody, Click ``Add a prompt```:

![cody_prompts_for_codebase_context-001](https://github.com/user-attachments/assets/54b0862c-479c-4bd2-8d1f-8fe59ddbf553)

Take the text contained in ```CODING-ASSISTANT-PROMPT.md``` and paste it in the new to be created prompt:

![cody_prompts_for_codebase_context-002](https://github.com/user-attachments/assets/c8a26787-7d3f-45c6-b4a5-7c1f0d4678d0)

Optionally, untick the box ```Draft```.

Click **Create prompt**

Your newly created prompt will look alike:

![cody_prompts_for_codebase_context-003](https://github.com/user-attachments/assets/43852a19-71a9-49d0-a462-da051edb6311)

After a refresh of the page, you should see the newly created prompt **Codebase-Context** in the pick-list of Cody (here highlighted in yellow):

![cody_prompts_for_codebase_context-004](https://github.com/user-attachments/assets/8735f6b4-9b3a-4f1e-8cc0-cf993f732f9e)

Click on the prompt **Codebase-Context**.

The prompt will open and a **Play** button will be shown (here in orange):

![cody_prompts_for_codebase_context-005](https://github.com/user-attachments/assets/ff60ba4e-cc5b-43e9-a7a3-ca02f126c1b7)

Click on the **Play** button to start the prompt.

Cody will use a Large Language Model (LLM), in the example ```Claude 3.5 Sonnet```, and return the outcome:

![cody_prompts_for_codebase_context-006](https://github.com/user-attachments/assets/1d488dca-7f6c-43be-a030-062bd87dc2f3)

Here is the outcome in text:

```
Certainly! I'm well-equipped to handle tasks related to the Codebase Context Specification. Based on the provided guidelines and the context from the codebase, I can confirm that I'm ready to assist you with understanding and working within this project's structure.

The project "codebase-context" is a flexible, tool-agnostic system designed to teach AI coding tools about your codebase. It's based on the Codebase Context Specification, which aims to revolutionize AI-assisted development.

The project is structured into several main sections:

1. Introduction
2. Requirements
3. Building Our Application
4. Conclusion

The "Building Our Application" section is further divided into subsections covering Context, Context Docs, Context Ignore, Context Lint, and Coding Assistant Prompt.

Of particular interest is the Context Lint feature, which provides a tool for validating the structure and content of Codebase Context Specification files. It can be installed globally via npm and used from the command line.

The project also includes guidelines for using the Codebase Context Specification with AI assistants, particularly focusing on the use of Cody for prompting.

I'm prepared to dive deeper into any aspect of this project, provide insights, answer questions, or assist with code generation based on the context provided. How would you like to proceed?
```

Not yet any information that is kept in **.context.md**, hence open the file **.context.md** in a tab, keep it selected, and with Cody choose ```Add context...``` and pick ```Current File ... .context.md```. 

Watch the result.


MORE ...

