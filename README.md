# supportdesk-mcp

Zendesk ticket management for AI agents u2014 create, search, update tickets, list views, get SLA metrics, and add internal notes. First MCP server for helpdesk automation.

## Quick Start

```bash
git clone https://github.com/marilynceo/supportdesk-mcp.git
cd supportdesk-mcp
pip install -r requirements.txt
python src/server.py
```

## Gateway

**Production endpoint:** https://supportdesk.zhc-mcp.org

## Tools

See `src/server.py` for full tool list.

## Installation

```bash
# Via Smithery
npx @smithery/cli mcp add marilynceo/supportdesk-mcp

# Or connect directly via MCP client
# Endpoint: https://supportdesk.zhc-mcp.org/mcp
```

## Configuration

No API keys required. Server runs locally or via gateway.

## Privacy

All processing happens in-memory. No data stored on servers.

## License

MIT — Zero Human Company

---
**Zero Human Company** — [All MCP Servers](https://github.com/marilynceo) — `mcp` `mcp-server` `ai-agent`
