---
title: Mute
type: docs
prev: /dtt
sidebar:
  open: true
---

Sends a request to get the Discord id for the name set in Garry's Mod/Steam.

Used internally for auto-mapping SteamID<->DiscordID.

## HTTP Request

POST /mute

### Body

```json
{
    "id": ""
    "status": false
}
```

| key    | type    | value             |
| ------ | ------- | ----------------- |
| id     | string  | Discord id        |
| status | boolean | Mute[1]/Unmute[0] |

### Response

#### Success

**Code**: 200/OK

#### Fail

**Codes**:  
400: Invalid Request  
500: Internal Server Error
