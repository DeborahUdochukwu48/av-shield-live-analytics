# AV-Shield Live Analytics

A frontend prototype of a fleet operations console for autonomous-vehicle sensor-integrity work. It is a single static page that simulates live telemetry so you can review layout, status language, and event-log behavior without a backend.

Open `prototype.html` in a browser. There is no build step.

## What it shows

- Fleet size, sensors cleaned today, and rolling uptime
- A live event log with OK, WARN, and ALERT rows
- Simulated cleaning and diagnostic events (rain, dust, mud, frost, debris, fog, and similar sensor issues)
- A UTC clock and a sensors-cleaned counter that ticks as cleaning-related events appear

The numbers and log lines are generated in the browser. They are not connected to real vehicles.

## How to run

```bash
open prototype.html
```

Or drag `prototype.html` into Chrome, Safari, or Firefox. The page loads Tailwind CSS and fonts from public CDNs, so you need a network connection the first time.

## Stack

- HTML and vanilla JavaScript
- [Tailwind CSS](https://tailwindcss.com/) via CDN
- [Space Grotesk](https://fonts.google.com/specimen/Space+Grotesk) and [IBM Plex Mono](https://fonts.google.com/specimen/IBM+Plex+Mono) from Google Fonts

## Notes

This is a demonstration UI only. Do not treat the feed as operational data.
