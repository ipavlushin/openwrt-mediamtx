# [MediaMTX Builder for OpenWrt](https://lanrat.github.io/openwrt-tailscale-repo)

Builds MediaMTX combined ipk packages for OpenWrt.

For information on how to use this, see: [ipavlushin.github.io/openwrt-mediamtx](https://ipavlushin.github.io/openwrt-mediamtx).


## Building

Run `build.sh`.

Optionally set `ARCH` and/or `BRANCH` to override the default architecture and version to build

Opkg feed and ipk files are generated in `packages/`!


## Adding A New Architecture?

Submit a pull request (preferred) or issue with the correct `GOARCH` and opkg `Architecture`.
