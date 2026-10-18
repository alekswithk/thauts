# thauts

A small, dependency-free blog published with GitHub Pages.

## Publish a new post

1. Copy `posts/second-brain-university/` to `posts/your-post-slug/`.
2. Replace the article title, description, date, reading time, and body in its `index.html`.
3. Add the post to the Writing section in `index.html`.
4. Commit and push to `main`. The GitHub Pages workflow publishes the site automatically.

Shared colors, type, and layouts live in `assets/css/style.css`. Shared theme and reading-progress behavior lives in `assets/js/main.js`.

To preview locally, run `python3 -m http.server` in the repository and open `http://localhost:8000`.
