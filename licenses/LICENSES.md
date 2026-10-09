# Tidelume asset provenance

The SVG illustrations (`background.svg`, `logo.svg`) and all files in `audio/` are original procedural works created specifically for Tidelume, a game by Shivam Gupta. These procedural assets contain no stock artwork, samples or recordings. Copyright © 2026 Shivam Gupta. All rights reserved, except where the repository's overall license grants rights to these original assets.

The original generation source is `tools/art/generate_assets.py` and `tools/art/generate_feedback.py`. Sound is synthesized mathematically as stereo 16-bit PCM at 22,050 Hz; no outside audio libraries or recordings were used. The ambience is a 32-second seamless loop with a gentle zero-amplitude boundary. All files are peak limited to 0.3 full scale, and UI effects are substantially quieter.

## Fonts

These fonts are redistributed under the SIL Open Font License 1.1. The corresponding complete license and copyright notice are included beside each font. The downloaded fonts have not been modified or renamed internally.

| File | Family | Source | License file |
| --- | --- | --- | --- |
| `fonts/Manrope.ttf` | Manrope, variable weight | https://github.com/google/fonts/tree/main/ofl/manrope | `fonts/Manrope-OFL.txt` |
| `fonts/NotoSansSymbols2.ttf` | Noto Sans Symbols 2 | https://github.com/google/fonts/tree/main/ofl/notosanssymbols2 | `fonts/NotoSansSymbols2-OFL.txt` |
| `fonts/CormorantGaramond.ttf` | Cormorant Garamond, variable weight | https://github.com/google/fonts/tree/main/ofl/cormorantgaramond | `fonts/CormorantGaramond-OFL.txt` |

Fonts are bundled locally so the game requires no font CDN, network access, account, or API key at runtime.

## Painted coastal backdrop

`coast-painted.png` is original AI-generated art created specifically for Tidelume with the built-in image-generation tool. It is not a stock photograph or a human-painted commission. The source prompt and usage are recorded in `docs/ART_DIRECTION.md`. The existing procedural lighthouse emblem and board rendering remain code-native. Copyright and use follow the repository license and applicable tool terms.
