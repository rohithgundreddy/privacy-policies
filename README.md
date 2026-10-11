# Privacy policies — Nova Celeste Game Studio

Static GitHub Pages site hosting the privacy policy for every game we publish.
Store listings (Google Play, App Store) link to these pages.

Live site: https://rohithgundreddy.github.io/privacy-policies/

| Game | Page |
|---|---|
| Neon Swarm | https://rohithgundreddy.github.io/privacy-policies/neon-swarm.html |

## Adding a new game

1. Copy `template.html` to `<game-slug>.html` (lowercase, hyphens).
2. Replace `GAME NAME`, the effective date, and keep only the "Data we collect" paragraph that is true for the game. Add any extra permissions.
3. Add a row to the list in `index.html` and to the table above.
4. Commit and push to `main`. Pages redeploys in about a minute.
5. Paste the page URL into the store console and into the game's in-app Privacy Policy link.

## Updating a policy

Edit the page, bump the *Effective* date, push. If the change adds data collection,
also update the store's Data Safety form and mention it in the release notes.

No build step, no Jekyll (`.nojekyll` is present). Plain HTML + one stylesheet.
