# HYROX Men's Doubles Strategy App - Plan

## Overview

A static, mobile-friendly race strategy page for Jordan & Casey's HYROX Men's Doubles Open plan. The page shows the full 16-segment race flow, cumulative target times, station split visualization, and a Shanghai-specific rules checklist.

## Target Time

- On-course target: 52:20
- ROX Zone allowance: about 5:00
- Full race target: about 57:20

## Rule Baseline

The app follows the current HYROX 25/26 Doubles Rulebook:

- 8 x 1km runs, completed by both athletes.
- Workout order: Ski Erg, Sled Push, Sled Pull, Burpee Broad Jumps, Row, Farmers Carry, Sandbag Lunges, Wall Balls.
- Workout distances: 1000m, 50m, 50m, 80m, 1000m, 200m, 100m, 100 reps.
- Men's Open weights: Sled Push 152kg, Sled Pull 103kg, Farmers Carry 2 x 24kg, Sandbag Lunges 20kg, Wall Ball 6kg.
- Athletes must remain within 5 seconds of each other and enter/exit workout stations together.

Sources: [HYROX 25/26 Doubles Rulebook](https://maintain.hyrox.com/rulebooks/HYROX_RulebookDoubles_EN.pdf) and [HYROX Shanghai event page](https://hyrox.com/event/hyrox-shanghai/).

Shanghai-specific items still need the athlete guide:

- Regular HYROX Doubles Men is listed for May 17, 2026.
- HYROX Pro Doubles Men is listed for May 16, 2026 and uses heavier Pro weights.
- Running lap count
- Venue map
- Lane direction and handoff points
- Final technical briefing details

## Current Station Plan

1. Run 1 - 1km together - 3:50
2. Ski Erg - 1000m - 3:30 - 250m / 250m / 250m / 250m
3. Run 2 - 1km together - 3:50
4. Sled Push - 50m - 1:35 - Jordan 25m, Casey 25m
5. Run 3 - 1km together - 3:50
6. Sled Pull - 50m - 2:30 - Jordan 25m, Casey 25m
7. Run 4 - 1km together - 4:00
8. Burpee Broad Jumps - 80m - 2:05 - target handoff about every 10m, final section length follows Shanghai venue layout
9. Run 5 - 1km together - 3:50
10. Row - 1000m - 4:05 - 250m / 250m / 250m / 250m
11. Run 6 - 1km together - 3:50
12. Farmers Carry - 200m - 1:35 - Jordan 100m, Casey 100m, pending Shanghai layout confirmation
13. Run 7 - 1km together - 3:50
14. Sandbag Lunges - 100m - 2:30 - 4 x 25m
15. Run 8 - 1km together - 3:50
16. Wall Balls - 100 reps - 3:40 - first set 10 reps, then switch in 20-rep sets, then repeat any No rep immediately

## Implementation Notes

- Main app: `index.html`
- No build step or dependencies
- Open directly in a browser
- Animation speed is controlled by `animationSlowdown` in the script

## Remaining Pre-Race Tasks

- Update Shanghai lap count once the athlete guide is available.
- Confirm Wall Ball target handling at the Shanghai technical briefing.
- Confirm carry/lunge lane lengths from the venue map.
