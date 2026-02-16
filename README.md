# Adventure Machine

Multiplayer AI-driven roleplay session client for FFXIV via [Dalamud](https://github.com/goatcorp/Dalamud).

Connect to an Adventure Machine server to manage characters, worlds, and live roleplay sessions with AI dungeon master support. Auto-populates character data from your current FFXIV game state.

## Installation

1. Open Dalamud Settings in-game (`/xlsettings`)
2. Go to the **Experimental** tab
3. Under **Custom Plugin Repositories**, add:
   ```
   https://raw.githubusercontent.com/adventuremachine/dalamud-repo/main/repo.json
   ```
4. Save and close settings
5. Open the plugin installer (`/xlplugins`), search for **Adventure Machine**, and install

## Features

- **Session Management** -- Create, browse, and join roleplay sessions (public, friends-only, private, or by invite code)
- **Character Auto-Creation** -- Characters are built from your in-game FFXIV data (name, race, class, appearance), or pick from saved characters
- **Real-Time Multiplayer** -- In-character and OOC chat, typing indicators, and streaming DM responses
- **AI Dungeon Master** -- Hosts can prompt the DM, retry/regenerate responses, and toggle NSFW
- **Combat System** -- Manual encounters with attacks, heals, special abilities, Fortuna points, and DC rolls
- **Friends System** -- Search users, send/accept/decline requests, manage your friends list
- **Host Tools** -- Pause/resume sessions, add NPCs, browse enemy templates, edit enemy stats
- **World Building** -- Select from saved worlds or auto-create from your current FFXIV zone

## Commands

| Command | Description |
|---------|-------------|
| `/rp` | Open the main Adventure Machine window |
| `/rp config` | Open settings (API key, display name) |

## Setup

After installing the plugin:

1. Log in at [imaginaryrobot.com/adventuremachine](https://imaginaryrobot.com/adventuremachine) and go to your Profile to generate an API token
2. Open settings with `/rp config` and paste your API token
3. Click **Save & Verify** to connect
4. (Optional) Set an **OpenRouter API Key** if you want to host sessions -- this powers the AI dungeon master

## Changelog

See [CHANGELOG.md](CHANGELOG.md) for release history.
