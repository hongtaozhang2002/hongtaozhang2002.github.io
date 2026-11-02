# Hongtao Zhang — Academic Homepage

Bilingual English / Chinese personal research website.

Live website: https://hongtaozhang2002-hash.github.io/

## Content

- Ph.D. introduction and affiliation, with research interests integrated into the biography
- Internship experience at Tencent Hunyuan and StepFun
- Seven publications in a single list
- Contact email
- GitHub and Google Scholar links
- Responsive layout, keyboard accessibility, and remembered language choice

Publication metadata was transcribed from the owner's Google Scholar profile on November 2, 2026:
https://scholar.google.com/citations?user=4bVA4qUAAAAJ

Conference labels reflect the Scholar profile. Preprints are labeled arXiv.

## Edit / 修改

The complete site is in `index.html`, including styles and scripts. No installation or build step is needed.

页面全部内容位于 `index.html`，无需安装依赖或运行构建。

- Bilingual text uses `data-en` / `data-zh` attributes. Update both attributes and the English text between the tags.
- Each publication is an `<article class="publication">`. Update titles, authors, URLs and badges there.
- Publications are maintained manually, not automatically synced.
- The seven papers remain visible when JavaScript is disabled. Language switching requires JavaScript.
- Keep `.nojekyll` in the repository root.

## GitHub Pages

Repository: `hongtaozhang2002-hash/hongtaozhang2002-hash.github.io`

In **Settings → Pages**, select **Deploy from a branch**, **main**, **/ (root)** and save.

The site uses no third-party scripts, external fonts, analytics, cookies, or secret keys. Language preference is stored only in the visitor's browser.
