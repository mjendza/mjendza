## AI
### Daily basis AI for me
- Claude Code (99.99% times via CLI)
- GitHub Copilot (95% times via CLI)
- Google Antigravity (Google Gemini) 100% via IDE

### Claude Code (this is the winner for now)
- https://www.anthropic.com/engineering/equipping-agents-for-the-real-world-with-agent-skills
- https://github.com/anthropics/claude-cookbooks
- https://github.com/anthropics/skills
- https://github.com/brennercruvinel/CCPlugins
- https://github.com/fcakyon/claude-settings
- https://github.com/affaan-m/everything-claude-code
#### Remote coding
- https://edjgeek.com/blog/claude-code-sandbox-for-ipad/
  
### 💰
- https://github.com/getagentseal/codeburn
- https://github.com/trickv/hass-claude-usage
- https://github.com/chrishutchinson/claude-receipts

### Other
- still nice to make a website https://bolt.new
- to check: https://paperclip.ing/
- https://github.com/AlexsJones/llmfit

### AI
- https://github.com/AlexsJones/llmfit
-

### Playground and tools to test
- https://github.com/ruvnet/ruflo
- https://claude.com/plugins/claude-code-setup

#### Agents & Tools
- https://github.com/HKUDS/nanobot
##### Skills
- https://graph.pm/
#### My favourite MCP servers
Sample command claude: `claude mcp add --transport http name-of-server https://mcp.server.ai/mcp`
Sample command GitHub Copilot: `~/.copilot/mcp-config.json`
```
"playwright": {
      "type": "local",
      "command": "npx",
      "args": ["@playwright/mcp@latest"],
      "env": {},
      "tools": ["*"]
    },
```

- excalidraw-mcp http https://mcp.excalidraw.com
- MicrosoftDocs-MCP http https://learn.microsoft.com/api/mcp
- Lokka (for Entra ID) (GitHub Copilot config)
  ```
  "Lokka-Microsoft-Lokal": {
			"command": "npx",
			"args": [
              "C:/dev/lokka/src/mcp/build/main.js"
          	],
			"env": {
				"CLIENT_ID":"",
				"TENANT_ID":"",
				"CLIENT_SECRET": ""
			}
		},

		"Lokka-Microsoft": {
			"command": "npx",
			"args": [
              "-y @merill/lokka"
          	],
			"env": {
				"CLIENT_ID":"",
				"TENANT_ID":"",
				"CLIENT_SECRET": ""
			},
			"type": "stdio"
		},
  ```
