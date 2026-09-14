# Kerapac HM Cue Board (Alt1)

Big on-screen visual cues for Kerapac, the Bound (Hard Mode).

Based on the same structure as the Zamorak Cue Board.

## What it does

- Large coloured banners appear over the game when a mechanic is called.
- Manual buttons (or number keys 1–6) for instant cues.
- Auto mode that watches for the classic chat trigger phrases (best-effort).
- Text + icons for clear callouts.

## Key cues

| Key | Banner              | Trigger text (chat)                          | What to do                                      |
|-----|---------------------|----------------------------------------------|-------------------------------------------------|
| 1   | WALK UNDER          | I'll tear right through you                  | Step under Kerapac to deny tear + stun          |
| 2   | DODGE SLAMS         | I will put you in your place / You will break beneath me | Dodge the 3 jumping slams (or stall)     |
| 3   | MOVE – LIGHTNING    | Witness the raw power of the Staff           | Surge / Bladed Dive through the wall(s)         |
| 4   | PHASE 2             | No. I control the threads of time / The time threads have split! | Phase 2 – echoes start appearing      |
| 5   | PHASE 3             | I... can... contain... ALL. ITS. POWER.      | Phase 3                                         |
| 6   | PHASE 4 – ECHOES    | Look at what you've done! You've fractured the threads of time! | Kill the 3 echoes then Kerapac          |

## How to install

1. Make sure Alt1 Toolkit is installed (https://runeapps.org/alt1).
2. Copy the whole `kerapac-cue` folder somewhere permanent (e.g. Documents).
3. In Alt1:
   - Right-click the Alt1 icon → **Add app**
   - Point it at the `appconfig.json` file inside the folder
   - Or open the folder in the Alt1 browser and click “Add app”
4. Grant **Pixel** and **Overlay** permissions when prompted (right-click the app → Permissions).

### Local file tip
If Alt1 complains about local files, relaunch Alt1 with the launch option:
```
--allow-file-access-from-files
```

## Icons

Place ability icons in the `icons/` folder (optional but recommended).  
Expected filenames (you can reuse the ones from your Zamorak board or grab them from the wiki / ability icons):

- `freedom.png`
- `anticipation.png`
- `deflect_melee.png`
- `debilitate.png`
- `devotion.png`
- `surge.png` (or any movement ability)

If an icon is missing the board falls back to plain text automatically.

## Tips

- Keep chat timestamps on.
- Chat font size 12 works best.
- Interface scaling 100%.
- You can drag the app window wherever is convenient; the banners appear in the middle of the game screen regardless.

Good luck on the HM kills!
