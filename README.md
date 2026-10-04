# VidEngineer for your assistant

Break down any video scene by scene — every cut, the hook, the transcript, the voice, the music and the
sound — then turn it into cut briefs and a planning canvas, right inside your assistant.

This repo contains the portable Agent Plugins package and Claude Code marketplace manifest. The work happens on
VidEngineer's hosted connector (`https://mcp.videngineer.com/mcp`). You sign in with your existing VidEngineer account.

## Install

**Claude Code**
```
/plugin marketplace add dherealmark289/videngineer-plugin
/plugin install videngineer@videngineer
```

**Codex CLI**
```sh
codex plugin marketplace add dherealmark289/videngineer-plugin
codex plugin add videngineer@videngineer
```
For a direct MCP connection, add `https://mcp.videngineer.com/mcp` in Codex and complete sign-in when prompted.
In the CLI, `codex mcp add videngineer --url https://mcp.videngineer.com/mcp` adds the hosted server and
`codex mcp login videngineer` starts OAuth. `codex mcp list` shows configured servers.

**Claude (claude.ai and desktop)** — Settings → Connectors → Add custom connector → `https://mcp.videngineer.com/mcp`.

**ChatGPT** — coming soon to the plugin directory.

Docs: https://docs.videngineer.com/agents/connector-api · Privacy: https://videngineer.com/privacy ·
Terms: https://videngineer.com/terms
