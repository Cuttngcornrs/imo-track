# IMO Shortlist Tracker

A clean, minimal tracker for IMO Shortlist problems. It is designed to feel more like a calm productivity app than a spreadsheet, with soft colors, rounded cards, and an uncluttered layout that makes it easy to keep momentum while solving.

**Live site:** [https://cuttngcornrs.github.io/imo-track/](https://cuttngcornrs.github.io/imo-track/)

## What it is

This is a personal tracker for logging progress on IMO Shortlist problems across years and problem sets. You can mark each problem with your own custom status labels and colors, open a problem popup, and store notes or problem text locally on your device.

The layout is intentionally aesthetic and minimal so it stays pleasant to use over time.

## Features

* **Full shortlist grid** for every year in your chosen range
* **A, C, G, N problem categories** with boxes for **1–10** in each category
* **Custom year range** so you can choose the start and end years
* **Custom statuses** such as:

  * Not seen
  * Working on it
  * Done
  * Solution seen
  * or any labels you want
* **Custom colors** for each status
* **Clickable problem boxes** that open a popup
* **Problem notes / LaTeX box** for each problem
* **Optional source URL field** for links such as AoPS pages
* **Live LaTeX preview** in the popup
* **Search bar** to quickly find a problem by label
* **Automatic saving** in the browser using `localStorage`
* **Minimal aesthetic UI** with soft shadows, rounded corners, and a calm layout

## How saving works

The tracker saves progress in two ways:

* **Local browser storage** when you are not signed in
* **Google sync** when you sign in with Google

That means your progress can follow you across browsers and devices once you are signed in. If you are not signed in, your data stays on the current device/browser only.

## Important limitation

If you are using local browser storage, progress can still be lost if you:

* clear browser cache or site data
* use private/incognito mode
* switch to a different browser
* switch to a different device
* manually remove the site’s saved data

## Backup recommendation

For the safest experience, sign in with Google so your progress can sync instead of living only in browser storage.

## Notes

* The tracker is static and works on GitHub Pages.
* It is meant to stay lightweight and easy to maintain.

## Files

* `index.html` — the full tracker app
* `README.md` — this file

## Tech stac

* HTML
* CSS
* JavaScript
* GitHub Pages
* MathJax for LaTeX preview

## Contributing / customizing

This project is intentionally simple, so it is easy to customize:

* change the default statuses and colors
* adjust the year range and grid layout
* improve the popup or add more note fields
* connect problem sources more tightly if you later add a backend


