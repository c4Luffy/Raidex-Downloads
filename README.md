# Raidex Downloads

## Latest version — 4.2

[Download for Windows x64](https://github.com/c4Luffy/Raidex-Downloads/releases/latest/download/Raidex.CoC.Automation-win-x64.zip) · [SHA-256 checksum](https://github.com/c4Luffy/Raidex-Downloads/releases/latest/download/Raidex.CoC.Automation-win-x64.zip.sha256) · [Release notes](https://github.com/c4Luffy/Raidex-Downloads/releases/tag/v4.2)

### What changed

- Fixes updates blocked by the background Remote Control helper.
- Keeps the previous installation intact when files are locked.
- Restores the previous version if the replacement fails its startup check, including when it has started a helper.
- Refuses updates while an automation engine is running and rechecks the downloaded ZIP checksum before installation.
- Preserves recovery files and records their locations if automatic recovery cannot finish.

If an older updater has already failed, download the latest ZIP and extract it into a fresh folder. Keep the old update backup. This installs the corrected updater for future updates; older running updater code cannot repair itself.

No new live game test was performed for 4.2. Update installation and recovery are checked without game input.

### Included from 4.1

- Runs Clan Games checks only in Clan Games mode, not during ordinary Home Village farming.
- Keeps Lord of Destruction eligible in Clan Games mode. Skips Building Boom Boom at every target, alongside Wall Whacker, Hog Rider Raid, Helping Hand, Riding and Gliding, Seeing Quadruple, Ride of the Valkyries, Cannon Cart Cruise, Donate Spells, and Giant Problem.
- Pauses Clan Games mode after two attacks confirm no progress and tells you to check the challenge.
- Reads zero-progress active challenges and single-battle loot objectives from the supplied game screens.
- Checks troop and spell quantities after each placement tap to avoid extra taps when a card reaches zero.
- Drops troops, siege, heroes and spells before activating hero abilities.

No new live game test was performed for 4.1.

### Included from 3.95

- Hardened minimize, restore and tray window transitions, with repeated UI stress checks.
- Added Clan Games mode, points/status and saved settings to website Remote Access. Update the PC app to 3.95 for these controls.
- Improved timer-list return handling and failure screenshots. Timer-scan errors check the screen instead of entering battle-surrender recovery.
- The original native minimize crash did not reproduce in the harness. The customer's timer-return screenshot remains unavailable. No attack was run for final validation.

### Also included

- Arrange windows on Home and Instances, compact emulator placement and the saved-profile startup optimization from 3.93.


- Fixed upgrade wake stopping when the timer reader missed a visible building name.
- Improved building-name recognition while keeping incomplete timer scans blocked.
- Timer scan logs now show Complete or Partial.
- Includes the Builder Base recovery fix from 3.91, Remote Control crash fix from 3.90 and interface improvements from 3.89.

- Private phone controls at raidexbot.com → My account → Remote: start profiles, Stop now, progress, logs and emulator screenshots.
- Full phone Automation editing, including upgrade priorities, schedules and run targets.
- Open Raidex, the assigned emulator and Clash of Clans through the optional background helper.
- A separate Remote Control Settings tab with live status and setup instructions. Controls refresh every two seconds.
- Includes the existing timer-list layout and Home Village upgrade-wake changes from 3.86.

Enable remote access in Raidex → Settings → Remote Control, then use the same Discord account on your phone. The PC must remain awake, online and signed in. Waking a sleeping or hibernating PC is not included.

Close Raidex, extract the full ZIP, and run **Raidex CoC Automation.exe**. Keep the Engine and Assets folders beside it.
