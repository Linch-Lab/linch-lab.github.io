---
title: PopLingo
summary: A Windows instant-translation tool that works in any text box — and keeps your IME working.
date: 2026-09-28
links:
  - type: site
    url: https://poplingo.billlinch.com/
  - type: github
    url: https://github.com/Linch-Lab/poplingo
tags:
  - Windows
  - Python
  - Translation
  - Open Source
status: published
draft: false
---

**PopLingo** is a global-hotkey translation tool for Windows. Press `Ctrl+Alt+T` inside any
text box, type in your own language in a small floating card, then press `Enter` to insert the
translation — no window switching, no copy-paste.

<!--more-->

Most similar tools use a low-level keyboard hook to intercept typing, and that **breaks
Chinese, Japanese and Korean input method composition** — IMEs need the real keystrokes to
build characters. PopLingo instead makes the card itself the input surface, so Zhuyin, Pinyin
and other IMEs keep working normally.

## Features

- **Global hotkeys** — `Ctrl+Alt+T` toggles translation mode, `Ctrl+Alt+C` brings focus back
  to the card, `Ctrl+Alt+Enter` inserts the translation from anywhere
- **Works with 14 providers** — DeepSeek, OpenAI, Qwen, Kimi, Groq and more, all
  OpenAI-compatible. Or run a **fully local model with Ollama** so nothing leaves your machine
- **Multi-monitor aware** — handles negative coordinates, mixed DPI scaling and arbitrary
  monitor arrangements
- **Configurable card** — font size and colour for both the input and the translation text,
  with a live preview in the settings window
- **No data collection** — no ads, no tracking, no telemetry
- **Settings survive updates** — stored in `%APPDATA%\PopLingo`
- **MIT licensed**, single Python file you can audit and build yourself

## Links

- Website: <https://poplingo.billlinch.com/>
- Download: <https://poplingo.billlinch.com/download.html>
- Source code: <https://github.com/Linch-Lab/poplingo>
- Documentation and FAQ: <https://poplingo.billlinch.com/faq.html>
