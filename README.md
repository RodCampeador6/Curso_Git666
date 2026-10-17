# Healthy Life Project 🥗🏃🧠

A simple, Git-tracked project to get healthier in three areas:

1. **Diet** – eat better without crazy rules
2. **Exercise** – move consistently, get stronger
3. **Sharp mind** – focus, learning, sleep, stress

You manage it like a software project: goals, a plan, weekly "commits" of progress, and reviews.

## Project structure

```
.
├── README.md                  ← you are here (how the project works)
├── plan/
│   └── 12-week-plan.md        ← the roadmap, phase by phase
├── prompts/
│   ├── 00-start-here.md       ← first prompt: build YOUR personal plan with AI
│   ├── diet.md                ← prompts for meals, grocery lists, habits
│   ├── exercise.md            ← prompts for workouts and progression
│   ├── mind.md                ← prompts for focus, learning, sleep, stress
│   └── weekly-review.md       ← prompt to review your week and adjust
└── tracking/
    ├── baseline.md            ← where you start (fill once)
    └── weekly-log-template.md ← copy every week
```

## How to do it (step by step)

1. **Fill your baseline** → `tracking/baseline.md` (weight, waist, sleep, how many push-ups, etc.).
2. **Run the first prompt** → copy `prompts/00-start-here.md` into Claude, fill the blanks, and save the answer as `plan/my-plan.md`.
3. **Follow the 12-week plan** → `plan/12-week-plan.md`. Start small: 3 habits only in week 1.
4. **Log every week** → copy `tracking/weekly-log-template.md` to `tracking/week-01.md`, `week-02.md`, …
5. **Review every Sunday** → paste your weekly log into `prompts/weekly-review.md` and adjust next week.
6. **Commit your progress** (this is your Git practice too):

```bash
git add tracking/week-01.md
git commit -m "Week 1: 3/4 workouts, 6 days veggies, slept 7h avg"
git push
```

Your Git history becomes your health diary. 📈

## The 3 golden rules

- **Small > perfect.** A 10-minute walk you do beats a 1-hour workout you skip.
- **Track, don't judge.** Data helps you adjust; a bad day is just a data point.
- **Never miss twice.** Missing one day is normal; missing two starts a new (bad) habit.

> ⚠️ This is general wellness guidance, not medical advice. If you have health conditions, take medication, or plan big changes in diet or training, talk to a doctor first.
