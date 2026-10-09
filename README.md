# TIDELUME · 타이드룸

**Carry the light home.** A complete short Godot puzzle voyage created by **Shivam Gupta** with AI-assisted development.

[Play now](https://shi1720.github.io/tidelume-play/)

Twelve authored levels, English/Korean, a six-step guide, three-level demo,
local profiles, undo, state-aware hints, and a narrative ending. In the final
chapter, memories stay lit as you explore both tides.

This repository contains the playable Web release and its licenses.
The source project is maintained in the creator's separate `tidelume` repository.

## Local play

```sh
python3 -m http.server 8765
```

Open http://localhost:8765. Serve over HTTP; do not open index.html as a file.
Single-threaded Godot Web export, Compatibility renderer. No gameplay server,
account, tracking, ads, or API keys. Profiles are local names, not online auth.
Clearing browser storage removes local progress. Export a backup from Profile.

## Controls

Click a mirror to turn it. Tab to the board, arrow keys select, Enter/Space
rotates. T changes tide, Z undoes, R resets, H hints, Escape pauses.

## Distribution and notices

This jam campaign is free to play. A proposed expanded $5.99 edition is not on sale.
All original assets are credited to Shivam Gupta. Godot and font licenses are in
`licenses/`. No claim of a commercial launch, cloud saves, or platform certification.
