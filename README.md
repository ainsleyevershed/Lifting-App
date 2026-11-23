# Lifting Log

A home-gym training app: hybrid 5×5 / 3×5 plans and a 30-minute fat-loss plan, automatic progression and deloads, warm-up sets, plate maths for the barbell, cable and Olympic dumbbells, rest timer, goals, bodyweight log and Gym Day import.

It runs entirely on your phone. Your data is saved on the device, so use **Settings → Back up (JSON)** regularly.

## Files

| File | What it is |
| --- | --- |
| `index.html` | The app |
| `manifest.json` | Name, colours and icons Android uses when you install it |
| `sw.js` | Lets the app open with no signal |
| `icons/` | App icons |

## Updating the app

1. Replace `index.html` with the new version.
2. In `sw.js`, change `lifting-log-v1` to the next number (`lifting-log-v2`, and so on).
3. Commit. GitHub Pages republishes within a couple of minutes, and the phone picks it up the next time the app opens with a signal.
