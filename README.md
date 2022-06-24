# Hopper ![License](https://img.shields.io/github/license/BRA1L0R/hopper-rs?style=flat-square)

<img src="./.github/hopper.webp" align="right" width="180">

**Hopper** is a lightweight reverse proxy for minecraft. It allows you to connect multiple servers under the same IP and port, with additional functionalities, just like **Nginx**. It is built with **Rust 🦀** to ensure maximum performance and efficiency.

Hopper works starting from version **1.7** up to the **latest** version of Minecraft.

## Configuration

Example `Config.toml`:

```toml
# the address hopper will listen on
listen = "0.0.0.0:25565"

# list of servers fronted by hopper
[routing.routes]
mc.gaming.tk = "127.0.0.1:25008"
other.gaming.tk = "127.0.0.1:25009"
```

## How to run

- TODO: cargo build explaination
- TODO: Doker image
- TODO: Github release
