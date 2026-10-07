# Raidex Downloads

## Latest version — 3.57

[Download Raidex 3.57 for Windows x64](https://github.com/c4Luffy/Raidex-Downloads/releases/latest/download/Raidex.CoC.Automation-win-x64.zip) · [SHA-256 checksum](https://github.com/c4Luffy/Raidex-Downloads/releases/latest/download/Raidex.CoC.Automation-win-x64.zip.sha256) · [What's new](https://github.com/c4Luffy/Raidex-Downloads/releases/tag/v3.57)

Raidex 3.57 shows the latest action decision and screen-read troop progress on Home. Instances can pause all running profiles after their current safe actions and resume a selected profile. Saved failure reviews can show the exact enemy loot area and threshold values used for the decision. Enemy OCR decisions are unchanged. The Balloon, Wall, donation and recovery fixes from 3.55 remain included.

## Choose building upgrade order

Open **Automation → Home Village** or **Automation → Builder Base** and use **Set order** beside Building upgrades. Enter only the English building name, without a level or count. Uppercase and lowercase both work. In Builder Base, an empty list allows any affordable eligible building; a named list restricts upgrades to those names in order. Home Village still tries other suggested buildings when its chosen names are unavailable. Turn on **Skip Town Hall** in Home Village or **Skip Builder Hall** in Builder Base to exclude that main building.

In Builder Base, **Hero upgrades → Set order** lets you choose Battle Machine and Battle Copter. An empty list allows either affordable hero; a named list limits upgrades to those heroes in order. Raidex checks the selected name again before spending resources.

## Skip Town Hall upgrades

Open **Automation → Home Village** for the profile you want to change, then turn on **Skip Town Hall**. Raidex will consider other suggested buildings while leaving Town Hall out. If it cannot confirm a building's name, it skips that upgrade.

## Set up hero priority

1. Open **Automation → Home Village** for the profile you want to change.
2. Turn on **Hero upgrades** and choose **Set order**.
3. Add the heroes you want, with your most important hero first. You can choose several heroes and give each profile a different order.

With an empty hero list, Raidex may upgrade any affordable eligible hero. When you add names, it tries only those heroes in your saved order. Hero upgrades do not wait for 90% storage. If none can be upgraded, it keeps the builder free for heroes instead of starting another building or wall upgrade.

![Find Hero upgrades and Set order in Raidex 3.16](https://github.com/c4Luffy/Raidex-Downloads/releases/download/v3.16/3.16-hero-settings.png)

![Choose heroes in priority order in Raidex 3.16](https://github.com/c4Luffy/Raidex-Downloads/releases/download/v3.16/3.16-hero-order.png)

## Builder Base fix

Raidex recognizes the boat on the live Home Village screen. In a Builder Base battle, Area 1 can reach 100% before the army moves to Area 2. Raidex waits for the Area 2 troop-planning screen and returned cards, then uses the battle timer to confirm the first troop was placed before sending the rest. It also presses the green resource button on two-choice upgrade confirmations, including Battle Machine.

## Set up account rotation

1. Save each Clash account in Supercell ID on the same emulator, and make a Raidex profile for each account.
2. Open **Profiles → Manage profile** and save that account's **Clash player tag**. Do this for every profile. Profile names can be anything.
3. For every profile, assign the same emulator. In **Automation → Home Village**, set the Gold, Elixir, and Dark Elixir storage limits, and turn on **Home Village attacks** and **Wall upgrades**.
4. Under **Full storage action**, choose **Account rotation** for each profile. On Home, choose the account you want to start with and press **Start Raidex**.

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

The 3.57 source passed 121 vision checks, 93 review-improvement checks, 101 instance checks, 36 run-target checks and the engine self-test. The protected customer package passed data compatibility, packaged GUI startup, updater/rollback and real saved-data preservation checks. The historical 3.37 updater also accepted this package.

One approved Test Profile / MuMu #0 Home Village attack returned Home and paused before another attack. The Balloon card and other troop cards were gray at x0. Raidex recorded one attack and refreshed resources. The 90% Wall rule correctly skipped upgrades at 26% Gold and 30.8% Elixir. This live test used the first 3.57 source commit `2d312b7d4287876d9785da5452f81a6a059fecb6`; later pause and evidence fixes were checked offline. No second live attack or live Wall spending test was performed.

The freshly downloaded public latest-download ZIP matches the tested 3.57 package and public checksum. It is 317,460,321 bytes with 578 entries, includes the OCR model/dictionary files, and contains no source, debug or private data files. Its SHA-256 is:
```text
1C86D83611F3F2ADE74753A23CD4D4C3A4A1DC6744F75C48DB358486CD235310
```

## Links

- [Latest release](https://github.com/c4Luffy/Raidex-Downloads/releases/latest)
- [Setup guide](https://raidexbot.com/setup/)
- [Raidex community](https://discord.gg/hNvTTWFv4b)
