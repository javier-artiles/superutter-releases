# SuperUtter

<p align="center">
  <img src="icon_color.png" alt="SuperUtter icon" width="128">
</p>

A native macOS menu bar app that reads clipboard text aloud using text-to-speech.

**Copy text → press a hotkey → hear it spoken.**

## Download

**[Download the latest release](https://github.com/javier-artiles/superutter-releases/releases/latest)**

Requires **macOS 15** (Sequoia) or later on Apple Silicon.

## Features

- **Menu bar app** — lives in the macOS menu bar, no Dock icon
- **Global hotkeys** — configurable shortcuts for read clipboard (⌃⌥U), pause/resume (⌃⌥P), and auto-play toggle (⌃⌥A)
- **Auto-play clipboard** — automatically reads text aloud whenever you copy
- **Two TTS engines:**
  - **ElevenLabs** — streaming cloud TTS with premium AI voices (BYO API key)
  - **Kokoro** — local CoreML TTS with 50+ voices, fully offline after ~99 MB model download
- **Floating playback overlay** — progress bar, elapsed/total time, play/pause controls
- **Streaming playback** — audio starts before the full response is generated
- **Secure** — API keys stored in macOS Keychain, never leaves your machine

## Installation

1. Download `SuperUtter.dmg` from the [latest release](https://github.com/javier-artiles/superutter-releases/releases/latest)
2. Open the DMG and drag **SuperUtter** to your Applications folder
3. Launch SuperUtter — an otter icon appears in your menu bar
4. Grant **Accessibility** permission when prompted (required for global hotkeys)
5. Open Settings and configure your preferred TTS provider

## Setup

### ElevenLabs (Cloud)
1. Get an API key from [elevenlabs.io](https://elevenlabs.io)
2. Paste it in Settings → ElevenLabs API Key
3. Select a voice and adjust speed/stability

### Kokoro (Local)
1. Switch to Kokoro in Settings
2. Click "Download" (~99 MB one-time download)
3. Select a voice — no internet needed after download

## Bug Reports

Please include your app version (shown at the bottom of Settings) when reporting issues.

## License

Copyright 2026 SuperUtter. All rights reserved.
