# FFT: War of the Lions multiplayer fork — playtest build

This is PPSSPP 1.20.4 with changes aimed at online Rendezvous/Melee play.

## Setup (both players)
1. Unzip anywhere and run `PPSSPPWindows64.exe`. If your saves don't show up in-game, copy your
   `ULUS10297...` folders from your regular PPSSPP's `memstick/PSP/SAVEDATA` into this build's.
2. Load the same US version of the game (ULUS-10297) as your partner.
3. Settings → Networking:
   - Enable networking/WLAN: **on**
   - Ad hoc server: pick the same relay server as your partner, e.g. **ArenaAnywhere US**
   - **Room code** (new): type the same code as your partner, e.g. `ramza42`. Only players with
     the same code can see each other, so you won't land in a stranger's game.
   - Nickname: anything unique
4. In a town tavern: Rendezvous (co-op) or Melee (versus) → Start a Mission.
   One player picks **Host**, the other **Join** within about 30 seconds.

## Good to know
- Ending a turn with Wait takes **two X presses**: one to pick the facing, one to confirm it.
  Until then your partner sees "Communicating…".
- Known issue being worked on: if one player's emulator closes or crashes mid-battle, the
  other player's game freezes instead of showing "disconnected". Restart to recover.

## Reporting problems
Note roughly when it happened (menu / mission select / which turn), what each screen showed,
and send screenshots from both players if you can.
