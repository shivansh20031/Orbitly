# Orbitly
Orbitly is a spaced-repetition tracker for DSA problems, built as an interactive 3D solar system. Each solved problem becomes a planet that glows when it's due for review. Rate your recall, and an SM-2-style scheduler spaces the next revision. Includes stats, streaks, a heatmap, and JSON backup, all stored privately in your browser.  
# Orbitly

**Your knowledge, in orbit.**

Live demo: https://orbitly-coral.vercel.app/

## About

Most people solve a DSA (Data Structures and Algorithms) problem, feel good about it, and forget the approach within weeks. Orbitly helps you remember. It stores each problem you solve and brings it back for review just before you're likely to forget it, using a spaced-repetition schedule.

## What It Does

- **Logs your DSA problems.** Record the title, link, topic, difficulty, approach or key insight, time complexity, space complexity, and the mistakes you made.
- **Schedules reviews.** Each problem is reviewed on a schedule that gets longer as you remember it better.
- **Visualizes your progress as a solar system.** Each problem is a planet, and its position and appearance show its difficulty, topic, and review status.
- **Tracks your activity.** It shows a daily streak, a 12-week activity chart, and topic strength.

## How It Works

### 1. Solve a problem anywhere
LeetCode, a book, a contest, or anywhere else. All of it counts.

### 2. Log it in Orbitly
Click **Add** (`＋ Add`) and fill in:
- Problem title and link
- Topic
- Difficulty (Easy, Medium, or Hard)
- Approach or key insight
- Time and space complexity
- Mistakes or watch-outs

### 3. Review it when its planet glows orange
Open **Today** to see what's due. For each review:
1. Try to recall the approach.
2. Reveal your notes.
3. Rate how well you remembered.

## Reading the Universe

| Visual cue | Meaning |
|---|---|
| **Planet size** | Difficulty. Small = Easy, medium = Medium, large = Hard. |
| **Ring** | Appears on Hard planets. |
| **Planet color** | Topic. Each topic has its own color. |
| **Orbit distance** | How soon it's due. The closer to the sun, the sooner the review. Far orbits mean well-memorized problems. |
| **Pulsing orange halo** | Due today or overdue. |

## Review Ratings and Scheduling

The review intervals (the "ladder") are **1, 3, 7, 14, 30, and 60 days**. After each review, you rate your recall:

| Rating | Effect on the schedule |
|---|---|
| **Forgot** | Resets to the start. You'll see the problem again tomorrow. |
| **Hard** | You got there with a struggle. The next gap shrinks to about 60% of the current gap. |
| **Good** | On schedule. The problem moves up one rung on the ladder. |
| **Easy** | Effortless. The problem jumps ahead, and the next gap is about 40% longer than usual. |

Past 60 days, the gaps keep growing with each Good rating.

**Mastered** means a problem has a 30+ day interval and is not currently due. **Topic strength** reflects recall and review spacing. Forgotten or overdue problems lower it.

## Features

- **Universe view:** 3D solar-system view. Drag empty space to rotate, pinch or scroll to zoom, and tap a planet to review it.
- **Filters:** Filter by topic, difficulty (Easy, Medium, Hard), and status (Due, Learning, Mastered).
- **Today view:** Shows what needs review now, and counts due reviews.
- **Stats view:** Streaks, 12-week activity, and topic signals.
- **Reduced motion:** In Settings, freezes the orbit animation and turns off camera flights, particles, and fireworks.
- **Backup and restore:** Export your library as JSON and import it on another device.

## Your Data

All data is stored **only in your browser**. Nothing is uploaded to a server.

- **To back up or move to another device:** Open Settings (⚙), choose **Export JSON**, then use **Import JSON** on the other device. Importing replaces the current library after confirmation.
- **Warning:** Clearing your browser data erases your library. Export regularly.
- **Sample data:** You can clear the sample data from Settings.

## Tips for Best Results

- Review daily. A few minutes each day works better than one long session per week.
- Write notes in your own words. If you can explain it simply, you understand it.
- Record your mistakes. Past errors are the best hints for next time.

## Getting Started

1. Open https://orbitly-coral.vercel.app/
2. Click **Add your first problem** or **Add**.
3. Check **Today** each day for reviews.



