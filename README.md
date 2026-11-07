# DayFlow

Mobile-first, offline-capable personal daily planner hosted on GitHub Pages.

Features: tasks, recurring routines, habits, calendar, focus timer, insights, light/dark mode, and browser-local backups.

## Launch
Go to Settings → Pages → Deploy from branch → `main` / `(root)`.

Expected URL: https://roogle2000rohith.github.io/dayflow/

Personal data is stored in your browser on each device; GitHub only hosts the application. Export backups regularly. Cross-device sync is not enabled.

## DayFlow Studio v2 — UI & planning upgrade

- Refined visual design with more consistent typography, spacing, dark-mode surfaces, contrast, touch states and reduced-motion support.
- Fast capture on Today and Tasks: parses `today`, `tomorrow`, `next week`, `8pm`, and `18:30` in simple inputs. This is intentionally rule-based, not AI, and only supports the documented patterns.
- Next-move card prioritizes the highest-priority incomplete task for the selected day.
- Past-due one-time tasks can be moved to today with one tap. Existing completed recurring occurrences remain intact.
- Last-seven-days completion overview on the Today dashboard.
- Cache bumped to v2 for installed PWA updates.

### Known limitations

The app stores data locally in the browser. No cloud account, sync, background push reminders, or full natural-language parsing yet. Repeating tasks remain based on their start date and built-in recurrence choices. Run the QA checklist on your own phone and browser before relying on it for important deadlines.
