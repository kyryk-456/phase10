# 🎴 Phase 10 Tracker

A clean, mobile-friendly score and phase tracker for the card game Phase 10. Built as a single HTML file — no installation, no app store, no account required.

## Features

- **2–6 players** — dynamically add players with unique color themes
- **Score tracking** — add points each round with a running total
- **Phase progress** — visual 5×2 badge grid showing completed, current, and upcoming phases
- **Phase reference** — full table of all 10 phases visible at a glance
- **Winner detection** — automatically crowns the winner when all 10 phases are complete (lowest score wins ties)
- **Confetti** — a burst of confetti fires when a winner is declared 🎉
- **Undo** — reverse the last score addition or phase advance, up to 50 steps back
- **Auto-save** — game state is saved automatically so closing and reopening picks up where you left off
- **Light & dark mode** — toggle between themes, preference is remembered between sessions
- **Responsive layout** — scales gracefully from desktop down to mobile
- **iPhone home screen support** — add to your home screen in Safari for a native app feel

## The 10 Phases

| # | Phase |
|---|-------|
| 1 | 2 sets of 3 |
| 2 | 1 set of 3 + 1 run of 4 |
| 3 | 1 set of 4 + 1 run of 4 |
| 4 | 1 run of 7 |
| 5 | 1 run of 8 |
| 6 | 1 run of 9 |
| 7 | 2 sets of 4 |
| 8 | 7 cards of one color |
| 9 | 1 set of 5 + 1 set of 2 |
| 10 | 1 set of 5 + 1 set of 3 |

## How to Use

1. Select the number of players at the top
2. Tap a player name to rename it
3. After each round, enter the points scored and tap **+ Add**
4. When a player completes their current phase, tap **✓ Complete Phase**
5. Use **↩ Undo** to reverse a mistake, or **↺ Reset Game** to start fresh
6. The winner is declared (with confetti!) when someone finishes all 10 phases

## Add to iPhone Home Screen

1. Open the [live app](https://kyryk-456.github.io/phase10) in **Safari**
2. Tap the Share button (box with arrow)
3. Tap **Add to Home Screen**
4. Tap **Add** — it'll appear as an icon and launch full screen

## Tech

Pure HTML, CSS, and JavaScript. Uses React via CDN and Google Fonts — no build tools, no dependencies, no tracking.
