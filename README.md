# twinzo-mcp

Twinzo MCP plugin for Cursor, Claude Code, Codex, and Copilot.

Connects to [https://mcp.twinzo.com](https://mcp.twinzo.com). Sign in with your Twinzo account when the client prompts for OAuth.

## Cursor

Install from the [Cursor Marketplace](https://cursor.com/marketplace) once listed, or add this repository at [cursor.com/marketplace/publish](https://cursor.com/marketplace/publish).

Local test: copy this folder to `%USERPROFILE%\.cursor\plugins\local\twinzo`, then **Developer: Reload Window**.

## Claude Code

```text
/plugin marketplace add 5-0-Technologies/twinzo-mcp
/plugin install twinzo@twinzo
```

## Codex / Copilot

Install this repository as an Agent Plugin (root `plugin.json` + `mcp.json`).
