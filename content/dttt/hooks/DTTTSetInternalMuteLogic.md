---
title: DTTTSetInternalMuteLogic
type: docs
prev: /dttt/hooks
sidebar:
  open: true
---

```lua
DTTTDiscordIDs(boolean enabled)
```

## Description
Can be called to change the [Console Variable]({{ref "convars"}}) [dttt_enable_internal_mute_logic]({{ref "enable_mute_logic"}})

### Example
```lua
local discord_ids = hook.Run("DTTTDiscordIDs")
```

## Returns
1. table discord_ids
> The table containing discord ids with the mapping SteamID-DiscordID