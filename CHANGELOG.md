# Adventure Machine Changelog

## v1.0.1.5
- Unified session browser: single filterable/sortable list replacing split My Sessions / Public Sessions
- Search, NSFW filter, visibility filter, and clickable sort headers (name, world, host, status, players, last played)
- Session rows show host name, non-canon/NSFW/visibility badges, and relative timestamps
- Join by Code moved to top of the Join tab
- Fix duplicate system messages when enemies flee/surrender in combat
- Fix NPC Fortuna not updating live after combat round grants
- Fix host actions failing when NPCs share the same UserId ("only the host can..." error)
- Widen Send button to fill remaining space in chat input row

## v1.0.1.4
- Fix OOC input row sizing and Send button alignment

## v1.0.1.3
- Add dedicated OOC input row to session window

## v1.0.1.2
- Remove server URL from settings UI (hardcoded to Adventure Machine server)
- Add /rp config command to open settings window directly

## v1.0.1.1
- Add /rp config command to open settings window directly

## v1.0.1.0
- Fix character selection when joining/resuming sessions: active sessions now resume with your existing character instead of re-creating from game data
- Add character picker popup when joining new sessions (public list, join-by-code), defaulting to your in-game character

## v1.0.0.0
- Create, browse, and join roleplay sessions (public, friends-only, private, or by invite code)
- Auto-create characters from your in-game FFXIV data (name, race, class, appearance)
- Real-time multiplayer chat with in-character and OOC messages, typing indicators, and streaming DM responses
- AI Dungeon Master controls for hosts: prompt the DM, retry/regenerate responses, toggle NSFW
- Combat system with manual encounters, attacks, heals, special abilities, Fortuna points, and DC rolls
- Friends system: search users, send/accept/decline requests, manage friends list
- Session host tools: pause/resume sessions, add NPCs, browse enemy templates from mob library, edit enemy stats
- World and character selection from saved lists or auto-created from current FFXIV zone/character
- Configurable server URL, display name, and OpenRouter API key for hosting
