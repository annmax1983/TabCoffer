# TabCoffer

English | [中文](README_zh.md) | [日本語](README_ja.md) | [Deutsch](README_de.md) | [Español](README_es.md) | [Français](README_fr.md)

A local-first tab session manager. Save the tabs you have open as a named vault, then bring them back in one click.

> Chrome · Edge · Firefox · Manifest V3 · Local-first · No account · No tracking

---

## Free vs Pro

| Capability | Free | Pro |
|------------|------|------|
| Saved sessions | **3** | 100 |
| Tabs per session | **20** | 200 |
| One-click save / restore | ✅ | ✅ |
| Rename, delete, sort | ✅ | ✅ |
| JSON export | ✅ | ✅ |
| Search sessions and tabs | — | ✅ |
| JSON import (merge, dedupe) | — | ✅ |
| Restore: skip duplicate URLs / only unopened tabs | — | ✅ |

**Saving, restoring and exporting sessions are free and unlimited in capability — the only limits are 3 sessions × 20 tabs.** Pro raises the caps and adds search, import and the two careful-restore options. A licence is optional: the free tier never asks for one.

---

## How to use

1. Open the tabs you want to keep together.
2. Click the TabCoffer icon, type a name and press **Save session**.
3. Close the tabs — the session stays in the vault.
4. Later, open the popup and choose **Open in new window** or **Add to this window**.

---

## Privacy

Sessions, titles, addresses and icons stay in `chrome.storage.local` on this device. TabCoffer reads no page content and sends no analytics. The only network request is the optional licence check when Pro is activated, sent to `api.annmax1983.com` with your licence key, a random install ID and browser metadata — never your sessions.

---

## Source

> This repository is for project presentation; the complete source is not published. Install from the official browser stores.

---

## Licence

Get a licence: `https://annmax1983.com/checkout?plugin=tabcoffer`

Activate it: TabCoffer popup → ⚙ → enter the key.

Copyright © 2026 TabCoffer. All rights reserved. Closed source.
