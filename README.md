# Raidex Downloads

## Latest version — 3.84

[Download Raidex 3.84 for Windows x64](https://github.com/c4Luffy/Raidex-Downloads/releases/latest/download/Raidex.CoC.Automation-win-x64.zip) · [SHA-256 checksum](https://github.com/c4Luffy/Raidex-Downloads/releases/latest/download/Raidex.CoC.Automation-win-x64.zip.sha256) · [What's new](https://github.com/c4Luffy/Raidex-Downloads/releases/tag/v3.84)

Raidex 3.84 deploys multi-use event troops before Heroes as troops, including event artwork that looks like a Siege card. Unfamiliar troop and spell cards in a confirmed battle bar can be used even when their initial count cannot be read. Saved drop lines and deployment order stay the same.

## Upgrade timers and rotation help

Open **Profiles → Upgrades** to see locally saved timers from the bot's automatic scan. Each section shows its own last read. Availability between scans follows the saved timers; a later scan corrects changes made in Clash.

Open **Automation → Home Village** or **Builder Base** and choose **How it works** beside Account rotation. The guide includes screenshots, player-tag setup, per-profile storage limits and Account A/B/C examples. Assign the same emulator to all participating profiles and use each account's actual caps.

## Choose building upgrade order

Open **Automation → Home Village** or **Automation → Builder Base** and use **Set rules** beside Building upgrades. Choose an ordinary building from the list. For a Crafted Defense, type the exact English name shown in Clash. In Builder Base, an empty list allows any affordable eligible building; a named list restricts upgrades to those names in order. Home Village still tries other suggested buildings when its chosen names are unavailable. Turn on **Skip Town Hall** or **Skip Crafted Defenses** in Home Village, or **Skip Builder Hall** in Builder Base, to exclude those upgrades.

In Builder Base, **Hero upgrades → Set order** lets you choose Battle Machine and Battle Copter. An empty list allows either affordable hero; a named list limits upgrades to those heroes in order. Raidex checks the selected name again before spending resources.

## Skip Town Hall upgrades

Open **Automation → Home Village** for the profile you want to change, then turn on **Skip Town Hall**. Raidex will consider other suggested buildings while leaving Town Hall out. If it cannot confirm a building's name, it skips that upgrade.

## Set up hero priority

1. Open **Automation → Home Village** for the profile you want to change.
2. Turn on **Hero upgrades** and choose **Set order**.
3. Add the heroes you want, with your most important hero first. You can choose several heroes and give each profile a different order.

With an empty hero list, Raidex may upgrade any affordable eligible hero. When you add names, it tries only those heroes in your saved order. Hero upgrades do not wait for 90% storage. When Walls is enabled, Raidex reserves one regular builder for Walls before starting a long building or hero upgrade. Eligible building work may continue when a selected hero cannot be upgraded.

![Find Hero upgrades and Set order in Raidex 3.16](https://github.com/c4Luffy/Raidex-Downloads/releases/download/v3.16/3.16-hero-settings.png)

![Choose heroes in priority order in Raidex 3.16](https://github.com/c4Luffy/Raidex-Downloads/releases/download/v3.16/3.16-hero-order.png)

## Builder Base fix

Raidex recognizes the boat on the live Home Village screen. In a Builder Base battle, Area 1 can reach 100% before the army moves to Area 2. Raidex waits for the Area 2 troop-planning screen and returned cards, then uses the battle timer to confirm the first troop was placed before sending the rest. It also presses the green resource button on two-choice upgrade confirmations, including Battle Machine.

## Set up account rotation

1. Save each Clash account in Supercell ID on the same emulator, and make a Raidex profile for each account.
2. Open **Profiles → Manage profile** and save that account's **Clash player tag**. Do this for every profile. Profile names can be anything.
3. For every profile, assign the same emulator. In **Automation → Home Village** or **Builder Base**, set the corresponding storage limits and enable the work you want for that village.
4. Under that village's **Full storage action**, choose **Account rotation** for each profile. On Home, choose the account you want to start with and press **Start Raidex**.

If Raidex cannot find or confirm the next account, it stops safely.

![Save the Clash player tag in Profiles](https://github.com/c4Luffy/Raidex-Downloads/releases/download/v3.14/profile-tag.jpg)

![Set storage limits and Account rotation in Automation](https://github.com/c4Luffy/Raidex-Downloads/releases/download/v3.14/account-rotation.jpg)

## Other features

The **Automation → Events** tab now has the Treasure Hunt chest and Equipment Blast Medal Event switches. More options can be added as Raidex supports new events.

![The Events tab](https://github.com/c4Luffy/Raidex-Downloads/releases/download/v3.14/events.jpg)

![The updated Home screen](https://github.com/c4Luffy/Raidex-Downloads/releases/download/v3.14/home.jpg)

## Install or update

1. Download and extract the full ZIP.
2. Keep the Engine and Assets folders beside Raidex CoC Automation.exe.
3. Open the app and sign in through Discord or use your license key. **Use license key** activates during sign-in. After Discord sign-in, activate in **Settings** only if access is not active yet. Website customers can copy their key from [Dashboard → Licenses](https://raidex-license-production.raidex-license-worker.workers.dev/dashboard/); Discord customers can use the key received privately.
4. Existing users can check for updates in **Settings**. Updating keeps their saved profiles and activation on the same Windows account.

Raidex supports up to eight **purchased** concurrent instance slots. Weekly, Monthly, and 3 Months include one slot, and Lifetime includes two. Extra slots are bought separately. Each running account needs its own saved profile and connected emulator device.

## Verification

The 3.84 source tag points to `a5b30cd866908a8a5386e30ba627398a11e14571`. The Release build, Engine self-check, 107 instance guards and 43 run-target checks passed. The customer package passed saved-data compatibility, packaged Windows startup, release smoke checks and the legacy 3.37 updater check.

A new live MuMu game cycle was skipped at the owner's request. The event troop fix was checked offline with numbered-card and unfamiliar-card cases; it has not been confirmed in a live battle.

The public 3.84 customer ZIP is 311,745,579 bytes with 844 files. The ZIP downloaded through `releases/latest/download` matches its public checksum and the uploaded package:

```text
C473CC79823D026445D590D2A72273EEE05C8BADFD93697C4D571CC33B44FB21
```

## Links

- [Latest release](https://github.com/c4Luffy/Raidex-Downloads/releases/latest)
- [Setup guide](https://raidexbot.com/setup/)
- [Raidex community](https://discord.gg/hNvTTWFv4b)





