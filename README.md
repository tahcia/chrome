# Tahcia — Browser Automation for Chrome

**Record clicks, forms, multi-tab flows, and screenshots. Run your workflows with AI.**

No pixel matching. No fragile macros. No engineering setup. Works on any website in Chrome.

![Tahcia Console](https://poscow.s3.amazonaws.com/media/51ed931365d9454eb158974055db3a5b/83556a09bd514bb5b5f84465c20adee4/tahcia-screenshot.png)

---

## Install

Tahcia is not yet on the Chrome Web Store. Install it in two steps:

**1. Download the latest release**

Go to [Releases](https://github.com/tahcia/chrome/releases) and download the latest `tahcia-extension.zip`. Unzip it anywhere on your machine.

**2. Load it into Chrome**

1. Open `chrome://extensions`
2. Enable **Developer mode** (top right toggle)
3. Click **Load unpacked**
4. Select the unzipped folder

That's it. The Tahcia icon will appear in your toolbar.

---

## What it does

Tahcia is a Chrome extension + AI console that turns browser workflows into replayable scripts.

**Record** — Perform a task once in your browser. Tahcia captures every click, input, scroll, tab switch, and screenshot as a structured, editable script.

**Replay** — Run it yourself anytime, or ask the AI console to run it for you.

**Debug** — A real step-through execution environment. Pause anywhere, step back, rerun just the broken step, continue. Not a log file — a debugger.

**Fork** — Every public script in the library is forkable. Customize it, extend it, make it yours.

---

## How it works

1. Install the extension and open [tahcia.com/console](https://www.tahcia.com/console)
2. Open any site, attach the tab to Tahcia
3. Hit record — do the task once
4. Run it yourself, ask AI to run it, or publish it to the library

![Tahcia Script Editor](https://poscow.s3.amazonaws.com/media/51ed931365d9454eb158974055db3a5b/5aec4124de03455987a08ae846b5dfdd/tahcia-script-screenshot.png)

---

## Debugger

![Tahcia Debugger](https://poscow.s3.amazonaws.com/media/51ed931365d9454eb158974055db3a5b/96984de537c44a19b8112ea60e07fae2/tahcia-debugger.png)

| Control | What it does |
|---|---|
| Pause / Continue | Freeze mid-script to inspect the current tab state |
| Step back | Rewind one step and re-examine what it produced |
| Rerun step | Fix and retry a single step without restarting |
| Abort | Stop cleanly — no orphaned actions left running |
| Screenshot | At any moment, on any tab |

---

## Requirements

- Google Chrome (latest)
- A [tahcia.com](https://www.tahcia.com) account (free)

---

## Links

- Website: [tahcia.com](https://www.tahcia.com)
- Console: [tahcia.com/console](https://www.tahcia.com/console)
- Docs: [tahcia.com/docs](https://www.tahcia.com/docs)

---

## Note on permissions

Tahcia requests broad host permissions to inject its recorder and replay engine into any site you automate. This is the same approach used by other browser automation tools. The extension is open source — you can audit exactly what it does with those permissions in this repo.
