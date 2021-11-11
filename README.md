# Simple HTTP Proxy Server

Simple HTTP proxy server powered by [hyperium/hyper](https://github.com/hyperium/hyper) with musl release

This project is just a modified version of [hyper http_proxy.rs example](https://github.com/hyperium/hyper/blob/master/examples/http_proxy.rs).

## Download

Download from [GitHub Release](https://github.com/ganlvtech/http-proxy-server-rs/releases)

## Usage

```bash
./http-proxy 127.0.0.1:8080
```

## Build

```bash
alias rust-musl-builder='docker run --rm -it -v "$(pwd)":/home/rust/src nwtgck/rust-musl-builder:1.56.1'
rust-musl-builder cargo build --release --target=x86_64-unknown-linux-musl
```

## License

[MIT License](https://github.com/hyperium/hyper/blob/master/LICENSE)
