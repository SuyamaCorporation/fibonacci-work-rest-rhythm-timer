# Fibonacci Work-Rest Rhythm Timer
Interval timer cycling through Fibonacci work periods: 1,1,2,3,5,8,13 minutes. Break is 20% of work time (configurable). Visual circular progress timer. Current/next period display. Session log. Completion sound via Web Audio API.

## Features
- Fibonacci work sequence: 1, 1, 2, 3, 5, 8, 13 minutes
- Configurable break percentage (10-50% of work time) via slider
- SVG circular progress ring with smooth stroke-dashoffset animation
- Color coding: yellow ring for work, green ring for break
- Start/Pause/Resume and Skip (Next) controls
- Web Audio API completion chimes for work→break, break→work, full session done
- Fibonacci sequence display showing completed (strikethrough) and active intervals
- Timestamped session log of all completed intervals
- Total session time accumulator
- Reset All button to restart from scratch
