---
name: my-studio
description: Use whenever I edit a video, give a note on an edit, or approve a video. Uses the 105 styles skill (brand-nat-styles) when editing and lets my saved preferences in MY-STYLE.md and NOTES.md guide the choices.
---

# My Studio

My personal video editing studio, built on top of the 105 styles skill at `.claude/skills/brand-nat-styles`
(styles in its `styles.md`, visual guide in `guide/index.html`). That skill's workflow, tools and house rules
still apply; this skill adds my own taste and memory on top.

Two files live next to this one:
- `MY-STYLE.md`: my look (captions, colours, pacing) and everything I never want. Rules here win over defaults.
- `NOTES.md`: every note I have ever given on an edit, dated, newest last.

## Every edit
1. Read `MY-STYLE.md` and `NOTES.md` first and follow them. Then use the 105 styles skill to edit.
2. Read both files again right before you render, so nothing gets forgotten halfway through.
3. After rendering, check the finished video against every rule in `MY-STYLE.md`, one by one, and label each check:
   - **Measured**: measured on the actual video file (words per line, gaps, how long nothing moves, colour values).
   - **Visually reviewed**: looked at frames taken from the actual video file.
   - **Unverified**: could not check it on the video; only the plan or an estimate says it is fine.
   Never say a check passed if it was only based on the plan or an estimate.
4. Fix anything that fails before showing me the video, then give me the list with its labels.

## Every note
1. Save the note in `NOTES.md` the moment I give it, before fixing anything. Do not wait until the end.
2. If I have said it before (same meaning, even in different words), add it to `MY-STYLE.md` as a rule and tell me:
   "You've said this before, so it's now a rule."
3. When I approve a video, save what worked to `MY-STYLE.md` (under "What worked").

## Finding my style (once)
If `MY-STYLE.md` still says the style has not been found yet: check ffmpeg the way the 105 styles skill does,
then ask me for 1 to 3 videos I love, or my own videos. If I have none, help me pick styles from the 105 style
guide. Look at frames from the videos and save what I like to `MY-STYLE.md`. Learn the style, do not copy the video.
Never invent preferences I did not show or say.
