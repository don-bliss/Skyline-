# SkyLine v27 — Community rooms and Games Lounge

Built on the uploaded SkyLine v26 Social Backend Update.

## Changes
- Added Games and Science to the Skyline Community room picker on the Timeline.
- Expanded Community Room configuration with dedicated room names, icons, descriptions and topic-specific headers for all eight rooms.
- Added conversation starters, message composer and per-room message history saved in the current browser's localStorage.
- Added Games Lounge activities: Rock, Paper, Scissors and quick trivia, with share-result actions that post into the local room chat.
- Added responsive room layout for narrow mobile screens.

## Important scope note
Room chat persistence in this version is browser-local only. Messages do not yet sync between users/devices and are not stored in PostgreSQL. The v26 backend README describes the social API capabilities, but it does not currently provide a community-room chat API. Do not advertise these room chats as live multi-user messaging until a room-message backend, authentication/authorization, moderation and realtime/polling delivery are implemented.

The existing v26 financial features remain prototypes/disabled as documented in the v26 notes.
