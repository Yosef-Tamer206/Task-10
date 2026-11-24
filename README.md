# COSMOS - Space Dashboard

A space exploration dashboard with live data: NASA's astronomy picture of the day, upcoming rocket launches and a planets explorer.

**Live demo:** https://yosef-tamer206.github.io/Task-10/

## Features

- NASA Astronomy Picture of the Day with a date picker and "open image" view
- Upcoming launch list with countdown details, formatted dates and times
- Planets explorer with per-planet detail cards
- Planet comparison view, including km-to-AU distance conversion
- Responsive dashboard layout

## Tech Stack

- HTML5, CSS3, vanilla JavaScript
- Tailwind CSS
- APIs: NASA APOD, Launch Library 2 (The Space Devs), Solar System OpenData

## Run Locally

```bash
git clone https://github.com/Yosef-Tamer206/Task-10.git
cd Task-10
```

Open `index.html` in a browser. An internet connection is required for live data.

## Notes

- The NASA API key is currently committed in the source. Moving it to NASA's public `DEMO_KEY` or a config file is a good next step.
- If the APOD section shows "Invalid Date", the shared API key has likely hit its usage limit for the day.
