# 🚴 Zwift Training Plan Generator

Automated Zwift training plan generator — builds personalized daily plans with zone-based workouts, route recommendations, event schedules, and more.

## ✨ Features

- 📋 **Zone-based workouts** — auto-selects .zwo workouts by training zone (VO2Max, Threshold, Sweet Spot, Endurance, W'bal, etc.)
- ⚡ **W'bal training** — Tabata, staircase, 30/30, and sprint finisher intervals targeting W' depletion/reconstitution
- 🔀 **60m + 30m split options** — offers a main + secondary workout combo for each day
- 🗺️ **Route recommendations** — prioritizes uncompleted and rebel routes with combo chaining
- 🔗 **Route combos** — chains multiple short routes into one ride
- 📡 **Zwift events** — fetches races/rides from Zwift API for your time window and groups
- 🏆 **WTRL TTT** — shows weekly Team Time Trial schedule
- 🔥 **Flamme Rouge** — displays tour stages and start times
- 💀 **Rebel Routes** — tracks completion via Strava segment API
- 📈 **Fatigue tracking** — scales intensity based on recent TSS load
- 🏅 **Weekly challenges** — shows current Zwift weekly challenges
- 📊 **Intervals.icu integration** — pulls ride history, W'bal profile, CTL/ATL/TSB fitness, peak powers, and power zone time distribution

## 📁 Project Structure

```
├── plan_output.md            # Generated training plan (Markdown)
├── Workouts/                 # .zwo workout files + power profile PNGs by zone
│   ├── Anaerobic/            # 20m–75m anaerobic intervals
│   ├── Cadence/              # 20m–150m cadence drills
│   ├── Endurance/            # 20m–450m endurance rides
│   ├── Neuromuscular/        # 20m–75m neuromuscular sprints
│   ├── Over-Unders/          # 20m–120m over-under intervals
│   ├── Recovery/             # 20m–360m recovery spins
│   ├── Special/              # FTP test (50m), race warmup (15m)
│   ├── Sweet Spot/           # 20m–180m sweet spot
│   ├── Tempo/                # 20m–300m tempo
│   ├── Threshold/            # 20m–120m threshold
│   ├── VO2 Max/              # 20m–90m VO2Max intervals
│   └── Wbal/                 # 20m–75m W'bal depletion intervals
└── Rebel_Routes/             # Rebel route guides & manifests
    ├── README.md             # Route table with links & status
    ├── *.txt                 # Route-by-route riding guides
    └── *.json                # Route manifests (segments, turns)
```

## 📊 Sample Output

Each day includes:
- 🎯 **Zone** + 🎚️ **Trainer difficulty**
- 📋 **Workout** (full duration) + 🔀 **Split** (main + secondary combo)
- 🗺️ **Uncompleted and Rebel Routes** with ZwiftInsider + VeloViewer links
- 🔗 **Improvement Combos** — completed routes ranked by PR improvement potential
- 📡 **Zwift events** (races + rides) in your time window
- 🏆 **WTRL TTT** / 🔥 **Flamme Rouge** when applicable
- 📈 **Fitness summary** — CTL, ATL, TSB, fatigue %
- 🏅 **Weekly challenges** — Climb of Week, Route of Week

## ✍️ Author

**Olek Senyk** — Initial work
