# agent-instructions

Agent instruction configs I sync across projects

## Installation

```bash
# pick a template
cp templates/CLAUDE.api.md your-project/CLAUDE.md
```

## How to use

```bash
# Claude Code reads CLAUDE.md from the repo root automatically
```

## Features

- Kept short: agents read every token every time
- Review checklist baked into instructions
- Per-archetype CLAUDE.md templates (api / cli / lib)
- Global coding-style rules in rules/

## Project structure

```text
├── .github/
│   └── pull_request_template.md
├── docs/
│   ├── faq.md
│   ├── roadmap.md
│   └── usage.md
├── examples/
│   └── quickstart.md
├── rules/
│   ├── review.md
│   └── style.md
├── templates/
│   ├── CLAUDE.api.md
│   └── CLAUDE.cli.md
├── .gitignore
├── CHANGELOG.md
├── CONTRIBUTING.md
└── SECURITY.md
```
