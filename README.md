# 📅 2027 Calendar &amp; Scheduler

A self-contained, printable **2027 calendar** with an **interactive scheduler** — pure HTML/CSS/JS, no dependencies, no server.

## Features

- **All 12 months** in a responsive grid (3 → 2 → 1 columns).
- **Per-month seasonal color themes** with an emoji and season label.
- **Seasonal background patterns** (CSS-generated): snowflakes for winter, petals for spring, sun rays for summer, falling leaves for autumn.
- **28 holiday dates** highlighted; floating dates (MLK Day, Memorial Day, Thanksgiving, Easter, solstices/equinoxes, etc.) are computed for 2027.
- **✨ Add your own schedule**: click any day to add, edit, and delete events (title, start/end time, notes, color).
- **Auto-save**: events are stored in your browser (`localStorage`) and persist between visits.
- **Export / Import**: back up your schedule to a JSON file and restore it anytime — handy for moving to another device or keeping a copy.
- **Print-friendly**: open in a browser and press `Ctrl/Cmd+P` to print or save as PDF (toolbar hidden when printing).
- Weeks start on **Monday**.

## Usage

Open `calendar-2027.html` in any browser.

**Adding events**
1. Click any day.
2. Enter a title (required), optional start/end time, notes, and pick a color.
3. Click **Add event**. A colored dot + label appears on that day.
4. Reopen the day to **edit** (✏️) or **delete** (🗑️) existing events.

**Toolbar**
- **⬇️ Export schedule** — downloads `calendar-2027-schedule.json`.
- **⬆️ Import schedule** — loads a previously exported file.
- **🗑️ Clear all** — removes every event (asks to confirm).

> 💡 Events save to the browser you're using. To move them to another computer, use **Export** then **Import** there.

To reuse the layout for another year, change `const YEAR = 2027;` in the script (note: holiday dates are hard-coded for 2027).

## Season themes

| Season | Months | Pattern |
|---|---|---|
| ❄️ Winter | Jan, Feb, Dec | Snowflake dots |
| 🌸 Spring | Mar, Apr, May | Petals + dots |
| ☀️ Summer | Jun, Jul, Aug | Sun-ray stripes |
| 🍁 Autumn | Sep, Oct, Nov | Falling-leaf dashes |
