# Save Gillman Forest — website

Residents' campaign site for Gillman Forest, Telok Blangah, Singapore.

## Structure

```
index.html          the whole site (single page, sections switched with JS)
assets/img/         photographs and graphics
assets/fonts/       Inter (woff2)
media/              hero.mp4 (background loop), film.mp4 (the film)
documents/          PDFs linked from the Resources section
```

## Editing

`index.html` is the only file that holds copy. Change it, commit, push —
the host rebuilds and the change is live within about a minute.

## History

Rebuilt on 3 Aug 2026 from the self-contained single-file version that was
circulated by hand. Assets were previously inlined as base64 (31 MB page);
they are now separate files, so the page loads in well under a second.
