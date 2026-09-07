# Raidex Downloads

Official customer downloads for Raidex CoC Automation.

## Latest version

Raidex CoC Automation 2.4.14 for Windows x64:

[Download the latest customer ZIP](https://github.com/c4Luffy/Raidex-Downloads/releases/latest/download/Raidex.CoC.Automation-win-x64.zip)

Extract the whole ZIP before opening the app. Keep the `Engine` folder beside `Raidex CoC Automation.exe`.

Version 2.4.14 fixes automatic building upgrades. Raidex now selects only the first row below `Suggested upgrades`, never an active upgrade above it. The final screen safely confirms the real resource before spending. Wall upgrades still search for Walls anywhere in the Builder list.

It also keeps the Engine startup/repair and hero/Clan Castle fixes. Confirmed hero slots do not need a matching pet or portrait. Clan Castle/Siege slots get one placement attempt, a log message, and then the attack continues even if empty.

After scanning the deployment bar, Raidex confirms the real left boundary instead of requiring an exact match with an older frame. Small card-animation changes no longer cause false settle or first-card restore errors.

An unclear card whose best category is Spell or Siege is reported and skipped instead of stopping the whole attack. Unknown Troops and other unsafe categories still stop safely.

If another clan member fills a request while Raidex is donating, Raidex now waits for the screen transition and continues when Home Village is safely restored. An unconfirmed screen still stops safely.

All Home Village hero abilities are clicked automatically after a fixed 4-second delay. The Hero timer controls are removed. Old saved timer values are ignored and cannot stop the attack.

Profiles without saved loot limits now start with Gold 500,000, Elixir 500,000 and Dark Elixir 3,000, all enabled. Existing saved values and disabled choices stay unchanged. Live battles with every pet or skin have not been verified.

Updating does not create a new license or restart its timer. The saved activation stays in the same Windows account. If Windows reports that the license belongs to another computer or account, open a private support ticket. Never post a license key in public.

See the [latest release notes](https://github.com/c4Luffy/Raidex-Downloads/releases/latest) for changes and the SHA-256 checksum.
