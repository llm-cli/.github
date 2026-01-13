# llm-cli

**LLM-first CLI tools** — Command-line interfaces optimized for AI agents.

## Philosophy

- **Token-efficient**: Concise output, minimal noise
- **Intuitive**: `--help` is all an agent needs
- **Unix-friendly**: Composable, scriptable, pipe-able
- **Lightweight**: No MCP overhead, just bash

## Tools

| Tool | Description |
|------|-------------|
| [claude-sessions](https://github.com/llm-cli/claude-sessions) | Manage Claude Code sessions and agents |
| [discord-notify](https://github.com/llm-cli/discord-notify) | Communicate with users via Discord DM |

## For AI Agents

Add one line per tool to your system prompt:

```
`discord-notify --help` - contact user via Discord
```

The `--help` is all an agent needs to discover and use the tool.
