---
name: mPASTE
summary: "Makes ⌘V paste plain text everywhere, with tracking parameters removed from links and your clipboard restored afterwards."
category: Utilities
tags:
  - plain-text
  - clipboard
  - menu-bar
  - keyboard-shortcuts
  - desktop-mac-toolkit
repository: https://github.com/starbudweiser/mPASTE
website: https://github.com/starbudweiser/mPASTE
license: MIT
licenseUrl: https://github.com/starbudweiser/mPASTE/blob/main/LICENSE
download: https://github.com/starbudweiser/mPASTE/releases/latest
macos: "14"
arch: both
notarized: true
freeDownload: true
featured: false
added: '2026-11-19'
verified: '2026-11-19'
sources:
  - https://github.com/starbudweiser/mPASTE
  - https://github.com/starbudweiser/mPASTE/blob/main/LICENSE
  - https://github.com/starbudweiser/mPASTE/releases
  - https://raw.githubusercontent.com/starbudweiser/mPASTE/main/README.md
assets:
  - path: ./assets/screenshot.png
    source: https://github.com/starbudweiser/mPASTE/blob/main/docs/screenshot.png
    credit: Starbudweiser
    license: MIT
  - path: ./assets/icon.png
    source: https://github.com/starbudweiser/mPASTE/releases/download/v1.0.2/mPASTE.zip
    credit: Starbudweiser
    license: MIT; upstream app icon, trademarks retained
screenshots:
  - src: ./assets/screenshot.png
    alt: "The mPASTE overview with plain-text paste active, the last paste and the four cleaning rules."
    source: https://github.com/starbudweiser/mPASTE/blob/main/docs/screenshot.png
    credit: Starbudweiser
icon: ./assets/icon.png
---
mPASTE changes what ⌘V does: whatever you copy, from a web page or a document, arrives as plain text. It sits in the menu bar and intercepts the shortcut with a keyboard event tap, so it needs the Accessibility permission.

Four rules decide how the text is cleaned, and each one has a switch:

- plain text only;
- tracking parameters such as utm_*, fbclid and gclid removed from links;
- extra spaces trimmed;
- curly quotes straightened.

Right after pasting, the app puts your original clipboard back, formatting included. ⌥⌘V pastes with the formatting when you want it, and ⌃⌥P pauses the cleaning. Pages, Keynote and Numbers are excluded by default, and you can edit the list of excluded apps.

mPASTE can run as a background agent. A user LaunchAgent installs and removes itself from the settings, without administrator rights, and the command mPASTE --service install, uninstall or status does the same from a terminal.

The README says it is inspired by Pure Paste by Sindre Sorhus and shares no code with it. Releases are universal builds for macOS 14 or later, notarized, in four languages, with updates from GitHub.
