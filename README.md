# Sandbox for building a new Gatling knowlege center

## Local Development

Pre-requisites: [Hugo](https://gohugo.io/getting-started/installing/), [Go](https://golang.org/doc/install) and [Git](https://git-scm.com)


1. Clone the repo


2. Change directory

```console
cd gatling-docs-sandbox
```

3. Start the server

```console
hugo mod tidy
hugo server --logLevel debug --disableFastRender -p 3000
```




### Update theme

```shell
hugo mod get -u
hugo mod tidy
```

See [Update modules](https://gohugo.io/hugo-modules/use-modules/#update-modules) for more details.

