# PS2 Cheats for PCSX2

Cheat files (`.pnach`) for the PCSX2 PlayStation 2 emulator. There's one folder per game, and each file is named `<SERIAL>_<CRC>.pnach` so PCSX2 picks it up automatically. Every cheat has a short description, and its status is shown at the start of the description.

> **Status:** cheats are verified by running the game in PCSX2 and checking the game's memory while it runs, to confirm each patch is applied and active. Cheats marked **[TESTED]** passed that check (Nov 4 2026; see the tables below). Cheats still marked **[UNTESTED]** were only checked against the game's executable. Back up your memory card before you try untested cheats, and enable them one at a time.

## Installing in PCSX2

1. Find the right file for your disc. The serial and CRC must match; PCSX2 shows both in the game list and in the log when the game boots.
2. Copy the `.pnach` file into the PCSX2 `cheats` folder:
   - Linux / Steam Deck: `~/.config/PCSX2/cheats/`
   - Windows: `Documents\PCSX2\cheats\`, or `cheats\` next to the PCSX2 program in portable mode
3. In PCSX2, right-click the game and open **Properties**, then go to **Cheats**.
4. Tick **Enable Cheats**, then tick each cheat you want. Leave the others off.
5. Start the game, or restart it if it's already running.
6. **Tip:** Save states keep patched game code. If you turn a cheat off, load a memory-card save or restart the game; loading an old save state can bring the old cheat back.

## Games

### Grand Theft Auto: Vice City Stories (PAL)

| Serial | CRC | Region |
|---|---|---|
| SLES-54622 | B3AD1EA4 | Europe/Australia (En, Fr, De, Es, It) |

| Cheat | Status | Notes |
|---|---|---|
| Infinite Health and Armour | Tested (verified in memory on PCSX2, Nov 4 2026) | luc-ita |
| Infinite Ammo (on foot and in vehicles) | Tested (verified in memory on PCSX2, Nov 4 2026) | Azagthoth NTSC, PAL port |
| Max Money | Tested (verified in memory on PCSX2, Nov 4 2026) | Saved to the memory card |
| Never Wanted | Tested (verified in memory on PCSX2, Nov 4 2026) | luc-ita |
| Infinite Sprint (and swim stamina) | Tested (verified in memory on PCSX2, Nov 4 2026) | luc-ita |
| Infinite Oxygen Underwater | Tested (verified in memory on PCSX2, Nov 4 2026) | luc-ita |
| Never Fall Off Bike | Tested (verified in memory on PCSX2, Nov 4 2026) | luc-ita |
| Player Car Indestructible (EXPERIMENTAL) | Untested | **May crash**; makes the car very heavy |
| Always Clear Weather (EXPERIMENTAL) | Untested | **May crash** |
| Auto Weapon Sets (all three) | Tested (verified in memory on PCSX2, Nov 4 2026) | Custom; gives weapon sets 1-3 automatically |
| Weapon Sets Give 9999 Ammo | Tested (verified in memory on PCSX2, Nov 4 2026) | Weapon sets give 9999 rounds per gun |
| Boomshine Blowout - Heat Never Rises (MISSION-SPECIFIC) | Tested (mission passed on PCSX2, Nov 4 2026) | **Enable only during Boomshine Blowout**, then turn it off |
| Auto Repair Current Car [TESTED] | Tested | Custom; repairs only the vehicle you are in. Do not combine with Player Car Indestructible |

### The Godfather (PAL)

| Serial | CRC | Region |
|---|---|---|
| SLES-53967 | 9C5C1478 | Europe |

| Cheat | Status | Notes |
|---|---|---|
| Infinite Health | Untested | Codejunkies; don't use with the Safe version |
| Infinite Health (Safe) | Tested (verified in memory on PCSX2, Nov 4 2026) | Custom replacement |
| Infinite Ammo | Tested (verified in memory on PCSX2, Nov 4 2026) | Codejunkies |
| No Reloads | Tested (verified in memory on PCSX2, Nov 4 2026) | Codejunkies |
| Extort Business For 99 Million | Tested (verified in memory on PCSX2, Nov 4 2026) | Codejunkies |
| Mob Vendetta Never Increases | Tested (verified in memory on PCSX2, Nov 4 2026) | Codejunkies |
| Police Bribes Never Wear Off | Tested (verified in memory on PCSX2, Nov 4 2026) | Codejunkies |
| Max Skill Points (Press L1+L2) | Untested | Codejunkies |
| All Films Unlocked | Untested | Codejunkies |
| Max Skill Points (Always On) | Tested (verified in memory on PCSX2, Nov 4 2026) | Custom; don't use with the L1+L2 version |
| Max All Skill Levels | Tested (verified in memory on PCSX2, Nov 4 2026) | Port of Code Master's CodeBreaker codes |
| Police Heat Never Increases | Untested | Custom |
| Police Heat Always Zero | Untested | Old version that may freeze; use the Safe one |
| Police Heat Always Zero (Safe) | Untested | Custom; don't use with the old version |

### The Godfather (NTSC-U)

| Serial | CRC | Region |
|---|---|---|
| SLUS-21385 | D850707E | USA |

| Cheat | Status | Notes |
|---|---|---|
| Infinite Health (Safe) | Tested (verified in memory on PCSX2, Nov 4 2026) | Port of the PAL custom code |
| Infinite Ammo | Tested (verified in memory on PCSX2, Nov 4 2026) | Same as the Codejunkies USA code |
| No Reloads | Tested (verified in memory on PCSX2, Nov 4 2026) | Same as the Codejunkies USA code |
| Extort Business For 99 Million | Tested (verified in memory on PCSX2, Nov 4 2026) | PAL code ported |
| Mob Vendetta Never Increases | Tested (verified in memory on PCSX2, Nov 4 2026) | PAL code ported |
| Police Bribes Never Wear Off | Tested (verified in memory on PCSX2, Nov 4 2026) | PAL code ported |
| Max Skill Points (Always On) | Tested (verified in memory on PCSX2, Nov 4 2026) | Custom |
| Max All Skill Levels | Tested (verified in memory on PCSX2, Nov 4 2026) | Port of Code Master's CodeBreaker codes |

### Grand Theft Auto: San Andreas (PAL)

| Serial | CRC | Region |
|---|---|---|
| SLES-52541 | B440A8FE | Europe/Australia v2.01 (En, Fr, De, Es, It) |

| Cheat | Status | Notes |
|---|---|---|
| Infinite Health and Armour | Tested (verified in memory on PCSX2, Nov 4 2026) | Custom; HUD hook adapted from a Codejunkies code |
| Max Money | Tested (verified in memory on PCSX2, Nov 4 2026) | Custom; saved to the memory card |
| Infinite Ammo | Tested (verified in memory on PCSX2, Nov 4 2026) | Custom; game's own FULLCLIP flag |
| Never Wanted | Tested (verified in memory on PCSX2, Nov 4 2026) | Custom; game's own AEZAKMI flag |
| Never Hungry | Tested (verified in memory on PCSX2, Nov 4 2026) | Custom; game's own cheat flag |
| Max Respect | Tested (verified in memory on PCSX2, Nov 4 2026) | Custom; game's own cheat flag |
| Max Stamina - Infinite Sprint | Tested (verified in memory on PCSX2, Nov 4 2026) | Custom |
| Max Vehicle Skills | Tested (verified in memory on PCSX2, Nov 4 2026) | Custom |
| Max Weapon Skills - Hitman | Tested (verified in memory on PCSX2, Nov 4 2026) | Custom |
| Auto Weapons - Full Set | Tested (verified in memory on PCSX2, Nov 4 2026) | Custom code cave + hook |

### Scarface: The World Is Yours (PAL)

| Serial | CRC | Region |
|---|---|---|
| SLES-54182 | 301A1B6E | Europe (En, Fr, Es, It) |

| Cheat | Status | Notes |
|---|---|---|
| Infinite Health | Tested (verified in memory on PCSX2, Nov 4 2026) | Codejunkies |
| Infinite Ammo | Tested (verified in memory on PCSX2, Nov 4 2026) | Codejunkies |
| No Car Damage | Untested | Codejunkies |
| Cop Heat Does Not Increase | Tested (verified in memory on PCSX2, Nov 4 2026) | Codejunkies |
| Gang Heat Does Not Increase | Tested (verified in memory on PCSX2, Nov 4 2026) | Codejunkies |
| Max Cash | Tested (verified in memory on PCSX2, Nov 4 2026) | Codejunkies; small code cave + hook, saved to the memory card |

### Bully (NTSC-U)

| Serial | CRC | Region |
|---|---|---|
| SLUS-21269 | 28703748 | USA |

| Cheat | Status | Notes |
|---|---|---|
| Phoenix Key | Untested | **Master code: leave OFF**; not needed in PCSX2 |
| Infinite Health | Tested (verified in memory on PCSX2, Nov 4 2026) | Direct write |
| Infinite Health (Alternate) | Untested | Code cave + hook; don't use with Infinite Health |
| Max Pocket Change | Tested (verified in memory on PCSX2, Nov 4 2026) | Direct write |
| Max Pocket Change (Alternate) | Untested | Code cave + hook; don't use with Max Pocket Change |
| Always Low Trouble Meter | Tested (verified in memory on PCSX2, Nov 4 2026) | |
| Press L1+L2 / R1+R2 For Low / High Trouble Meter | Untested | Button codes |
| Press R1+Select / R2+Select For Top / End Of The Hour | Tested (seen working in game on PCSX2, Nov 4 2026) | Button codes |
| Press L1+Select For (12:00 A.M. to 11:00 P.M.), 24 codes | Untested | Button codes; enable only one |
| Max / No (Stats screen counters), 454 codes | Untested, except Max Tickets Collected (tested) | Max/No pairs for each stat; never enable both of a pair; saved to the memory card |

### Grand Theft Auto: Vice City (PAL)

| Serial | CRC | Region |
|---|---|---|
| SLES-51061 | 26954C46 | Europe v3.00 (not v1.50/v2.03) |

| Cheat | Status | Notes |
|---|---|---|
| Infinite Health and Armour | Tested (verified in memory on PCSX2, Nov 4 2026) | Custom code cave; hook site from RyTheHexer |
| Infinite Ammo (on foot and in vehicles) | Tested (verified in memory on PCSX2, Nov 4 2026) | GameHacking.org PAL list |
| Max Money | Tested (verified in memory on PCSX2, Nov 4 2026) | Saved to the memory card |
| Never Wanted | Tested (verified in memory on PCSX2, Nov 4 2026) | GameHacking.org PAL list |
| Infinite Sprint | Tested (verified in memory on PCSX2, Nov 4 2026) | Game's own flag |
| Auto Weapon Sets (all three) | Tested (verified in memory on PCSX2, Nov 4 2026) | Custom code cave + hook |

### Manhunt (PAL)

| Serial | CRC | Region |
|---|---|---|
| SLES-52023 | FE419424 | Europe v1.03 (En, Fr, De, Es, It) |

| Cheat | Status | Notes |
|---|---|---|
| Infinite Health | Untested | Patch applied; takes effect when a level starts, not from a save state |
| Infinite Stamina (Infinite Run) | Tested (verified in memory on PCSX2, Nov 4 2026) | Codejunkies |
| Infinite Ammo (No Clip Drain) | Untested | Patch applied; effect not confirmed yet |
| Infinite Reload | Untested | Patch applied; effect not confirmed yet |
| Infinite-Max Ammo (99) (EXPERIMENTAL) | Untested | Don't use with the two codes above |
| Hunters Ignore You (Low AI) (EXPERIMENTAL) | Tested (verified in memory on PCSX2, Nov 4 2026) | Codejunkies |
| Open All Levels | Tested (verified in memory on PCSX2, Nov 4 2026) | Saved to the memory card |
| All Levels Max Stars (EXPERIMENTAL) | Tested (verified in memory on PCSX2, Nov 4 2026) | Unlocks bonus features; saved to the memory card |
| First Person Mode (EXPERIMENTAL) | Untested | Camera did not change in testing |

## Credits

- **luc-ita**: Vice City Stories PAL codes, [GameHacking.org](https://gamehacking.org/game/110916)
- **Azagthoth**: Vice City Stories NTSC raw codes (GTAForums topic 442950), ported to PAL
- **Codejunkies**: The Godfather Action Replay MAX codes (PAL and USA), decrypted with omniconvert, mirrored at [GameHacking.org](https://gamehacking.org/game/101576)
- **Code Master**: The Godfather NTSC-U CodeBreaker stat codes
- **Codejunkies**: Scarface: The World Is Yours PAL Action Replay codes (via the European CodeBase)
- **CheatDevicePS2** (codes) and **xs1l3n7x** (pnach conversion): Bully NTSC-U codes
- **CMX, luc-ita, RyTheHexer**: GTA Vice City PAL codes, [GameHacking.org](https://gamehacking.org/game/101599)
- **Codejunkies** (raw PCSX2 form by **GoggleBug**, ps2-home.com): Manhunt PAL codes
- Custom code-cave cheats and ports by IRISHDEVELOPERDEV

## What's not included

There are no game ISOs, BIOS files, saves or other copyrighted game data here. You need your own copy of each game. These files only patch the game's memory while it runs.

## License

The cheat codes and docs made for this pack are released under **CC0 1.0** (public domain); see `LICENSE`. Codes from the third parties listed above still belong to their original authors and are credited here.
