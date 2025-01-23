---
title: DTTTPlayerMuted
type: docs
prev: /dttt/hooks
sidebar:
  open: true
---

```lua
DTTTPlayerMuted(Player ply, boolean mute_status)
```

## Description
Called when the mute state of the Player changes.

This only gets called when the state actually got changed so disabling [ConVars]({{<ref "convars">}}) like [dttt_enable_mute_logic]({{<ref "enable_mute_logic">}}), [dttt_enable_mute]({{<ref "enable_mute">}}) or [dttt_enable_unmute]({{<ref "enable_unmute">}}) may result in this hook not triggering.


### Example
```lua
hook.Add("DTTTPlayerMuted", "PrintMutedPlayer", function(ply)
  print("Player Muted")
  print(ply:Name())
end)
```

## Arguments

1. Player ply
> The player that got muted/unmuted

2. boolean mute_status
> The new mute status of the player