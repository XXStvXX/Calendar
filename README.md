# Calendar ICS Generator

A lightweight browser-based tool for generating `.ics` calendar files from flexible date inputs.

## Features

* Two input modes:

  * Paste date text (supports flexible formats)
  * Select dates by month
* Custom date order (YMD / DMY / MDY)
* Supports numeric and text months (e.g. `03`, `Mar`, `March`)
* All-day or timed events
* Instant `.ics` file download (no backend required)

## Demo

Live site: [https://xxstvxx.github.io/Calendar-ICS_generator/]

## Usage

1. Enter project name and description
2. Choose a date input mode
3. Provide dates (paste or select)
4. Click **Generate ICS File**
5. Import into your calendar app

## Supported Date Formats (Paste Mode)

Examples:

* `2026-05-12`
* `12/05/2026`
* `March 12 2026`
* `12 Mar 2026`

Supports separators like `- / _ . ,` and spaces.

## Tech Stack

* HTML
* CSS
* JavaScript (Vanilla)
* GitHub Pages (deployment)

## Notes

* No data is stored or sent — everything runs locally in your browser
* Designed for fast academic scheduling (assignments, exams, etc.)

## License

MIT
