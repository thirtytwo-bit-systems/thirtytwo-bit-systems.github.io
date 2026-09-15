<img src="https://www.thirtytwobit.systems/assets/logo/32bs-appicon-leads.svg" width="88" alt="Thirtytwo Bit Systems">

# thirtytwobit.systems

The Thirtytwo Bit Systems website. Static HTML and CSS, no build step, served
by GitHub Pages at **[www.thirtytwobit.systems](https://www.thirtytwobit.systems)**.

## Layout

```
index.html          the whole site, one page
styles.css          all of its styling
assets/logo/        brand kit - the canonical copy (see its own README)
CNAME               custom domain
```

## Working on it

There is nothing to install and nothing to compile. Serve the folder and open it:

```sh
python3 -m http.server 8000
```

Google Fonts is the only external request the page makes; everything else is
local.

## Brand assets

`assets/logo/` is the single home for the logo in every variant - mark, inverse,
mono, small, app icons and lockups, plus PNG renders and favicons.
[`assets/logo/README.md`](assets/logo/README.md) says which file to use when.
Do not copy these elsewhere; link to them.

## Deploying

Merging to `main` publishes. GitHub Pages rebuilds within a minute or so, and
the CDN holds the old page for up to ten minutes after that.

## Contact

**hello@thirtytwobit.systems** · +91 8050728498
Bengaluru, India
