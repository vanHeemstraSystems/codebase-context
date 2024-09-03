# 400 - Context Lint

## 100 - 📦 Installation

You can install the linter globally using npm:

```
$ npm install -g codebase-context-lint
```

## 200 - 🚀 Usage
After installation, you can use the linter from the command line:

```
$ codebase-context-lint <directory_to_lint>
```

Replace <directory_to_lint> with the path to the directory containing your Codebase Context Specification files.

Here, inside the root of the repository where the ```.context.md``` file resides: 

```
$ codebase-context-lint .
```

## 300 - ✨ Features

🔍 Validates the structure and content of .context.md, .context.yaml, and .context.json files<br/>
✅ Checks for required fields and sections<br/>
📄 Verifies the format of .contextdocs.md files<br/>
🚫 Validates ignore patterns in .contextignore files<br/>
💬 Provides detailed error messages and warnings<br/>
