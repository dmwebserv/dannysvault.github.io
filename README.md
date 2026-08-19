# Danny's Vault

Danny's personal portfolio site: a small static HTML/CSS site showcasing
graphic and web design work.

## Structure

- `index.html` - home page
- `work.html` - project showcase
- `about.html` - about Danny
- `contact.html` - contact details
- `style.css` - shared styling for all pages
- `favicon.svg` / `apple-touch-icon.png` - site icons
- `og-image.png` - social share preview image
- `work-silverton.png` / `work-madingley.png` - project preview images used on `work.html`
- `robots.txt` / `sitemap.xml` - search engine crawling and indexing

No build step, framework, or dependencies are used. It's plain HTML and CSS.

## Previewing changes locally

Open any of the `.html` files directly in a browser, or serve the folder
with a simple local server, for example:

```
python3 -m http.server 8000
```

Then visit `http://localhost:8000/` in your browser.

## Deploying

This site is deployed via GitHub Pages from this repository. Pushing changes
to the default branch (`main`) is picked up automatically by GitHub Pages
and published at https://dannysvault.github.io/. There is no separate build
or deploy step.
