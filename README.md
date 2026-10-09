# TIDELUME

**Carry the light home.** An atmospheric puzzle voyage created by **Shivam Gupta**.

[Play TIDELUME](https://tidelume.web.app) | [Watch the narrated gameplay demo](https://youtu.be/WGfP8QVITXw)

Twelve authored islands, a six-step field guide, an optional three-island demo,
local keeper profiles, undo, state-aware hints, original sound effects and a
complete story ending. In the final chapter, memories stay lit as you explore
both tides. The English interface adapts to desktop and portrait screens.
Small portrait screens scroll to keep the board and controls readable.

## Play locally

Serve this folder over HTTP:

```sh
python3 -m http.server 8765
```

Then open `http://localhost:8765`. Opening `index.html` directly as a file is
unsupported. The game uses a single-threaded Godot Web export and does not
require a gameplay server, passwords, subscriptions or API keys.

## Controls

Click or tap a circular mirror to turn it. With a keyboard, Tab to the board,
use arrow keys to select a mirror, then Enter or Space to rotate it.
T changes tide, Z undoes, R resets, H provides a hint, and Escape pauses.

## Your progress

Profiles and progress stay in this browser or device. Clearing browser storage
removes them. Use Profile > Export save to keep a portable backup, and Import
save to restore one. Local profiles do not provide online authentication or
cloud synchronization.

## Downloads and credits

[Download version 1.1.0](https://github.com/shi1720/tidelume-play/releases/tag/v1.1.0).
The release also includes the narrated gameplay video, subtitle file and thumbnail.
The macOS application is unsigned and not notarized. The web version is the
recommended option for immediate play.

Creative direction and release decisions: Shivam Gupta. Development, original
art and sound production were assisted by AI tools. Built with Godot Engine.
Original source and assets use MIT; font and third-party notices are included
in `licenses/`. This public repository distributes the playable release. The
creator maintains the source project separately.
