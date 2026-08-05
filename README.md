# moosebuilds.github.io

Static site. No generator, no build step, no dependencies.

- `index.html` — post list
- `posts/*.html` — one file per post
- `style.css` — the whole design

To add a post: copy an existing file in `posts/`, change the content, add a line
to the list in `index.html`. Commit and push; GitHub Pages serves `master`.

Deliberately has no JavaScript, no webfonts, no analytics and no CSS animations.
