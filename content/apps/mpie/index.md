---
name: mPIE
summary: "Opens a ring under the pointer to launch apps, jump between running ones, send shortcuts and control Apple Music or Spotify."
category: Utilities
tags:
  - pie-menu
  - launcher
  - menu-bar
  - music-controller
  - desktop-mac-toolkit
repository: https://github.com/starbudweiser/mPIE
website: https://github.com/starbudweiser/mPIE
license: MIT
licenseUrl: https://github.com/starbudweiser/mPIE/blob/main/LICENSE
download: https://github.com/starbudweiser/mPIE/releases/latest
macos: "14"
arch: apple-silicon
notarized: true
freeDownload: true
featured: false
added: '2026-11-19'
verified: '2026-11-19'
sources:
  - https://github.com/starbudweiser/mPIE
  - https://github.com/starbudweiser/mPIE/blob/main/LICENSE
  - https://github.com/starbudweiser/mPIE/releases
  - https://raw.githubusercontent.com/starbudweiser/mPIE/main/README.md
assets:
  - path: ./assets/screenshot.png
    source: https://github.com/starbudweiser/mPIE/blob/main/docs/screenshot.png
    credit: Starbudweiser
    license: MIT
  - path: ./assets/icon.png
    source: https://github.com/starbudweiser/mPIE/releases/download/v1.0.2/mPIE.zip
    credit: Starbudweiser
    license: MIT; upstream app icon, trademarks retained
screenshots:
  - src: ./assets/screenshot.png
    alt: "The mPIE ring open on the Launcher module, with an app slice highlighted and the module bar below."
    source: https://github.com/starbudweiser/mPIE/blob/main/docs/screenshot.png
    credit: Starbudweiser
icon: ./assets/icon.png
---
mPIE opens a ring of slices around the pointer. Hold ⌥ Space, or ⌥ with the middle button, and release over a slice to act on it. A quick press keeps the ring open so you can click instead.

The ring has four modules, which you switch with Tab, the scroll wheel or the keys 1 to 4. The modules are:

- Launcher, with up to 16 apps, folders and files placed clockwise from the top;
- Open apps, which jumps to a running app, most recently used first, and lets you exclude the ones you never want;
- Controller, which sends the shortcuts of the frontmost app. Ready-made sets cover Finder, Safari, Chrome, Mail, Notes, Terminal, DaVinci Resolve, Blender, Xcode and VS Code, and you can write your own;
- Music, with play and pause, next, previous, shuffle and repeat for Apple Music and Spotify, plus the title and artwork.

Settings offer presets that fill the launcher from ready-made sets, such as macOS essentials, video, development or design, keeping only the apps installed on your Mac. You can also choose how the ring opens: keyboard and mouse, keyboard only, mouse only, or tap then click.

The Controller needs the Accessibility permission, and the music remote asks for Automation the first time. The README says the app is inspired by Pieoneer by App ahead and uses none of its code or assets. Releases are Apple silicon builds for macOS 14 or later, notarized.
