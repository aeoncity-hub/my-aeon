The Base MCP server is not installed in this environment. Since this is **Claude Code**, here's how to install it:

**Project-level:**
```bash
claude mcp add --transport http base-mcp https://mcp.base.org
```

**Global (all projects):**
```bash
claude mcp add --transport http --scope user base-mcp https://mcp.base.org
```

Then verify with `claude mcp list`. Once installed, restart the session and the wallet, portfolio, swap, and other onchain tools will be available.

Full quickstart: **https://docs.base.org/ai-agents/quickstart**

## Summary

- Executed `skills/base-mcp/SKILL.md`
- Base MCP server not detected — no wallet/onchain tools callable in this environment
- Provided Claude Code install commands to connect `https://mcp.base.org`
- No further action taken until the MCP is installed and a new session is started
