This folder is the standalone website source.

There is no Hugo build required for normal edits anymore.

Edit these files directly:

- `index.html` for the homepage
- `css/resume.css` for shared styling
- `js/resume.js` for homepage interactions
- other `*.html` files for section and article pages
- `img/` and `files/` for assets

Deployment assumption:

- the published site is served directly from the contents of `public/`

Notes:

- the older Hugo source folders still exist in the parent project, but they are no longer needed for routine website updates
- if you keep using GitHub Pages from this folder or branch, pushing changes here is enough
