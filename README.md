<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/logo-dark.png">
    <img alt="PixelBrew — a Good Eye Studios project" src="assets/logo.png" width="540">
  </picture>
</p>

**Drive your USB mini-LCD panel with whatever you want.**
A lightweight Windows app from **Good Eye Studios** that pushes custom content —
graphs, video, YouTube, a mirrored window, a clock, an audio spectrum, and more —
to a small USB-HID LCD panel (the kind bundled with some CPU coolers), replacing
the stock vendor software.

<p>
  <a href="https://ko-fi.com/goodeyebrad">
    <img alt="Buy me a bag of beans" src="https://img.shields.io/badge/%E2%98%95%20buy%20me%20a%20bag%20of%20beans-Ko--fi-FF5E5B">
  </a>
  <a href="../../releases/latest">
    <img alt="Download" src="https://img.shields.io/badge/download-latest-2b7cff">
  </a>
</p>

> **Donationware.** PixelBrew is free to use. If it earns a spot on your desk,
> you can toss a few beans in the jar — see [Support](#support). No purchase, no
> license key, no nag screens.

---

## ⚠️ Not affiliated with Thermalright

PixelBrew is an **independent, clean reimplementation** created for
**interoperability with hardware you already own**. It is **not** affiliated with,
endorsed by, or connected to Thermalright or any panel manufacturer. All product
names, trademarks, and registered trademarks are property of their respective
owners. No vendor code, firmware, or assets are included. See [`TERMS.md`](TERMS.md).

---

## What it does

Pick a **source**, point it at the panel, hit **Start**. Build a **queue** of
sources that rotate on timers, loop, and show a live countdown. Minimizes to the
system tray.

**Sources**
- 🧪 Test pattern &nbsp;·&nbsp; 🖼️ Image &nbsp;·&nbsp; 🎬 Video file
- ▶️ YouTube &nbsp;·&nbsp; 📡 Live stream (URL / RTSP / HLS)
- 🖥️ Screen region &nbsp;·&nbsp; 🪟 Window capture
- 📊 System monitor (CPU / GPU / disk / network graphs, configurable)
- 🎵 Audio spectrum analyzer (selectable audio device)
- 🕒 Clock &nbsp;·&nbsp; ⛅ Weather &nbsp;·&nbsp; 🗂️ Slideshow
- 📱 **DLNA cast target** — cast to PixelBrew from a phone/app on your LAN

**Panel control**
- Rotate in 90° steps (the panel often mounts sideways)
- Resolution probe / calibration card
- 8 built-in themes (Luna, Graphite, Zune, Windows 98, Aero…) **+ user themes**

## Download

1. Grab the latest **[release ZIP](../../releases/latest)**.
2. Unzip anywhere and run **`PixelBrew.exe`** — it's self-contained, no .NET install needed.
3. **Close the stock vendor app first** — it holds the panel open.

**Requirements:** Windows 10/11. Some sources use the bundled **ffmpeg** (video/
stream/YouTube) and **yt-dlp** (YouTube); see [`third-party-licenses/`](third-party-licenses/).

What changed between versions is in the [changelog](CHANGELOG.md); older releases
stay available on the [Releases](../../releases) page.

## Questions / ideas

Head to **[Discussions](../../discussions)** for help, feature ideas, and show-and-tell,
or open an **[Issue](../../issues)** for bugs.

## Support

PixelBrew is free. If you'd like to **buy me a bag of beans**:
👉 **https://ko-fi.com/goodeyebrad**

## License

Proprietary freeware — see [`LICENSE`](LICENSE) and [`TERMS.md`](TERMS.md).
Bundled third-party tools keep their own licenses; see
[`third-party-licenses/`](third-party-licenses/).

---

*PixelBrew · a Good Eye Studios project.*
