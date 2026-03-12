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
├── ride_intervals.py         # Intervals.icu activity fetcher
├── rides_intervals_icu.md    # Generated ride history + analytics
├── Workouts/                 # .zwo workout files by zone
│   ├── Anaerobic/            # 20m–120m anaerobic intervals
│   ├── Cadence/              # 20m–120m cadence drills
│   ├── Endurance/            # 20m–120m endurance rides
│   ├── Neuromuscular/        # 20m–120m neuromuscular sprints
│   ├── Over-Unders/          # 20m–120m over-under intervals
│   ├── Recovery/             # 20m–120m recovery spins
│   ├── Special/              # FTP test, race warmup
│   ├── Sweet Spot/           # 20m–120m sweet spot
│   ├── Tempo/                # 20m–120m tempo
│   ├── Threshold/            # 20m–120m threshold
│   ├── VO2 Max/              # 20m–120m VO2Max intervals
│   └── Wbal/                 # 20m–75m W'bal depletion intervals
└── Rebel_Routes/             # Rebel route guides & manifests
    ├── README.md             # Route table with links & status
    ├── *.txt                 # Route-by-route riding guides
    └── *.json                # Route manifests (segments, turns)
```

## 📊 Sample Output

Each day includes:
- 🎯 **Zone** + 🎚️ **Trainer difficulty**
- 📋 **Workout** (90m) + 🔀 **Split** (60m + 30m)
- 🗺️ **Uncompleted and Rebel Routes** with ZwiftInsider links
- 🔗 **Route combos** for multi-route rides
- 📡 **Zwift events** in your time window
- 🏆 **WTRL TTT** / 🔥 **Flamme Rouge** when applicable

## ✍️ Author

**Olek Senyk** — Initial work
