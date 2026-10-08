# Zhenhan Yin personal academic website

A static, single-page academic website designed for GitHub Pages. The homepage contains an introduction, research interests, selected publications, education, and public profile links.

## Local preview

From this directory, run `python -m http.server 8000` and open `http://localhost:8000`.

## Publish on GitHub Pages

1. Create a public repository named `zhenhanyin.github.io` in the `zhenhanyin` account.
2. Put the contents of this directory at the repository root. The entry file is `index.html`.
3. In repository **Settings → Pages**, select **Deploy from a branch**, choose `main` and `/(root)`, then save.
4. Visit `https://zhenhanyin.github.io/` after Pages finishes publishing.

Before publishing, review all copy and the portrait for public release. The source does not include the résumé, phone number, or private documents.

## Editing

- Change biography, publications, and links in `index.html`.
- Change visual styles in `styles.css`.
- Replace `portrait.jpg` to update the portrait.

The site has no build step or JavaScript dependencies. Google Fonts are optional; system fonts are used if they are unavailable.
