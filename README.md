# Raidex Downloads

Official customer downloads for Raidex CoC Automation.

## Latest version

Raidex CoC Automation 2.4.83 for Windows x64:

Version 2.4.83 finds both Gold and Elixir Wall Upgrade cards when their action-panel positions move. It requires the real green Okay confirmation, never accepts Select Row as an upgrade card, skips an optional Battle Options reward only after safe retries, and improves profile-summary colors.

> **2.4.84 is not published for download yet.** Its source now accepts every Wall list row, including `Wall xN`, while still rejecting Select Row and Upgrade More. After Wall spending ends, it retries closing the selected Wall and can continue from a confirmed Home Village if only WallSelection remains; BuilderList and unknown screens still stop. The live run confirmed 13 Wall upgrades, but the post-spending continuation, Clan Capital, and MuMu/ADB changes still need controlled live validation before this becomes the customer download.

The pending source also refreshes the original dark interface: a simpler sidebar without the stray rounded outline, clearer menu and device controls, better fitting Profiles and Settings pages, a timed-license countdown, and separate colored Builder Base Wall and Building totals. The extra Nova theme was removed. These interface changes passed a local build and a live visual check at the app's minimum window size. This is not a published customer update yet.

The pending 2.4.84 app also shows why Start is blocked and opens the correct repair page, makes Pause and safe Stop progress clear, moves reset actions under More, sends the exact selected saved failure from Failure Review, and tests the selected MuMu and ADB connection from Profiles.

The latest 2.4.84 source also checks Builder Base Walls before using the last free Builder on an affordable Building. For Builder Base attacks, it uses a confirmed legal troop-drop point when the saved line lands on cliffs or water. A live run confirmed 18 Wall upgrades but exposed a false `Remove Wall` or `Add Wall` target when resources ran low; both controls are now excluded. The fix passed local build and the saved-screen check, but still needs a live retest before publishing the customer ZIP.

The pending source now checks that a Builder Base Wall row has stopped moving before selecting it and skips a non-Wall panel without spending resources. It also taps the 1x speed button again in Area 2 when the battle speed resets. A focused live Wall test found an affordable Elixir card that the older detector missed; the new detector confirmed further Wall upgrades and a later Wall-only run finished cleanly after no affordable Walls remained. The Area 2 speed change and the full app still need live validation before publishing a new customer ZIP.

A newer Builder Base Wall-only test found that a previous selected Wall could stay active after a different list row was tapped. The pending source now clears that old selection before checking the next row and keeps the last Builder free when a row cannot be verified. A live Wall-only run confirmed 18 Wall upgrades and checked the remaining `Wall xN` rows without starting a Building. This is still pending source, not a customer download.

The pending Builder Base Wall scan now returns to the top after confirmed upgrades, because a Wall changing level can split or move `Wall xN` rows. A live Wall-only test confirmed three upgrades and a second full pass; a follow-up pass with no affordable Walls finished without buying anything. The customer download remains unchanged.

Builder Base troop taps now follow the saved spread line around a verified legal starting point instead of stacking at that point. One live Area 1 attack showed troops spread across the edge and returned safely to Builder Base. Area 2 still needs a live spread check before customer release.

Version 2.4.82 fixes stopped-attack recovery getting stuck on the confirmed **My Army** screen. Raidex now presses Back only when that screen is positively detected, then requires Home Village confirmation. Unknown screens still receive no blind input.

Version 2.4.81 hardens Home Village Wall recovery. Raidex waits for delayed startup overlays, ignores every grouped **Wall ×N** Builder-list entry, and closes a normal Wall panel through the Builder button instead of sending Escape. This prevents **Select Row**, **Rotate Row**, and accidental game-exit dialogs. It also includes the 2.4.79 fix for **Start all ready**, which starts every eligible saved profile up to the purchased instance limit.

Version 2.4.78 fixes guarded recovery after a cold launch. Raidex now closes the confirmed **Welcome Back Chief** screen before checking for an active battle, instead of mistaking the overlay for a battle confirmation.

Version 2.4.77 improves Home Village Wall upgrades by waiting for the real confirmation screen before deciding a resource tap failed. It also records raid loot during battle when available, while keeping the verified storage-change fallback. The normal Wall path continues to ignore **Select Row** and every whole-row batch control.

