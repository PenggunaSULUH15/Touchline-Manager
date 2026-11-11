# First task for Codex

Read `AGENTS.md` and `README.md` first. Inspect the whole starter project before making changes.

Goal: turn this starter into a reliable first playable desktop prototype without attempting to implement the entire game at once.

Tasks:
1. Verify the Electron + Vite + React app starts with `npm install` and `npm run dev`.
2. Fix any dependency, configuration, import or runtime errors you find.
3. Verify the Overview, Squad and Match Centre navigation works.
4. Verify the Phaser pitch mounts and cleans up correctly when leaving/re-entering Match Centre.
5. Add a basic Tactics page where the user can select one of the formations in `formations.json` and see its 11 positions.
6. Keep the match engine separate from Phaser. Do not implement fake match results.
7. Add a small test strategy and document how to run checks.
8. Run the production build and report the exact result.

Do not implement transfers, finances, scouting, or full match simulation in this task. Do not replace the architecture without explaining why.
