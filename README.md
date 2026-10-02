# RawManor Website

Static website for RawManor, publisher of focused, private apps. RawIron Log is the first app.

## Files

- `index.html` — RawManor home page (apps overview, featuring RawIron Log)
- `styles.css` — RawManor styles. The brand palette ("Graphite & Iron Red") in `:root` is shared with the RawIron Log app (`Resources/Styles/Colors.xaml`); keep them in sync. The red bar before each `.eyebrow` is the shared brand signature.
- `images/` — RawManor mark (`rawmanor-mark.svg`, from `_proposals/digital-product-icons/05-raw-mark.svg`), tab icon, and iOS home-screen icon
- `rawironlog/` — RawIron Log landing, support, privacy, and terms pages (see `rawironlog/README.md`)
- `_proposals/` — design drafts; not published by GitHub Pages while Jekyll is enabled

## Local testing

Press F5 in VS Code. It starts a local server on port 8081 and opens Chrome.

## Before publishing

1. Complete the checklist in `rawironlog/README.md`.
2. Replace the placeholder RawManor mark with a final logo when one is designed.
3. Push to a public GitHub repository and enable GitHub Pages from the `main` branch and `/ (root)` folder.
