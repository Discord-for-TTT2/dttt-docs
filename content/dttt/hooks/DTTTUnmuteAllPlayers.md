---
title: DTTTUnmuteAllPlayers
type: docs
prev: /dttt/hooks
sidebar:
  open: true
---

```lua
DTTTUnmuteAllPlayers()
```

## Description
Can be called to unmute all players in the lobby.
To unmute a specific player use [DTTTUnmutePlayer]({{<ref "DTTTUnmutePlayer">}})

Running this hook directly avoids checks for [dttt_enable_internal_mute_logic]({{<ref "enable_internal_mute_logic">}}) and [dttt_enable_internal_unmute]({{<ref "enable_internal_unmute">}})

### Example
```lua
hook.Run("DTTTUnmuteAllPlayers")
```