# Discord for TTT2 - Documentation

This is is the documentation for the Discord for TTT2 Addon, but also all custom addons and forks for it that we maintain!

This project is built on:

- [Hugo](https://gohugo.io/)
- [Hextra](https://github.com/imfing/hextra)
- [GitHub Pages](https://pages.github.com/)

## Local Development

Pre-requisites: [Hugo](https://gohugo.io/getting-started/installing/), [Go](https://golang.org/doc/install) and [Git](https://git-scm.com)

```shell
# Clone the repo
git clone https://github.com/Discord-for-TTT2/dttt-docs

# Change directory
cd dttt-docs

# Start the server
hugo mod tidy
hugo server --logLevel debug --disableFastRender -p 1313
```

### Update theme

```shell
hugo mod get -u
hugo mod tidy
```

See [Update modules](https://gohugo.io/hugo-modules/use-modules/#update-modules) for more details.
