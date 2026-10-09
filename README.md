# Zhenhan Yin academic homepage

Published at https://zhenhanyin.github.io/ from the public GitHub repository https://github.com/zhenhanyin/zhenhanyin.github.io.

The site is plain HTML and CSS. Navigation links scroll to sections of the page, and the publication and profile links open external sites. It has no backend, build step, or JavaScript dependency.

## Local preview

Run `python -m http.server 8000` in this directory and open `http://localhost:8000`.

## Editing

- Update biography, publications, awards, patents, profile links, and metadata in `index.html`.
- Update layout, typography, and responsive styles in `styles.css`.
- The deployed page embeds the portrait in `index.html`. To change it, replace the image data URI in the portrait `src`; `portrait.jpg` is a local source copy.
- Sidebar icons are stored in `assets/icons/`. The location, mail, and GitHub icons are from Bootstrap Icons under the included MIT license; the Hugging Face logo is from Hugging Face.
- Publication thumbnails in `assets/publications/` are local copies of model figures from the [Magic-W0 project page](https://embodied.magiclab.top/works/wam/magic-w0/index.html), the [WSA₁ project page](https://zaleni.github.io/TBot-SA1/), and Figure 2 on the [MiVLA project page](https://mivla-research.github.io/). Each thumbnail opens its full-size figure.

The site does not include the résumé, phone number, or private documents.
