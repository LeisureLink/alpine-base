# leisurelink/alpine-base

A minimal [Alpine Linux](https://alpinelinux.org/) based docker image with the [s6 process supervisor](https://github.com/just-containers/s6-overlay) applied.

## What's in the box

This docker image adds the `s6-overlay` to the official [alpine image](https://hub.docker.com/_/alpine/).

The container does not specify a command; your container based on this one should.

## Tags (Asset Versions)

* **1.0.0** (Alpine 3.2, S6 Overlay v1.17.1.1)
* **1.0.2** (Alpine 3.3, S6 Overlay v1.17.2.0)


## License

[MIT](https://github.com/LeisureLink/alpine-base/blob/master/LICENSE)
