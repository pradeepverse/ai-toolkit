# 🤖 Pradeep's AI Toolkit

A personal collection of AI-related assets — skills, prompt templates, cursor rules, and automation scripts — organized for reuse across projects and AI coding workflows.

## 📁 Structure

```
ai-toolkit/
├── README.md               # This file
├── AGENTS.md               # Notes and guidelines for AI agents working in this repo
├── claude-skills/          # Reusable skill definitions for Claude / Antigravity
│   ├── explain-code/       # Skill: explain code clearly and concisely
│   └── frontend-design/    # Skill: design and build polished frontend UIs
├── prompt-library/         # Reusable prompts and system instructions
│   ├── code-reviews.md     # Prompts for structured code review workflows
│   └── system-prompts.yaml # System-level prompts for various AI personas/tasks
├── cursor-rules/           # Cursor IDE configuration
│   └── .cursorrules        # Project-wide rules for Cursor AI
└── scripts/                # Utility and automation scripts
    └── git-automation.py   # Python script for Git workflow automation
```

## 🚀 Purpose

This repo serves as a centralized hub for:

- **Claude Skills** — Drop-in skill folders that extend AI agent capabilities for specific tasks
- **Prompt Library** — Battle-tested prompts for code reviews, system instructions, and more
- **Cursor Rules** — `.cursorrules` configs to guide Cursor AI behavior in projects
- **Scripts** — Helper scripts to automate repetitive Git and dev tasks

## 🛠️ Usage

### Claude Skills
Copy any skill folder into your project's `.agents/skills/` (or equivalent) directory to make it available to your AI agent.

### Prompt Library
Reference prompts directly or paste them into your AI tool of choice. YAML files are structured for easy parsing and reuse.

### Cursor Rules
Copy `.cursorrules` into the root of your project to apply consistent AI behavior in Cursor IDE.

### Scripts
```bash
python scripts/git-automation.py
```

## 📝 Contributing

This is a personal toolkit — feel free to fork and adapt it for your own AI workflows.

---

*Maintained by [Pradeep](https://github.com/pradeepverse)*
