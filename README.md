# Renfei (Alex) Zhang — personal website

Academic homepage built on the [Minimal Light](https://github.com/yaoyao-liu/minimal-light) Jekyll theme.

## Publish on GitHub Pages

1. Create a public GitHub repository named `<your-github-username>.github.io`.
2. Upload everything in this folder to the repository's `main` branch (drag-and-drop in the GitHub web UI works).
3. In the repository, open **Settings → Pages**, set **Source** to "Deploy from a branch", choose `main` and `/ (root)`, and save.
4. After a minute or two the site is live at `https://<your-github-username>.github.io/`.

## Where to edit

| What | File |
|---|---|
| Name, position, email, profile links, photo | `_config.yml` |
| About Me, Research Interests, News | `index.md` |
| Publications (title, authors, venue, links, thumbnail) | `_data/publications.yml` |
| Profile photo and paper thumbnails | `assets/img/` |

Thumbnails are 1392 × 984 px (the theme shows them in a 174 × 123 box on desktop and a wider, shorter box on phones), with the figure centered on white so nothing important is cropped.

Optional links (GitHub, LinkedIn, CV PDF) are commented out in `_config.yml`; uncomment and fill them in to show the icons.

## Preview locally (optional)

```bash
bundle install
bundle exec jekyll serve
```

Then open http://localhost:4000.
