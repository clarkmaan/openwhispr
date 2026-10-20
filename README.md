# Notes sidebar overflow: review evidence

Screenshots approved for the PR from clarkmaan/openwhispr:codex/notes-folder-load-more into OpenWhispr/openwhispr:main.

Source commit: `7627f6f64e7f0d731290d5a9d71e12fb88d11bdb`. Baseline: `2b4706f283811cca48ece6e90a3ab255c6677023`. The after captures were made from the identical source before committing. Source fingerprint: `27b018b30943e906abd72d260b2474089dd382d67d8facc784d3113f3dcd2a67`.

Primary `full-*` captures show the real Electron app on macOS 26.5.1 with an isolated SQLite profile containing synthetic notes, at a 1200 × 800 content viewport and 2× scale. `10-narrow.png` and `02-over-limit.png` are supplemental Electron component fixtures with mocked storage; the latter shows the shared private/Teamspaces tree. Relative minute labels advance between captures.

The dark before/after comparison uses `full-before-dark.png` and `full-11-folder-overview.png` to match the folder-overview state. `full-08-over-limit-dark.png` and `full-09-view-all-popover-dark.png` additionally show the older active note pinned in dark mode.
