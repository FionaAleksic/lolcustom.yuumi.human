# Heartseeker Human Yuumi V4 – Celeste test

Import `Heartseeker Human Yuumi V4.fantome` in the mod manager. This test replaces the base Yuumi skin. Disable the previous Heartseeker test mod before enabling V4.

## Changes
- V4 Elegant Idle, including idle variants.
- V4 Run (in-place, retargeted to the existing 95-bone game rig), slower locomotion and idle/run transitions.
- Custom loading-screen texture, 308 x 560 pixels.
- The other 100 WAD entries from the existing test package are unchanged.

## Files
- `Heartseeker_V4_Test_Preview.blend`: Blender scene and animations.
- `animations/`: exported Idle, Run and Walk ANM files.
- `build-report.json`: package checksum, clip inventory and validation.
- `../../Yuumi/anim/`: source animation files.
- `../../Yuumi/LoadingScreen/`: cropped loading portrait and game TEX.

Offline ZIP/WAD parsing, animation track checks and texture decoding passed. Actual import and in-game behavior still need testing. Do not treat this as a production release.
