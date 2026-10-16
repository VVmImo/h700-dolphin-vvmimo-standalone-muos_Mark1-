H700 Dolphin Emulator — V.V.mImo Standalone for muOS

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

Read the [Beta Tester Manual — Game Settings & Game Patches]([VVMIMO-BETA-GAME-SETTINGS-AND-PATCHES-EN.pdf)](https://github.com/VVmImo/h700-dolphin-vvmimo-standalone-muos_Mark1-/releases/download/H700_Dolphin_Emulator_Standalone_for_muOS/VVMIMO-BETA-GAME-SETTINGS-AND-PATCHES-EN.pdf) before testing. The full English manual and complete `.muxupd` distribution package accompany the release. Use the documents matching your build.

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
