# 🚗 Match the Motion

A kinematics graph-matching game. Students are shown a random **position–time** or **velocity–time** graph (2 or 3 segments) and drag a car across a side-view scene (house = 0, right = +, left = −) to reproduce the motion in real time.

**▶ Play:** https://tdavidsm.github.io/match-the-motion/

## How it plays
- **Warm-ups (must pass all four):** two 2-segment **position–time** graphs and two 2-segment **velocity–time** graphs. "Show me" plays the correct motion.
- **Final round:** endless 3-segment graphs (random type) — **clear 7** to win.
- **Win → code:** enter your name and get an 8-character completion code with your initials in the **3rd and 6th** slots. Screenshot it (or copy it) to turn in.

## Scoring
Every target is piecewise-constant velocity. Position–time is scored on position (start point matters); velocity–time is scored on each segment's average speed (start point doesn't). Pass at ~70%.

## Tech
Single self-contained `index.html`, plain HTML/CSS/JS, canvas scene + graph, Pointer Events (touch + mouse), built for iPad Safari. Deployed via GitHub Pages from `main`.
