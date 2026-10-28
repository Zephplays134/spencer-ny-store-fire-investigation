# Spencer NY Store Fire Investigation

An open case-file website tracking the investigation into the fire that destroyed the **Shurfine Food Mart, 15 N. Main St., Spencer, New York**, on **Friday, September 11, 2026**.

- The building was a total loss; staff evacuated safely and no injuries were reported.
- The origin and cause are under investigation by the **Tioga County Fire Investigation Team**; no cause has been announced as of the Oct 10, 2026 follow-up.
- The store was the village's only full-service grocery.

All facts on the site are drawn from published local news reports, linked in the Sources section.

## Run it

Everything (HTML, CSS, JS) lives in one file: `index.html`. Open it in a browser, or serve it:

```bash
python3 -m http.server 8000
# then open http://localhost:8000
```

## Updating the site

The case content is held in four JavaScript lists at the top of the `<script>` block in `index.html`: `FACTS`, `TIMELINE`, `UPDATES` and `SOURCES`. To add an update, add one object to `UPDATES` (newest first) and the page renders it automatically. No HTML edits needed.

## Structure

- `index.html` — the whole site: sticky nav, case summary, timeline, updates, emergency response, community impact, investigation status, sources, and a stats footer.

This is an independent community page, not an official source. It will be updated if and when official findings are released.
