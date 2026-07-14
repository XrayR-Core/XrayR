# XrayR

[![](https://img.shields.io/badge/TgChat-@XrayR讨论-blue.svg)](https://t.me/XrayR_project)
[![](https://img.shields.io/badge/Channel-@XrayR通知-blue.svg)](https://t.me/XrayR_channel)
![](https://img.shields.io/github/stars/XrayR-Core/XrayR)
![](https://img.shields.io/github/forks/XrayR-Core/XrayR)
![](https://github.com/XrayR-Core/XrayR/actions/workflows/release.yml/badge.svg)
![](https://github.com/XrayR-Core/XrayR/actions/workflows/docker.yml/badge.svg)
[![GitHub All Releases](https://img.shields.io/github/downloads/XrayR-Core/XrayR/total.svg)]()

[Chinese](./README-cn.md) | [English](./README-en.md) | [Iranian (Farsi)](./README_Fa.md) | [Vietnamese](./README-vi.md)

XrayR is a backend framework built on Xray-core that supports V2Ray, Trojan, and Shadowsocks protocols. It is easy to extend and supports integration with multiple panel systems.

If you find this project useful, please consider giving it a `star` and `watch`.

## Documentation

Detailed guide: [XrayR Documentation](https://xrayr-Core.github.io/XrayR-doc/)

## Disclaimer

This project is maintained as a personal learning and development effort. No warranty is provided. The author is not responsible for any consequences caused by using this software.

## Features

- Fully open-source and free.
- Supports multiple protocols: V2Ray, Trojan, and Shadowsocks.
- Supports modern features such as VLESS and XTLS.
- Supports multi-panel and multi-node integration in a single instance.
- Supports online IP limit.
- Supports both node-level and user-level rate limiting.
- Simple and clear configuration.
- Automatically restarts after configuration changes.
- Easy to build and upgrade, with fast Xray-core updates.

## Capability Matrix

| Capability | V2Ray | Trojan | Shadowsocks |
|---|---|---|---|
| Fetch node information | √ | √ | √ |
| Fetch user information | √ | √ | √ |
| User traffic statistics | √ | √ | √ |
| Report server information | √ | √ | √ |
| Auto-issue TLS certificates | √ | √ | √ |
| Auto-renew TLS certificates | √ | √ | √ |
| Online user counting | √ | √ | √ |
| Online user limits | √ | √ | √ |
| Audit rules | √ | √ | √ |
| Node port rate limiting | √ | √ | √ |
| User-level rate limiting | √ | √ | √ |
| Custom DNS | √ | √ | √ |

## Supported Panels

| Panel | V2Ray | Trojan | Shadowsocks |
|---|---|---|---|
| sspanel-uim | √ | √ | √ (single-port multi-user and V2Ray-Plugin) |
| v2board | √ | √ | √ |
| [PMPanel](https://github.com/ByteInternetHK/PMPanel) | √ | √ | √ |
| [ProxyPanel](https://github.com/ProxyPanel/ProxyPanel) | √ | √ | √ |
| [WHMCS (V2RaySocks)](https://v2raysocks.doxtex.com/) | √ | √ | √ |
| [GoV2Panel](https://github.com/pingProMax/gov2panel) | √ | √ | √ |
| [BunPanel](https://github.com/pennyMorant/bunpanel-release) | √ | √ | √ |

## Installation

<<<<<<< HEAD
### One-click install
=======
| 前端                                                     | v2ray | trojan | shadowsocks             |
|--------------------------------------------------------|-------|--------|-------------------------|
| sspanel-uim                                            | √     | √      | √ (单端口多用户和V2ray-Plugin) |
| v2board                                                | √     | √      | √                       |
| [PMPanel](https://github.com/ByteInternetHK/PMPanel)   | √     | √      | √                       |
| [ProxyPanel](https://github.com/ProxyPanel/ProxyPanel) | √     | √      | √                       |
| [WHMCS (V2RaySocks)](https://v2raysocks.doxtex.com/)   | √     | √      | √                       |
| [GoV2Panel](https://github.com/pingProMax/gov2panel)   | √     | √      | √                       |
| [BunPanel](https://github.com/pennyMorant/bunpanel-release)   | √     | √      | √                       |
| [Xboard](https://github.com/cedar2025/Xboard)          | √     | √      | √                       |
>>>>>>> c6b9a8db (Add Xboard panel compatibility)

```bash
wget -N https://raw.githubusercontent.com/XrayR-Core/XrayR-release/master/install.sh && bash install.sh
```

### Docker

[Docker deployment tutorial](https://xrayr-Core.github.io/XrayR-doc/xrayr-xia-zai-he-an-zhuang/install/docker)

### Manual install

[Manual installation tutorial](https://xrayr-Core.github.io/XrayR-doc/xrayr-xia-zai-he-an-zhuang/install/manual)

## Configuration and Usage

[Detailed tutorial](https://xrayr-Core.github.io/XrayR-doc/)

## Acknowledgements

- [Project X](https://github.com/XTLS/)
- [V2Fly](https://github.com/v2fly)
- [VNet-V2ray](https://github.com/ProxyPanel/VNet-V2ray)
- [Air-Universe](https://github.com/crossfw/Air-Universe)

## License

[Mozilla Public License Version 2.0](./LICENSE)

## Telegram

[XrayR Discussion Group](https://t.me/XrayR_project)

[XrayR Channel](https://t.me/XrayR_channel)

<<<<<<< HEAD
## Stargazers Over Time

[![Stargazers over time](https://starchart.cc/XrayR-Core/XrayR.svg)](https://starchart.cc/XrayR-Core/XrayR)
=======
>>>>>>> c6b9a8db (Add Xboard panel compatibility)
