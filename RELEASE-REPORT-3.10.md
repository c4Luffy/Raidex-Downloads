# Raidex 3.10 verification

- Package source: `2dc97fa73e57f48d62c3fe576d5947b793052ec9`, tagged `v3.10` in the source repository. The merged source tree is identical to the tested tree.
- Build: passed with zero warnings and zero errors.
- Instance guards: all 51 passed without game input.
- Run targets: all 37 checks passed, covering confirmed-attack counting, time-based targets, daylight-saving behavior, work/rest persistence, and restart prevention after reaching a target.
- Protected engine self-check: passed.
- Normal and protected saved-data compatibility: matched against an isolated snapshot. Package checks preserved real application data.
- Packaged GUI startup: passed. A package missing an Engine dependency was refused as expected.
- Release checks: runtime assets, executable metadata, executable and ZIP checksums, successful update, missing-checksum compatibility, rollback, and unsafe-folder refusal passed.
- Visual checks: the full app was checked at 1168 × 657, including the Instances overview, profile selection, failure tabs, and independent scrolling.
- Approved live check: exactly one regular Home Village attack completed, returned to the village, and stopped at **Attack target reached (1/1)**. No second attack started. The profile's original settings were restored afterward.
- Live-check scope: the attack used a protected preview built from the same source commit. The final customer package passed its own package checks. Its protected Engine and Engine Host assemblies have identical hashes to the live-tested preview; the bundled GUI executable differs. No second live cycle, live time-based target, or simultaneous multi-profile run was performed.
- Draft assets: GitHub's uploaded ZIP digest matched the verified local package before publication.
- Publication: the Downloads release was published as `v3.10` and set to Latest on 30 September 2026.
- Public latest-download verification: the actual public ZIP and checksum were downloaded after publication. Both match the verified local package hash.
- Public labels: the Downloads README and setup guide show 3.10. The deployed customer portal serves the 3.10 version label and the correct rounded size of 253 MiB; its dashboard HTML matches the updated source after normalizing CSP nonces. No additional authenticated customer download was performed.
- Portal update checks: 41 unit checks, 9 local Worker/D1 integration checks, and a production deployment dry run passed. The deployed health endpoint returned `ok`.

ZIP size: **265,648,269 bytes**.

SHA-256:

```text
1EBEB2053AB89CEA95409353D12525F279235E20488F8EDA9C4AD59B64190901
```

[Download](https://github.com/c4Luffy/Raidex-Downloads/releases/latest/download/Raidex.CoC.Automation-win-x64.zip) · [Checksum](https://github.com/c4Luffy/Raidex-Downloads/releases/latest/download/Raidex.CoC.Automation-win-x64.zip.sha256) · [Release](https://github.com/c4Luffy/Raidex-Downloads/releases/tag/v3.10)
