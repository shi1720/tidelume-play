# Tidelume asset provenance

The SVG illustrations (`background.svg`, `logo.svg`) and all files in `audio/` are original procedural works created specifically for Tidelume, a game by Shivam Gupta. They contain no stock artwork, samples, recordings, or third-party generated content. Copyright © 2026 Shivam Gupta. All rights reserved, except where the repository's overall license grants rights to these original assets.

The original generation source is `tools/art/generate_assets.py`. Sound is synthesized mathematically as stereo 16-bit PCM at 22,050 Hz; no outside audio libraries or recordings were used. The ambience is a 32-second seamless loop with a gentle zero-amplitude boundary. All files are peak limited to 0.3 full scale, and UI effects are substantially quieter.

## Fonts

These fonts are redistributed under the SIL Open Font License 1.1. The corresponding complete license and copyright notice are included beside each font. The downloaded fonts have not been modified or renamed internally.

| File | Family | Source | License file |
| --- | --- | --- | --- |
| `fonts/Manrope.ttf` | Manrope, variable weight | https://github.com/google/fonts/tree/main/ofl/manrope | `fonts/Manrope-OFL.txt` |
| `fonts/NotoSansKR.ttf` | Noto Sans KR, variable weight | https://github.com/google/fonts/tree/main/ofl/notosanskr | `fonts/NotoSansKR-OFL.txt` |
| `fonts/CormorantGaramond.ttf` | Cormorant Garamond, variable weight | https://github.com/google/fonts/tree/main/ofl/cormorantgaramond | `fonts/CormorantGaramond-OFL.txt` |

Fonts are bundled locally so the game requires no font CDN, network access, account, or API key at runtime. Noto Sans KR supplies Korean glyph coverage.
