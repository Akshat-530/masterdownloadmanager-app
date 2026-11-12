<p align="center">
  <img src="https://raw.githubusercontent.com/Akshat-530/masterdownloadmanager-app/main/assets/logo.png" width="132" alt="Master Download Manager">
</p>

<h1 align="center">Master Download Manager</h1>

<p align="center">
  <b>Free download manager for Windows</b><br>
  One list for files, video, image galleries and torrents.
</p>

<p align="center">
  🪟 Windows 10 &amp; 11 · 📦 Installer &amp; Portable &amp;nbsp;·&amp;nbsp; 🚫 No ads · 🕵️ No telemetry · 👤 No account
</p>

<p align="center">
  <a href="https://akshat-530.github.io/masterdownloadmanager/"><b>🌐 Website — every feature in detail</b></a>
  &nbsp;·&nbsp;
  <a href="../../releases">⬇️ Downloads</a>
</p>

---

## ✨ Highlights

| | |
|---|---|
| ⚡ **Segmented downloads** | One file, many connections — split, rejoin, and finish fast over HTTP, HTTPS and FTP. |
| 🛟 **Crash-safe resume** | The part file keeps its own state, so a crash or a lost connection continues where it stopped. |
| 🧩 **Browser capture** | Chrome, Chromium, Edge, Brave, Opera, Vivaldi and Firefox hand downloads straight to the app. |
| 🎬 **Video &amp; audio** | YouTube and hundreds of other sites, with quality and format choice — four extractors as fallbacks. |
| 📺 **Live streams** | Twitch, YouTube live and more, through Streamlink. |
| 🖼️ **Image galleries** | Whole galleries, sorted into folders named after the site and the set. |
| 🧲 **BitTorrent** | Magnets and <code>.torrent</code> files in the same list, with seeding limits and blocklists. |
| 🔗 **Link grabber** | Every link on a page, filtered by type — a batch of files in one click. |
| 🕒 **Scheduler &amp; queues** | Start queues at a time, on chosen days, with retries and a later queue. |
| 🚦 **Speed limits** | Per-download and global, so a big download never eats the whole line. |
| 📂 **Categories &amp; folders** | A folder per file type, or one folder for everything. |
| ✅ **Checksums &amp; archives** | MD5, SHA-1, SHA-256 verification; extract ZIP, TAR and XZ right after the download. |
| 🖥️ **Command line &amp; MCP** | The classic <code>/d /p /f</code> switches, a JSON terminal downloader, a local API, and an MCP server for AI assistants. |
| 🌍 **85 languages** | Interface, dates, numbers and sizes follow your language. |
| 🎨 **Themes &amp; accessibility** | Light and dark looks, interface scaling, keyboard navigation and the system's accessibility tree. |
| 📱 **Remote control** | Add downloads from a paired phone on your own network — off until you enable it. |

<p align="center">
  <a href="https://akshat-530.github.io/masterdownloadmanager/"><b>→ Read about every feature on the website</b></a>
</p>

---

## 📦 Download

Windows 10 and 11, 64-bit. **Every release is a full bundle** — the download engine, the browser
integration and every helper program are inside, so video, galleries and torrents work on the
first start with nothing else to install.

| Build | What it is |
|---|---|
| 🧰 **Installer** | Sets the app up for the current user, with browser integration and a Start menu entry. |
| 🎒 **Portable** | A folder you can put anywhere: settings, list, logs and helpers stay inside it — nothing in your profile. |

Both are on the [Releases](../../releases) page with their SHA-256 checksums.

### 🧰 What is inside

| Helper | Used for | Licence |
|---|---|---|
| **yt-dlp** | Video and audio from web pages | Unlicense |
| **lux** | A second extractor, for pages yt-dlp struggles with | MIT |
| **Streamlink** | Live streams | BSD-2-Clause |
| **Ember** | Social platforms | MIT |
| **gallery-dl** | Image galleries | GPL-2.0 |
| **FFmpeg** | Muxing video and audio into one file | its build's licence |
| **Python 3** | The runtime Streamlink and Ember run in | PSF License Agreement |

Each ships with its licence text in the package. The app verifies every helper before it runs it,
and updates them from their publishers when you ask in the Helpers window. RAR and 7z extraction
is the one thing not bundled — it uses a 7-Zip you already have, because that program's unRAR
licence cannot be redistributed.

---

## 🔒 Privacy

No telemetry, no analytics, no account, no advertising. The app talks to the servers you give it
and to its own release list for updates — nothing else. A crash report is written to a file on
your computer and stays there until you choose to send it. The local API listens on
<code>127.0.0.1</code> behind a token; remote control is off until you enable it.

---

## 📜 Licence

**Free to use.** Master Download Manager is distributed under the **GNU General Public License,
version 3 or later** — the licence that comes with the software it is built on, and it stays under
it.

- Install it on as many computers as you like, at home or at work.
- Share it freely; no price, no subscription, no account.
- The complete corresponding source for each build is supplied with the build and available on
  request, as the licence requires.

The name, the icon and this repository's text are the project's own and are not covered by that
licence. The package ships every bundled program's licence text in <code>licences/</code>.

---

## 🏅 Credits

**Made by**

- **Akshat** — product, design and direction, and every release.
- **Moon** — a custom agent harness by Akshat — built the application with him: the interface, the
  engine work, the browser extension, the audit, and this page.

**Special thanks**

- **Ahmed Nefzaoui**, author of Mister Download Manager — for providing the core engine as open
  source.

**Third-party components**

Fonts Geist and Poppins (SIL OFL 1.1); icons from Lucide (ISC), Tango (public domain), Silk
(CC BY 2.5), Fluent (MIT), Adwaita and Breeze (LGPL-3.0); language flags from flag-icons (MIT); the
IP-to-country table from DB-IP (CC BY 4.0, looked up on your computer). The interface is built on
egui and eframe, the network on Tokio, rustls and reqwest, torrents on librqbit — the full crate
list and licences are in the build's software bill of materials.

---

## 🔎 Reference

This application was **inspired by** the download managers people already know — **Internet
Download Manager**, **Free Download Manager** and **Mister Download Manager** — in the way any tool
in a crowded field learns from what came before: from the idea of a segmented downloader with a
list, a queue and a browser hand-off.

**No code, no artwork, no icons, no text and no trademarks of those products are used here**, apart
from the open-source licence and copyright notice of the project this one is built on, which are
kept as the GPL requires. Nothing was copied, decompiled or reverse engineered. This application is
not affiliated with, endorsed by, sponsored by or connected to any of them, and all of their names
and marks belong to their respective owners. The names are mentioned only to describe where the idea
came from, which is what a reference note is for.

---

<p align="center">
  <b>Master Download Manager</b> — free to use, GPL-3.0-or-later<br>
  Built by Akshat with Moon · <a href="https://akshat-530.github.io/masterdownloadmanager/">Website</a> · <a href="../../releases">Releases</a>
</p>