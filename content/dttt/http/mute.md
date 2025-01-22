---
title: Mute
type: docs
prev: /dtt
sidebar:
  open: true
---

Sends a request to mute/unmute a specified Discord user.

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
