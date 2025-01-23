---
title: DTTTMutePlayer
type: docs
prev: /dttt/hooks
sidebar:
  open: true
---

```lua
DTTTMutePlayer(Player ply)
```

## Description
Can be called to mute the specified player.

Running this hook directly avoids checks for [dttt_enable_mute_logic]({{<ref "enable_mute_logic">}}) and [dttt_enable_mute]({{<ref "enable_mute">}})

### Example
```lua
hook.Run("DTTTMutePlayer", ply)
```

## Arguments

1. Player ply
> The player that should get muted