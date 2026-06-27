<div align="center">
  <img src="assets/distill-logo.png" width="150" alt="Distill logo"/>
  <h1>Distill</h1>
  <p><b>Turn any video into knowledge.</b></p>
</div>

![Distill](assets/distill-banner.png)

[![License: MIT](https://img.shields.io/badge/License-MIT-06b6d4.svg)](LICENSE)
[![Obsidian](https://img.shields.io/badge/Obsidian-plugin-8b5cf6.svg?logo=obsidian&logoColor=white)](https://obsidian.md)
[![Buy Me a Coffee](https://img.shields.io/badge/Buy%20Me%20a%20Coffee-carbeneai-ffdd00.svg?logo=buymeacoffee&logoColor=black)](https://www.buymeacoffee.com/carbeneai)

A faster, cleaner way to save and study YouTube videos in Obsidian. Think of it as MediaNote, rebuilt: one-click capture, a genuinely resizable player, click-to-seek timestamps, and AI notes, all in your vault.

## What it does today

**One-click capture.** Install the [bookmarklet](https://carbene.ai/distill/install.html) and save any YouTube video to your vault as a clean note: a clean URL that always starts at 0:00 (no more resume-timestamp), the real video title as the filename (no junk index, no illegal characters), and tidy properties (channel, video id, source).

**A real player.** Open the video in a resizable, pop-out pane. Drag it as large as you like, or move it into its own window onto a second monitor. The tiny fixed embed is gone.

**Click-to-seek timestamps.** Tap a hotkey to drop a timestamp while you watch; click it later and the player jumps to that exact second.

**AI notes, powered by [Fabric](https://github.com/danielmiessler/fabric).** `summarize` and `extract_wisdom`, appended to the note automatically.

## A note on transcripts (the honest part)

YouTube has locked down direct caption access, so a pure in-plugin transcript fetch isn't reliable yet. Today the AI summaries run best through a companion transcript workflow (for example a `yt-dlp`-based job) or your own transcript. A portable transcript path is the number-one roadmap item. Until then, capture, the player, and timestamps work for everyone, and the AI works wherever a transcript is available.

## Install

- **Bookmarklet (capture):** drag-to-install at **[carbene.ai/distill/install.html](https://carbene.ai/distill/install.html)**.
- **Plugin (player + timestamps):** manual for now. Copy the build into `.obsidian/plugins/distill/`. A Community Plugins listing comes once it's polished.

## Roadmap

We will flesh this out later. The short version:

- Portable transcripts, so the AI works anywhere, on any device
- Anki flashcards generated from your timestamps
- Graph-linking: people and concepts become atomic `[[notes]]`
- More sources: podcasts, articles, local files

## Tech

- Obsidian plugin (TypeScript)
- [Fabric](https://github.com/danielmiessler/fabric) patterns for the AI layer
- Cloud LLMs or a local Ollama

## Support

Free and open source under the MIT license. If it saves you time, you can fuel the build:

[![Buy Me a Coffee](https://img.shields.io/badge/Buy%20Me%20a%20Coffee-carbeneai-ffdd00.svg?logo=buymeacoffee&logoColor=black)](https://www.buymeacoffee.com/carbeneai)

## Credits

Built by [CarbeneAI](https://carbene.ai). AI extraction powered by [Fabric](https://github.com/danielmiessler/fabric). MIT licensed.
