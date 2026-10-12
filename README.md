# TimeMafia — Date & Time Tools

A lightweight static website for GitHub Pages with four categories: Time Utilities, Countdowns, Date Calculators, and Year Planning.

## Publish on GitHub Pages
1. Upload the contents of this folder to a GitHub repository, keeping `index.html` at the repository root.
2. Open **Settings → Pages** and choose **Deploy from a branch**, `main`, and `/(root)`.
3. Save and wait for GitHub Pages to publish the site.

## Included tools
- Date difference calculator
- Add or subtract days from a date
- Days until a date, including elapsed days for past dates
- Time until a clock time
- Time-zone converter
- Leap-year checker
- Day-of-year calculator

All calculator logic is in `assets/app.js`; styles are in `assets/style.css`. Inputs are processed in the browser. One contextual external reference appears on the homepage only.

## Notes
This is a static site with no backend. Date calculations use the visitor's device date and local calendar. Verify time-zone conversions around daylight-saving transitions when precision is critical.
