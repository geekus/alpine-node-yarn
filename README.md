# Alpine 3.5 Node LTS 6.9.2  with Yarn

*This build removes NPM*

```docker build -t alpine-node-yarn .```


##Want to change versions?

```docker build --build-arg NODE_VERSION=6.9.2 --build-arg=YARN_VERSION=0.18.1 .```
- [Available Node Versions](https://pkgs.alpinelinux.org/packages?name=nodejs&branch=v3.5)
- [Avaialable Yarn Versions](https://github.com/yarnpkg/yarn/releases)
