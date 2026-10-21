# Raidex 3.9 verification

- Package source: `3117cd9ac4a457fa968f9f907f093f24ef849824`, tagged `v3.9` in the source repository.
- Builder deployment fix: `72b3234cce90dca34191c7d9ee129dfa694c5593`, included in the tagged source.
- Build: passed with zero warnings and zero errors.
- Instance guards: all 49 passed without emulator or game input.
- Protected engine self-check: passed, including deployment evidence, bounded recovery retries, stop/pause handling, and pre-recovery report image checks.
- Normal and protected saved-data compatibility: matched against a stable snapshot.
- Packaged app startup: exit code 0. No Windows Application warning/error events were recorded in the release validation window.
- Release smoke checks: package contents, version 3.9, executable checksum, runtime assets, successful update, missing-checksum rejection, rollback, and unsafe-folder rejection passed.
- Real AppData preservation: both self-test/startup and updater before/after comparisons passed.
- Live game input: not performed. The original customer visual failure remains unconfirmed until the affected machine is retested. Earlier reports captured the village after recovery; this release preserves the failed battle frame before recovery.
- GitHub draft: contained exactly the ZIP and its checksum. Downloaded draft assets matched the local package.
- Publication: source and Downloads releases are published as `v3.9`; the Downloads release is Latest.
- Public latest-download ZIP and checksum: downloaded independently after publication. Both match the local and draft package hashes. The public archive contains the expected app, engine, and 3.9 release notes.

ZIP size: **265,633,752 bytes**.

SHA-256:

```text
2A88C38F5B28490D6575AB07CAFA41C6774F8EC85118B94DE2BF7F3B8DA366CA
```

[Download](https://github.com/c4Luffy/Raidex-Downloads/releases/latest/download/Raidex.CoC.Automation-win-x64.zip) · [Checksum](https://github.com/c4Luffy/Raidex-Downloads/releases/latest/download/Raidex.CoC.Automation-win-x64.zip.sha256) · [Release](https://github.com/c4Luffy/Raidex-Downloads/releases/tag/v3.9)
