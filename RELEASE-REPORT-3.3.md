# Raidex 3.3 release report

## Status

Raidex 3.3 is published as the Latest customer release in [Raidex-Downloads](https://github.com/c4Luffy/Raidex-Downloads/releases/tag/v3.3). The Windows customer ZIP and checksum are attached, the public Latest download was fetched, and its hash matches the published checksum.

## Issue and cause

Local report RX-326A37 recorded a safe stop because Raidex did not confirm the normal **Find a Match** button after Multiplayer opened. The bot sent no input. The report has no screenshot from after Multiplayer opened, so the exact reason the button was missed is not confirmed.

The supplied Home Village screenshot showed a separate detection bug: generic Upgrade cards on the selected Hero Hall were counted as Wall upgrade choices. This incorrectly classified the screen as WallSelection. It was not confirmed as the cause of the stopped attack.

## Fix

- Wall selection and recovery now require the visible Wall title with an upgrade card.
- Attack startup checks for the normal Find a Match button for up to four more seconds. It sends no tap until the button is confirmed and still stops safely if it never appears.

## Build and package checks

- Source commit 77102464f6057450db4d8762d2246f46e6d4556f and tag v3.3 are pushed to GitHub.
- Development package 3.3 passed the Release build, 39 no-input instance guards, engine self-check, and release smoke check. ZIP size: 255,753,592 bytes. SHA-256: 860EC1F52ABC7673FC38DDD46D4443ADBBFA1C4CCA390FE7DE7A24741E193C32. The updated test GUI opened and responded.
- Protected customer package 3.3 passed the Release build, 39 no-input instance guards, engine self-check, saved-data compatibility and parity checks, and Test-Release smoke check. ZIP size: 255,753,587 bytes. SHA-256: 409643B47271F1CEF2B645A20D30F27BEEDB4CA05A3B0380E711A3BAB8774D2C.
- No live game cycle was run. Offline checks do not prove live Find a Match timing.

## Public customer download

Release: [Raidex 3.3](https://github.com/c4Luffy/Raidex-Downloads/releases/tag/v3.3)

The actual ZIP from releases/latest/download was downloaded on 2026-09-28. It is 255,753,587 bytes, and its SHA-256 409643B47271F1CEF2B645A20D30F27BEEDB4CA05A3B0380E711A3BAB8774D2C matches the downloaded public .sha256 file and the local customer package.

The public ZIP contains Raidex CoC Automation/Raidex CoC Automation.exe. Its product version is 3.3 and its SHA-256 is 075F10A1527F1C26923A64983A9F42F621BA3C05F58E14880F17A64E38717745. The engine host executable is also present.

Before 3.3 was published, Latest pointed to version 3.2.3. That public ZIP was 255,752,603 bytes with SHA-256 8D059C2C6B023DB7A9B2BB0700C1ACC452C287EE6099AACEB733CA07A4D75462, matching its then-public sidecar. Its app executable reported product version 3.2.3. The earlier download was inspected but not run.
