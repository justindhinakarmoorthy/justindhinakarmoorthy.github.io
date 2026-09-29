# justindhinakarmoorthy.github.io

Personal site of Justin Dhinakar Moorthy: https://justindhinakarmoorthy.github.io

Plain HTML, CSS and JavaScript. No build step.

## Where to edit

| What | File |
| --- | --- |
| Intro, experience, links | `index.html` |
| Project cards | `data/projects.json` |
| Articles list | `data/articles.json` |
| Colours and layout | `css/styles.css` |

## Adding an article

1. Put the article page in its own folder, e.g. `articles/my-article/index.html`.
2. Add an entry to `data/articles.json` with `title`, `url` (e.g. `articles/my-article/`), `date` (`YYYY-MM-DD`), `displayDate` (e.g. `OCT 2026`) and `excerpt`.

## Publishing

Every push to `main` runs the **Deploy site** workflow, which copies the site to the `gh-pages` branch. GitHub Pages serves that branch.

The earlier al-folio (Jekyll) version of the site is kept on the `al-folio-backup` branch.

## Credits

Design based on the [Minimal Portfolio Template](https://github.com/ganeshkumarm1/ganeshkumarm1.github.io) by Ganesh Kumar Marimuthu, used under the MIT License (see `License.md`).
