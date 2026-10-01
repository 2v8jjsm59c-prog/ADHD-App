# Tiny Wins: an ADHD-friendly to-do app

A simple to-do app that runs on your phone. It's built around the hard parts of ADHD: **starting**, **finishing**, and **feeling like you made progress**.

## How it works

The app is designed mainly around **starting**, because that's where things get stuck.

1. **Brain dump.** Type anything into the box and hit Add. Don't sort it, just get it out of your head.
2. **The purple card picks for you.** The top of the screen always shows *one* next tiny step, with a big **🚀 Start: 2 min** button. You don't have to decide what to do; tap "Not this one" to see a different task.
3. **Vague tasks get a first physical move.** If a task has no steps yet, the app asks *"What's the very first physical move?"* (open the laptop, find the document, pick up the phone…) and then launches it.
4. **3-2-1, go.** A short countdown and then a 2-minute timer. Starting earns XP and counts towards your streak, so you're rewarded for starting, not just for finishing.
5. **After 2 minutes:** "That was the hard part. Ride the momentum?" Choose **Keep going: 10 min**, Done, or Stop. Stopping after you've started is fine.
6. **🧱 I'm stuck** asks *why* and responds to the reason:
   - too big → make the first step smaller
   - not sure where to begin → a 2-minute "work out the first move" step
   - dreading it → only the first 2 minutes
   - boring → race a 10-minute clock
   - no energy → swap to a different task
7. **Prioritise (optional).** Open a task and rate it with one tap each: **Importance** (Low/Medium/High), **Urgency** (Whenever/This week/ASAP) and **Effort** (Quick/Medium/Big). Tap a rating again to clear it; unrated counts as medium. Use **Sort by** to order the list:
   - **Smart** (default): importance + urgency, with a nudge towards quick tasks
   - Most important / Most urgent / Easiest first
   - **Quick wins**: important *and* easy
   - Oldest / Newest

   The Start card follows your sort, so choosing "Easiest first" on a low-energy evening makes it suggest easy tasks. In "I'm stuck", **No energy** jumps straight to your easiest task.
8. **Pick 3 for today.** Star ☆ up to three tasks; these come first on the Start card.
9. **Celebrate.** Confetti, chimes, XP, a daily-goal ring, a streak, levels, and a **Done list** that shows what you started (🚀) and finished (✅ 🏁).

Finished tasks leave your list. Tasks you decide not to do can be deleted ("Let it go"), with Undo.

## Running it

It's one HTML file with no build step and no account. Your data stays in your browser on that device.

- **On a computer:** open `index.html` in a browser.
- **On your iPhone (recommended):** host it via GitHub Pages (repo **Settings → Pages → Deploy from branch**), open the URL in Safari, then use **Share → Add to Home Screen**. It then works like an app, including offline.

Use **Wins → Export backup** now and then. Data lives on one device and is lost if you clear Safari's website data.

## Files

- `index.html`: the whole app (UI, logic, styles)
- `manifest.json`, `sw.js`, `icon*`: these let it install to your home screen and work offline
