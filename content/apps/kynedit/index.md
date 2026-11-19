---
name: kYNEDIT
summary: "Browses, tags and transcodes video clips, copies camera cards with checks, and exports to DaVinci Resolve or Final Cut Pro."
category: Media
tags:
  - media-browser
  - video-converter
  - prores
  - dit
  - desktop-mac-toolkit
repository: https://github.com/starbudweiser/KyNEDIT
website: https://github.com/starbudweiser/KyNEDIT
license: MIT
licenseUrl: https://github.com/starbudweiser/KyNEDIT/blob/main/LICENSE
download: https://github.com/starbudweiser/KyNEDIT/releases/latest
macos: "14"
arch: apple-silicon
notarized: true
freeDownload: true
featured: false
added: '2026-11-19'
verified: '2026-11-19'
sources:
  - https://github.com/starbudweiser/KyNEDIT
  - https://github.com/starbudweiser/KyNEDIT/blob/main/LICENSE
  - https://github.com/starbudweiser/KyNEDIT/releases
  - https://raw.githubusercontent.com/starbudweiser/KyNEDIT/main/README.md
assets:
  - path: ./assets/screenshot.png
    source: https://github.com/starbudweiser/KyNEDIT/blob/main/docs/screenshot.png
    credit: Starbudweiser
    license: MIT
  - path: ./assets/icon.png
    source: https://github.com/starbudweiser/KyNEDIT/releases/download/v1.0.0/kYNEDIT-1.0.0.zip
    credit: Starbudweiser
    license: MIT; upstream app icon, trademarks retained
screenshots:
  - src: ./assets/screenshot.png
    alt: "The kYNEDIT Convert tab with three clips queued and the ProRes 422 HQ preset selected."
    source: https://github.com/starbudweiser/KyNEDIT/blob/main/docs/screenshot.png
    credit: Starbudweiser
icon: ./assets/icon.png
---
kYNEDIT is a media browser and transcoder for editors. You open a folder of clips, and it indexes them into a local catalogue with thumbnails, full-text search and grid or list views. Ratings, colour labels, keywords, notes, markers and subclips live in that catalogue, and the source files are never modified.

The Convert tab queues clips against about 60 built-in presets, for editing, proxies, Avid, delivery and dailies, or your own. It writes ProRes, DNxHR or DNxHD in MOV or MXF, H.264 and H.265. It can resize, change the frame rate, pick audio channels, apply a LUT, convert camera log to Rec.709, burn in timecode, reel or text, and export an ALE file. With no picture change, decoded frames go straight to the hardware encoder.

Other tabs cover the rest of a day on set:

- Workshop trims a clip losslessly with in and out points, and extracts a still frame or the audio alone;
- Offload copies a card to up to four destinations, checks every copy with MD5 and writes an MHL hash list.

Exchange files are available for DaVinci Resolve and Final Cut Pro, and for Premiere Pro, whose import is untested. Blackmagic RAW and RED R3D clips decode through the manufacturers' libraries, which are bundled in the release but are not part of the repository. The README names Kyno and EditReady as inspirations and says it is not affiliated with them. Releases are notarized Apple silicon builds for macOS 14 or later.
