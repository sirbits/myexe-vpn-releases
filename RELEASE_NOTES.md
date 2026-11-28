# MyExe VPN v1.2.1

**Experimental** - early software under active development. Expect rough edges
and breaking changes between releases. Use at your own risk.

## What's new in v1.2.1
- **WebRTC leak closed.** A direct-route shortcut could let a browser reveal
  your real address through WebRTC. Only the traffic that needs the shortcut now
  uses it, and the installer can set Chrome, Edge, Brave and Firefox to keep
  WebRTC on the tunnel.
- **Fast Lane is now a fallback.** Everything goes through the tunnel first. The
  direct lane takes over on its own only when the tunnel stops carrying traffic,
  and hands back as soon as the tunnel recovers.
- **DNS stays on a working path.** Encrypted DNS no longer waits behind a route
  that is still connecting, which caused pages to stall after connect.
- **Stability.** Fixed a crash in the packaged app after long sessions and a
  case where a second copy would close itself in proxy mode.
- **Live traffic meter.** The speed and usage display follows the tunnel
  continuously.
- **Lighter while connected.** Background server testing slows down while you
  are connected, and dead or delisted servers are pruned sooner.
- **Cleaner exit and updates.** Firewall rules and TTL settings are released on
  exit, leftovers from an interrupted session are repaired at the next start,
  and the installer releases the packet driver so an update is never blocked.

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
Download `MyExe-VPN-Setup-1.2.1.exe` below and run it. The installer is
code-signed, but because the publisher is independent, SmartScreen may still warn:
click **More info** then **Run anyway**. Launch as **Administrator** for the
system-wide tunnel and the hotspot.

## Notes
- Windows 10/11, 64-bit.
- Provided as-is, without warranty. See LICENSE.
