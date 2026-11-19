---
name: TESSERaCT
summary: "Creates virtual machines on Apple silicon Macs and lists ARM64 systems to try, downloaded and installed for you."
category: Developer tools
tags:
  - virtual-machines
  - virtualization
  - apple-silicon
  - linux
  - desktop-mac-toolkit
alternativeTo:
  - parallels-desktop
  - vmware-fusion
repository: https://github.com/starbudweiser/TESSERaCT
website: https://github.com/starbudweiser/TESSERaCT
license: Apache-2.0
licenseUrl: https://github.com/starbudweiser/TESSERaCT/blob/main/LICENSE
download: https://github.com/starbudweiser/TESSERaCT/releases/latest
macos: "27"
arch: apple-silicon
notarized: true
freeDownload: true
featured: false
added: '2026-11-19'
verified: '2026-11-19'
sources:
  - https://github.com/starbudweiser/TESSERaCT
  - https://github.com/starbudweiser/TESSERaCT/blob/main/LICENSE
  - https://github.com/starbudweiser/TESSERaCT/releases
  - https://raw.githubusercontent.com/starbudweiser/TESSERaCT/main/README.md
assets:
  - path: ./assets/screenshot.png
    source: https://github.com/starbudweiser/TESSERaCT/blob/main/docs/screenshot.png
    credit: Starbudweiser
    license: Apache-2.0
  - path: ./assets/icon.png
    source: https://github.com/starbudweiser/TESSERaCT/releases/download/v1.0.0/TESSERaCT.zip
    credit: Starbudweiser
    license: Apache-2.0; upstream app icon, trademarks retained
icon: ./assets/icon.png
---
TESSERaCT creates and runs virtual machines on Apple silicon Macs. Its first page, Discover, lists ARM64 systems worth trying, among them Debian, Fedora CoreOS, FreeBSD, OpenBSD, NixOS, Haiku, Redox and OpenWrt. You pick one, press the download button, and a machine is built with default settings.

The catalogue refreshes itself every day. It finds each system's newest release on the official mirrors, flags new versions, checks that the download links still answer and shows a screenshot of the desktop. Downloads resume after an interruption and are checked against the published SHA-256 or SHA-512 checksum before anything is installed.

Beyond the catalogue, the app installs macOS, Linux and Windows 11 for Arm guests. It keeps snapshots, saves a configured machine as a template, shares folders and the clipboard, forwards ports and attaches USB devices. A tctl command-line tool and an MCP server let scripts and AI agents run commands in a guest. Most guests use Apple's Virtualization framework, while the BSDs, Haiku, Redox and OpenWrt run on a bundled QEMU engine.

TESSERaCT is a fork of SwiftVM and covers the same ground as Parallels Desktop or VMware Fusion. The difference is that its catalogue lets you try a system without hunting for an installer first. It needs macOS 27 and an Apple silicon Mac, and it runs ARM64 guests only, so x86 systems are not supported yet. The interface comes in English, French, Spanish and Italian.
