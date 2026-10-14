# PokéSurvivor saves, sync and account recovery

[Back to the game overview](../README.md) · [Play PokéSurvivor](https://survivorpoke.com/)

Starting the game restores the account in your browser or creates an anonymous account automatically. You can keep permanent progress and enter eligible leaderboard runs without manually registering. A browser copy and a cloud save are separate stages: read the save status before leaving or changing devices.

## What is saved

Your permanent save includes owned and shiny Pokémon, coins, tickets, regional gacha pity, per-Pokémon upgrades, achievements and completed-run statistics. Progress is stored in the current browser first, then queued for cloud sync when online services are available.

Choosing the first partner and completing a run are cloud checkpoints. Accepted cloud writes have a minimum spacing of about **65 seconds**; an action that updates the browser copy may still wait for upload. The visible status is more useful than a stopwatch, because being online does not mean every change has already reached the server.

**The active battle is not resumable.** Refreshing ends it. Current move levels, ordinary run-stat cards, the held item and the live battlefield are not restored as a continuation. To finish a solo run, open pause with **Esc/P** or the pause icon, choose **Quit run**, review the result and choose **Back to menu** before reloading.

## Read the status and take the next step

Open **Settings → Account** to inspect account type and save status.

| Status | Meaning | Next step |
| --- | --- | --- |
| Synced to the cloud / Saved in the cloud | The latest accepted upload is available to this account | Leave after finishing normally |
| Saved on this browser; cloud sync pending | A local copy exists; upload is queued | Keep this browser data and stay online |
| Saved on this browser; syncing | An upload is in progress | Wait for the synced status |
| Cloud is offline | Queued changes cannot currently upload | Restore the connection in the same browser session |
| Local account / saved only in this browser | Progress is stored here without cloud recovery | Keep that browser's data |
| Temporary play / no save | Permanent progress is not retained | Use automatic saving or an existing account for lasting progress |

If the game warns that browser storage is blocked, allow site storage in your browser settings and return to the same session. Do not clear the existing data as your first troubleshooting step.

## Protect the current account with Google

The menu provides optional Google account protection:

1. Stay in the anonymous account that holds the progress you want to retain.
2. Choose **Protect account with Google**, in the menu or **Settings → Account**.
3. Choose your Google account in the sign-in window.
4. Confirm that binding succeeds and that your same nickname, collection and progress remain visible.
5. Wait for cloud sync before using another device. On that device, explicitly sign into the existing linked Google account.

Successful binding keeps the same game and ranking identity. It is optional for saving in your current browser and playing here. Live Google sign-in and cross-device recovery on this hosted version still await an end-to-end verification, so confirm the binding result and retain the original browser session while checking recovery.

If that Google account already belongs to another game account, the current save stays intact. Choose another Google account or deliberately switch to the existing game account. **The two saves are not merged.** Clearing browser data does not resolve an account-linking conflict.

## If progress appears missing

1. Confirm the address is **survivorpoke.com**. Accounts, collections and records from the original site at pokesurvivor.com do not transfer automatically.
2. Use the same browser, browser profile and device where you played. A private window or installed shortcut may have different login storage.
3. Check the nickname and account type in Settings. A new anonymous nickname can indicate a different session rather than deletion of your earlier save.
4. If you previously linked Google, explicitly sign into that existing account. Existing name-and-password accounts can use their original credentials.
5. If the original browser shows pending or offline, reconnect there and wait for sync before expecting the latest progress elsewhere.

An **unbound anonymous account cannot be recovered from its public nickname alone**. Clearing site data, closing a private browsing session or switching identities can remove the local login handle even when a cloud record remains. Keep the original session until you have a working recovery method.

## Saving and leaderboard uploads are separate

A visible run result or cloud-synced save does not by itself prove that the ranking upload has finished. Complete an eligible run normally, keep the game online and allow the result to appear before refreshing. Read [leaderboard rules](https://survivorpoke.com/guides/leaderboard/) if a result is absent.

Account deletion is a separate action in the game's account controls. Clearing browser storage removes local access; it does not delete the server account. See [privacy and account deletion](https://survivorpoke.com/privacy/) before choosing either action.

[Full save guide](https://survivorpoke.com/guides/save-and-sync/) · [Mobile contexts](controls-and-mobile.md) · [Troubleshooting](troubleshooting.md)
