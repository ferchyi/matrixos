# MatrixOS

AI Second Brain health scanner for Claude Code.

Scores 45 check layers across CLAUDE.md, skills, hooks, memory, and planning artifacts.

## Install

```bash
npm install -g @ferchyi/matrixos
```

## Usage as MCP server (Claude Code)

Add to your `.claude/settings.json`:

```json
{
  "mcpServers": {
    "matrixos": {
      "command": "node",
      "args": ["/path/to/node_modules/@ferchyi/matrixos/dist/index.js"]
    }
  }
}
```

## License

MIT — Fernando Rodriguez
