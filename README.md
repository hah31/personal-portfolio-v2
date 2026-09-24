# hashim-hassan.com (v2)

Static HTML/CSS. No build step. Open any `.html` file in a browser to preview.

## Pages

| File | What it is | Status |
| --- | --- | --- |
| `index.html` | Home: name, one-liners, `>` links to everything else | Filled |
| `work.html` | Project cards (stats + screenshots) + timeline | Filled |
| `now.html` | What I'm focused on this month | Filled |
| `story.html` | My story | Intro only |
| `pivotal-moments.html` | Pivotal moments | Coming soon |
| `hot-takes.html` | Hot takes | Coming soon |
| `writing.html` | Writing / essays | Coming soon |
| `resources.html` | Stuff I wish I knew about sooner | Coming soon |
| `bookshelf.html` | Books | Coming soon |

To fill a placeholder page, replace the `<p class="coming-soon">coming soon.</p>` line with
your copy: wrap paragraphs in `<div class="prose">…</div>`, use `<ul class="dash-list">` for
lists and `<h2 class="section-title">` for sub-headings.

To add or drop a page: create/delete the file, then update the `>` link list in `index.html`.
Subpages have no nav, just a "← back to home" link, so there's nothing else to keep in sync.

## Styling

Modeled on atjasonwang.com and austnkennedy.com: Geist Mono body, Geist for page titles,
zinc greys, blue for outbound links, centered home page. All colors, fonts and widths are
variables at the top of `style.css` (`:root`). Dark mode follows the visitor's system setting.

## Going live

This repo has no `CNAME` on purpose, so it doesn't fight the current site
(`hah31/hashim-hassan.com`) for the domain. When v2 is ready, copy these files into
that repo (keeping its `CNAME`), or move the `CNAME` file over here.
