# Study Planner

A study planner that runs entirely in the browser: one `index.html`, no account and no server.
It works offline, and your data stays on your device.

## What it does

- **Today**: tasks due now and this week, today's study blocks, exam countdowns, time studied today and your study streak.
- **Tasks**: homework and revision tasks with subject, due date, priority and notes.
- **Focus**: a Pomodoro-style timer (focus, break, and a long break every fourth round). Focus time is logged to the subject you pick, and time studied elsewhere can be logged by hand.
- **Cards**: flashcards with spaced repetition. Cards you know come back after 1, 3, 7, 14 and then 30 days; cards you miss come back straight away. Add them one at a time or paste many at once.
- **Timetable**: your regular weekly study blocks.
- **Subjects**: colours, exam dates and a weekly time goal with a progress bar.
- **Progress**: a 14-day chart of study time by subject, and totals.
- **Backup**: download everything as a JSON file and restore it later or on another device.

## Get it

- **Website**: https://anandhavaradhan.github.io/Study-Management/ (it can be installed from the browser menu and works offline)
- **Android**: [StudyPlanner.apk](https://github.com/Anandhavaradhan/Study-Management/releases/download/studyplanner-latest/StudyPlanner.apk)
- **Windows**: [StudyPlanner.exe](https://github.com/Anandhavaradhan/Study-Management/releases/download/studyplanner-latest/StudyPlanner.exe) (portable, no installation)

The apps are built by `.github/workflows/apps.yml` from `android/` and `desktop/` on every change to `main`.
Each one keeps its own data, so use Backup to move your planner between the website and the apps.

Or open `index.html` in any browser.

Data is kept on the device (the browser's local storage). Clearing site data erases it, so download a backup from time to time.
