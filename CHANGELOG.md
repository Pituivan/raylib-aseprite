# Changelog

All notable changes to this project will be documented in this file.

## [6.0.1] - 2026-09-11

### Fixed

- Black pixels not rendering ([#31](https://github.com/RobLoach/raylib-aseprite/pull/31))
- C++ compilation by removing `inline` from `GetAsepriteTexture()` ([#32](https://github.com/RobLoach/raylib-aseprite/pull/32))
- Memory leak when loading an invalid Aseprite file
- Out-of-bounds read in `LoadAsepriteSliceFromIndex()` when given a negative index
- Crash in `SetAsepriteTagFrame()` and `GetAsepriteTagFrame()` when given an empty tag
- C++ compilation error from the string literal in `GenAsepriteSliceDefault()`
- Deprecated `FetchContent_Populate()` usage, which fails on CMake 4.x

## [6.0.0] - 2026-04-23

### Changed

- Updated to raylib 6.0 ([#29](https://github.com/RobLoach/raylib-aseprite/pull/29))

### Fixed

- Grayscale support by checking `ase->mode` ([#30](https://github.com/RobLoach/raylib-aseprite/pull/30))

[6.0.1]: https://github.com/RobLoach/raylib-aseprite/releases/tag/v6.0.1
[6.0.0]: https://github.com/RobLoach/raylib-aseprite/releases/tag/v6.0.0
