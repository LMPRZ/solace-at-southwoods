# Solace at Southwoods

Availability calendar website for Solace at Southwoods. View-only: guests check dates, then message to book.

## Update booked dates
Open `index.html`, find `OWNER SETTINGS` near the bottom, and edit the `booked` list:

```js
booked: [
  "2026-11-14",               // one night
  "2026-11-27 to 2026-11-29", // several nights (first and last night)
],
```

Delete a line to remove a booking. Commit the change and the site updates.

Also set `messageLink` there to your Messenger, Viber, WhatsApp or Instagram link.

## Publish with GitHub Pages
1. Create a new repository and upload `index.html` (and this README).
2. Go to Settings > Pages.
3. Under Build and deployment, choose Deploy from a branch, select `main` and `/ (root)`, then Save.
4. Your site goes live at `https://YOUR-USERNAME.github.io/REPO-NAME/` after a minute or two.
