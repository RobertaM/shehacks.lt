# SheHacks LT

Static one-page site for GitHub Pages at [shehacks.lt](https://shehacks.lt).

## Customize the content

- Confirmed events go in the `events` array near the bottom of `index.html`; multi-day events can use `endDate`.
- Journal entries go in the `posts` array in the same file.
- The visual palette is defined in the `:root` variables at the top of `index.html`.
- The site has no build step or external dependency: commit the files to the `main` branch and GitHub Pages can serve them directly.

The `CNAME` file is intentionally kept at the repository root for the custom domain.
