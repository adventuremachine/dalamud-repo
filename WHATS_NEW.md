# What's New in Adventure Machine (Dalamud Plugin)

---

## March 15, 2026 — v1.0.1.6

### Host Whispers
- Send **private directives** to the DM that other players can't see — queue up instructions like "spawn a battle next post" without breaking immersion.
- Add, edit, or delete whispers from the sidebar before they're consumed.

### Cancel DM Generation
- A new **Cancel** button appears while the DM is writing, so you can stop a response that's going off the rails without waiting for it to finish.

### Combat in Chat
- Combat rounds now show **turn-by-turn narration** directly in chat — you can follow the action without switching views.
- **Dice rolls** display inline so you can see what everyone rolled.
- Combat action display now shows the **target name** instead of a blank — "Attacking → Grimjaw" instead of just "Attacking."
- If you reconnect mid-combat, the plugin correctly remembers **who has already acted** this round.

### Readiness Toggle
- Players can mark themselves as **ready** with a toggle. Badges show who's ready at a glance — helpful for coordinating before the host generates the next DM turn.

### Kicked from Session
- If a host kicks you, you now get a **clear overlay** explaining what happened instead of the session silently breaking.

### Removed
- **Typing indicators** removed — they added clutter without much value since the DM streaming indicator already shows when something is happening.

---

## February 22, 2026 — v1.0.1.5

### Redesigned Session Browser
- Sessions are now in a **single filterable, sortable list** instead of split tabs — search by name, world, or host.
- **NSFW filter**, **visibility filter**, and clickable column headers for sorting.
- Session rows show **host name**, **badges** (Non-Canon, NSFW, Private, Friends-Only), and **relative timestamps** ("5m ago").
- **Join by Code** moved to the top of the Join tab so it's easier to find.

### Bug Fixes
- Fixed **duplicate system messages** appearing when enemies flee or surrender in combat.
- Fixed **NPC Fortuna** not updating live after combat — previously required a rejoin to see the change.
- Fixed **host actions failing** when NPCs were in the session ("only the host can..." errors).
- Widened the **Send button** to fill the remaining space in the chat input row.

---

## February 16, 2026 — v1.0.1.4

### OOC Chat Fix
- Fixed **OOC input row sizing** and Send button alignment so the out-of-character chat input looks correct.

---

## February 16, 2026 — v1.0.1.3

### OOC Chat
- Added a **dedicated OOC input row** — you can now send out-of-character messages without leaving the session window.

---

## February 16, 2026 — v1.0.1.2

### Simplified Setup
- **Removed the server URL setting** — the plugin now connects directly to the Adventure Machine server. One less thing to configure.
- Added **`/rp config`** command to open the settings window directly from chat.

---

## February 16, 2026 — v1.0.1.0

### Character Selection Fix
- **Resuming a session** now correctly uses your existing character instead of re-creating one from your current game data — no more losing your character sheet when you log back in.
- **Joining a new session** shows a character picker popup, defaulting to your current in-game character. Pick from your saved characters or create a new one on the fly.

---

## February 15, 2026 — v1.0.0.0

### Initial Release
- **Create, browse, and join** roleplay sessions — public, friends-only, private, or by invite code.
- **Auto-create characters** from your in-game FFXIV data — name, race, class, and appearance are pulled automatically.
- **Real-time multiplayer chat** with in-character and OOC messages, streaming DM responses, and live updates.
- **AI Dungeon Master** controls for hosts — prompt the DM, retry or regenerate responses, toggle NSFW.
- **Combat system** — start encounters, attack, heal, use special abilities, earn Fortuna, and roll against DCs.
- **Friends system** — search users, send and manage friend requests.
- **Host tools** — pause/resume sessions, add NPCs, browse enemy templates, edit enemy stats mid-fight.
- **World and character selection** from your saved library or auto-created from your current FFXIV zone and character.
- **Configurable settings** — display name and OpenRouter API key for hosting sessions.
