# Raidex 3.12 verification

- Package source: `192b1fe2f312ffd8891acf2a24056425206dfe22`, tagged `v3.12`. [PR #5](https://github.com/c4Luffy/Raidex-CoC-Automation/pull/5) merged as `6c499ee5c27ecc98a3a16af38a1e91a890c64b54`. The merged tree is identical to the packaged source tree.
- Review regression checks: all 31 passed. Instance guards: all 54 passed. Run targets: all 37 passed. No game input was used.
- Release/x64 build: passed with zero warnings and zero errors. Normal and protected engine self-checks passed. Obfuscar 2.2.50 verified 5,616 renamed engine symbols while preserving the WinUI shell.
- Saved-data compatibility: normal/protected builds agreed against an isolated saved-data snapshot. Package checks preserved real application data. Compatibility fingerprint: `26F10BEC893798AE4C0853179BEFA76D68DF0566E78FD1FFB7A65E5CD87EF8AF`.
- Packaged startup: passed. A separate fresh-cache `--verify-engine-startup` probe returned exit 0 with no new matching Windows Application error events. This validates startup, not a complete interactive UI walkthrough.
- Release checks: version 3.12, runtime assets, expected archive contents, dependency refusal, data preservation, and updater success, missing-checksum compatibility, rollback, and unsafe-folder refusal passed.
- Live-game scope: no new live-game cycle or simultaneous multi-profile game test was performed.
- Draft assets: GitHub ZIP digest and size matched the local package. The checksum asset's own SHA-256 also matched: `59CDAB2974779CB801A0B3C9982469D6F30A3F3EA51DDDD9CF5522F000D0DD86`.
- Publication: `v3.12` was published as Latest on 30 September 2026 at 16:44:27 UTC.
- Public latest-download verification: the actual public latest ZIP and checksum were downloaded and verified at 16:44:44 UTC. The public ZIP hash matches both the local package and downloaded checksum. Archive entries include `Raidex CoC Automation/Raidex CoC Automation.exe`, `Engine/Raidex.Engine.Host.exe` beneath that folder, and release notes headed `Raidex 3.12`.
- Public labels: the Downloads README and this report describe 3.12. Website and authenticated customer portal labels were not deployed or independently verified in this release.

ZIP size: **265,661,343 bytes** (253 MiB rounded).

SHA-256:

```text
CA274DC29C49AE464F06DF510128D35E8FB202D5B81FC871F99088B09CA3F5E0
```

[Download](https://github.com/c4Luffy/Raidex-Downloads/releases/latest/download/Raidex.CoC.Automation-win-x64.zip) · [Checksum](https://github.com/c4Luffy/Raidex-Downloads/releases/latest/download/Raidex.CoC.Automation-win-x64.zip.sha256) · [Release](https://github.com/c4Luffy/Raidex-Downloads/releases/tag/v3.12)
