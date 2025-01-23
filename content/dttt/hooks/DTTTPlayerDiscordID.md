---
title: DTTTPlayerDiscordID
type: docs
prev: /dttt/hooks
sidebar:
  open: true
---

```lua
DTTTPlayerDiscordID(Player ply)
```

## Description
Can be called to get the discord id of a the given player.

Will be nil if the player is not mapped

### Example
```lua
local discord_id = hook.Run("DTTTPlayerDiscordID", ply)
```

## Returns
1. str|nil discord_id
> The current discord id of the player