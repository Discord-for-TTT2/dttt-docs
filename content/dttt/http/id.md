---
title: Id
type: docs
prev: /dtt
sidebar:
  open: true
---

Sends a request to get the Discord id for the name set in Garry's Mod/Steam.

Used internally for auto-mapping SteamID<->DiscordID.

## HTTP Request

GET /id

### Query Parameters:

`nick`: The player's nickname
`name`: The player's username

### Response

```json
{
  "name": "",
  "nick": "",
  "id": ""
}
```

| key  | type   | value            |
| ---- | ------ | ---------------- |
| name | string | Discord username |
| nick | string | Discord nickname |
| id   | string | Discord id       |
