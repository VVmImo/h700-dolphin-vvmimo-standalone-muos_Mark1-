H700 Dolphin Emulator — V.V.mImo Standalone for muOS

## Current release: Mark1.B.V211 — 18 October 2026

Dolphin Standalone for muOS — compilation and configuration by **V.V.Mimo**.

[Download the complete V211 installer](https://github.com/VVmImo/h700-dolphin-vvmimo-standalone-muos_Mark1-/releases/download/H700_Dolphin_Emulator_Standalone_for_muOS/h700-dolphin-vvmimo-standalone-muos_Mark1.B.V211.muxupd) · [SHA-256](https://github.com/VVmImo/h700-dolphin-vvmimo-standalone-muos_Mark1-/releases/download/H700_Dolphin_Emulator_Standalone_for_muOS/h700-dolphin-vvmimo-standalone-muos_Mark1.B.V211.muxupd.sha256)

**Required: enable BOTH zRAM and the Swap option in muOS before launching games. Keep both enabled while using this build.**

Estimated overall performance improvement of around **20%**, according to the developer's tests. Results vary by game, scene, device and settings; this is not a controlled benchmark or a guaranteed improvement in every game.

- Dynamic Near/Far JIT capacity and adaptive vertex/index buffers, with circular synchronized uniform buffers.
- Independent CPU/VI controls, current game patches, profiles, CRT filters and experimental frame generation.
- Image Scale **40–100%**, in 1% steps: centres a smaller output image without changing internal resolution or OSD size. Find it in **General Settings V.V.mImo → FPS Control → Image Scale (%)**.
- Main OSD limited to two lines, with an independently selectable Generated FPS display. Generated FPS means real plus predicted frames, not game-logic speed.
- Internal-controller mapping wizard, save/load shortcuts and automatic creation of the save-state directory. Hold Select first, then R1 to save or L1 to load.
- Temporary development measurements removed; functional feedback and all existing controls retained.

Complete distribution with the developer device's current global/game INIs and Config application settings, matching reset references, runtime libraries, shaders, launcher, core association and service suspend/restore helper. No games, ROMs, personal saves or memory cards are included.

Back up your saves/settings on your PC before installation. Close Dolphin and Config, place the `.muxupd` in the SD card's `ARCHIVE` directory, install using **muOS Applications → Archive Manager**, then restart muOS. The package installs the supplied developer settings at the packaged paths; existing personal settings there will be replaced. Save-state compatibility across builds is not guaranteed. If needed, use **Controls → Configure internal controller** for your model.

### Recommended games to test

This list includes **only games labelled Experimental on the developer's muOS device**. Here that label means **playable and tested by the developer**, and recommended for community testing. It does not promise full speed, a completed playthrough, perfect graphics/audio or compatibility with another revision. Names below preserve the device labels; IDs come from the game headers. Multi-disc entries share a row when their ID is the same.

| Game ID | Game name / muOS label |
| --- | --- |
| `GFPEA4` | Frogger - Ancient Shadow (USA) (En,Es) |
| `GHSY69` | Harry Potter and the Chamber of Secrets (Europe) (En,Fr,De) |
| `GHSX69` | Harry Potter and the Chamber of Secrets (Europe) (Es,It,Pt) |
| `RHDE8P` | House of the Dead 2 & 3 Return, The (USA) (En,Fr,Es).nkit |
| `GP4J18` | Hudson Selection Vol. 3 - PC Genjin - Pithecanthropus Computerurus (Japan) |
| `GKYP01` | Kirby Air Ride (Europe) (En,Fr,De,Es,It) |
| `G4SE01` | Legend of Zelda, The - Four Swords Adventures (USA).nkit |
| `GZLP01` | Legend of Zelda, The - The Wind Waker (Europe) (En,Fr,De,Es,It) |
| `GZLE01` | Legend of Zelda, The - The Wind Waker (USA).nkit |
| `GZ2P01` | Legend of Zelda, The - Twilight Princess (Europe) (En,Fr,De,Es,It) |
| `GLME01` | Luigi's Mansion (USA).nkit |
| `GLME05` | Luigi's Mansion Premium Deluxe (v2.2.1) |
| `GM4P01` | Mario Kart - Double Dash!! (Europe) (En,Fr,De,Es,It) |
| `GM4E08` | Mario Kart Double Dash (Retro Track Grand Prix v2.1) |
| `RMCE01` | Mario Kart Wii (USA) (En,Fr,Es).nkit |
| `GM8P01` | Metroid Prime (Europe) (En,Fr,De,Es,It) |
| `GOWP69` | Need for Speed - Most Wanted (Europe) |
| `GP2P69` | Pac-Man World 2 (Europe) (En,Fr,De,Es,It) |
| `G89EAF` | Pac-Man World Rally (USA) |
| `GXXE01` | Pokemon XD - Next Gen (v1.2.1) |
| `GPUP8P` | Puyo Pop Fever (Europe) (En,Fr,De,Es,It) |
| `GRJP69` | R-Racing |
| `GRAP75` | Rally Championship (United Kingdom) |
| `GRFP78` | Red Faction II |
| `GRDP5D` | RedCard |
| `GR9P6L` | Reign of Fire |
| `GBIE08` | Resident Evil (USA) (Disc 1) / Resident Evil (USA) (Disc 2) |
| `GCDP08` | Resident Evil - Code - Veronica X (Europe) (En,Fr,De,Es,It) (Disc 1) / Resident Evil - Code - Veronica X (Europe) (En,Fr,De,Es,It) (Disc 2) |
| `GHAP08` | Resident Evil 2 (Europe) (En,Fr,De,Es,It) |
| `GHAE08` | Resident Evil 2 (USA) |
| `G4BP08` | Resident Evil 4 (Europe) (En,Fr,De,Es,It) (Disc 1) / Resident Evil 4 (Europe) (En,Fr,De,Es,It) (Disc 2) |
| `G4BE08` | Resident Evil 4 (USA) (Disc 1) / Resident Evil 4 (USA) (Disc 2) |
| `GBZP08` | Resident Evil Zero (Europe) (En,Fr,De,Es,It) (Disc 1) / Resident Evil Zero (Europe) (En,Fr,De,Es,It) (Disc 2) |
| `GBZE08` | Resident Evil Zero (USA) (Disc 1) / Resident Evil Zero (USA) (Disc 2) |
| `GKRPB2` | Ribbit King |
| `GRBP6S` | Robotech - Battlecry |
| `GKUE9G` | Scaler (USA) (En,Fr) |
| `G3BP9G` | Serious Sam - Next Encounter (Europe) (En,Fr,De) |
| `GPWP69` | Spawn - Armageddon (Europe) (En,Fr,De,Es,It) |
| `GF7P01` | Star Fox - Assault (Europe) (En,Fr,De,Es,It) |
| `GSAP01` | Star Fox Adventures (Europe) (En,Fr,De,Es,It) (Rev 1) |
| `GBWP64` | Star Wars - Bounty Hunter (Europe) |
| `GJKP52` | Star Wars - Jedi Knight II - Jedi Outcast (Europe) |
| `GSWP64` | Star Wars - Rogue Squadron II - Rogue Leader (Europe) |
| `GALP01` | Super Smash Bros. Melee (Europe) (En,Fr,De,Es,It) |
| `GWWE01` | Wario World (USA).nkit |
| `GZWP01` | WarioWare, Inc. - Mega Party Game$! (Europe) (En,Fr,De,Es,It) |
| `GWMP8P` | Worms 3D |
| `GWBP41` | Worms Blast (Europe) (En,Fr,De,Es,It) |
| `G3EP51` | XGIII |
| `GXAP51` | XGRA - Extreme G Racing Association |


### Beta testing

Read the [Beta Tester Manual — Game Settings & Game Patches (PDF)](https://github.com/VVmImo/h700-dolphin-vvmimo-standalone-muos_Mark1-/releases/download/H700_Dolphin_Emulator_Standalone_for_muOS/VVMIMO-BETA-GAME-SETTINGS-AND-PATCHES-EN.pdf). Start from the supplied defaults, change one approved per-game option at a time and compare the same scene.

Report results in [GitHub Discussions](https://github.com/VVmImo/h700-dolphin-vvmimo-standalone-muos_Mark1-/discussions), including device, muOS, V211, exact game ID/region/revision, settings, game speed, audio, graphics and stability. Successful tests and problems are equally useful. Never upload game files.

---

An unofficial, experimental Dolphin project for GameCube and supported Wii games on H700 handhelds running muOS.

The goal is practical playability on limited hardware: reduce emulation overhead, improve presentation and give each game its own configuration. This is a **standalone emulator**, with a dedicated configuration application—not a RetroArch/libretro core or a KNULLI package.

## What makes this project different?

- Experimental PPC-to-ARM64 JIT optimizations and memory-access controls.
- Automatic emulated CPU adjustment, independent VI controls and configurable scene profiles.
- Rendering-cycle skipping and experimental frame generation to improve perceived smoothness.
- Per-game graphics, emulation, audio and timing settings.
- Custom patches for selected games, including selective effects, scenery and lighting reduction, native timing and memory expansion.
- A configuration application, controller mappings, launcher, loading image and reset defaults.

Not every mechanism benefits every game. Frame generation does not make game logic faster, and a high FPS counter does not guarantee full-speed movement or synchronized sound. Compatibility and useful settings are recorded by exact game ID.

## Beta testers wanted

We welcome testers who can compare the supplied defaults with individual per-game changes and report both improvements and regressions.

For this beta, **test only Game Settings and Game Patches**. Leave all other menus at the supplied defaults unless the maintainer specifically requests a diagnostic test.

Read the [Beta Tester Manual — Game Settings & Game Patches](https://github.com/VVmImo/h700-dolphin-vvmimo-standalone-muos_Mark1-/releases/download/H700_Dolphin_Emulator_Standalone_for_muOS/VVMIMO-BETA-GAME-SETTINGS-AND-PATCHES-EN.pdf) before testing. The full English manual and complete `.muxupd` distribution package accompany the release. Use the documents matching your build.

Reports should include the device, muOS version, package/build, exact game ID, region/revision, changed settings, affected scene and a short video if possible.

## Compatibility

- **Playable:** the game can be played.
- **In progress:** playable, but still needs adjustments.
- **Cursed:** the game runs, but requires substantial development.

These are user-reported categories, not promises of full speed or perfect graphics/audio. See the [complete GameCube and Wii compatibility catalogue](GAMECUBE-COMPATIBILITY.en.md) and the [repository README](README-REPOSITORY.en.md) for implementations, installation and recorded results.

## Original games required

You must own the original games and use lawfully obtained dumps. No games, ROMs or game-download links are supplied. Do not attach copyrighted game files to reports.

## Status and credits

Experimental beta: back up saves, memory cards and settings before installing. No universal performance improvement or compatibility guarantee is claimed.

Based on Dolphin Emulator and the work of its contributors. V.V.mImo is not an official Dolphin, Nintendo, muOS or Anbernic release. Preserve upstream copyright and licensing notices; binary releases must include the corresponding source and required licensing material.
