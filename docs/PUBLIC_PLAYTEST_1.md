# Hordicus v23.8.51 — Public Playtest 1

This is the first public Hordicus playtest package.

## Download

- [Release page](https://github.com/Sponsor-Sorter/Hordicus/releases/tag/v23.8.51)
- [Direct Windows x64 download](https://github.com/Sponsor-Sorter/Hordicus/releases/download/v23.8.51/Hordicus_v23_8_51_Public_Playtest_1_Windows_x64.zip)

## What this build contains

- Current Shattered March authored map and gameplay content
- Current weapon, enemy, boss, progression and UI systems
- Inventory and Shop
- Current HUD and Run Over polish
- Persistent profile/settings support
- Public-playtest packaging and developer-feature hardening

## Known issue

- Some watch towers currently have no collision box.

## Public package cleanup

This release is deliberately player-only.

Removed from the public package:

- source code
- Hordicus Map Builder / map editor
- internal tools and tests
- compiler/import libraries
- build intermediates
- asset-authoring packs and metadata
- development documentation that is not required to play

Runtime assets, the current authored map and required recovery data remain included.

## Playtest focus

Please pay particular attention to:

- launching and closing the game normally
- starting new runs
- movement, aiming, firing and reloading
- healing
- Shop and Inventory
- fullscreen switching
- save/profile persistence after relaunching
- HUD placement and weapon information
- Run Over summary and upgrade presentation
- map collision, foreground/occlusion and region transitions
- audio and graphics behaviour
- crashes, freezes or major performance problems

## Reporting a bug

Please include:

- exact Hordicus version
- Windows version
- what you were doing immediately before the problem
- clear reproduction steps
- expected behaviour
- actual behaviour
- whether it happens every time
- screenshots or video when useful

Please submit reports through the official Hordicus Discord bug-report forum.

## Integrity

Public ZIP:

```text
Hordicus_v23_8_51_Public_Playtest_1_Windows_x64.zip
SHA-256: 936d2124905f1c864cf7d9a6e14a14d1ec94b7c8d011f79814d7f6256ce5257a
```

Executable:

```text
Hordicus.exe
SHA-256: b760afe5428fa53c6d2e521503fa0224a7bc5143b786fe960c4697ee9cb4666d
```

The GitHub release asset digest matches the expected public ZIP SHA-256.
