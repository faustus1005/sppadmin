# SPP Legion Admin Panel

SPP Legion Admin is an in-game admin control panel addon for the WoW 7.3.5 (Interface 70300) SPP Legion private server repack. It is based on MarsAdmin/TrinityAdmin and includes bundled Ace2/FuBar libraries plus a full set of UI frames, commands, and lookup tools.

## Features

- Tabbed admin panel with sections for character, tickets, server, NPC/GO, PvP, events, vendors, ahbot, and more.
- Quick-action buttons for common GM commands and a prefilled command input box for arguments.
- Teleport browser and `.gps` helper data, including saved favorites.
- Ticket list, player info lookups, and server info refresh on login.
- Lookup tools for items, spells, quests, creatures, objects, and skills.
- Optional minimenu/toolbar and FuBar plugin icon.
- Chat linkifier for clickable item/teleport links.
- Persistent per-account and per-character saved variables.

## Installation

1. Create a folder named `SPPLegionAdmin` inside your WoW `Interface/AddOns` directory.
2. Copy the entire contents of this repository into that folder (all Lua files, `Commands/`, `Frames/`, `Locales/`, `Libraries/`, `Textures/`, and `Sound/`).
3. Launch the game and enable the addon in the AddOns menu.

## Usage

- `/sppadmin` or `/sppgm` to toggle the main panel.
- Slash subcommands:
  - `/sppadmin toggle` — toggle the panel.
  - `/sppadmin transparency` — toggle transparency mode.
  - `/sppadmin tooltips` — toggle tooltips.
  - `/sppadmin minimenu` — toggle the minimenu/toolbar.
- Click a button to send its command immediately; commands that require arguments are prefilled in the input box.

## Notes

- Commands are sent through in-game chat and are expected to be GM commands supported by your server.
- The command lists and UI sections are defined in the `Commands/` and `Frames/` folders. Update those if your server uses different syntax.

## Credits

- MarsAdmin by SecretMars (GPLv3), derived from TrinityAdmin. See the original repository for upstream history and licensing: https://github.com/Secretmars/MarsAdmin.
