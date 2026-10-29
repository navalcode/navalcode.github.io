# GitHub Pages resources

[Español](README.es.md) · [Personal website](https://navalcode.github.io/personal-website/) · [GitHub profile](https://github.com/navalcode)

Static resources used by app association, privacy policies and authentication examples. The personal website is maintained in [personal-website](https://github.com/navalcode/personal-website).

| Path | Purpose |
|---|---|
| `.well-known/assetlinks.json` | Android app association data |
| `privacy/` | Application privacy pages |
| `app-ads.txt` | Existing app advertising declaration |
| `AuthFromServer.json`, `RegFromServer`, `index.html` | Existing authentication example resources |
| `portfolio/` | Compatibility redirects for earlier personal website URLs |

GitHub Pages serves `main` from the repository root at `https://navalcode.github.io/`. The previous custom domain has been retired. App configurations that still use the previous hostname need their own migration; preserving these files does not update installed applications.

Existing application resources retain their content and history. Changes to app association or service configuration should be reviewed against the application that consumes them.
