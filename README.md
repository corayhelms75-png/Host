# Host
Startup

## Firecrawl MCP server

Add this server configuration to your MCP client:

```json
{
  "mcpServers": {
    "firecrawl": {
      "type": "local",
      "command": "npx",
      "args": ["-y", "firecrawl-mcp"],
      "env": { "FIRECRAWL_API_KEY": "COPILOT_MCP_FIRECRAWL_API_KEY" },
      "tools": ["*"]
    }
  }
}
```
