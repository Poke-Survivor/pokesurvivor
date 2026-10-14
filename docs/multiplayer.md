# PokéSurvivor multiplayer and co-op

[Back to the game overview](../README.md) · [Play PokéSurvivor](https://survivorpoke.com/)

Co-op supports **2–4 players total, including the host**. Add a friend by their public game nickname, invite them to a room and let the host start after the browsers finish connecting. The site's online anonymous accounts can use friends and co-op without manual registration.

## Add a friend and start a room

1. Both players open [survivorpoke.com](https://survivorpoke.com/) and start with online account services available.
2. Open **Friends** and share the exact public nickname shown in the game. Use that nickname, rather than a Google email or a nickname from another site's account.
3. Send a friend request. The other player must accept it.
4. When the friend is online and available, choose **Invite**. The host creates or uses a room; the friend accepts the room invitation.
5. Choose an owned Pokémon in the lobby. Keep the game tabs open and wait for peer connection status.
6. The **host** starts when at least two members are present and no required member is still connecting or failed.

Being listed in a room means the invitation was accepted. It does not prove that the browsers can exchange live game data. The host's start button stays unavailable while a required connection is incomplete.

## Understand lobby connection states

| State | Meaning | What to do |
| --- | --- | --- |
| Connected | The peer data connection is ready | Wait for the host to start |
| Connected via server | A configured relay carries the connection | Wait for the host to start |
| Connecting | The browsers are negotiating a connection | Keep both tabs open and the network available |
| Failed / retrying | The current network pair cannot connect | Try another Wi-Fi or mobile-data network and allow a retry |

Direct browser-to-browser connections depend on both networks allowing peer traffic. **TURN relay access for this hosted version is still being configured**, so some restrictive network pairs cannot connect yet. The game retains four-player support; a successful room on one network does not establish universal cross-network connectivity or verify a full four-player run.

If the start button remains unavailable, have the host inspect **every** member's status, rather than only their own.

## Play as a team

The host coordinates shared enemies, group start, legendary encounters and the team result. Each teammate controls their own Pokémon and active attack. Plan complementary moves, but remember that ordinary inactive slots do not attack; only the selected slot or active Bonded group fires.

Stay near a fallen teammate for about **three seconds** to revive them. Keep the area clear during the revive. Your ordinary pause menu does not freeze the shared battlefield, although shared reward, item and Bond choices can hold the group while decisions are resolved.

A rift can take the party into the same legendary arena. Enter before the **45-second** portal closes and defeat the legendary within **120 seconds**. The host coordinates entry and the encounter result. See [legendary rifts and Bonds](https://survivorpoke.com/guides/legendary-rifts/) for eligibility and reward rules.

Losing the host connection interrupts the hosted battle. Refreshing also ends the live battle and can disconnect the party; it does not restore a running group session afterward.

## If the room will not connect

1. Confirm both players use this site's accounts and the exact current nicknames.
2. Check that both the friend request and room invitation were accepted.
3. Return everyone to the lobby. A player in another active run may not be available.
4. Keep both game tabs visible while connection negotiation finishes.
5. If it fails, try a different Wi-Fi or mobile-data connection. A restrictive firewall, VPN or private network can block peer traffic.
6. Let the host check that all required members are connected before trying to start again.

Deleting or switching accounts cannot repair a blocked network connection. Preserve the account that owns your collection and friends. For a public issue report, include device/browser versions, the number of players, the exact connection state and whether changing networks helped.

## Privacy and group rankings

Friends and room invitations use the public nickname. A direct peer connection can expose your network IP address to teammates, so choose people you trust. Google email is not displayed as the public friend identifier.

For an eligible completed group run of at least **60 seconds**, the host submits the team record. Group and Solo boards are separate, and changing team members creates a different team record. Keep the connection available after finishing; a cloud-synced account save is not confirmation that the ranking upload is complete.

[Full on-site multiplayer guide](https://survivorpoke.com/guides/multiplayer/) · [Leaderboard rules](https://survivorpoke.com/guides/leaderboard/) · [Account protection](save-and-sync.md) · [Troubleshooting](troubleshooting.md)
