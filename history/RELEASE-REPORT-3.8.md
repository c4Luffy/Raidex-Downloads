# Raidex 3.8 verification

- Source: `28db912957b93988d8329dba915cc9e5a4be2584`, tagged `v3.8`.
- Build: passed with zero warnings and zero errors.
- Instance guards: all 49 passed without emulator or game input. The eight-slot case uses four synthetic MuMu and four synthetic LDPlayer device identities; eight real emulator windows were not run.
- Protected engine self-check: passed.
- Normal and protected saved-data compatibility: matched against a stable snapshot.
- Packaged app startup: exit code 0; no Windows Application warning/error events in the release smoke window.
- Release smoke checks: package contents, runtime assets, healthy install, missing-checksum update, automatic rollback, and unsafe-package rejection passed.
- Real AppData comparisons: skipped because an installed Raidex automation session was actively writing its log and profile data during packaging. The running session was not stopped.
- Live game input: skipped at the release owner's request.
- Public latest-download ZIP and checksum: downloaded independently after publication; both match the local and draft ZIP SHA-256 and size.

Local ZIP size: **265,627,369 bytes**.

Local SHA-256:

```text
AB304232C75CAEC588AF5857E44DDF8A4507AB9E808197864008CB2F029DD6DB
```

[Download](https://github.com/c4Luffy/Raidex-Downloads/releases/latest/download/Raidex.CoC.Automation-win-x64.zip) · [Checksum](https://github.com/c4Luffy/Raidex-Downloads/releases/latest/download/Raidex.CoC.Automation-win-x64.zip.sha256) · [Release](https://github.com/c4Luffy/Raidex-Downloads/releases/tag/v3.8)
