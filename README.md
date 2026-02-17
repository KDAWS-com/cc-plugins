# KDAWS Plugin Marketplace

Claude Code plugins by [KDAWS](https://kdaws.com).

## Install

```
/plugin marketplace add KDAWS-com/cc-plugins
/plugin install wflow@kdaws
/plugin install quality@kdaws
```

## Prerequisites

- [compound-engineering](https://github.com/EveryInc/compound-engineering-plugin) plugin must be installed first (required by `wflow`)

## Available Plugins

| Plugin | Description | Repo |
|--------|-------------|------|
| `wflow` | GitHub Issue-driven workflow orchestrator | [cc-wflow](https://github.com/KDAWS-com/cc-wflow) |
| `quality` | AI-powered code quality and security scanning | [cc-quality](https://github.com/KDAWS-com/cc-quality) |

## Update

```
/plugin update wflow@kdaws
/plugin update quality@kdaws
```

## Adding a Plugin

1. Create a new repo in `KDAWS-com` with `.claude-plugin/plugin.json`
2. Tag a release (e.g., `v1.0.0`)
3. Add an entry to `.claude-plugin/marketplace.json` in this repo
4. Merge to main

## License

MIT
