# 🚴 Preferences

1) Using the info below, create a ride for a target day - day after today
1) Offer in the target day (race or workout) for ride
2) Offer in the target day a zone workout fit best: each day duration 90 mins, offer also 60m + 30m

# 📊 My Stats

* ⚡ Zwift level: 75
* 💪 FTP: 253
* 🏆 ZRS: 417
* 👥 My groups: B, C, D, E

# 📏 Rules

See [RULES.md](RULES.md) — training schedule, event sources, workout/route selection, output format.

# 🏁 Race Guides

When I ask how to ride any race/event, save full guide (route breakdown, equipment, pacing, tips, what bikes not allowed on a race) to a file:
* File per event series: `D:\zwift\zwift_training\{PLATFORM}_{DATES}_{SeriesName}.txt`
  - FRR example: `FRR_2026.02.14-22_World_Tour.txt`
  - Other platforms: `WTRL_...`, `ZRL_...`, `SISU_...`, etc.
* Order: newest stage/event on top, separated by `===`
* Content per stage: route (how to ride), equipment (frame/wheels), pacing (power targets per segment), tips

# 📁 Folder Structure

* 📂 zwift_training/ — only scripts I explicitly asked to create
* 🔧 zwift_training/zwift_service_scripts/ — any utility/helper scripts the agent creates for tasks
* 💀 zwift_training/Rebel_Routes/ — rebel route guides (.txt), manifests (.json), README
* 🔄 d:\zwift\garmin_strava_zwift\ — Garmin/Strava/Zwift sync scripts
* 📋 zwift_training/Workouts/ — .zwo workout files
* 🔑 All scripts use sync_config.yaml for credentials
* 🚫 Git: no auto-commit, no auto-push — I decide when to commit and push
* 🕐 Timestamps: always show 3 time zones (EST / UTC / EET)

# 🗺️ Routes Uncompleted

**World codes:** W=Watopia, I=Innsbruck, N=New York, M=Makuri Islands, S=Scotland, R=Richmond, F=France, L=London, Y=Yorkshire

- 🔴 L — London PRL Full — 173.8 km / 2628 m — Difficulty 5/5 — 3460 XP
- 🔴 W — The Uber Pretzel — 128.8 km / 2381 m — Difficulty 5/5 — 2560 XP
- 🔴 W — The Mega Pretzel — 111.0 km / 1659 m — Difficulty 5/5 — 2140 XP
- 🔴 W — Four Horsemen — 90.4 km / 2111 m — Difficulty 5/5 — 1780 XP
- 🔴 N — Fuhgeddaboudit — 79.0 km / 838 m — Difficulty 5/5 — 1595 XP
- 🔴 M — Makuri Pretzel — 78.7 km / 623 m — Difficulty 5/5 — 1550 XP
- 🔴 W — Watopia Pretzel — 73.0 km / 1361 m — Difficulty 5/5 — 1440 XP
- 🟠 W — Big Foot Hills — 69.9 km / 714 m — Difficulty 4/5 — 1340 XP
- 🟡 F — Tire-Bouchon — 63.9 km / 587 m — Difficulty 3.5/5 — 1220 XP
- 🟠 I — Achterbahn — 47.7 km / 990 m — Difficulty 4.5/5 — 950 XP
- 🟠 W — Three Sisters — 48.5 km / 896 m — Difficulty 4.5/5 — 950 XP
- 🔴 W — Quatch Quest — 46.8 km / 1706 m — Difficulty 5/5 — 920 XP
- 🔴 W — Power to the Tower — 45.6 km / 1496 m — Difficulty 5/5 — 900 XP
- 🟡 W — ZG25 Queen — 44.8 km / 894 m — Difficulty 3/5 — 895 XP
- 🟡 W — Accelerate to Elevate — 43.5 km / 1158 m — Difficulty 3/5 — 825 XP
- 🟠 L — Surrey Hills — 44.1 km / 1034 m — Difficulty 4/5 — 820 XP
- 🟡 F — La Reine — 22.9 km / 1201 m — Difficulty 3.5/5 — 460 XP
- 🟢 N — Lady Liberty — 12.6 km / 206 m — Difficulty 2/5 — 240 XP
- 🟢 L — London Flat — 12.4 km / 115 m — Difficulty 1/5 — 240 XP
- 🟢 Y — Tour Of Tewit Well — 10.9 km / 204 m — Difficulty 2/5 — 210 XP
- 🟢 S — Rolling Highlands — 14.1 km / 106 m — Difficulty 2/5 — 180 XP
- 🟢 M — Farmland Loop — 8.0 km / 58 m — Difficulty 1.5/5 — 155 XP
- 🟢 M — Valley to Mountaintop — 5.1 km / 131 m — Difficulty 1.5/5 — 100 XP

# 💀 Rebel Routes Uncompleted
**Source:** https://veloviewer.com/zwift-insider/rebel-routes
**Check script:** `zwift_service_scripts/check_rebel_routes.py` — run each session to refresh from Strava API

**Status: 6/25 completed** (Big Ring Little Ring, COMPLETED (6):, Hilly KOM Bypass, Mangrove Circuit, Nessie's Loop, Spiral Into the Volcano, Summit City Velodrome)

W — The Full Watopia — 154.5 km / 2852 m
F — Toutes les Routes — 104.8 km / 1968 m
W — The Marvelous Metric — 102.0 km / 489 m
W — KOMonster — 99.8 km / 2570 m
W — The Perimeter — 82.3 km / 1874 m
M — The Full Makuri — 80.9 km / 650 m
W — The Snake — 77.4 km / 661 m
W — Litus Fugit — 61.0 km / 269 m
N — The Full New York — 57.8 km / 596 m
W — The Roads Less Traveled — 53.6 km / 437 m
W — Cliffside Epic Double — 52.7 km / 991 m
W — Down Up Down — 49.4 km / 1257 m
W — Big Ring Little Ring Reverse — 20.6 km / 143 m
S — Fower Power — 19.7 km / 214 m
W — Epic Loop — 14.4 km / 378 m
M — Canyon to Cavern — 13.4 km / 87 m
S — Sgurr 8 — 12.6 km / 150 m
M — Urukazi Flats — 7.5 km / 22 m
M — Dirty Temple KOM Loop — 4.4 km / 75 m
