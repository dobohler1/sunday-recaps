# Sunday Recaps

Static site (GitHub Pages) with short sermon summaries, a recap written for young men, and a reflection activity.

## Structure

```
index.html                         sermon index (one card per Sunday)
assets/site.css                    shared stylesheet
sermons/YYYY-MM-DD-slug/index.html sermon page: title links to recap.html, plus a summary
sermons/YYYY-MM-DD-slug/recap.html recap for young men + activity (answers stay in the browser)
```

## Adding a Sunday

1. Copy `sermons/2026-10-25-promise-keeper/` to a new dated folder.
2. Edit `index.html` (summary) and `recap.html` (recap + questions) in that folder.
3. Add a card to the top of the list in the root `index.html`.

Activity answers are kept in `localStorage` only; "Copy my answers" formats them for a text message. Nothing is sent anywhere.
