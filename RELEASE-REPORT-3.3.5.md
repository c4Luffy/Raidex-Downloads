# Raidex 3.3.5 release report

Published as the latest customer download on 28 September 2026 UTC.

## Changes

- The Windows login uses the selected Night Village photo as a still background.
- The video player and Pause/Play button are removed.
- The unused MP4 is absent from the customer ZIP.
- The six heroes, blank sign, Raidex logo, centered login controls, and branded Discord completion page remain.

## Verification

- Source commit `11f0561`, tag `v3.3.5`.
- Fresh checkout protected build: zero errors and warnings; 39 no-input safety checks, engine self-check, saved-data compatibility, and update recovery passed.
- Packaged Windows app `--verify-engine-startup` exited 0. The login photo was visually checked in the app.
- Actual public Latest ZIP downloaded and checked: 265,566,217 bytes; SHA-256 `4F0D95DCD18C9FEA4468E34BD22DBF4FFD8373F27752CCA952F2392CE705D68F`, matching the public sidecar and tested package.
- Archive contains the app, Night Village photo, and Engine host. It contains no login MP4.
- Live Setup page shows 3.3.5 and its screenshot matches the repository file. Live customer portal shows 3.3.5 and 253 MB.
- No new live game cycle was run for this visual update. The scene is generated fan artwork, not official Supercell media.

[Download](https://github.com/c4Luffy/Raidex-Downloads/releases/latest/download/Raidex.CoC.Automation-win-x64.zip) · [Release](https://github.com/c4Luffy/Raidex-Downloads/releases/tag/v3.3.5)
