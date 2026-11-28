<p align="center">
  <img src="docs/assets/logo.svg" width="96" alt="MyExe VPN logo">
</p>

<h1 align="center">MyExe VPN</h1>

<p align="center">
  <b>A free, stealth-focused VPN client for Windows.</b><br>
  One click to connect. It finds and tests working servers for you, routes your
  whole PC through an encrypted tunnel, and keeps working on restrictive networks
  that try to block or throttle VPN traffic.
</p>

<p align="center">
  <a href="../../releases/latest"><img alt="Latest release" src="https://img.shields.io/github/v/release/sirbits/myexe-vpn-releases?label=latest&color=2ea44f"></a>
  <a href="../../releases"><img alt="Downloads" src="https://img.shields.io/github/downloads/sirbits/myexe-vpn-releases/total?color=blue"></a>
  <img alt="Platform" src="https://img.shields.io/badge/platform-Windows%2010%20%2F%2011%20(64--bit)-0078d6">
  <img alt="Status" src="https://img.shields.io/badge/status-experimental-orange">
</p>

<p align="center">
  <a href="../../releases/latest"><b>Download the latest release</b></a>
</p>

---

> **Experimental.** This is early software under active development. Expect rough
> edges, occasional instability and breaking changes between releases. Use at
> your own risk.
>
> Downloads are on the [**Releases**](../../releases) page. The source code is
> not part of this repository.

## Features

- **One-click connect (AUTO).** No server list to manage. The app continuously
  discovers, tests and ranks working servers and picks the fastest, switching
  automatically if one slows down or fails.
- **Bring your own servers (USER).** Import your own configs or subscription
  links. Supports VLESS, VMess, Trojan, Shadowsocks, Hysteria2, TUIC, SSH,
  WireGuard, SSR, Snell and more.
- **System-wide tunnel.** Route *all* PC traffic through the tunnel with a TUN
  adapter, with no need to configure a proxy in each app. Falls back to a system
  proxy automatically.
- **Stealth built in.** Adaptive DPI evasion that learns and evolves per network,
  TLS fragmentation, CDN domain-fronting (Cloudflare and CloudFront), traffic
  shaping and fake-packet techniques help the connection survive deep-packet
  inspection on tough networks.
- **Share to your phone.** Turn your PC into a Wi-Fi hotspot that shares the
  protected connection, with a built-in captive-portal login and per-device
  access control.
- **Leak protection.** A host-wide kill-switch holds the block the instant a
  connection drops, so your real IP stays hidden while the tunnel re-establishes.
  Fake-DNS stops any DNS query from leaking your browsing.
- **Blocks ads and trackers.** A self-updating blocklist stops ad and tracker
  domains for your whole PC, and for every device sharing the hotspot.
- **Clean, compact desktop UI.** Live connection status, honest switch logging,
  and a signed installer.

## Install

1. Download `MyExe-VPN-Setup-<version>.exe` from the
   [**Releases**](../../releases) page.
2. Run the installer. Because it is a new app from an independent developer,
   Windows SmartScreen may warn you. Click **More info** then **Run anyway**.
3. Launch **MyExe VPN**. For the system-wide tunnel and the hotspot, allow the
   **Administrator** prompt (Windows needs it to create the network adapter and
   the hotspot).

## Using it

- **AUTO mode:** just press connect. It handles server discovery and failover.
- **USER mode:** add or import your own server(s) and the app runs only those.
- **Hotspot:** toggle it on to share the connection. Devices join the Wi-Fi and
  sign in on the portal page.

## Requirements

- Windows 10 or 11, 64-bit.
- Administrator rights for the system-wide tunnel and the Wi-Fi hotspot. Ordinary
  proxy mode works without admin.

## Privacy and responsible use

MyExe VPN is for lawful privacy and for accessing an open internet. In AUTO mode
you may be routed through community or public servers operated by third parties.
Treat such connections like any public network. You are responsible for complying
with your local laws and with the terms of any service you reach through it.
Provided **as-is, without warranty of any kind**.

## Support

Found a bug or have a request? Open an issue on the [**Issues**](../../issues)
page.

<!-- v1.2.1 -->
