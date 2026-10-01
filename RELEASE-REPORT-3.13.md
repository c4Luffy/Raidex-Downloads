# Raidex 3.13 verification

- Package source: `3150089b5c811f006ba5b9c144ee0ccc83f12a9c`, tagged `v3.13`. Source fix [PR #6](https://github.com/c4Luffy/Raidex-CoC-Automation/pull/6) merged as `403d9c82900a840ec3eddc58399780253107804`. Release version metadata [PR #7](https://github.com/c4Luffy/Raidex-CoC-Automation/pull/7) merged as `2b4e05ff46e668486f03678b3041f2e0925e7fb4`; its tree matches the package tag.
- Offline regression checks: all 41 passed, including fake-ADB village switching in both directions, confirmation, bounded retries, Stop, dry-run, and unknown-screen refusal. All 54 instance guards and 37 run-target checks passed (132 checks total).
- Release/x64 protected build: passed with zero warnings or errors. Normal and protected engine self-tests passed. Obfuscar 2.2.50 verified 5,642 renamed engine symbols while preserving the WinUI shell.
- Builder fixtures verified Area 2 with no reinforcements, a single surviving troop, and separate planning and active-battle controls. Failure-screen preservation checks passed.
- Saved-data compatibility: normal and protected builds matched the isolated snapshot. Compatibility fingerprint: `26F10BEC893798AE4C0853179BEFA76D68DF0566E78FD1FFB7A65E5CD87EF8AF`.
- Package smoke passed: archive/version/runtime assets, fresh-cache packaged startup, missing-engine dependency refusal, data preservation, and updater success, missing-checksum compatibility, rollback, and unsafe-folder refusal.
- Separate packaged startup probe exited 0; no matching Windows Application error events were found.
- Live-game scope: no live Builder attack, village switch, or multi-profile cycle was run. Customer testing of these two changes remains needed.
- Source repository release: `v3.13` published at 00:52:56 UTC on 1 October 2026.
- Downloads release: `v3.13` published as Latest at 00:52:07 UTC on 1 October 2026. Both uploaded asset digests matched the local package and checksum.
- Public latest-download verification: the actual latest ZIP and checksum were downloaded at 00:52:41 UTC. The ZIP hash and size match the validated local package; its archive includes the executable, Engine host, and 3.13 release notes.
- Downloads README and this report describe 3.13. Website and customer portal labels were not updated or checked.

ZIP size: **265,815,273 bytes** (253 MiB rounded).

SHA-256:

```text
9C954B94DFEF0B67AA4F087F3B0115807515DE42454C8C18CE30E30213F5B7FF
```

[Download](https://github.com/c4Luffy/Raidex-Downloads/releases/latest/download/Raidex.CoC.Automation-win-x64.zip) · [Checksum](https://github.com/c4Luffy/Raidex-Downloads/releases/latest/download/Raidex.CoC.Automation-win-x64.zip.sha256) · [Downloads release](https://github.com/c4Luffy/Raidex-Downloads/releases/tag/v3.13) · [Source release](https://github.com/c4Luffy/Raidex-CoC-Automation/releases/tag/v3.13)
