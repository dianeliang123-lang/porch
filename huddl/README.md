# The Huddl

A clickable demo for college football players and coaches. Mobile-first, one static page, no build step, no login, no database. All names and numbers are made-up sample data.

## Screens

- **Player › Check-in** — tap the five daily routine items (film study, 8 hours of sleep, recovery/stretching, hydration, pre-practice focus).
- **Player › Progress** — current streak, a 7-day chart of items completed per day, and an encouraging line based on the week.
- **Coach** — 12 sample players with position, this week's completion %, and status (on track ≥ 80%, slipping 60–79%, needs check-in < 60%). Sort by status, completion or name; tap a player to see their week and which items they miss most.

Use the **Player / Coach** switch in the header to flip views. The demo player ("Jordan Reyes, #11") also appears on the coach list, so a check-in shows up there right away.

## Run it

```sh
cd huddl
python3 -m http.server 8000
# then visit http://localhost:8000
```

Today's check-in is saved in the browser's `localStorage` (key `huddl-v1`) and resets each day. "Reset today" at the bottom of the check-in screen clears it.
