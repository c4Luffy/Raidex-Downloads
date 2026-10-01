# Raidex Downloads

## Latest version — 3.18

[Download Raidex 3.18 for Windows x64](https://github.com/c4Luffy/Raidex-Downloads/releases/latest/download/Raidex.CoC.Automation-win-x64.zip) · [SHA-256 checksum](https://github.com/c4Luffy/Raidex-Downloads/releases/latest/download/Raidex.CoC.Automation-win-x64.zip.sha256) · [What's new](https://github.com/c4Luffy/Raidex-Downloads/releases/tag/v3.18)

Raidex 3.18 waits for the Area 2 troop cards to settle instead of giving up after 20 seconds. If the cards still cannot be read, the report includes a game image. The Home Stop safely button also has a clearer border when unavailable.

## Set up hero priority

1. Open **Automation → Home Village** for the profile you want to change.
2. Turn on **Hero upgrades** and choose **Set order**.
3. Add the heroes you want, with your most important hero first. You can choose several heroes and give each profile a different order.

Raidex tries them when their Elixir or Dark Elixir reaches 90% of your saved storage limit. If none can be upgraded, it keeps the builder free for heroes instead of starting another building or wall upgrade.

![Find Hero upgrades and Set order in Raidex 3.16](https://github.com/c4Luffy/Raidex-Downloads/releases/download/v3.16/3.16-hero-settings.png)

![Choose heroes in priority order in Raidex 3.16](https://github.com/c4Luffy/Raidex-Downloads/releases/download/v3.16/3.16-hero-order.png)

## Builder Base fix

Raidex recognizes the boat on the live Home Village screen. In a Builder Base battle, Area 1 can reach 100% before the army moves to Area 2. Raidex now waits for the Area 2 troop-planning screen and returned cards to become readable before deploying. It also presses the green resource button on two-choice upgrade confirmations, including Battle Machine.

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
3. Open the app and sign in through Discord or use your license key. Automation requires a valid Raidex license.
4. Existing users can check for updates in **Settings**. Updating keeps their saved profiles and activation on the same Windows account.

Raidex supports up to eight **purchased** concurrent instance slots. Weekly, Monthly, and 3 Months include one slot, and Lifetime includes two. Extra slots are bought separately. Each running account needs its own saved profile and connected emulator device.

## Verification

Windows build, offline screenshot checks, saved-profile compatibility, packaged startup, and installer smoke tests passed. A live two-area battle was not run for this release.

The verified ZIP is 265,858,097 bytes. Its SHA-256 is:
```text
34F64E59990235DEA9A6DED14BC9FBC1FA7BE7E22847A804FE0ECC1AA00300EB
```

## Links

- [Latest release](https://github.com/c4Luffy/Raidex-Downloads/releases/latest)
- [Setup guide](https://raidexbot.com/setup/)
- [Raidex community](https://discord.gg/hNvTTWFv4b)
