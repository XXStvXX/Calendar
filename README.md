# Calendar ICS Generator
# UTSC Course Calendar ICS Generator

A lightweight browser-based tool for generating `.ics` calendar files from flexible date inputs.
A lightweight browser-based tool for building a Summer 2026 UTSC course calendar and downloading it as an `.ics` file.

## Features

* Two input modes:

  * Paste date text (supports flexible formats)
  * Select dates by month
* Custom date order (YMD / DMY / MDY)
* Supports numeric and text months (e.g. `03`, `Mar`, `March`)
* All-day or timed events
* Instant `.ics` file download (no backend required)
* Shows UTSC Summer 2026 academic dates before the form:
  * first sub-session (`fss`)
  * second sub-session (`sss`)
  * full session (`fs`)
  * reading week (`rw`)
  * first sub-session final period (`fss_fp`)
  * second sub-session final period (`sss_fp`)
  * full session final period (`fs_fp`)
* Course-level workflow that prevents mixing different course codes in one ICS calendar.
* Add multiple course items such as projects, assignments, presentations, exams, and reports.
* Each event description can include grade weight, notes, room/location, and a link.
* Two date input modes:
  * Paste flexible dates, including newline-separated, comma-separated, or glued strings.
  * Pick recurring weekdays inside the selected Summer session (`fss`, `sss`, or `fs`).
* All-day or timed events.
* Instant `.ics` file download with no backend required.

## Demo

Live site: [https://xxstvxx.github.io/Calendar-ICS_generator/]

## Usage

1. Enter project name and description
2. Choose a date input mode
3. Provide dates (paste or select)
4. Click **Generate ICS File**
5. Import into your calendar app
1. Review the Summer 2026 Academic Date panel.
2. Enter course name, course code, and course session.
3. Enter one item name, grade weight, notes, room/location, and link.
4. Choose event time settings.
5. Provide dates by either pasting dates or selecting recurring weekdays in the selected session.
6. Click **添加到课程日历** to add this item to the current course calendar.
7. Repeat steps 3–6 for additional items in the same course.
8. Click **完成课程日历并下载 ICS** to download the whole course calendar.

## Supported Date Formats (Paste Mode)
## Supported Paste Date Formats

Examples:

* `2026-05-12`
* `12/05/2026`
* `March 12 2026`
* `12 Mar 2026`

Supports separators like `- / _ . ,` and spaces.
* `2026/05/12`
* `20260512`
* `May 12 2026`
* `12 May 2026`
* `2026-05-122026-05-19` (glued dates are accepted)

## Tech Stack

* HTML
* CSS
* JavaScript (Vanilla)
* GitHub Pages (deployment)

## Notes

* No data is stored or sent — everything runs locally in your browser
* Designed for fast academic scheduling (assignments, exams, etc.)
* No data is stored or sent — everything runs locally in your browser.
* Recurring weekday generation is currently scoped to UTSC Summer 2026 course sessions only.

## License

MIT
