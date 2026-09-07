# Raidex Downloads

Official customer downloads for Raidex CoC Automation.

## Latest version

Raidex CoC Automation 2.4.19 for Windows x64:

[Download the latest customer ZIP](https://github.com/c4Luffy/Raidex-Downloads/releases/latest/download/Raidex.CoC.Automation-win-x64.zip)

Extract the whole ZIP before opening the app. Keep the `Engine` folder beside `Raidex CoC Automation.exe`.

Version 2.4.19 checks for updates when Raidex starts. When a newer release is ready, the customer sees the new version and can install it immediately or choose Later. The manual check remains in Settings. The full Settings page now scrolls when Windows display scaling needs more room, so license text and controls are not cut off. The long line below the three license summary cards was also removed so the cards stay visually separate.

It also keeps the 2.4.16 upgrade scheduling improvements. Dark Elixir pressure can use the last free Builder for the first suggested building when Gold and Elixir are below the Wall trigger. Gold or Elixir pressure keeps Wall priority. If a full resource cannot be spent, Raidex farms for five attacks before repeating maintenance.

It also keeps the 2.4.15 donation and profile fixes. One donation pass can check up to 12 requests, and the Home profile picker stays available while bots run so another profile and its live log can be viewed. Settings remain locked during automation.

It also keeps the 2.4.14 automatic building fix. Raidex selects only the first row below `Suggested upgrades`, never an active upgrade above it. The final screen safely confirms the real resource before spending. Wall upgrades still search for Walls anywhere in the Builder list.

It also keeps the Engine startup/repair and hero/Clan Castle fixes. Confirmed hero slots do not need a matching pet or portrait. Clan Castle/Siege slots get one placement attempt, a log message, and then the attack continues even if empty.

After scanning the deployment bar, Raidex confirms the real left boundary instead of requiring an exact match with an older frame. Small card-animation changes no longer cause false settle or first-card restore errors.

An unclear card whose best category is Spell or Siege is reported and skipped instead of stopping the whole attack. Unknown Troops and other unsafe categories still stop safely.

If another clan member fills a request while Raidex is donating, Raidex now waits for the screen transition and continues when Home Village is safely restored. An unconfirmed screen still stops safely.

All Home Village hero abilities are clicked automatically after a fixed 4-second delay. The Hero timer controls are removed. Old saved timer values are ignored and cannot stop the attack.

Profiles without saved loot limits now start with Gold 500,000, Elixir 500,000 and Dark Elixir 3,000, all enabled. Existing saved values and disabled choices stay unchanged. Live battles with every pet or skin have not been verified.

Updating does not create a new license or restart its timer. The saved activation stays in the same Windows account. If Windows reports that the license belongs to another computer or account, open a private support ticket. Never post a license key in public.

See the [latest release notes](https://github.com/c4Luffy/Raidex-Downloads/releases/latest) for changes and the SHA-256 checksum.
