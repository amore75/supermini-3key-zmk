# SuperMini NRF52840 — 3-Key ZMK (Matrix with Diodes)

Repo layout:
```
.github/workflows/build.yml   # GitHub Actions workflow (must be at repo root)
config/                       # ZMK config lives here
  boards/shields/supermini_3key/supermini_3key.overlay
  boards/shields/supermini_3key/supermini_3key.conf
  keymap/keymap.keymap
  README.md
```
Build: the workflow clones ZMK and builds `nice_nano_v2` with `-DSHIELD=supermini_3key`.
