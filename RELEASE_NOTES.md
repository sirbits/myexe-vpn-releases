# MyExe VPN v1.2.0

**Experimental** - early software under active development. Expect rough edges
and breaking changes between releases. Use at your own risk.

## What's new in v1.2.0
- **No real-IP leak on reconnect.** A host-wide kill-switch holds the block the
  instant a connection drops, so your traffic stays protected while the app
  re-establishes the tunnel.
- **No unexpected self-exit.** The app no longer quits on its own after being
  connected for a while, and a background UI window recycling can no longer bring
  down the whole app.
- **Single taskbar button.** Only one window shows on the taskbar during splash
  and after start.
- **Private logs.** Connection logs no longer print your network or operator name.
- **Live server in the UI.** The server dropdown follows the node actually in use
  and updates instantly as the fastest-node pilot switches routes.
- **Clean exit.** On close or crash, all child processes and helper threads are
  torn down with nothing left running in the background.
- **Signed installer** with a valid Authenticode signature.

## Highlights
- One-click **AUTO** mode: automatic server discovery, testing and failover.
- **USER** mode: run your own servers or imported subscriptions (VLESS, VMess,
  Trojan, Shadowsocks, Hysteria2, TUIC, SSH, WireGuard, SSR, Snell, and more).
- **System-wide tunnel** (TUN) with automatic system-proxy fallback.
- **Stealth:** adaptive DPI evasion, TLS fragmentation and CDN domain-fronting
  (Cloudflare and CloudFront) to survive deep-packet inspection.
- **Wi-Fi hotspot** sharing with a captive-portal login and per-device access.
- **Leak protection:** kill-switch and fake-DNS, plus encrypted DNS and bridges.
- **Blocks ads and trackers** device-wide and for every hotspot client.

## Install
Download `MyExe-VPN-Setup-1.2.0.exe` below and run it. The installer is
code-signed, but because the publisher is independent, SmartScreen may still warn:
click **More info** then **Run anyway**. Launch as **Administrator** for the
system-wide tunnel and the hotspot.

## Notes
- Windows 10/11, 64-bit.
- Provided as-is, without warranty. See LICENSE.
