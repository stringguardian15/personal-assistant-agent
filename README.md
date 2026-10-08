# personal-assistant-agent

A custom [Kiro CLI](https://kiro.dev) agent that acts as a personal assistant. Built incrementally — capabilities are added over time as new needs come up.

## What is a Kiro agent?

Kiro CLI supports custom agents defined as JSON config files. Each agent has a name, a system prompt, and a set of tools it can use. Dropping a `.json` file into `~/.kiro/agents/` makes it available as a named agent in the CLI.

## Usage

```sh
kiro chat --agent personal-assistant
```

## Current capabilities

- Read and write files
- Run shell commands
- Search files and content
- Research and note-taking via knowledge base
- Task planning with todo lists

## Adding capabilities

Edit `personal-assistant.json` to add tools, update the prompt, or connect MCP servers.
