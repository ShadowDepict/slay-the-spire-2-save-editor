# Changelog

All notable changes to Slay the Spire 2 Save Editor are documented here. Versions follow semantic versioning.

## [1.0.0] — 2026-11-22

### Added

- Save slot browser: lists the profiles found in the folder you select, with act, floor and character read from the file.
- Card panel: add any of the 566 cards to a deck or to the collection, filtered by class.
- Gold, max HP, current HP and potion slot fields, each written back independently.
- Relic panel: add every relic in the game to the inventory, or remove individual entries.
- Automatic timestamped backup of the original save before the first write.
- Portable settings file stored beside the application; remembers the last folder and slot.
- Parse guard: if a game build changes the save layout, the editor reports that it cannot read the file instead of writing a guess.
- Photographic project landing page with an interactive value preview.

### Notes

- First public build. Everything runs locally and offline.
- No game installation is required to edit a save; the game must be closed while you write.
- The save format may change between early access builds; check this file after a large patch.

## [Unreleased]

### Planned

- Preset export and import, so a favourite configuration can be shared as a small text file.
- Read-only diff view before writing, showing every changed field side by side.
- Optional per-slot notes so several test profiles stay distinguishable.
- Deck order editor for testing opening hands.
