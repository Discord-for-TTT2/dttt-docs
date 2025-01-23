---
title: DTTTDiscordIDs
type: docs
prev: /dttt/hooks
sidebar:
  open: true
---

```lua
DTTTDiscordIDs()
```

## Description
Can be called to get the current mapping of discord ids

### Example
```lua
local discord_ids = hook.Run("DTTTDiscordIDs")
```

## Returns
1. table discord_ids
> The table containing discord ids with the mapping SteamID-DiscordID