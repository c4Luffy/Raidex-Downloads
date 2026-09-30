# Raidex 3.11 verification

- Package source: `61cb8dd7c33d7ffd105937c0a63dabbd19f0e118`, tagged `v3.11` in the source repository. PR #4 was merged as `e7619320a62cade9719240318fc9ff11c738122f`; the merged tree is identical to the packaged tree.
- Protected customer build: passed with zero warnings and zero errors.
- Instance guards: all 51 passed without game input.
- Run targets: all 37 checks passed without game input.
- Protected engine self-check: passed, including independent chart metric totals, Today, village filters, zero series, and 1/7/30-day boundaries.
- Normal and protected saved-data compatibility: matched against an isolated snapshot. Package checks preserved real application data.
- Packaged GUI startup: passed. A separate `--verify-engine-startup` probe returned exit 0 with no new matching Application error events. The final customer package also opened at its sign-in screen.
- Release checks: runtime assets, executable metadata and version 3.11, executable and ZIP checksums, successful update, missing-checksum compatibility, rollback, and unsafe-folder refusal passed. A missing Engine dependency was refused as expected.
- Visual checks: the updated app source was checked at approximately 1166 × 656 across Home, Profiles Overview/Device/Manage, Instances, Automation/Humanization, Settings, and the failure-report tabs. Real history covered separate Loot and Activity charts, Today with zero loot, seven days, five weeks, and an empty village filter; an isolated preview also checked 30-day dates.
- Live-game scope: a new cycle was skipped with the release owner's explicit approval. These changes concern charts, controls, layout, and wording; no new live-game or simultaneous multi-profile result is claimed.
- Draft assets: GitHub's uploaded ZIP and checksum asset digests matched both verified local files before publication.
- Publication: `v3.11` was published as Latest on 30 September 2026 at 11:58:04 UTC.
- Public latest-download verification: the actual public ZIP and checksum were downloaded at 11:59:16 UTC. Both match the verified package. The public archive contains the app executable, Engine host, and 3.11 release notes in the expected folders.

ZIP size: **265,648,340 bytes** (253 MiB rounded).

SHA-256:

```text
E8C47F15745F47A746900F7880E3A8866BF9AEFC3062C1C98F78AC0E57AA4294
```

[Download](https://github.com/c4Luffy/Raidex-Downloads/releases/latest/download/Raidex.CoC.Automation-win-x64.zip) · [Checksum](https://github.com/c4Luffy/Raidex-Downloads/releases/latest/download/Raidex.CoC.Automation-win-x64.zip.sha256) · [Release](https://github.com/c4Luffy/Raidex-Downloads/releases/tag/v3.11)
