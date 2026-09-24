# hashim-hassan.com (v2)

Static HTML/CSS. No build step. Open any `.html` file in a browser to preview.

## Pages

| File | What it is | Status |
| --- | --- | --- |
| `index.html` | Home: intro, currently, previously, links to everything else | Filled |
| `work.html` | Projects with screenshots + timeline | Filled |
| `now.html` | What I'm focused on this month | Filled |
| `story.html` | My story | Coming soon |
| `pivotal-moments.html` | Pivotal moments | Coming soon |
| `hot-takes.html` | Hot takes | Coming soon |
| `writing.html` | Writing / essays | Coming soon |
| `resources.html` | Stuff I wish I knew about sooner | Coming soon |
| `bookshelf.html` | Books | Coming soon |

To fill a placeholder page, replace the `<p class="coming-soon">Coming soon.</p>` line with
your copy (plain `<p>` tags, `<h2>` for sub-headings, `<ul>` for lists).

To add or drop a page: create/delete the file, then update the "More of me" list in
`index.html`. The top nav is repeated in every file, so edit it in each one.

## Styling

All colors, fonts and widths are variables at the top of `style.css` (`:root`).
Dark mode follows the visitor's system setting.

## Going live

This repo has no `CNAME` on purpose, so it doesn't fight the current site
(`hah31/hashim-hassan.com`) for the domain. When v2 is ready, copy these files into
that repo (keeping its `CNAME`), or move the `CNAME` file over here.
