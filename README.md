# threads-board

A static dashboard of my Threads posts ([@tsun.tw](https://www.threads.com/@tsun.tw)): a contribution-style posting calendar, monthly totals and a sortable list of every thread.

## What's inside

- `index.html` — the page (plain HTML + d3 from cdnjs, no build step)
- `data/threads_posts.json` — one row per thread (a self-thread counts once; numbers are from its first post), captured on 2026-10-10

## Run locally

The page loads its data with `fetch`, so serve the folder instead of opening the file directly:

```sh
python3 -m http.server 8000
# then open http://localhost:8000
```

It also works as-is on GitHub Pages.
