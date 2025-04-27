# MCP_SERVER

Commands
MAC:
open ~/Library/Application\ Support/Claude
touch ~/Library/Application\ Support/Claude/claude_desktop_config.json

Windows:
Powershell
explorer "%AppData%\Claude
New-Item -Path "%AppData%\Claude" -Name "claude_desktop_config.json" -ItemType File

For cmd
explorer "%AppData%\Claude
type nul > "%AppData%\Claude\claude_desktop_config.json"

Linux:
xdg-open ~/.config/Claude
touch ~/.config/Claude/claude_desktop_config.json