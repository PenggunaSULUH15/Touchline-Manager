# Project instructions for Codex

## Project goal
Build a standalone PC football management simulation called Touchline Manager.

## Technology
- Electron for the desktop shell.
- React for management UI.
- Phaser 3 for 2D match rendering.
- JavaScript modules.
- JSON for starter databases.
- SQLite may be introduced later for persistent career data.

## Architecture rules
1. Keep Electron main-process code separate from renderer code.
2. Keep match simulation independent from Phaser rendering.
3. Keep business/game rules out of React components.
4. Use stable IDs for clubs, players, competitions and fixtures.
5. Treat JSON files as seed data, not as the long-term save format.
6. Do not place secrets or unrestricted Node APIs in the renderer.
7. Use context isolation and keep nodeIntegration disabled.
8. Prefer small modules and reusable components.

## Gameplay principles
- Support both real-time matches and instant match simulation.
- Both modes must use the same underlying match rules and event model.
- Player attributes, roles, tactics, condition, sharpness and morale should influence performance.
- Avoid arbitrary outcomes that ignore match events.
- Keep fictional content clearly identified.
- Do not bundle copyrighted player photos, club crests or proprietary game assets.

## Development workflow
- Inspect existing files before editing.
- Make focused changes.
- Do not rewrite working systems unnecessarily.
- Run the relevant tests and build after changes.
- Report what changed, what was tested and what remains incomplete.
- Never claim a feature works unless it has been implemented and tested.

## UI direction
Modern minimalist desktop interface, dark navy surfaces, restrained blue accent, readable typography, compact data tables and clear navigation.
