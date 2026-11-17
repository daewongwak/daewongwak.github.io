# Daewon Gwak — Academic Homepage (v5)

Classic, lightweight Jekyll academic homepage for `daewongwak.github.io`.

## Publish on GitHub Pages

1. Create a **public** GitHub repository named `daewongwak.github.io` under user `daewongwak`.
2. Unzip the archive on your computer and upload **its contents**, not the ZIP and not an extra top-level folder, to the repository root. Include `_data/`, `_includes/`, `assets/`, `index.html`, and `_config.yml`.
3. Commit the files to the `main` branch.
4. In **Settings → Pages**, set **Build and deployment → Source → Deploy from a branch**, Branch `main`, Folder `/(root)`, then save.
5. Visit `https://daewongwak.github.io` after deployment.

The `index.html` file has Jekyll front matter, so GitHub Pages will process its Liquid tags and Markdown-formatted About text. Do not add a `.nojekyll` file.

## Edit content

- `_data/about.yml`: About introduction and research interests. Each item under `paragraphs` is its own paragraph; Markdown links work.
- `_data/publications.yml`: Paper titles, authors, venues, links (add CollabBank Paper URL once it becomes public).
- `_data/awards.yml`: Scholarship and awards.
- `_data/service.yml`: Conference service venues and years.
- `_config.yml`: Site URL, name, email, basic profile metadata.
- `index.html`: Page layout and education section.
- `assets/css/style.css`: Styling.

## Before sharing publicly

- Confirm that the ETRI award subtitle matches the certificate.
- Verify any external reviewer role is suitable to represent publicly (official registration versus consultation with a formally appointed reviewer).
- CollabBank paper URL is intentionally empty until available.
- Domestic conference papers, campus awards, and social profile links are intentionally omitted.
