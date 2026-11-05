# Jamiat Al Ansar website

The website for [jamiatalansar.ca](https://jamiatalansar.ca), hosted on GitHub Pages.

The site was moved here from Unicorn Platform. It's plain HTML with no build step: whatever is on `main` goes live within a minute or two.

## Layout

- `index.html` is the homepage
- Each other page has its own folder with an `index.html` inside (`jumuah/`, `services/`, `sisters/`, and so on)
- `assets/img/` holds the images
- `assets/unicorn/` holds the original Unicorn Platform CSS and JS, which the pages still use for styling and menus
- `CNAME` sets the custom domain. Don't delete it.

## Editing

Edit the HTML, then commit and push to `main`. Links between pages are relative (`../jumuah/`), so keep new links in that style.

## Domain

DNS is managed at GoDaddy: 4 GitHub A records on `@` and a `www` CNAME to `abdullahelqabbany.github.io`. Leave the Google Workspace MX and SPF records as they are.
