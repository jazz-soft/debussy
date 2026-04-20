# midi-mcp
coming soon...

### Claude for Desktop
MacOS/Linux: `code ~/Library/Application\ Support/Claude/claude_desktop_config.json`  
Windows PowerShell: `code $env:AppData\Claude\claude_desktop_config.json`

```json
{
  "mcpServers": {
    "midi": {
      "command": "npx",
      "args": ["-y", "midi-mcp"]
    }
  }
}
```

### VSCode
`code .vscode\mcp.json`

```json
{
  "servers": {
    "midi": {
      "command": "npx",
      "args": ["-y", "midi-mcp"]
    }
  }
}
```