# DayFlow QA checklist

## Desktop and mobile

- [ ] Navigate Today, Tasks, Calendar, Habits, Insights, Focus, Settings
- [ ] Verify desktop sidebar and mobile bottom tabs / floating add button
- [ ] Add, edit, complete, uncomplete and delete a task
- [ ] Verify high/medium/low priority, categories and optional time
- [ ] Verify task text and notes render safely
- [ ] Verify one-time vs recurring daily/weekdays/weekly/monthly task occurrences
- [ ] Verify completion history is independent for each occurrence
- [ ] Create a habit and toggle its daily completion
- [ ] Move across calendar months and select a day
- [ ] Use task search and status filters
- [ ] Start, pause and reset Focus timer
- [ ] Test light and dark themes
- [ ] Export and restore JSON backup
- [ ] Refresh and confirm browser-saved data persists
- [ ] Install the PWA and reopen it offline after an online visit
- [ ] Test Android Chrome and desktop Chrome/Edge

## Known v1 limitations

No real-time sync between devices, push notifications, AI day planning or cloud backup. Focus timer is subject to browser background throttling. Data resides in browser storage; export backups regularly. Source-level syntax validated, but automated browser end-to-end and physical-device tests remain outstanding.

## v2 regression checks

- [ ] Quick capture: create plain task and phrases `tomorrow 8pm`, `today 18:30`, `next week`
- [ ] Verify priority spotlight shows a pending task and Done completes it
- [ ] Verify overdue single-occurrence items show in Needs your attention and can move to today
- [ ] Verify completed historical occurrences are not accidentally moved
- [ ] Verify last-seven-day completion overview updates after checking off a task
- [ ] Confirm old v1 browser task records remain after update and offline refresh
- [ ] Verify dark mode contrast, narrow 320 px layout, keyboard navigation and reduced-motion setting
