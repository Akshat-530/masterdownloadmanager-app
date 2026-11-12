<p align="center">
  <img src="https://raw.githubusercontent.com/Akshat-530/masterdownloadmanager-app/main/assets/logo.png" width="132" alt="Master Download Manager">
</p>

<h1 align="center">Master Download Manager</h1>

<p align="center">
  <b>Free download manager for Windows</b><br>
  Files, video, image galleries and torrents — in one list.
</p>

<p align="center">
  🪟 Windows 10 &amp; 11 &nbsp;·&nbsp; 📦 Installer &amp; Portable &nbsp;·&nbsp; 🚫 No ads &nbsp;·&nbsp; 🕵️ No telemetry &nbsp;·&nbsp; 👤 No account
</p>

<p align="center">
  <a href="https://akshat-530.github.io/masterdownloadmanager/"><b>🌐 Website</b></a> &nbsp;·&nbsp;
  <a href="../../releases"><b>⬇️ Downloads</b></a> &nbsp;·&nbsp;
  <a href="https://akshat-530.github.io/masterdownloadmanager/#features"><b>📖 Every feature</b></a>
</p>

---

## ✨ Why it's different

> **Downloads that finish.** A file is split across many connections and rejoined as it arrives —
> and if the app or the connection dies, it picks up exactly where it stopped.

### ⚡ It's fast, and it stays fast

- **Many connections per file** — split, resume and rejoin over HTTP, HTTPS and FTP.
- **Crash-safe** — the part file carries its own state; nothing restarts from zero.
- **Speed limits that work both ways** — per download or global, upload or download.

### 🎬 It downloads everything, not just files

- **🎬 Video & audio** — YouTube and hundreds of other sites, with quality and format choice.
- **📺 Live streams** — Twitch, YouTube live, and more.
- **🖼️ Image galleries** — whole sets, filed neatly by site and name.
- **🧲 BitTorrent** — magnets and `.torrent` files in the same list as everything else.
- **🔗 Link grabber** — every link on a page, one click to queue the ones you want.

### 🧩 It fits your browser and your workflow

- **Browser capture** — Chrome, Chromium, Edge, Brave, Opera, Vivaldi and Firefox hand downloads over,
  cookies included.
- **⌨️ Command line, local API and MCP** — scripts, terminals and AI assistants can drive it.
- **🕒 Scheduler and queues** — start at a time, retry failures, keep a later queue.
- **📱 Remote control** — add downloads from a paired phone on your network; off until you enable it.

### 🔒 It's private, and it's yours

- **No ads, no telemetry, no account** — ever.
- **85 languages**, light and dark themes, interface scaling, keyboard navigation.
- **Installer or portable** — the portable build keeps everything, helpers included, in one folder.

<p align="center">
  <a href="https://akshat-530.github.io/masterdownloadmanager/"><b>→ The full feature list lives on the website</b></a>
</p>

---

## 📦 Download

Windows 10 and 11, 64-bit. **Every release is a full bundle** — the engine, the browser integration
and every helper are inside, so video, galleries and torrents work on the first start.

| Build | What it is | Download |
|---|---|---|
| 🧰 **Installer** | For the current user: browser integration and a Start menu entry. | [MDM.setup.exe](../../releases/tag/setup-v5.2.0) |
| 🎒 **Portable** | A folder anywhere on your disk: settings, list, logs and helpers stay inside it. | [MDM_Portable.zip](../../releases/tag/v5.2.0) |

Each build is its own release with its own SHA-256 checksum file. The browser extension has a
release of its own too: [Browser extension 1.0.0](../../releases/tag/extension-v1.0.0).

<details>
<summary><b>🧰 What's inside the bundle</b></summary>

| Helper | Used for | Licence |
|---|---|---|
| **yt-dlp** | Video and audio from web pages | Unlicense |
| **lux** | A second extractor, for stubborn pages | MIT |
| **Streamlink** | Live streams | BSD-2-Clause |
| **Ember** | Social platforms | MIT |
| **gallery-dl** | Image galleries | GPL-2.0 |
| **FFmpeg** | Muxing video and audio into one file | its build's licence |
| **Python 3** | The runtime Streamlink and Ember run in | PSF License Agreement |

Each ships with its licence text in the package; the app verifies every helper before running it.

</details>

---

## 🔒 Privacy

No telemetry, no analytics, no account, no advertising. The app talks to the servers you give it and
to its own release list for updates — nothing else. A crash report is written to a file on your
computer and stays there until you send it. The local API listens on `127.0.0.1` behind a token;
remote control is off until you enable it.

---

## 📜 Licence

**Free to use.** Distributed under the **GNU General Public License, version 3 or later** — the
licence that comes with the software it is built on, and it stays under it.

- Install it on as many computers as you like, at home or at work.
- Share it freely; no price, no subscription, no account.
- The complete corresponding source for each build is supplied with the build and available on
  request, as the licence requires.

The name, the icon and this repository's text are the project's own and are not covered by that
licence.

---

## 🏅 Credits

**Made by** — **Akshat** (product, design, direction, every release) and **Moon**, a custom agent
harness by Akshat, which built the application with him: the interface, the engine work, the
browser extension, the audit and this page.

**Special thanks** — **Ahmed Nefzaoui**, author of Mister Download Manager, for providing the core
engine as open source.

**Third-party** — Geist and Poppins fonts (SIL OFL 1.1); Lucide (ISC), Tango (public domain), Silk
(CC BY 2.5), Fluent (MIT), Adwaita and Breeze (LGPL-3.0) icons; flag-icons (MIT); DB-IP's
IP-to-country table (CC BY 4.0, looked up on your computer); egui/eframe, Tokio, rustls, reqwest and
librqbit underneath. Full list in the build's software bill of materials.

---

## 🔎 Reference

Inspired by the download managers people already know — **Internet Download Manager**, **Free
Download Manager** and **Mister Download Manager** — the way any tool in a crowded field learns
from what came before: the idea of a segmented downloader with a list, a queue and a browser
hand-off.

**No code, no artwork, no icons, no text and no trademarks of those products are used here**, apart
from the open-source licence and copyright notice of the project this one is built on, which are
kept as the GPL requires. Nothing was copied, decompiled or reverse engineered. This application is
not affiliated with, endorsed by, sponsored by or connected to any of them; their names and marks
belong to their respective owners, and are mentioned only to describe where the idea came from.

---

<p align="center">
  <b>Master Download Manager</b> — free to use, GPL-3.0-or-later<br>
  Built by Akshat with Moon &nbsp;·&nbsp; <a href="https://akshat-530.github.io/masterdownloadmanager/">Website</a> &nbsp;·&nbsp; <a href="../../releases">Releases</a>
</p>