---
title: DTTTUnmutePlayer
type: docs
prev: /dttt/hooks
sidebar:
  open: true
---

```lua
DTTTUnmutePlayer(Player ply)
```

## Description
Can be called to unmute the specified player.

Running this hook directly avoids checks for [dttt_enable_mute_logic]({{<ref "enable_mute_logic">}}) and [dttt_enable_unmute]({{<ref "enable_mute">}})

### Example
```lua
hook.Run("DTTTUnmutePlayer", ply)
```

## Arguments

1. Player ply
> The player that should get unmuted