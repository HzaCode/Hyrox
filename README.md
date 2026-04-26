# HYROX Men's Doubles Strategy

A single-page planner for HYROX Men's Doubles teams. Drop in your target time, partner names, and station splits, and the page renders an animated 16-segment timeline plus a rules checklist you can scan at a glance.

The current numbers are filled in for Jordan & Casey's plan around HYROX Shanghai 2026 as a worked example, but every section is meant to be edited for your own race and city. Numbers and rule chips are configured for **Men's Doubles** at Open loads (152 / 103 / 24 / 20 / 9kg). Mixed, Women's, and Pro divisions need their own station plans.

## What's on the page

- **Animated 16-segment timeline** — 8 runs and 8 stations in race order with cumulative target times, so partners can agree on pacing before race day.
- **Per-station partner split** — Ski Erg, Row, Sled Push/Pull, Burpees, Farmers Carry, Lunges, Wall Balls each show who does which share, in YGIG format.
- **Rule checklist** — together-at-the-lane-line rule, station entry/exit together, Open Men's weights, 3.00m Wall Ball target, referenced against the current HYROX 25/26 Doubles Rulebook.

## New here? Hover the Tips badge

Each station header has a small `Tips` badge. Hover it on desktop, or tap it on mobile, and a small popover shows two things:

- **Rule** — what the official rulebook says about that station (release the handle on Ski Erg, sled fully crosses the line on the push, no flying handoffs on Wall Balls, etc.).
- **Coach tip** — a short, practical suggestion drawn from common Doubles strategy write-ups (switch the Ski Erg every 125–250m instead of 500/500; never push the sled solo for 25m; on Wall Balls work in 10–15 rep sets).

This is mainly for first-time HYROX teams — it lets you understand what's legal and what's smart at each station without leaving the page.

## Plan your own race

1. Open `index.html` in a browser, or host it on GitHub Pages.
2. Edit the team name and partner names in the page header.
3. Update the target time block and per-station durations in `raceSchedule` to match your goal pace.
4. Adjust the station split notes (e.g. Ski Erg 250/250/250/250, Sled Push 4 x 12.5m) to how your team plans to swap.
5. Re-check the rule checklist against the latest [HYROX Doubles Rulebook](https://maintain.hyrox.com/rulebooks/HYROX_RulebookDoubles_EN.pdf) and your event's athlete guide.

See `PLAN.md` for the full worked example (Jordan & Casey's 57:20 plan), which you can use as a reference when filling in your own numbers.

## Example target (Jordan & Casey, HYROX Shanghai 2026)

- On-course target: 52:20
- ROX Zone allowance: about 5:00
- Full race target: about 57:20
- Event window: May 16–17, 2026. Wave time, lap count, and venue layout are still TBA — confirm them from the athlete guide before race day.

## Official race structure

Mixed Doubles is 8 x 1km runs plus 8 workout stations:

1. Ski Erg - 1000m
2. Sled Push - 50m
3. Sled Pull - 50m
4. Burpee Broad Jumps - 80m
5. Row - 1000m
6. Farmers Carry - 200m
7. Sandbag Lunges - 100m
8. Wall Balls - 100 reps

Both athletes complete every 1km run. Workout stations use YGIG format: one athlete works while the partner stays in the station.

## Rule checks (verify against your event's athlete guide)

- Both athletes must complete every 1km run together and enter/exit each workout station together. "Within 5 seconds" is a common coaching cue, but the rulebook only enforces *together at the lane line* — partners cannot start or leave a station alone.
- Men's Doubles uses Open Men's loads: Sled Push 152kg, Sled Pull 103kg, Farmers Carry 2 x 24kg, Sandbag Lunges 20kg, Wall Ball 9kg.
- Wall Ball target: 3.00m for both athletes (Men's Doubles uses one shared target — there are no athlete-specific heights here).
- Wave time, lap count, and venue layout vary by event — confirm them in your athlete guide.

Sources: [HYROX 25/26 Doubles Rulebook](https://maintain.hyrox.com/rulebooks/HYROX_RulebookDoubles_EN.pdf) and the [official HYROX events listing](https://hyrox.com/events/).

## Usage

Open `index.html` directly in a browser. No dependencies, no build step.

## Credits & contributions

Built on top of [bertovmill/toronto_hyrox_2025](https://github.com/bertovmill/toronto_hyrox_2025); the timeline layout and animation come from that earlier work. Coach-tip wording draws on the public HYROX Doubles Rulebook and common community strategy write-ups (e.g. Rox Lyfe, Edge).

Issues and PRs with corrections, additional rule checks, or other event venues are welcome — the goal is to make race-day planning a little easier for the next Mixed Doubles team.
