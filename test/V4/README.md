# Heartseeker Human Yuumi V4 - Celestial test

## Current test build: V4.3
Import `Heartseeker Human Yuumi V4.3 All Skins.fantome` in Celestial. Disable previous Heartseeker test mods first. This build replaces all 79 installed Yuumi skin IDs, including chromas, and doubles the visual mesh scale from 1.0 to 2.0.

## Changes
- V4 Elegant Idle, including idle variants.
- V4 Run (in-place, retargeted to the 95-bone game rig), slower locomotion and idle/run transitions.
- Custom loading-screen textures (308 x 560) for all 11 skin groups.
- V4.3 doubles visual model scale for all 79 skin IDs; all other 140 WAD entries remain byte-identical to V4.2. Model and book scale together. Animations, loading portraits, and original gameplay parameters remain unchanged.

## Files
- `Heartseeker_V4_Test_Preview.blend`: Blender scene and animations.
- `animations/`: exported Idle, Run and Walk ANM files.
- `build-report.json`: original V4 package validation.
- `all-skins-build-report.json`: V4.2 skin mapping and validation.
- `scale-build-report.json`: V4.3 scale validation and checksum.
- `../../Yuumi/anim/`: source animation files.
- `../../Yuumi/LoadingScreen/`: cropped loading portrait and game TEX.

V4.2 was visually tested in game; V4.3 passed offline ZIP/WAD validation. In-game scale, healthbar alignment and skin-specific effects still need testing. Champion-select splash art is unchanged. Earlier packages are retained for comparison.
