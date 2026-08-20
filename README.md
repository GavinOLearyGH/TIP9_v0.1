# TIP9 v0.2

**Nine balls. One purpose.**

TIP9 is the Quick Practice companion to TIP7. The golfer chooses where they are practicing, TIP9 recommends a focused nine-ball practice, and the work happens in three blocks of three balls.

## v0.2 product test

- Recommendation-led front door: Range, Putting Green, or Short Game.
- 26 programmed practice families from the TIP9 Programming Master:
  - 8 Swing practices.
  - 18 Skill practices.
- `Give me another` provides a different recommendation without forcing the golfer into a library.
- Browse remains available for prototype testing.
- Every TIP9 is exactly nine balls and only three phone check-ins.
- Clearer `WHAT TO DO` language states the setup/action plus an explicit `SUCCESS` condition.
- Swing is adaptive between three-ball blocks:
  - 0/3 → Reset and simplify.
  - 1/3 → Reinforce the same support.
  - 2–3/3 → Progress toward a more normal golf shot.
- Swing completion uses `Felt Good / Keep Working` rather than foregrounding an overall 0–9 score.
- Skill remains a scored execution challenge; 7/9 currently unlocks the next level.
- Three levels per practice: Find/Learn → Control → Perform.
- Reset prototype progress remains available for repeated testing.
- No badges, XP, daily streak, or forced schedule.

## Product architecture hypothesis

TIP7 = Quick Body (Stretch + Strength)

TIP9 = Quick Practice (Swing + Skill)

TIP OS = Smart Journal / Digital Coach. The lightweight coaching loop we are testing is: golfer tells TIP what happened → TIP remembers → TIP prescribes a specific TIP7 or TIP9 action. Larger multi-session Plans remain a deeper coaching layer rather than the required unit of every recommendation.

## Files

- `index.html` — mobile prototype and interaction logic.
- `tip9_data.js` — practice library, level progression, setup language and success conditions.

The programming source for this build is `TIP9_Programming_Master_v1.xlsx` created during the design process.