# N50 site with live cameras (preview)

Review copy of the North 50 Building Systems site. Not the live site. Set to stay out of search engines.

The home page keeps the lab readings. Its "Open the full lab dashboard" button opens `lab/`, the dashboard page, which carries the V Wall and L Wall live cameras.

Cameras: Cloudflare Stream, live-only WebRTC, muted. They start when the dashboard loads, and stop after 10 minutes without activity or while the tab is hidden, with a Keep watching button. Viewing hours daily 7:00 AM to 5:00 PM Alaska time (one setting, `SCHED`, in `lab/index.html`). Outside those hours the page shows the offline message. Add `?camtest=1` to the address to ignore the schedule while testing.

Only public playback IDs are in these pages. No publishing addresses, keys or tokens.
