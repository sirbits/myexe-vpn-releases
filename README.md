<p align="center">
  <img src="docs/assets/logo.svg" width="96" alt="MyExe VPN logo">
</p>

# MyExe VPN

**A free, stealth-focused VPN client for Windows.** One click to connect - it
finds and tests working servers for you, routes your whole PC through an
encrypted tunnel, and is built to keep working on restrictive networks that try
to block or throttle VPN traffic.

> ⚠️ **Experimental.** This is early software under active development - expect
> rough edges, occasional instability and breaking changes between releases.
> Use at your own risk.

> Downloads are on the [**Releases**](../../releases) page. Source code is not
> part of this repository.

---

## Features

- **One-click connect (AUTO).** No server list to manage - the app continuously
  discovers, tests and ranks working servers and picks the fastest.
- **Bring your own servers (USER).** Import your own configs or subscription
  links. Supports VLESS, VMess, Trojan, Shadowsocks, Hysteria2, TUIC, SSH,
  WireGuard, SSR, Snell and more.
- **System-wide tunnel.** Route *all* PC traffic through the tunnel with a TUN
  adapter - no need to configure a proxy in each app. Falls back to a system
  proxy automatically.
- **Stealth built in.** Adaptive DPI evasion that learns and evolves per network,
  TLS fragmentation, CDN domain-fronting (Cloudflare & CloudFront), traffic shaping
  and fake-packet techniques help the connection survive deep-packet inspection on
  tough networks.
- **Share to your phone.** Turn your PC into a Wi-Fi hotspot that shares the
  protected connection, with a built-in captive-portal login and per-device
  access control.
- **Safety controls.** Block-direct / kill-switch so nothing leaks around the
  tunnel, fake-DNS so no DNS query leaks your browsing, plus optional bridges and
  encrypted DNS.
- **Blocks ads & trackers.** A self-updating blocklist stops ad and tracker
  domains for your whole PC - and for every device sharing the hotspot.
- **Clean, compact desktop UI.**

## Install

1. Download `MyExe-VPN-Setup-<version>.exe` from the
   [**Releases**](../../releases) page.
2. Run the installer. Because it's a new app from an independent developer, Windows SmartScreen may
   warn you - click **More info → Run anyway**.
3. Launch **MyExe VPN**. For the system-wide tunnel and the hotspot, allow the
   **Administrator** prompt (Windows needs it to create the network adapter and
   the hotspot).

## Using it

- **AUTO** mode: just press connect - it handles server discovery and failover.
- **USER** mode: add or import your own server(s) and the app runs only those.
- **Hotspot**: toggle it on to share the connection; devices join the Wi-Fi and
  sign in on the portal page.

## Requirements

- Windows 10 or 11, 64-bit.
- Administrator rights for the system-wide tunnel and the Wi-Fi hotspot
  (ordinary proxy mode works without admin).

## Privacy & responsible use

MyExe VPN is for lawful privacy and for accessing an open internet. When using
AUTO mode you may be routed through community/public servers operated by third
parties - treat such connections like any public network. You are responsible
for complying with your local laws and with the terms of any service you reach
through it. Provided **as-is, without warranty of any kind**.

## Support

Found a bug or have a request? Open an issue on the
[**Issues**](../../issues) page.

<!-- v1.1.0 -->
