# Workout Timer

A web-based workout timer and tracker built to keep me on track with exercising.
It runs in any browser (iPad, phone, laptop) and is designed to be mirrored or cast to a TV.

## How it works

- Enter the exercises for the workout of the day. Each exercise lasts **1 minute**.
- The last minute of every round is a **cooldown (rest) minute**. With 4 exercises, a round is 5 minutes.
- Choose the number of rounds. The total workout time is added up automatically (5 rounds × 5 minutes = 25:00).
- During the workout:
  - The current exercise, the minute countdown and the total time left are shown in large type.
  - The screen is green during exercise minutes and blue during the cooldown minute.
  - The **last 10 seconds** of every minute switch to a big orange countdown with a beep each second, flashing red for the final 3.
  - Exercises can be announced out loud, and the number of **rounds completed** is shown on screen.
- When a workout finishes (or is ended early after at least a minute) the date, rounds completed and minutes are saved.

## Progress tracking

The **Progress** tab shows total workouts, rounds completed, workouts in the last 7 days, the current day streak,
a 14-day chart of rounds completed and a full workout log.

History is stored in the browser on the device you use (`localStorage`). Use **Copy history** to copy a backup you can paste into Notes,
and **Import pasted history** to restore it on another device.

## Running it

It's a single `index.html` file with no dependencies.

- **Locally:** open `index.html` in a browser.
- **Online:** enable GitHub Pages (Settings → Pages → Deploy from branch → `main` / root). The app will be at
  `https://<username>.github.io/workout-timer/`.

## Watching on a TV

1. Open the page on the iPad and tap **Start workout**.
2. Tap **Full screen** (where the browser supports it), or add the page to the Home Screen for a full-screen view.
3. Use **Screen Mirroring** from Control Center to an Apple TV or AirPlay-compatible TV. Beeps and announcements play through the TV.

Keyboard: press **Space** to pause or resume.
