# Claude Code Plugin Marketplace

A curated collection of Claude Code plugins by Anders Hagberg.

## Structure

- **`/plugins`** - Plugins developed and maintained in this repo
- **`/external_plugins`** - Plugins hosted in their own repositories

## Installation

To add this marketplace:

```bash
/plugin marketplace add andershagberg/claude-marketplace
```

To install a plugin:

```bash
/plugin install <plugin-name>@claude-marketplace
```

Or browse available plugins in `/plugin > Discover`.

## Available Plugins

### External Plugins

| Plugin | Description | Source |
|---|---|---|
| [long-running-harness](https://github.com/andershagberg/long-running-harness) | Structured harness for long-running AI agent tasks with planning, generator-evaluator feedback loops, progress tracking, and session resumption. | [repo](https://github.com/andershagberg/long-running-harness) |

## Plugin Structure

Each plugin follows the standard Claude Code plugin structure:

```
plugin-name/
├── .claude-plugin/
│   └── plugin.json      # Plugin metadata (required)
├── .mcp.json            # MCP server configuration (optional)
├── commands/            # Slash commands (optional)
├── agents/              # Agent definitions (optional)
├── skills/              # Skill definitions (optional)
└── README.md            # Documentation
```

## License

MIT
