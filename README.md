# Bob CRM — Landing Page

Public landing page for **Bob**, a personal network management system (NMS) built with Claude Code.

**Live:** https://rkroft.github.io/bob-crm-landing/

## What this is

A single, self-contained marketing page (`index.html`) — no build step, no dependencies. It tells the story of Bob: who introduced whom, what those intros became, and who's owed a hello. Brand and styling match the Bob wordmark (lowercase `bob.` in Fraunces italic, coral palette `#d65b3c`).

## Structure

| File | Purpose |
| --- | --- |
| `index.html` | The entire page — HTML, CSS, and inline JS in one file |
| `bob-avatar.png` | Bob avatar asset |

## Hosting & deploy

- Hosted on **GitHub Pages** from the `main` branch, root path.
- **Deploy = push to `main`.** Pages rebuilds automatically (~1 minute), then serves the update.

```bash
git add index.html
git commit -m "…"
git push origin main
```

## Analytics

Uses **[GoatCounter](https://www.goatcounter.com/)** — privacy-friendly, no cookies, no consent banner required.

- Beacon (in `<head>` of `index.html`):
  ```html
  <script data-goatcounter="https://bob-crm.goatcounter.com/count"
          async src="//gc.zgo.at/count.js"></script>
  ```
- Dashboard: **https://bob-crm.goatcounter.com** (site code `bob-crm`).

> **Note:** Some networks and browsers DNS-block analytics domains (`gc.zgo.at`, `goatcounter.com`). On such a network your own visits won't be counted and the dashboard may fail to load — this is a client-side blocker, not a problem with the page. Visitors on normal networks are counted correctly. To verify or view stats, use a network without a tracker-blocker (e.g. cellular).

## License

Personal project — all rights reserved.
