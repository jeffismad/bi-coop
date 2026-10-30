# BI Co-op

Two players on one island, in VR, over Steam. An unofficial fan mod for **Bootstrap Island** (Maru VR), made with
UE4SS. Not made or endorsed by Maru VR.

**Beta.** Built and tested by bots on one PC and on a virtual SteamVR headset; two real players over Steam is what
this build is for. Expect rough edges and please [report what you see](https://github.com/jeffismad/bi-coop/issues).

## Download

The newest build is on the [Releases](https://github.com/jeffismad/bi-coop/releases/latest) page:
`bicoop_release_<date>_p<protocol>.zip`. Both players need the same build (the protocol number in the name must
match); monface updates both.

## Install

1. Unzip anywhere. Close the game.
2. Double-click `monfaceinstaller.exe` and press **Install**. It finds Bootstrap Island through Steam, adds files
   next to the game's exe and changes none of the game's own. If Windows says "Windows protected your PC": More info
   > Run anyway (the programs are not signed).
3. Start the game from Steam as usual.

`monface` (put on your desktop by the installer) shows what changed, updates and uninstalls;
`monfaceuninstaller.exe` only uninstalls. `README_BICoop.txt` in the zip has the details.

## Needs

- Both players own Bootstrap Island on Steam and are Steam friends.
- SteamVR (tested with the Index and Oculus Touch layouts). The Oculus runtime without SteamVR is untested.

## Play

- At the start menu, left of the game's own buttons: **Host co-op**, **Join a friend**, **Invite a friend** (a list
  of your online Steam friends), **Leave lobby**. Every co-op button works like the game's: point the laser, pull
  the trigger. Or right-click the host in your Steam friends list and choose **Join Game**.
- The host starts the game; a friend's game goes to the host's island by itself. A friend already in a run of their
  own can switch over from the in-game menu ("Go to the host's island").
- On the island, open the game's menu: the co-op panel beside it shows who is in the session and the host's choices
  (friendly fire, chest loot shared or each their own, egg credit, bandolier and bridge, day count).
- Each player runs their own island; the host's items, animals, weather and time of day are shared. Pick up, throw,
  pass and steal things from each other. Hogs, wolves, apes and the boss go after both players. Cutscenes play for
  whoever is near; fire, eating, building and chests are shared.

## Your saves

The host plays on their own slot, as always. A friend who joins plays on a co-op save of the host's world
(`SaveGames\bsicoop_<8 letters>.sav`) and never on their own slots; their slots are backed up
(`Saved\BSICoop_backups`) and put back if the game changes one.

## If something goes wrong

Each game writes `ue4ss\Mods\BSICoop\telemetry.jsonl` (what happened, in order). Open an
[issue](https://github.com/jeffismad/bi-coop/issues) with both players' files and the time it happened.

## Licence

Free to play, all rights reserved: please don't sell it, change it or re-upload it; share this page's link instead
(`LICENSE.txt` in the zip). The source is not public. UE4SS is MIT (its LICENSE is in the zip).