Version 2.4.76 fixes Builder Base Clock Tower maintenance switching areas when the Clock Tower is already confirmed on the current screen. Raidex now uses the visible Clock Tower in place and changes areas only as a fallback.

Version 2.4.75 restores the compact Home Village and Builder Base resource number fields, keeps their Gold, Elixir, and Dark Elixir colors, and gives the Home Start button enough room to show `Start Raidex` without clipping.

Version 2.4.74 fixes Builder Base appearing to start when no work is enabled. Raidex now blocks an empty Builder Base run before touching MuMu or Clash of Clans, tells the user to enable at least one action, keeps Night's Watch available, and shows a clear enabled-action count with cleaner Builder Base setting groups.

Version 2.4.73 improves the Raidex interface and everyday controls. Start, stop, profile, instance, automation, report, and failure-review actions now show clearer names, exact blocked reasons, and better help. Storage settings explain how full-storage stops and 90% upgrade triggers work. Failure Review can copy the reason, open its screenshot, or open the logs folder. Profile lifetime totals are easier to read, and number fields are larger.

Version 2.4.72 adds clear, exact recovery steps to Failure Review, removes old Army-slot wording, and clearly separates **This Run** loot from saved lifetime totals. It also fixes cold-start controller hangs, makes child-process exit handling reliable, prevents MuMu from locking the Raidex update folder, and safely returns to Home Village before automation starts.

Version 2.4.65 fixes Wall maintenance closing the Wall panel after an unconfirmed tap. It adds local failure review with a screenshot and exact reason, plus safe export/import for one profile without replacing another profile or copying its old MuMu device link.

Version 2.4.64 reduces the manual support-report cooldown to 5 minutes and restores the Send button when it ends. It also fixes Gold-only Walls being detected as duplicate Gold upgrade options.

Version 2.4.63 fixes low-level Walls that show only a Gold upgrade button. Raidex now confirms the real resource icon and still supports higher-level Walls that show both Gold and Elixir.

Version 2.4.62 adds Clan Capital attacks, reward handling, Capital Gold upgrades, and saved Capital counters. It also adds all three village choices across Raidex, improves safe troop deployment retries, and fixes Wall automation missing an affordable Gold upgrade when Elixir is too low.

Version 2.4.61 gives Raidex a cleaner interface with refined panels, borders, shadows, colors, buttons, and spacing. The familiar checkbox style stays unchanged, and every Home maintenance countdown now fits fully inside its card.

Version 2.4.60 fixes Battle Options completion after the third reward. Support reports are now manual, include the verified Discord customer, and keep the existing anti-spam cooldown. Profiles now show a clearer account summary, maintenance text fits correctly, and attack deployment remains fast and safe.

Version 2.4.35 improves Night's Watch donation flow. It finishes every colored troop and spell card on the visible page before swiping, waits through brief panel animations instead of reopening too early, and counts one donation request instead of every card tap. The Home and Instances pages now show current donations, lifetime donations, and the last donation time. A reset button clears the saved counters.

Version 2.4.34 adds Night's Watch donation and check counters. It fills visible troops and spells before swiping, removes redundant per-tap work, and refreshes the Donate button immediately before tapping so rapid new chat requests cannot leave a stale position.

Version 2.4.33 keeps Night's Watch running through short, safe detection misses. It retries every five seconds for up to one minute, while a continuing problem still stops with a clear error.

Version 2.4.32 fixes active automation stopping when the Home page unloads. Night's Watch and normal sessions now keep running while Raidex stays open. Closing Raidex still stops all sessions safely.

Version 2.4.31 adds **Night's Watch • Auto Donate** on the Home page. One press opens Clan Chat and keeps it open for fast checks on a five-second schedule. It fills visible troop and spell requests first, then scans later pages only when needed.

Night's Watch works from Home Village or Builder Base without switching villages. It runs donation only: no attacks, upgrades, troop requests, collection, or Builder actions.

[Download the latest customer ZIP](https://github.com/c4Luffy/Raidex-Downloads/releases/latest/download/Raidex.CoC.Automation-win-x64.zip)

Extract the whole ZIP before opening the app. Keep the `Engine` folder beside `Raidex CoC Automation.exe`.

Version 2.4.29 restores window dragging across the large empty top strip and removes the clipped cyan profile-selection bar in Instances.

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
