# TIP9 v0.1

**Nine balls. One purpose.**

TIP9 is the Quick Practice companion to TIP7. It gives a golfer a small, structured practice prescription without requiring a full plan or session.

## v0.1 product test

- Golfer chooses context: Range, Putting Green, or Short Game.
- Six initial Quick Practices:
  - Swing: Contact, Tempo, Playable Tee Ball
  - Skill: Start Line, Distance Control, Lag Putting
- Every TIP9 is three blocks of three balls.
- The golfer hits all three balls before touching the phone, then records 0–3 successful attempts for the block.
- A nine-ball strip visualizes progress.
- 7/9 unlocks the next competency level; missing the threshold simply leaves the current level active.
- Three levels are modeled for each Quick Practice.
- No daily streak, badges, XP, or forced schedule.
- Progress, best score, current level, total TIP9s, and Swing feel are stored locally.

## Product architecture hypothesis

TIP7 = Quick Body (Stretch + Strength)

TIP9 = Quick Practice (Swing + Skill)

TIP OS = Smart Journal / Digital Coach. A near-term product hypothesis is that TIP OS can stay very simple: the golfer tells TIP what happened, TIP remembers, and its lightweight prescriptions are specific TIP7 or TIP9 actions. Larger multi-session Plans can remain a deeper coaching layer rather than being required for every recommendation.

## Prototype scope

This is intentionally a single-file, dependency-free mobile web prototype. The goal is to test whether `Give me 9` removes enough planning friction to make a golfer actually perform a purposeful nine-ball practice.