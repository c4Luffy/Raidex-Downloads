# Raidex Downloads

Official customer downloads for Raidex CoC Automation.

## Latest version

Raidex CoC Automation 2.4.29 for Windows x64:

Version 2.4.29 restores window dragging across the large empty top strip while keeping page actions and Windows caption buttons clickable. It also removes the clipped cyan profile-selection bar in Instances.

[Download the latest customer ZIP](https://github.com/c4Luffy/Raidex-Downloads/releases/latest/download/Raidex.CoC.Automation-win-x64.zip)

Extract the whole ZIP before opening the app. Keep the `Engine` folder beside `Raidex CoC Automation.exe`.

Version 2.4.28 fixes top-page buttons being covered by the invisible Windows drag area. Instances now has larger command buttons below the caption controls, a compact license summary, and a larger Live Activity panel with clearer recent logs.

Version 2.4.27 fixes MuMu inactivity recovery. If **Reload Game** leaves Clash of Clans in the background, Raidex brings it to the front and waits for the normal loading screen before checking the village. The fix applies to Home Village and Builder Base.

Version 2.4.25 improves the Instances page with live attack count, confirmed Wall count, current village, and recent activity lines. Builder Base normal buildings now start only from Suggested upgrades. Builder Base Wall scanning taps eligible rows directly, follows confirmed list movement, and no longer stops on the old 45-second Wall scan timer.

Version 2.4.24 runs enabled upgrades before stopping at full storage after an attack. It also tries Walls when building selection starts no upgrade and Gold or Elixir has reached the Wall trigger.

Version 2.4.23 fixes donation scanning. Troop, Siege, and spell cards can have any quantity or price. Raidex follows every colored card across the full carousel, ignores the tab appearance, rechecks unclear cards, and only finishes when scanned cards are gray. If the panel closes, it checks for another visible Clan Chat request before returning Home.

Version 2.4.22 keeps the retired desktop build removed, centralizes the app version, and adds a focused GUI polish pass. Status messages are easier to read, invalid automation numbers are highlighted with a recovery hint, disabled controls have clearer contrast, and the current action has better accessibility text.

Version 2.4.21 removed the retired desktop build path, kept personal saved data out of source control, and added stronger release and customer-package startup checks. It was verified with a real MuMu live-input cycle.

It also keeps the 2.4.20 GUI clarity fixes. Home explains when Raidex will start the assigned MuMu device, Profiles no longer mentions removed Hero timer controls, small helper text is larger, and the Instances capacity wording is clearer.

It also keeps the 2.4.19 Settings scaling fix and startup update check. When a newer release is ready, the customer sees the new version and can install it immediately or choose Later.

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
