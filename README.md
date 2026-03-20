# Gym Reference Card

A minimal, installable PWA gym reference card. Tap a tier, do the work, leave.

**Live:** [alexghanem.github.io/gym-routine](https://alexghanem.github.io/gym-routine/)

## What it is

A single-page web app / installable PWA with four workout tiers:

| Tab             | Purpose                                                |
| --------------- | ------------------------------------------------------ |
| **Floor**       | Worst-case session — cardio only, ~35 min              |
| **Day A: Push** | Bench, OHP, laterals + rower, ~55 min                  |
| **Day B: Pull** | Lat pulldown, cable row, face pull + rower, ~55 min    |
| **Day C: Legs** | Hex bar deadlift, leg press, leg curl + rower, ~55 min |
| **Restart**     | Protocol for returning after any gap > 1 week          |

## Install as an app

On iPhone: open in Safari → Share → **Add to Home Screen**
On Android: open in Chrome → menu → **Add to Home Screen**
On desktop: click the install icon in the address bar

## Development

No build step. Edit `index.html` directly.

```sh
# Preview locally
open index.html
# or
npx serve .
```

Push to `main` and GitHub Actions deploys to GitHub Pages automatically.
