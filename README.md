# Apps Legal

Privacy policies (and other legal pages) for Neel Studios apps, published with GitHub Pages.

## Layout

One folder per app, each with a `privacy.html`:

| App | Page | Public URL |
|---|---|---|
| MetaClean | `meta-clean/privacy.html` | https://nikhilfuge.github.io/apps-legal/meta-clean/privacy.html |

## Adding an app

1. Create a folder named after the app (lowercase, hyphenated), e.g. `my-app/`.
2. Add `my-app/privacy.html` as a self-contained page (inline CSS, no external scripts).
3. Commit to `main`; the page is served at `https://nikhilfuge.github.io/apps-legal/my-app/privacy.html`.
4. Use that URL in the app and in App Store Connect → App Privacy → Privacy Policy URL.

## Hosting

GitHub Pages → Deploy from a branch → `main`, folder `/ (root)`. `.nojekyll` makes Pages serve
files as they are.
