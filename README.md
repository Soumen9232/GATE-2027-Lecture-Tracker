# GATE 2027 Lecture Tracker v2

## Corrected setup
- Computer Networks: lecture 37 is the current point; 48 lectures remain; total = 85.
- Algorithms: separate subject with 40 lectures.
- Other subject totals are prefilled from the previous tracker and can be edited from **Edit subject totals / progress**.

## New features
- Timeline: Aug 11–Sep 30, 2026.
- Daily target (default 8).
- Automatic plan/day calculation from remaining lectures.
- Subject progress and lecture buttons.
- LocalStorage persistence.
- PWA manifest + service worker + 192/512 icons.
- Install-app button when the browser exposes the PWA install prompt.
- Notification permission button.
- Urgent in-app warning and optional beep when behind the daily target.

## Important alert limitation
A normal GitHub Pages PWA can beep while the app is open/active. Background reminders when the app is fully closed are not guaranteed by a simple JavaScript timer; reliable closed-app push notifications require a push backend/service. This version therefore avoids pretending that a closed-app beep is guaranteed.
