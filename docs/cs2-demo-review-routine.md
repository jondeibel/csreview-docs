# 15-Minute CS2 Demo Review Routine & Native Console Binds

Full guide: https://csreview.app/how-to-review-cs2-demos

1. **Pick one close loss (13-10 or OT), not a blowout.** Reviewing one close match beats skimming five.
2. **Keep your real POV with Steam Game Recording.** 64-tick server demos smooth out micro-adjustments and drop your voice comms and HUD timing.
3. **First watch every death with X-ray OFF (or CT/T Intel fog of war).** Judge the decision strictly on what you could have known from sight, sound, radar, and utility.
4. **Skip buy phases, saves, and clean eco wins.** Jump straight to deaths, lost opening duels, and dropped clutches.
5. **Tag each death with one blunt label** (dry peek, crosshair low, no trade, died with util, over-peeking with advantage) and stop after picking two repeating habits for your next five matches.

## Useful Native CS2 `demoui` Console Binds

```cfg
bind "f5" "demo_togglepause"
bind "f6" "demo_timescale 0.5"
bind "f7" "demo_timescale 1"
bind "f8" "demo_timescale 4"
```

## Mirage / General Smoke Practice Config

```cfg
sv_cheats 1; bot_kick; mp_roundtime_defuse 60; mp_freezetime 0; mp_buy_anywhere 1; mp_maxmoney 60000; mp_startmoney 60000; ammo_grenade_limit_total 5; sv_infinite_ammo 1; sv_grenade_trajectory_prac_pipreview 1; mp_restartgame 1
```

Want the manual clipping and `demoui` scrubbing automated on Windows? Try [CSReview](https://csreview.app) (free, no account, 9 full 2D & 3D replays included).
