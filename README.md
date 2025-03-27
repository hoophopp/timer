JavaScript Timer – README
About This Project
This is a simple stopwatch built with JavaScript. It tracks time, allows pausing and resuming, and saves lap times. The timer progress is also stored, so it remains even after refreshing the page.

Features
Start, Pause & Resume – Click "Start" to begin, "Pause" to stop, and "Resume" to continue.

Reset Timer – Resets everything back to 00:00.

Lap Feature – Saves timestamps while the timer is running.

Saves Progress – The timer and lap records are stored in LocalStorage, so they are not lost on refresh.

How It Works
When you click Start, the timer begins using setInterval().

Pause stops it without resetting. Click Resume to continue counting.

Reset clears everything and starts fresh.

Clicking Save Lap adds the current time to a list, which is saved in LocalStorage.

What I Used
JavaScript for timing, event handling, and local storage.

HTML & CSS for the layout and styling.

Future Plans
Add a countdown mode.

Play a sound every minute.

Improve the UI with animations.

This project is simple but functional, and it keeps track of time efficiently.
