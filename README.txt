THE ACE PROJECT — B10.0 STAGE 3

FOCUS
Ultimate Team lazy mounting.

WHAT CHANGED
- Ultimate Team now stays on lightweight Home until the player chooses a section.
- Squad no longer renders in the background on startup.
- Squad is detached while inactive and its player/bench/chemistry DOM is cleared.
- My Club is detached while inactive.
- Premium Pack Store is generated only when Packs opens and removed on exit.
- The old hidden legacy Pack Panel is removed completely.
- Home and Profile generated DOM are released when they are not active.
- Missions remain mounted because the compact topbar reads their live progress.
- Chemistry runs only while Squad is open.
- Topbar MutationObserver updates are coalesced into one animation frame.
- Closed mission dropdown is no longer rebuilt on every progress change.
- Removed duplicate eager Home/Profile/Pack rendering.

NEXT
Stage 4: multiplayer/network optimisation — Realtime first, slower fallback polling.
