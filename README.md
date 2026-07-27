# ashley-site

Personal website and blog for Ashley Mitchell. Plain HTML/CSS, hosted on GitHub Pages.

## Structure

- `index.html` — landing page (bio, recent writing, links)
- `blog/index.html` — full post list
- `blog/*.html` — individual posts
- `css/style.css` — the one stylesheet (light + dark mode)
- `img/` — images

## Adding a blog post

1. Copy `blog/hello-world.html` to `blog/your-post-slug.html`
2. Update its `<title>`, `<h1>`, date, and content
3. Add a line to the list in `blog/index.html` (newest first)
4. Optionally add it to the "Writing" list on `index.html`
5. Commit and push — GitHub Pages redeploys automatically

## Local preview

Open `index.html` in a browser, or run `python3 -m http.server` in this folder
and visit http://localhost:8000.
