<div align="center">

<img src=".github/banner.png" alt="FitMaker — Custom FiveM clothing, no Blender needed" width="100%">

# FitMaker

### Custom FiveM clothing, no Blender needed

<a href="https://github.com/KVRNL/fitmaker/releases/latest"><img alt="Latest version" src="https://img.shields.io/github/v/release/KVRNL/fitmaker?display_name=tag&label=version&color=F5A623&labelColor=0d0d0f&style=for-the-badge"></a>
<img alt="Platform" src="https://img.shields.io/badge/platform-Windows%2010%20%7C%2011-0d0d0f?style=for-the-badge&labelColor=0d0d0f">
<img alt="Price" src="https://img.shields.io/badge/price-FREE-F5A623?style=for-the-badge&labelColor=0d0d0f">
<a href="./LICENSE"><img alt="License" src="https://img.shields.io/badge/license-Proprietary%20Freeware-0d0d0f?style=for-the-badge&labelColor=0d0d0f"></a>

<br>

Design custom clothing for your FiveM server without Blender, OpenIV, or CodeWalker. Restyle a base garment with colours, patterns, and your own logos, preview it in 3D on the freemode ped, and export a drop-in resource that streams straight onto your server.

### **[⬇&nbsp; Download FitMaker — free at kvrnl.io](https://kvrnl.io/products/fitmaker/)**

</div>

<br>

---

## What it does

FitMaker takes the pain out of making FiveM clothing. Pick a base garment, recolour it, drop on patterns and your own logos, and watch it update live in 3D on the male or female freemode ped — no Blender, no OpenIV, no CodeWalker, and none of the modelling knowledge they usually demand.

When it looks right, FitMaker exports a clean, drop-in resource folder that streams straight onto your server — correctly named and ready to go. The heavy 3D engine it needs sets itself up on first run, so there's nothing to install by hand. Free to use; claim your license key and download it straight from this page.

## Features

- **Restyle base garments — colours, patterns & your own logos**
- **Live 3D preview on the male or female freemode ped**
- **Exports a drop-in resource that streams onto your server**
- **No Blender, OpenIV, or CodeWalker — it's all built in**

## Download &amp; install

FitMaker is **completely free**. Each install needs its own license key, which you get
with a free KVRNL account.

