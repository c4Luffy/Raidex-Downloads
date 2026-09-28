# Raidex 3.3.2 release report

Published 28 September 2026 as the Latest customer release.

## Changes

- Eight-second Night Village welcome video, upscaled in Google Flow to 1920x1080 at 24 fps.
- Centered compact login, visible original Raidex logo, pause/play control and matching still fallback.
- Branded browser success/failure pages after Discord sign-in, with HTML-encoding checks.
- Discord OAuth asks for identify, email and guilds.join. Joining is limited to the Raidex server and a join failure does not block sign-in.
- Generated fan artwork; not official Supercell media.

## Verification

- Source: a145d33, tag v3.3.2; pushed to source branch and main.
- Build passed with zero errors/warnings; 39 no-input instance guards, protected self-check, normal/protected data compatibility and update recovery checks passed.
- Final packaged Windows startup exited 0; real packaged video login visually checked. Pause and missing-video fallback checked in the development build.
- Full video decode passed. App video retains the original 1080p stream; audio was removed without video re-encoding.
- Callback success/failure HTML rendered from the real app code; encoding regression check passed.
- Live OAuth scope, server-join disclosure, account and health checks passed. Actual new-member joining has not been exercised with a fresh consenting customer.
- No new live game cycle was run for this login update.
- Draft had the intended ZIP and checksum. Published as Latest at 2026-09-28T18:30:44Z.
- Actual public latest-download ZIP fetched; checksum matched both public sidecar and tested package.
- ZIP size: 285602949 bytes (about 272 MiB).
- SHA-256: `42C96D09F58650DF96A951DDD084779F3A1ECAE47A1E9DBA17C48F0472A7BF8A`
- Archive contains the Windows app, Engine host and `Assets/raidex-login-welcome.mp4`.
- Website deployment: 80eae986-a70b-47cf-958f-c54071a8d6b6. Live Setup version and screenshot hash matched.
- Customer portal deployment: ee0a282b-e2a2-40d8-97e2-b374ade635bb. Live version 3.3.2 and size 272 MB verified.

[Download](https://github.com/c4Luffy/Raidex-Downloads/releases/latest/download/Raidex.CoC.Automation-win-x64.zip) · [Release](https://github.com/c4Luffy/Raidex-Downloads/releases/tag/v3.3.2)
