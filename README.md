# Focus Blanket

**English** · [Русский](README_RU.md)

Focus Blanket is a REAPER Lua toggle that adds a single full-screen “focus blanket” track to reduce visual noise while you listen.

<p align="center">
  <img src="assets/ui.png" alt="Focus Blanket UI" width="400">
</p>


## Overview

Focus Blanket is built for moments when you want to *listen more than look*. It temporarily replaces the busy arrange view with a calm, minimal visual layer: one tall track at the top and one long neutral-colored item spanning the project length.

When you toggle it off, it removes the focus track and restores your previous selection and arrange-view time range.

**Key ideas:**
- Reduce visual noise during playback
- One-track full-screen visual “blanket”
- Clean toggle workflow with restore

---

## Features

- Toggle script (run once to enable, run again to disable)
- Creates one top track named `U ^ ェ ^ U`
- Track height expands to fill the arrange view (REAPER clamps to available space)
- One long item spanning the project length (minimum 30s if the project is shorter)
- Restores previous selection and arrange-view time range when disabled
- No js_ReaScriptAPI required
- macOS & Windows compatible

---

## Who is it for?

- Podcast editors
- Dialogue editors
- Post-production editors
- Sound designers doing critical listening
- Anyone who gets distracted by a busy timeline

---

## Installation

### ReaPack

Import the [Patch34 ReaPack catalog](https://raw.githubusercontent.com/patch-34/patch34-reapack/main/index.xml) via **Extensions → ReaPack → Import repositories…** and install **Focus Blanket** in **Browse packages**.

### Manual installation

Copy `Focus_Blanket.lua` to REAPER's `Scripts` directory and use **Actions → Show action list → New action → Load ReaScript**.


## License and credits

Distributed under the [MIT License](LICENSE).

Author: [Aleksei Vorobev / Patch34](https://github.com/patch-34).
