# Tiny Wins: an ADHD-friendly to-do app

A simple to-do app that runs on your phone. It's built around the hard parts of ADHD: **starting**, **finishing**, and **feeling like you made progress**.

## How it works

1. **Brain dump.** Type anything into the box at the top and hit Add. Don't sort it, just get it out of your head.
2. **Pick 3 for today.** Star ☆ up to three tasks. The cap of three is deliberate, because a short list is one you can actually finish.
3. **Break it down.** Tap a task to add tiny steps. If a step would take more than about 15 minutes, split it again. Starter chips like "Open / find what I need" help when you're stuck on the first move.
4. **Focus.** Press ▶ (or "🎲 Pick for me" if you can't decide). You'll see **only the next step**. Choose a time window: 2 min ("just start"), 5, 10, 15 or 25.
5. **When the timer ends**, choose Done, +5 min, Split it, or Stop. Stopping still earns XP for showing up.
6. **Celebrate.** Every step and task you finish gives you confetti, a chime, XP, a daily-goal ring, a streak, levels and a **Done list** of everything you've completed.

Finished tasks leave your list and go to the Done list. Tasks you decide not to do can be deleted ("Let it go"), with Undo in case you change your mind.

## Running it

It's one HTML file with no build step and no account. Your data stays in your browser on that device.

- **On a computer:** open `index.html` in a browser.
- **On your iPhone (recommended):** host it via GitHub Pages (repo **Settings → Pages → Deploy from branch**), open the URL in Safari, then use **Share → Add to Home Screen**. It then works like an app, including offline.

Use **Wins → Export backup** now and then. Data lives on one device and is lost if you clear Safari's website data.

## Files

- `index.html`: the whole app (UI, logic, styles)
- `manifest.json`, `sw.js`, `icon*`: these let it install to your home screen and work offline
