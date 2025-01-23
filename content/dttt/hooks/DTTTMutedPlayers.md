---
title: DTTTMutedPlayers
type: docs
prev: /dttt/hooks
sidebar:
  open: true
---

```lua
DTTTMutedPlayers()
```

## Description
Can be called to get the mute status of every player

### Example
```lua
local muted_players = hook.Run("DTTTMutedPlayers")
```

## Returns
1. table muted_players
> The table containing discord ids with the mapping SteamID-boolean