1. Go to **[kvrnl.io/products/fitmaker/](https://kvrnl.io/products/fitmaker/)**
2. Create a free account — email verification, nothing else
3. Claim your license key — instant, no waiting
4. Download and install

> [!NOTE]
> FitMaker isn't code-signed yet, so Windows SmartScreen may warn you on first run.
> Click **More info → Run anyway**. Code signing is on the roadmap.

## Your license key

- **Free, one per product**, issued from your KVRNL account.
- **A key activates on one machine.** The first device to activate it claims it.
- **Switching computers?** Hit **Release device** on your
  [account page](https://kvrnl.io/account/) and the key is free to use again.
- Keys are checked over HTTPS at launch. See [Privacy](#privacy).

## Requirements

- **Windows 10 or 11** (64-bit)
- A free [KVRNL account](https://kvrnl.io/signup/) for your license key

## Privacy

FitMaker sends KVRNL only what's needed to validate your license: **the key, the
product name, and a hardware ID**. No telemetry, no analytics, no tracking, and
none of your files. Full policy: **[kvrnl.io/privacy](https://kvrnl.io/privacy/)**

## What's new

**v1.0.29** — 2026-09-25
  - Fixed: at some window sizes your exported design came out one pixel too small, which the game can refuse to load. Exports are now always the exact size the game expects.
  - The Classic Tee is made for the male character, so FitMaker now keeps it on Male. Exporting it for the female character gave a broken result in-game.
  - Fixed: typing a full colour code like #8A1A1A into the colour box no longer gets changed while you type.
  - If your design can't be built into the garment, FitMaker now tells you and saves your colourways as images, instead of saying the export finished.
  - Updates now wait until an export or engine setup has finished, instead of restarting FitMaker in the middle of it.
  - Engine setup is more reliable: a stalled download now stops with a clear message, and a setup that was interrupted halfway is noticed and done again properly.
  - Smaller fixes: the 3D preview always shows the colourway you picked last, logos can't be dragged off the fabric and lost, and very large images get a clear message instead of slowing the app down.

**v1.0.28** — 2026-09-25
  - The activation screen is redesigned. It walks you through getting your free key step by step: create a free KVRNL account, click Get FitMaker on its page, then copy your key from your account page. Each step has its own button, so it's easy even if you downloaded FitMaker from somewhere other than kvrnl.io.
  - Pasting your key is easier: there's a Paste button, right-click paste works, and extra spaces or line breaks picked up while copying are cleaned up for you.
  - When something is wrong with a key, the message now says exactly what to do, with a button that takes you straight to the fix, like releasing your key from an old PC.
  - On a slow connection, FitMaker now shows a Checking your license screen when it starts instead of a blank wait.
  - Your license is better protected. It stays tied to your own PC, and FitMaker can't be used until it's activated.
  - Fixed: an update could restart FitMaker while you were typing your key, and pressing Enter several times could send your key more than once.

**v1.0.27** — 2026-09-06
  - The engine log now speaks plain English. Instead of pages of technical output from the helper, you see short lines like "Loaded classic-tee-male.ydd." The full technical output is still there behind a "Show technical details" switch in Settings > Engine.
  - Bug reports sent from Settings > Help & support now include that technical log automatically, so you never have to copy anything.

**v1.0.26** — 2026-09-06
  - A brand-new layout. Everything is on one screen now: pick a garment on the left, design the fabric in the middle, and watch it appear on the character on the right, live as you work. No more stepping through pages.
  - Export is one clear panel: it checks your design, builds the folder, and shows you exactly the two lines to add to your server.
  - Settings is a single tidy panel with tabs for Updates, Engine, Help & support and About. Bug reports are sent from there.
  - Fixed: parts of the app could be cut off by the edge of the window on smaller screens. The window now fits your screen and every panel resizes properly.
  - New in the designer: quick-pick colours, a hex colour box, size and turn sliders plus a Centre button for logos, the Delete key removes a logo, and colourways have their own list.

**v1.0.25** — 2026-09-05
  - Fixed: exporting a hat from your own model file without the engine set up showed an error even though your files had been written.
  - Fixed: the Reset view button in the 3D preview now works.
  - Fixed: a hiccup on our end during the license check could send you back to the activation screen. The app now rides it out the same way it does a dropped internet connection.
  - Fixed: picking an image the app could not read left the Add logo and Import texture buttons stuck. It now tells you and lets you try another file.
  - Smoother 3D preview when switching between colourways many times, plus small reliability fixes to engine setup and activation.

Full history → **[kvrnl.io/changelog/fitmaker](https://kvrnl.io/changelog/fitmaker/)**

## Documentation

Setup guides and how-tos → **[kvrnl.io/docs/fitmaker](https://kvrnl.io/docs/fitmaker/)**

## Support

> [!IMPORTANT]
> **We don't use GitHub Issues.** Report bugs from inside the app — it's the
> fastest route to us and it attaches the details we need automatically.

- 🐛 **Found a bug?** Use **Report a Problem** inside FitMaker
- 💬 **Chat with us** → **[Discord](https://discord.gg/Ub4SdAuhu)**
- ✉️ **Anything else** → **[kvrnl.io/contact](https://kvrnl.io/contact/)**
- ❓ **FAQ** → [kvrnl.io/faq](https://kvrnl.io/faq/)

## License

**Proprietary freeware — free to use, not open source.**

This repository hosts the installer releases, documentation, and license for
FitMaker. **The application source code is not published.** See
**[LICENSE](./LICENSE)** for the full terms.

---

<div align="center">
<br>

**[kvrnl.io](https://kvrnl.io)** &nbsp;·&nbsp; **[All products](https://kvrnl.io/products/)** &nbsp;·&nbsp; **[Changelog](https://kvrnl.io/changelog/)** &nbsp;·&nbsp; **[Discord](https://discord.gg/Ub4SdAuhu)** &nbsp;·&nbsp; **[Contact](https://kvrnl.io/contact/)**

<sub>© 2026 <b>KVRNL</b> — an AI-powered software studio shipping free desktop tools.</sub>

</div>
