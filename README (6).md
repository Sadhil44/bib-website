# Bhangra in the Burgh — Website

Static website for Bhangra in the Burgh (BIB), Pittsburgh's premier collegiate Bhangra competition, run by students at Carnegie Mellon University and the University of Pittsburgh.

## Pages

| File | Page |
|------|------|
| `index.html` | Home |
| `event.html` | Event details (BIB XX + Rangeela) |
| `history.html` | History, past winners, BIB 19 results |
| `board.html` | Board members |
| `impact.html` | Charity impact |
| `apply.html` | Team applications, FAQ, code of conduct |
| `sponsors.html` | Sponsorship tiers and past sponsors |

Each page is fully self-contained — fonts, logos, and photos are embedded as base64, so there are no external asset dependencies. Internal links are relative, so the site works when opened locally or served from any static host.

## Hosting on GitHub Pages

1. Push these files to a repository.
2. In the repo, go to **Settings → Pages**.
3. Under **Source**, select the branch (e.g. `main`) and the root folder.
4. Save. The site publishes at `https://<username>.github.io/<repo>/`.

`index.html` is the entry point.

## Notes

- **Fonts:** TAN Nimbus (display) and Garet (body) are embedded. Both are commercial fonts — verify your web license before public deployment.
- **Placeholders:** ticket and registration links currently point to Instagram until those go live.
- BIB XX: Saturday, January 23, 2027 · August Wilson African American Cultural Center, Pittsburgh, PA.
