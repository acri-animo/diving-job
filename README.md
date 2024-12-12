# FiveM Diving Job (Sandbox/Mythic Framework)

A FiveM diving job script for SandboxRP version of Mythic framework.

Note: Requires Sandbox version of Mythic framework


You can rename the files as you wish and place them within their respective directories within sandbox-labor (client/server/config).

You must also add the following to sandbox-labor > server > startup.lua (edit the pay & reputation as you wish).

```lua
Labor.Jobs:Register("Diving", "Diving", 0, 2000, 85)
```

Edit job rewards in server.lua