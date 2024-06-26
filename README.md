# esp32-rust-mqtt [![Build project with nix](https://github.com/n8henrie/esp32-rust-mqtt/actions/workflows/build.yml/badge.svg)](https://github.com/n8henrie/esp32-rust-mqtt/actions/workflows/build.yml)

This will eventually be a little rust-based esp32 project for connecting up
esp32 to mqtt, using nix as a build system. I'm hoping to have it build from
aarch64-darwin as well as x86_64-linux.

Using nix adds some complexity but should help ensure reproducibility; my blog
post detailing my process for getting a prior iteration working (prior to [the
release of `esp-wifi` on crates.io](https://crates.io/crates/esp-wifi)) may be
useful to novices and hobbyists (such as myself):
https://n8henrie.com/2023/09/compiling-rust-for-the-esp32-with-nix/
