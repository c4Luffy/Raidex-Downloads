# Raidex 3.7 verification

- Source: `1529dfcd45f66e02a910e02b698500c3ea3534ee`, tagged `v3.7`.
- Build: passed, zero warnings and zero errors.
- Instance guards: all 45 passed without emulator or game input.
- Protected engine self-check: passed.
- Normal/protected saved-data compatibility: matched.
- Packaged app startup: exit code 0, no relevant Windows Application errors.
- Release smoke checks: package contents, runtime assets, healthy install, missing-checksum update, automatic rollback, and unsafe-package rejection passed.
- Visual checks: welcome photo restored; Home Village, Builder Base, Clan Capital, and Humanization fit at the normal app size without page scrolling. The previous top section and dark background remain, with Clan interval fields beside their labels.
- Live game input: skipped at the release owner's request.
- Local ZIP, downloaded draft ZIP, and actual public latest-download ZIP: identical SHA-256 and size.

ZIP size: **261,713,065 bytes**.

SHA-256:

```text
921A020D9879514736C1B539D33985F07B2A375EC30F58450959CB9EEF7C9B4F
```

[Download](https://github.com/c4Luffy/Raidex-Downloads/releases/latest/download/Raidex.CoC.Automation-win-x64.zip) · [Checksum](https://github.com/c4Luffy/Raidex-Downloads/releases/latest/download/Raidex.CoC.Automation-win-x64.zip.sha256) · [Release](https://github.com/c4Luffy/Raidex-Downloads/releases/tag/v3.7)
