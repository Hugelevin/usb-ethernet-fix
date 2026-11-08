# USB Ethernet Fix for TV

A fast wired connection for Android TV and Google TV over a USB Ethernet adapter, on TVs that stopped supporting them (for example Philips TVs on Android TV 14). The app drives the adapter itself. No root needed.

**[Download the latest version](https://github.com/Hugelevin/usb-ethernet-fix/releases/latest)** · **[Help pages](https://hugelevin.github.io/usb-ethernet-fix/)** · **[Report a problem](https://github.com/Hugelevin/usb-ethernet-fix/issues/new?template=problem.yml)**

## Install on the TV

1. Install **Downloader** (by AFTVnews) from the Play Store on the TV.
2. In the TV's Settings, allow Downloader to install unknown apps.
3. In Downloader, type `hugelevin.github.io/usb-ethernet-fix/get` and select Go.
4. Install, then open **USB Ethernet Fix**.

Full steps: [Install the app](https://hugelevin.github.io/usb-ethernet-fix/install.html).

## What it does

- **Full Speed** for Realtek RTL8153 adapters, such as the TP-Link UE300: about 900 Mbps on a gigabit network.
- **Compatible** mode for other standard USB Ethernet adapters.
- Reconnects by itself after standby and restarts, with auto-connect turned on.
- Built-in speed test, a DNS choice (router, Cloudflare or your own) and a Report a Problem QR code.

See [Supported adapters](https://hugelevin.github.io/usb-ethernet-fix/adapters.html) for what has been tested.

## Good to know

- Android shows the connection as a VPN, because that's the only way an app may carry a TV's network traffic. Your traffic goes from the TV through the adapter to your router and nowhere else.
- No ads, no accounts, nothing collected.
- Auto-connect is an accessibility service that only presses OK on Android's USB access prompt. You turn it on yourself, and it does nothing else.

## Reporting a problem

In the app, open Settings, then About & Support, and scan the **Report a Problem** QR code with your phone. It opens a report already filled in with the app version, adapter and connection details, with no IP or MAC addresses. You choose whether to send it.

---

Not made by or affiliated with Philips, Google, TP-Link or Realtek.
