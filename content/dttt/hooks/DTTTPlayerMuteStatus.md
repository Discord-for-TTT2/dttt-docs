---
title: DTTTPlayerMuteStatus
type: docs
prev: /dttt/hooks
sidebar:
  open: true
---

```lua
DTTTPlayerMuteStatus(Player ply)
```

## Description
Can be called to get the mute status of a the given player.

Will be nil if the player never got un/muted

### Example
```lua
local mute_status = hook.Run("DTTTPlayerMuteStatus", ply)
```

## Returns
1. str|nil mute_status
> The current discord id of the player