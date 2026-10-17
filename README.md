# -claude-ia
## MCP: obscanner

The `obscanner` MCP server is configured in `.mcp.json`. The API key is read
from the `OBSCANNER_API_KEY` environment variable and is never committed:

```sh
export OBSCANNER_API_KEY=obs_...
```

In Claude Code on the web, set `OBSCANNER_API_KEY` in the environment's
variables instead.
