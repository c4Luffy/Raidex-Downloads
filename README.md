# Raidex Downloads

## Latest version — 4.7.3

[Download for Windows x64](https://github.com/c4Luffy/Raidex-Downloads/releases/latest/download/Raidex.CoC.Automation-win-x64.zip) · [SHA-256 checksum](https://github.com/c4Luffy/Raidex-Downloads/releases/latest/download/Raidex.CoC.Automation-win-x64.zip.sha256) · [Release notes](https://github.com/c4Luffy/Raidex-Downloads/releases/tag/v4.7.3)

### What changed

- Fixes Home upgrade recognition on discounted confirmations, including Hammer Jam prices and fragmented Wall titles. Uses the verified current price; gray or Town Hall-blocked confirmations remain unavailable.
- Recognizes Spell Tower mode names and the current resource Confirm button while preserving exact name, price, and currency checks.
- Fixes the alternate Lab Assistant prompt and the small Assign Apprentice card, including its direct confirmation. Assignments still require the correct helper and target.
- Handles verified post-battle overlays, including the captured Gold Pass popup, before a long Builder Base recovery wait.
- Avoids repeating a confirmed unaffordable hero search in the same maintenance pass when eligibility has not changed.
- Reuses the freshly verified village state after Builder Base donations instead of checking it twice.

Unknown screens, stale results, Stop, dry-run protection, and stable village confirmation retain their safety checks. Popup tests replay the real captured failure screen; savings vary by the screens and actions in each run.

### Included from 4.7.2

- Fixes Lab Assistant failing to find the Laboratory when it is absent from building-upgrade suggestions.
- Opens the human helper directly from Army Upgrades, checks the active research and matching confirmation, and verifies Job in progress.
- Recognizes an already-working assistant without assigning again. Gem upgrades and Goblin offers are excluded.

Live testing confirmed assignment to Barbarian research, return Home, and correct handling of the already-working assistant. The gem balance stayed unchanged.

### Included from 4.7.1

- Recovers from the recognized English rating dialog using its verified Later button.
- Avoids unnecessary Hero and Building checks when fresh information confirms they cannot proceed; reuses fresh recovery scans and confirmed busy Pet timers.
- Shows **Maintenance complete — attacks disabled** instead of implying that storages are full.
- Uses bundled vector icons for Home, Settings, and Failures, avoiding missing-font boxes.

The rating popup recovery was checked with a constructed fixture and real negative game screenshots; it has not recurred during live testing. The Lab Assistant navigation issue noted in 4.7.1 is fixed in 4.7.2. Camera reset and separate clan-request/donation processes are unchanged.

### Included from 4.7

- Checks for updates at startup and every six hours while Raidex is open.
- Opening Settings no longer triggers extra checks. Manual checks remain available.

### Included from 4.6

- Retries uncertain resource readings using up to two fresh screenshots. Reader agreement, screen confirmation, capacity and spending checks remain active.
- Rechecks the selected Wall resource/control after a refreshed balance read.
- Waits for stable startup village frames after known-popup recovery, within bounded limits and with Stop handling.
- Saves the exact recognition failure image for its matching support report.
- Reads raised troop-count headers correctly, keeping Rapid deployment batches active when consecutive counts agree.

Live preview: 10 troops deployed in 5.29 seconds versus earlier 6.11–6.57 seconds (13–20% less troop deployment time). Full army time remained about 21 seconds. Only one prepared army was measured in different battles; these are not universal timing guarantees. Five live resource reads and stable Home confirmation passed. The original intermittent OCR conflict was not reproduced from the later report screenshot; recovery limits and failure-image preservation were tested separately.

Final protected-build smoke: ten troops deployed in 4.98 seconds and total army deployment was 19.74 seconds in that run. The controlled attack completed and returned Home.

### Included from 4.5

- Faster Home Village Wall passes with verified price, Builder, resource and purchase checks.
- Hero ability timers checked during deployment, including between spell batches.
- Rapid batches require consistent consecutive screen counts.
- Builder Base startup recognition for another laboratory HUD appearance.
- Clearer status icons on Home and Instances, and keyboard focus/date navigation for profile charts.

### Included from 4.3

- Donation taps wait for visible progress and skip unresponsive cards, in normal donation and The Night's Watch.
- Profiles > Upgrades fits compact windows without scrolling, with Laboratory and Pets beside the builder cards.
- Upgrade-wake details are under How it works, with status still visible.

Live Night's Watch donation testing remains pending.

### Included from 4.2

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
