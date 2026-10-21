# Team C_deepens-HabitGrid

**HabitGrid** is a habit tracker web app with a GitHub-style yearly heatmap and streaks. Target price: $4.99.

## What it does
Add any habits you want to build, mark days done, and see a full year of progress as a contribution-style heatmap for each habit.

## How to run
No install or build step. Open `index.html` in any modern browser, or serve the folder:
```
python3 -m http.server 8000
```
Then visit http://localhost:8000. Data is stored locally in your browser (localStorage).

## Features
- Unlimited habits: add, rename, delete
- Yearly heatmap (last 52 weeks) per habit; click any square to toggle that day
- "Done today" one-click button
- Current streak, best streak, last-365-day count, and all-time total
- Export / import your data as JSON (backup or move devices)
- Works offline, no account, single file
