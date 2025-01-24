---
title: Contributing
type: docs
prev: /development
---

## The repository

Start by forking the GitHub repository:
https://github.com/Discord-for-TTT2/dttt-backend/fork

And clone it using \*git

<small>\* [git](https://git-scm.com/) is a very popular version control system</small>

### Merging

Just open up a pull request on the [GitHub repository](https://github.com/Discord-for-TTT2/dttt-backend) explaining your changes and your reason.  
We'll make sure to check them out!

## Dependencies

### Node.js

Node.js is the tool that we use to execute JavaScript code.
Install it for your platform via the instructions from:  
https://nodejs.org

### JavaScript Libraries

Install the required modules with your preferred package manager.

{{< tabs items="yarn,npm" >}}

{{< tab >}}

```shell
yarn install
```

{{< /tab >}}
{{< tab >}}

```shell
npm install
```

{{< /tab >}}

{{< /tabs >}}

## Launching development mode

We use nodemon to monitor for file changes and relaunch the bot once it notices any.
To launch it you can use the script defined in the [package.json](https://github.com/Discord-for-TTT2/dttt-backend/blob/8ab06731b8608fbb7c422cbcb0868d9d90d18569/package.json#L13).
This can be done using your preferred package manager like this:
{{< tabs items="yarn,npm" >}}

{{< tab >}}

```shell
yarn dev
```

{{< /tab >}}
{{< tab >}}

```shell
npm run dev
```

{{< /tab >}}

{{< /tabs >}}

## Coding

The language we use for this project is TypeScript, if you are familiar with any typed language, you will get the hang of it pretty quickly.
Nonetheless, I recommend you to check out the [TypeScript Handbook](https://www.typescriptlang.org/docs/handbook/) and get used to TypeScript first!

## Building

To compile it for a release, we use the bundler esbuild. Run it via our build script located in scripts/build.sh, that you of course run with your package manager:

{{< tabs items="yarn,npm" >}}

{{< tab >}}

```shell
yarn build
```

{{< /tab >}}
{{< tab >}}

```shell
npm run build
```

{{< /tab >}}

{{< /tabs >}}

## Running

To test your built code you can use the start script.
{{< tabs items="yarn,npm" >}}

{{< tab >}}

```shell
yarn start
```

{{< /tab >}}
{{< tab >}}

```shell
npm run start
```

{{< /tab >}}

{{< /tabs >}}

## External interfaces

The library we use to communicate with the Discord API is called discord.js for which the documentation can be found at: https://discord.js.org/docs

When communicating with our base addon DTTT, use the reference [documentation]({{< ref "http" >}}).
If you need help with HTTP requests, check out the great documentation from the mozilla foundation: https://developer.mozilla.org/en-US/docs/Web/HTTP/Methods
