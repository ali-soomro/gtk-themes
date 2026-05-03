# gtk-themes — Cutefish GTK Themes

## Purpose
GTK themes for Cutefish desktop (light, dark, and default variants). Pure CSS themes for GTK application styling consistency.

## Build
```bash
cmake -B build -DCMAKE_INSTALL_PREFIX=/usr && sudo cmake --install build
```

## Dependencies
None (install-only, no compilation)

## Structure
- `Cutefish/` — default GTK theme
- `Cutefish-light/` — light GTK theme
- `Cutefish-dark/` — dark GTK theme

## Install Targets
- All three theme directories → `${CMAKE_INSTALL_PREFIX}/share/themes/`

## Qt5→Qt6 Migration Notes
- `cmake_minimum_version` bumped to 3.16

## Status
✅ Ported, built, installed, pushed (github.com/ali-soomro)
