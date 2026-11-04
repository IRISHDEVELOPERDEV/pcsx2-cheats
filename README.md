# PS2 Cheats for PCSX2

Cheat files (`.pnach`) for the PCSX2 PlayStation 2 emulator. There's one folder per game, and each file is named `<SERIAL>_<CRC>.pnach` so PCSX2 picks it up automatically. Every cheat has a short description, and its status is shown at the start of the description.

> **Status:** every cheat here is marked **[UNTESTED]**. The addresses were checked against the game's executable, but none of the cheats are confirmed in game yet. Back up your memory card before you try them, and enable them one at a time.

## Installing in PCSX2

1. Find the right file for your disc. The serial and CRC must match; PCSX2 shows both in the game list and in the log when the game boots.
2. Copy the `.pnach` file into the PCSX2 `cheats` folder:
   - Linux / Steam Deck: `~/.config/PCSX2/cheats/`
   - Windows: `Documents\PCSX2\cheats\`, or `cheats\` next to the PCSX2 program in portable mode
3. In PCSX2, right-click the game and open **Properties**, then go to **Cheats**.
4. Tick **Enable Cheats**, then tick each cheat you want. Leave the others off.
5. Start the game, or restart it if it's already running.

## Games

### Grand Theft Auto: Vice City Stories (PAL)

| Serial | CRC | Region |
|---|---|---|
| SLES-54622 | B3AD1EA4 | Europe/Australia (En, Fr, De, Es, It) |

| Cheat | Status | Notes |
|---|---|---|
| Infinite Health and Armour | Untested | luc-ita |
| Infinite Ammo (on foot and in vehicles) | Untested | Azagthoth NTSC, PAL port |
| Max Money | Untested | Saved to the memory card |
| Never Wanted | Untested | luc-ita |
| Infinite Sprint (and swim stamina) | Untested | luc-ita |
| Infinite Oxygen Underwater | Untested | luc-ita |
| Never Fall Off Bike | Untested | luc-ita |
| Player Car Indestructible (EXPERIMENTAL) | Untested | **May crash**; makes the car very heavy |
| Always Clear Weather (EXPERIMENTAL) | Untested | **May crash** |
| Auto Weapon Sets (all three) | Untested | Custom; gives weapon sets 1-3 automatically |
| Weapon Sets Give 9999 Ammo | Untested | Weapon sets give 9999 rounds per gun |
| Boomshine Blowout - Heat Never Rises (MISSION-SPECIFIC) | Untested | **Enable only during Boomshine Blowout**, then turn it off |

### The Godfather (PAL)

| Serial | CRC | Region |
|---|---|---|
| SLES-53967 | 9C5C1478 | Europe |

| Cheat | Status | Notes |
|---|---|---|
| Infinite Health | Untested | Codejunkies; don't use with the Safe version |
| Infinite Health (Safe) | Untested | Custom replacement |
| Infinite Ammo | Untested | Codejunkies |
| No Reloads | Untested | Codejunkies |
| Extort Business For 99 Million | Untested | Codejunkies |
| Mob Vendetta Never Increases | Untested | Codejunkies |
| Police Bribes Never Wear Off | Untested | Codejunkies |
| Max Skill Points (Press L1+L2) | Untested | Codejunkies |
| All Films Unlocked | Untested | Codejunkies |
| Max Skill Points (Always On) | Untested | Custom; don't use with the L1+L2 version |
| Max All Skill Levels | Untested | Port of Code Master's CodeBreaker codes |
| Police Heat Never Increases | Untested | Custom |
| Police Heat Always Zero | Untested | Old version that may freeze; use the Safe one |
| Police Heat Always Zero (Safe) | Untested | Custom; don't use with the old version |

### The Godfather (NTSC-U)

| Serial | CRC | Region |
|---|---|---|
| SLUS-21385 | D850707E | USA |

| Cheat | Status | Notes |
|---|---|---|
| Infinite Health (Safe) | Untested | Port of the PAL custom code |
| Infinite Ammo | Untested | Same as the Codejunkies USA code |
| No Reloads | Untested | Same as the Codejunkies USA code |
| Extort Business For 99 Million | Untested | PAL code ported |
| Mob Vendetta Never Increases | Untested | PAL code ported |
| Police Bribes Never Wear Off | Untested | PAL code ported |
| Max Skill Points (Always On) | Untested | Custom |
| Max All Skill Levels | Untested | Port of Code Master's CodeBreaker codes |

## Credits

- **luc-ita**: Vice City Stories PAL codes, [GameHacking.org](https://gamehacking.org/game/110916)
- **Azagthoth**: Vice City Stories NTSC raw codes (GTAForums topic 442950), ported to PAL
- **Codejunkies**: The Godfather Action Replay MAX codes (PAL and USA), decrypted with omniconvert, mirrored at [GameHacking.org](https://gamehacking.org/game/101576)
- **Code Master**: The Godfather NTSC-U CodeBreaker stat codes
- Custom code-cave cheats and ports by IRISHDEVELOPERDEV

## What's not included

There are no game ISOs, BIOS files, saves or other copyrighted game data here. You need your own copy of each game. These files only patch the game's memory while it runs.

## License

The cheat codes and docs made for this pack are released under **CC0 1.0** (public domain); see `LICENSE`. Codes from the third parties listed above still belong to their original authors and are credited here.
