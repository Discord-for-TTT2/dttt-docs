---
title: Custom
type: docs
prev: /development
---

To implement your own custom backend, all you need is:

- a HTTP handler
- a way to communicate with the Discord API (a barebones HTTP handler could suffice, but is unnecessarily complicated when starting out)
- some knowledge in programming

## Communicating with Discord

Start by searching for a Discord library in your favorite programming language.
A few examples:

- C#: [Discord.Net](https://github.com/discord-net/Discord.Net)
- Java: [Discord4J](https://github.com/Discord4J/Discord4J)
- Discord.js: [JavaScript/TypeScript](https://github.com/discordjs/discord.js)
- Python: [discord.py](https://github.com/Rapptz/discord.py)

find more, including your favorite language, in this [repository](https://github.com/apacheli/discord-api-libs)!

## Communicating with DTTT (Discord for TTT2)

You just need to expose an HTTP webserver, that handles the requests defined in the [DTTT documentation]({{< ref "http" >}}).

## Knowledge in programming

Not a lot is required if you are willing to learn!
Just start and see where it leads you!
If you need some starting points, start with one of the libraries mentioned in [Communicating with Discord](#communicating-with-discord) and google your way through like:
"discord.js mute users"
"node.js http server"

and built your first application step by step! (It does not need to be perfect)
