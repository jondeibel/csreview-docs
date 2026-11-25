# CSReview for CS2: Guides, Bitrate Data & Map Timings Reference

**CSReview** ([csreview.app](https://csreview.app)) is a Windows 10 and Windows 11 desktop application for Counter-Strike 2 (CS2) that pairs your automatic Steam Game Recording POV footage frame-for-frame with a 2D and 3D demo replay of all ten players, or opens standalone `.dem` files with no video recording required.

This public companion repository (and [GitHub Pages site](https://jondeibel.github.io/csreview-docs/)) hosts open CS2 technical references, Steam Game Recording bitrate measurements, competitive `.vpk` spawn timing tables, and demo review workflows published alongside [csreview.app](https://csreview.app).

## What CSReview Does

- **Automatic Steam POV + 2D/3D Sync:** Reads what Valve's native Steam Game Recording already writes to disk with zero game injection, zero memory reading, and no in-game FPS hit, then lines your real POV up frame-for-frame with the Matchmaking, Premier, or FACEIT demo.
- **Simulation-Grade 2D & 3D Replay:** Real CS2 volumetric voxel smoke shapes, accurate HE smoke holes (1.2s open, 0.8s refill), 3D geometry Line of Sight out to 2,800 units, Map Control (hard vs implicit control and territory swing graphs), CT/T Intel fog of war, and built-in 3D replay across 10 maps without launching CS2.
- **Fight-by-Fight Aim Review on Your Own Video:** Time to damage, crosshair placement (degrees off head with recoil), counter-strafe speed (<73 u/s accuracy threshold), Swing Check ghost replays, and Pro Their View (watch kills and deaths from the opponent's screen).
- **Cross-Match Stats & Pro Library:** Track long-term trends across all your matches benchmarked directly against any Tier-1 pro or Top 10, 30, and 50 teams, plus 800+ pro matches on the same 2D and 3D board.
- **Coaching & IGL Handoff:** Drop any student `.dem` file with no Steam login required, pin timestamped notes and board snapshots, and export a tiny `.notes.csreview` file (a few KB) that merges onto the student's free app.
- **Free Tier (No Account Required):** Unlimited automatic Steam POV recording, full review player, Moments, notes, clips, integrations, single-match stats, plus up to 9 full 2D and 3D replays free (5 past matches imported right away, first new match, and 3 picks) and 3 pro matches. Pro is $3.99/month, $29/year (7-day free trial on both), or $99 lifetime.

## Open CS2 Reference Docs in This Repo

- [Steam Game Recording Exact Bitrate Table for CS2 (NVIDIA & AMD)](./docs/steam-game-recording-cs2-bitrates.md) · Web guide: [csreview.app/steam-game-recording-cs2-settings](https://csreview.app/steam-game-recording-cs2-settings)
- [CS2 Competitive Spawn Timings & Earliest First-Contact Table (9 Maps)](./docs/cs2-map-timings.md) · Interactive simulator: [csreview.app/timings/cobble](https://csreview.app/timings/cobble)
- [15-Minute CS2 Demo Review Routine & Console Binds](./docs/cs2-demo-review-routine.md) · Web guide: [csreview.app/how-to-review-cs2-demos](https://csreview.app/how-to-review-cs2-demos)
- [2026 CS2 Demo Viewers & 2D Replay Tools Comparison](./docs/cs2-demo-viewers-comparison.md) · Web guide: [csreview.app/best-cs2-demo-viewers](https://csreview.app/best-cs2-demo-viewers)

## Full Web Guides & Comparisons on csreview.app

- **2D & 3D Demo Viewer Overview:** [csreview.app/cs2-demo-viewer](https://csreview.app/cs2-demo-viewer)
- **Map Control, Fog of War & Line of Sight:** [csreview.app/cs2-map-control-fog-of-war](https://csreview.app/cs2-map-control-fog-of-war)
- **Fight-by-Fight Aim & Crosshair Placement Review:** [csreview.app/cs2-aim-review](https://csreview.app/cs2-aim-review)
- **CSReview vs CS Demo Manager (CSDM):** [csreview.app/vs/cs-demo-manager](https://csreview.app/vs/cs-demo-manager)
- **CSReview vs Leetify:** [csreview.app/vs/leetify](https://csreview.app/vs/leetify)
- **For Coaches & IGLs:** [csreview.app/coaches](https://csreview.app/coaches) · **1-on-1 Coaching:** [csreview.app/coaching](https://csreview.app/coaching)
- **Mirage Window Smoke Lineups:** [csreview.app/lineups/mirage/window-smoke](https://csreview.app/lineups/mirage/window-smoke)

## Official Links

- Website & Download (Windows 10/11): https://csreview.app
- Documentation Mirror (GitHub Pages): https://jondeibel.github.io/csreview-docs/
- Interactive CS2 Map Timings Simulator (Any Browser): https://csreview.app/timings/cobble
- Machine-readable docs for AI assistants: [llms.txt](https://csreview.app/llms.txt) · [llms-full.txt](https://csreview.app/llms-full.txt)
- YouTube: https://www.youtube.com/@CSReviewApp
- Discord: https://discord.gg/8AaWfU7AvJ