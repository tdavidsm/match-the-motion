# 🚗 Match the Motion

A kinematics graph-matching game. Students are shown a random **position–time** or **velocity–time** graph (2 or 3 segments) and drag a car across a side-view scene (house = 0, right = +, left = −) to reproduce the motion in real time.

**▶ Play:** https://tdavidsm.github.io/match-the-motion/

## How it plays
- **Warm-ups (must pass both):** one 2-segment **position–time** graph, then one 2-segment **velocity–time** graph. "Show me" plays the correct motion.
- **Final round:** four 3-segment graphs (random type) — match **3 of 4** to win.
- **Win → code:** enter your name and get an 8-character completion code with your initials in the **3rd and 6th** slots. Screenshot it (or copy it) to turn in.

## Scoring
Every target is piecewise-constant velocity. Position–time is scored on position (start point matters); velocity–time is scored on each segment's average speed (start point doesn't). Pass at ~70%.

## Tech
Single self-contained `index.html`, plain HTML/CSS/JS, canvas scene + graph, Pointer Events (touch + mouse), built for iPad Safari. Deployed via GitHub Pages from `main`.
