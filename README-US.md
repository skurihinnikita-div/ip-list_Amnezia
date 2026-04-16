# 🛡 AmneziaVPN: CIDR lists for Split Tunneling

Ready-to-use IP network (CIDR) sets for routing **only specific sites through VPN** in AmneziaVPN.  
Bypass censorship without overloading your channel or CPU.

## 📦 Contents

| File | Number of networks | Coverage |
|------|--------------------|-----------|
| `compact.json` | ~96 | Top‑20 services (Telegram, YouTube, Google, Meta, Discord, Netflix, Spotify, AWS, Cloudflare, Hetzner) |
| `medium.json` | ~365 | Almost all foreign CDNs, clouds, hosting, social networks (extended) |
| `full.json` | ~1600+ | Whole IPv4 (slow, not recommended) |

## 🚀 Quick start

1. Download the JSON file you need.
2. In AmneziaVPN: **Settings → Split Tunneling → Only specified sites go through VPN**.
3. Click **Import** and choose the file.
4. Reconnect VPN.

> ✅ The lists contain only CIDR networks (IP with masks), so they work fast without a DNS proxy.

## 🧠 Recommendation

- Start with `compact.json` – it's enough for 99% of users.
- If some site doesn't open – add its IP network manually (`nslookup` + `whois`).
- `medium.json` – for maximum coverage without heavy CPU load.

## 📜 License

MIT – free to use.

## 🙏 Credits

Compiled from public RIPE, ARIN lists and personal tests.
