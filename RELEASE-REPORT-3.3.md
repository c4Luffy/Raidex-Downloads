# Raidex 3.3 release report

## Status

The 3.3 GitHub release is a pre-release while its Windows customer ZIP and checksum are being attached. Raidex 3.2.3 remains the latest customer download.

## Issue found

The local report RX-326A37 recorded this safe stop: Automatic attack: normal Find a Match button was not confirmed; no input sent. The bot did not send an input. The saved report does not include the screen after Multiplayer opened, so the exact reason the button was not detected is not confirmed.

The supplied Home Village screenshot also exposed a separate screen-classification bug: generic Upgrade cards on the selected Hero Hall were counted as Wall upgrade options. This made the screen detector report WallSelection incorrectly.

## Fix

- Wall selection and recovery now require the visible Wall title with the upgrade card.
- Attack startup checks for the normal Find a Match button for up to four more seconds. It sends no tap until the button is confirmed and still stops safely if it never appears.

## Offline checks

- Source commit 77102464f6057450db4d8762d2246f46e6d4556f and tag v3.3 are pushed to GitHub.
- Development package 3.3 passed the release build, 39 no-input instance guards, engine self-check, and release smoke check. ZIP SHA-256: 860EC1F52ABC7673FC38DDD46D4443ADBBFA1C4CCA390FE7DE7A24741E193C32.
- Protected customer package 3.3 passed the release build, saved-data compatibility checks, and release smoke check. ZIP SHA-256: 409643B47271F1CEF2B645A20D30F27BEEDB4CA05A3B0380E711A3BAB8774D2C.
- No live game cycle was run. The screenshot and offline checks do not prove the live Find a Match button timing.

## Download status

The public release entry is [v3.3](https://github.com/c4Luffy/Raidex-Downloads/releases/tag/v3.3). It currently has only GitHub's generated source archives; the customer ZIP and .sha256 file are not attached. The Windows package is ready locally, but the public customer download is not complete.
