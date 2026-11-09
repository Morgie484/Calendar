# 📅 2027 Calendar

A self-contained, printable **2027 calendar template** — pure HTML/CSS/JS, no dependencies.

## Features

- **All 12 months** in a responsive grid (3 → 2 → 1 columns).
- **Per-month seasonal color themes** with an emoji and season label.
- **Seasonal background patterns** (CSS-generated): snowflakes for winter, petals for spring, sun rays for summer, falling leaves for autumn.
- **28 holiday dates** highlighted as colored pills — hover any one for its name. Floating dates (MLK Day, Memorial Day, Thanksgiving, Easter, solstices/equinoxes, etc.) are computed for 2027.
- **Print-friendly**: open in a browser and press `Ctrl/Cmd+P` to print or save as PDF.
- Weeks start on **Monday**.

## Usage

Open `calendar-2027.html` in any browser. To reuse for another year, change `const YEAR = 2027;` in the script (note: holiday dates are hard-coded for 2027).

## Season themes

| Season | Months | Pattern |
|---|---|---|
| ❄️ Winter | Jan, Feb, Dec | Snowflake dots |
| 🌸 Spring | Mar, Apr, May | Petals + dots |
| ☀️ Summer | Jun, Jul, Aug | Sun-ray stripes |
| 🍁 Autumn | Sep, Oct, Nov | Falling-leaf dashes |
