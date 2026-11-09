<p align="center"><img src="media/icon.jpg" width="96" alt="iSims app icon"></p>

<h1 align="center">iSims</h1>
<p align="center"><b>The companion the iOS Simulator always needed.</b><br>A macOS menu bar app for iOS developers: capture, control & inspect any simulator from one window.</p>

<p align="center">
  <a href="media/tour.mp4"><img src="media/poster.jpg" width="820" alt="iSims beside its feature list. Click to watch a 27-second tour."></a><br>
  <sub>▶ <a href="media/tour.mp4">Watch the 27-second tour</a></sub>
</p>

> **Showcase repo.** The source code is private. This repo holds screenshots, a video tour and the feature list.

## Screenshots

| Home | Search | Accessibility |
|:-:|:-:|:-:|
| <img src="media/home.jpg" width="260" alt="Home: screenshot and record buttons, capture options, simulator actions and feature pages"> | <img src="media/search.jpg" width="260" alt="Typing 'loc' finds the Lock action and the Location page"> | <img src="media/accessibility.jpg" width="260" alt="Text size, contrast and Reduce Motion, Bold Text, Grayscale switches"> |
| **Network Monitor** | **Location** | **Light mode** |
| <img src="media/network.jpg" width="260" alt="Network monitor with HTTPS inspection, filter and HAR export"> | <img src="media/location.jpg" width="260" alt="Pick a city or enter coordinates to fake the GPS position"> | <img src="media/light-home.jpg" width="260" alt="The home screen in light mode"> |

## Features

**Capture**
- Screenshots with device bezels, a floating thumbnail and a post editor (backgrounds, caption, shadow); export at App Store Connect sizes
- Screen recording with GIF export, touch circles drawn into the video, optional 120 fps window capture
- Global shortcuts (⌃⌥⌘S screenshot, ⌃⌥⌘R record, ⌃⌥⌘D dark/light), rebindable

**Control the simulator**
- Boot / shut down; install, launch, terminate & uninstall apps; add photos, videos & contacts
- Deep links, push notifications, location, a clean 9:41 status bar, privacy permissions
- Language, region & time zone overrides; dark mode, Dynamic Type, contrast
- Accessibility switches: Reduce Motion / Transparency, Bold Text, Button Shapes, Invert, Grayscale
- Simulator actions (rotate, home, lock, shake, Face ID, memory warning) and Home Screen Quick Actions
- UserDefaults editor and app container reveal

**Inspect**
- Accessibility audit (missing labels, tap targets under 44 pt, duplicates) and a VoiceOver-order navigator
- Network monitor: local proxy, optional HTTPS inspection, decoded bodies (gzip, deflate, Brotli), copy as cURL or **for AI** with credentials redacted, HAR export
- Network speed throttling, design overlay, grid & guides, magnifier, build insights from DerivedData

**Teams, devices & AI**
- A committed `.isims.json` shares bundle IDs, deep links, pushes & locations across the team
- Physical devices via `devicectl`, iPhone screen mirroring over USB, a simulator camera feed package
- `isims` command line (`isims screenshot --bezel`, `isims audit --json`, `isims record --gif` …) and two bundled **Claude Code skills**, so coding agents can drive the simulator

## Built with

Swift 6 · SwiftUI · AppKit · Swift Package Manager (no Xcode project) · `simctl` / `devicectl` · AVFoundation · Network.framework

---
Made by [Anil Upadhyay](https://github.com/anil291987) · [LinkedIn](https://www.linkedin.com/in/anil-u-a70061a7/)
