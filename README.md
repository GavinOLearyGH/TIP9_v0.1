# TIP9 v0.2

**Nine balls. One purpose.**

TIP9 is the Quick Practice companion to TIP7. The golfer selects the practice context that is available right now, TIP9 recommends a focused practice that is valid for that context, and the work happens in three blocks of three.

## v0.2 product test

- Context-first front door with five practice contexts:
  - **Range** — full flight, targets and turf.
  - **Hitting Bay** — net, simulator or launch monitor.
  - **Putting Green** — start line, speed and scoring.
  - **Short Game** — chip, pitch and bunker work.
  - **No Ball** — rehearsals, motion and feel.
- Practices can be eligible for more than one context instead of being assigned to a single location.
- No Ball uses **9 reps**, not 9 balls, and only recommends rehearsal-compatible Swing work.
- 26 programmed practice families:
  - 8 Swing practices.
  - 18 Skill practices.
- Recommendation-led experience with `Another practice` and Browse available for deliberate prototype testing.
- Ball-based TIP9s are exactly nine balls and require only three phone check-ins.
- Clear `WHAT TO DO` language states setup/action plus an explicit `SUCCESS` condition.
- Swing is adaptive between three-ball or three-rep blocks:
  - 0/3 → Reset and simplify.
  - 1/3 → Reinforce the same support.
  - 2–3/3 → Progress toward a more normal golf shot.
- Swing completion uses `Felt Good / Keep Working` rather than foregrounding an overall 0–9 score.
- Skill remains a scored execution challenge; 7/9 currently unlocks the next level.
- Three levels per practice: Find/Learn → Control → Perform.
- Reset prototype progress remains available for repeated testing.
- No badges, XP, daily streak, or forced schedule.

## Product architecture hypothesis

TIP7 = 7-minute body work (Stretch + Strength)

TIP9 = 9-ball practice / 9-rep No Ball work (Swing + Skill)

TIPPED = the single front door that contains both quick-hit products.

TIP OS = Smart Journal / Digital Coach. The lightweight coaching loop we are testing is: golfer tells TIP what happened → TIP remembers → TIP prescribes a specific TIP7 or TIP9 action. Larger multi-session Plans remain a deeper coaching layer rather than the required unit of every recommendation.

## Files

- `index.html` — mobile prototype and interaction logic.
- `tip9_data.js` — practice library, context eligibility, level progression, setup language and success conditions.

The current programming source is `TIP9_Programming_Master_v2_Context_Model.xlsx` from the design process.