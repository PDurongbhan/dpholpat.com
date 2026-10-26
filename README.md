# dpholpat.com

Personal website of Pholpat Durongbhan. One hand-written page, no build step.

- `index.html` holds everything: content, styles and the three figures (the hero schematic with its two tabs, cell aggregate and joint; the timeline; the coauthor network).
- The timeline and the network are drawn from the publication list, so adding a paper means adding one `<li>` under Publications. Give it `data-line="brain|joints|aggregates"` and `data-lead="1"` if you were first or corresponding author, and wrap the author list in `<span class="au">…</span>`.
- `404.html`, `og.png` (link preview card), `favicon.svg` and `apple-touch-icon.png` are the only other files.
- `CNAME` points GitHub Pages at the domain.
