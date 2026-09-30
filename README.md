# Raidex Downloads

## Latest version — 3.10

[Download Raidex 3.10 for Windows x64](https://github.com/c4Luffy/Raidex-Downloads/releases/latest/download/Raidex.CoC.Automation-win-x64.zip) · [SHA-256 checksum](https://github.com/c4Luffy/Raidex-Downloads/releases/latest/download/Raidex.CoC.Automation-win-x64.zip.sha256) · [Changelog](https://github.com/c4Luffy/Raidex-Downloads/releases/tag/v3.10)

Raidex 3.10 adds per-profile **Run targets** under **Automation > Humanization**: stop after a chosen number of confirmed attacks, at a local time, or whichever comes first. Raidex finishes the current action before stopping. Target progress continues through scheduled work and rest, and reaching a target pauses automatic restarts until you press Start again.

The redesigned **Instances** page shows every profile's status, village, action, run target, and activity. **Failures & recovery** now has Overview, Screenshot, and Technical details tabs, with report actions kept visible while the report list and technical log scroll independently. The extra battle-options helper sentence has been removed from Automation.

Raidex supports up to eight **purchased** concurrent instance slots. Weekly, Monthly, and 3 Months include one slot, and Lifetime includes two. Extra slots are bought separately. Each running account needs its own saved profile and connected emulator device. The Instances overview scrolls through all profiles, and Start all ready respects the license's available slots.

## Install or update

1. Download and extract the full ZIP.
2. Keep the `Engine` and `Assets` folders beside `Raidex CoC Automation.exe`.
3. Open `Raidex CoC Automation.exe` and sign in through Discord or use your license key. Automation requires a valid Raidex license.
4. Existing users can check for updates in **Settings**. Updating preserves saved profiles and activation for the same Windows account.

## Verification

The release build, all 51 instance guard checks, all 37 run-target checks, protected engine self-check, packaged app startup, saved-data compatibility and preservation, runtime assets, and updater success, missing-checksum compatibility, rollback, and unsafe-folder checks passed.

One approved Home Village attack confirmed that the attack target stops at 1/1 after returning to the village. The profile settings were restored afterward. Time-based targets and work/rest behavior have automated coverage; no simultaneous multi-profile live test was performed. See the report for the live-check and customer-package scope.

The actual public latest-download ZIP and checksum were downloaded and compared with the verified package. Both hashes match.

- ZIP size: 265,648,269 bytes.
- [Verification report](RELEASE-REPORT-3.10.md)

SHA-256:

```text
1EBEB2053AB89CEA95409353D12525F279235E20488F8EDA9C4AD59B64190901
```

## Links

- [Latest release](https://github.com/c4Luffy/Raidex-Downloads/releases/latest)
- [Setup guide](https://raidexbot.com/setup/)
- [Raidex community](https://discord.gg/hNvTTWFv4b)
