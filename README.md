<div align="center">

<img src="assets/logo.png" alt="Master Download Manager" width="120">

# Master Download Manager

**Free download manager for Windows.**
One list for files, video, image galleries and torrents.

No ads · No telemetry · No account · Free to use

</div>

---

## What it is

Master Download Manager takes a file apart across many connections, keeps it resumable across
crashes and restarts, and puts video, image galleries and BitTorrent in the same list as ordinary
downloads. A browser extension hands downloads over from the page you are on, a scheduler starts
queues while you are asleep, and every window is the app's own — no embedded browser, no telemetry,
no account anywhere.

---

## Features

### Downloads

| Feature | What it does |
|---|---|
| **Segmented downloads** | Splits a large file across many connections, reopens what drops, and rejoins the segments as they finish. HTTP, HTTPS and FTP. |
| **Crash-safe resume** | A part file beside the destination carries its own state: a restart, a crash or a lost connection continues where it stopped, not from zero. |
| **Queues and batches** | A main queue, a later queue and a batch queue, with a maximum number of connections per server and per file. |
| **Scheduler** | Starts and stops queues at a chosen time, on chosen days, with retries for what fails. |
| **Speed limits** | Per-download and global limits, in either direction, so a large download does not take the whole line. |
| **Categories and folders** | Categories by file type, each with its own folder — or one folder for everything. |
| **Checksums** | Verify a finished file against MD5, SHA-1 or SHA-256 without leaving the app. |
| **Archive extraction** | Extracts `.zip`, `.tar` and `.xz` after the download; RAR and 7z through a 7-Zip you already have. |
| **Duplicate handling** | Recognises a link you have already added and asks what to do instead of downloading it twice. |

### Sources and media

| Feature | What it does |
|---|---|
| **Browser capture** | A native messaging host hands downloads from Chrome, Chromium, Edge, Brave, Opera, Vivaldi and Firefox to the app, with the page, its referrer and its cookies. |
| **Video and audio** | Page downloads through yt-dlp, with lux, Streamlink and Ember as fallbacks for pages yt-dlp cannot read. Live streams through Streamlink. Quality and format selection. |
| **Image galleries** | Whole galleries through gallery-dl, with folders named after the site and the set. |
| **BitTorrent** | Magnets and `.torrent` files in the same list, with seeding limits, blocklists, port forwarding and proxy support. |
| **Link grabber** | Reads a page and lists every link on it, with filters by type, so a batch of files is one click. |
| **RSS feeds** | Watches a feed and adds what it matches. |
| **Debrid accounts** | Real-Debrid, AllDebrid and Premiumize can fetch a link for you; tokens stay in the system keychain. |
| **Site logins** | Credentials per site, kept in the system keychain, for the servers that ask. |

### Network

| Feature | What it does |
|---|---|
| **Proxy support** | HTTP, HTTPS and SOCKS proxies, from the settings, the system, the browser or a PAC script. |
| **DNS options** | The system's DNS, or DNS over HTTPS with a provider you choose, per network. |
| **Network adapter** | Binds downloads to one interface on a machine that has several. |
| **Remote control** | Off by default. When enabled, paired phones and computers on your own network add downloads over HTTPS. |

### The application

| Feature | What it does |
|---|---|
| **Command line** | The classic `/d /p /f /a /n /s` switches, a terminal downloader with JSON output, and a local API for other programs. |
| **MCP server** | An assistant that speaks the Model Context Protocol can add and watch downloads. |
| **Themes** | Built-in looks, light and dark, with the interface size and font weight you choose. |
| **85 languages** | The interface, dates, numbers, sizes and speeds follow the language you choose. |
| **Tray and portable mode** | Keeps running in the notification area, or keeps its settings beside the program in a portable folder. |
| **Accessibility** | Keyboard navigation throughout, the system's accessibility tree, and Windows' high contrast. |
| **Crash reports** | A crash is written to a file in the app's data folder — nothing is uploaded. |
| **Private by construction** | No telemetry, no analytics, no account and no advertising. The local API listens on `127.0.0.1` only, behind a token. |

---

## Download

Windows 10 and 11, 64-bit. Two builds:

| Build | What it is |
|---|---|
| **Installer** | Sets the app up for the current user, with the browser integration and an entry in the Start menu. |
| **Portable** | A folder you can put anywhere: settings, list, logs and helpers stay inside it; nothing is written to your profile. |

Both are published on the [Releases](../../releases) page with their SHA-256 checksums. Video
helpers (yt-dlp, lux, Streamlink, Ember, FFmpeg) are downloaded and verified by the app when you
ask for them — they are not required for ordinary downloads.

---

## Privacy

There is no telemetry, no analytics, no account and no advertising. The app talks to the servers
you give it, to its own release list when it checks for updates, and to the helper programs you
choose to install — nothing else. A crash report is written to a file on your computer and stays
there until you choose to send it. The local automation API listens on `127.0.0.1` behind a token;
remote control binds only the network interfaces you pick, with pairing, and is off until you
enable it.

---

## Licence

**Master Download Manager is free to use.**

It is distributed under the **GNU General Public License, version 3 or later** — the licence that
comes with the software it is built on, and it stays under it.

- Install it on as many computers as you like, at home or at work.
- Share it with anyone; there is no price, no subscription and no account.
- The complete corresponding source code for each build is supplied with the build and is
  available on request, as the licence requires.

The name, the icon and this repository's text are the project's own and are not covered by that
licence.

---

## Credits

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
IP-to-country table from DB-IP (CC BY 4.0, looked up on your computer). Helper programs keep their
own licences and ship theirs with the app: yt-dlp (Unlicense), lux (MIT), Streamlink (BSD-2-Clause),
Ember (MIT), FFmpeg and Python (their own). The interface is built on egui and eframe; the full
list of Rust crates and their licences is in the build's software bill of materials.

---

## Reference

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

<div align="center">

**Master Download Manager** — free to use, GPL-3.0-or-later.
Built by Akshat with Moon. No telemetry, no account.

</div>