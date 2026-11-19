---
name: mUGGINFACE
summary: "Lists the Hugging Face models that suit your Mac, scored for its chip and memory, and downloads them or hands them to an AI agent."
category: AI
tags:
  - huggingface
  - local-ai
  - models
  - apple-silicon
  - desktop-mac-toolkit
repository: https://github.com/starbudweiser/mUGGINFACE
website: https://github.com/starbudweiser/mUGGINFACE
license: MIT
licenseUrl: https://github.com/starbudweiser/mUGGINFACE/blob/main/LICENSE
download: https://github.com/starbudweiser/mUGGINFACE/releases/latest
macos: "15"
arch: apple-silicon
notarized: true
freeDownload: true
featured: false
added: '2026-11-19'
verified: '2026-11-19'
sources:
  - https://github.com/starbudweiser/mUGGINFACE
  - https://github.com/starbudweiser/mUGGINFACE/blob/main/LICENSE
  - https://github.com/starbudweiser/mUGGINFACE/releases
  - https://raw.githubusercontent.com/starbudweiser/mUGGINFACE/main/README.md
assets:
  - path: ./assets/screenshot.png
    source: https://github.com/starbudweiser/mUGGINFACE/blob/main/docs/screenshot.png
    credit: Starbudweiser
    license: MIT
  - path: ./assets/icon.png
    source: https://github.com/starbudweiser/mUGGINFACE/releases/download/v1.0.5/mUGGINFACE-1.0.5.zip
    credit: Starbudweiser
    license: MIT; upstream app icon, trademarks retained
screenshots:
  - src: ./assets/screenshot.png
    alt: "The mUGGINFACE recommendations list for video models, with the detected Mac, size and score of each model."
    source: https://github.com/starbudweiser/mUGGINFACE/blob/main/docs/screenshot.png
    credit: Starbudweiser
icon: ./assets/icon.png
---
mUGGINFACE answers one question: which Hugging Face models are worth running on this Mac. You tick the domains you care about, among text, code, image, video, voice, vision, embeddings and translation, and the app lists matching models.

It detects your chip, usable memory and free disk space, shows them in a card, and gives each model a score that combines estimated performance and lightness. A model that is too heavy for the machine is flagged. The score is built from size, popularity, trend and freshness, so the README calls it an estimate and not a benchmark.

Beside the recommendations the sidebar holds:

- Favorites;
- Watch, which keeps checking for new models;
- Downloads;
- AI agent;
- My hardware.

For a model you want, the app can download it itself, with resume and a SHA-256 check. It can also send the install instructions to an AI agent: Claude Code, the Claude API or a command of your own.

Filters narrow the list by weight, license and format, and a search field finds a model by name. The interface comes in French, English, Spanish and Italian. Releases are Apple silicon builds for macOS 15 or later, and they are notarized.
