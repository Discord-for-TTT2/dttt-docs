---
title: DTTTMuteAllPlayers
type: docs
prev: /dttt/hooks
sidebar:
  open: true
---

```lua
DTTTMuteAllPlayers()
```

## Description
Can be called to mute all players in the lobby.
To mute a specific player use [DTTTMutePlayer]({{<ref "DTTTMutePlayer">}})

Running this hook directly avoids checks for [dttt_enable_mute_logic]({{<ref "enable_mute_logic">}}) and [dttt_enable_mute]({{<ref "enable_mute">}})

### Example
```lua
hook.Run("DTTTMuteAllPlayers")
```