# Martin Nygren

Static personal page. English is the default; Swedish is the other language on the switch.

Plain HTML and CSS, no build step. Paths are relative, so the same files work from a project subpath.

- Preview: https://evergreenvulcano.github.io/martin-nygren/
- Intended address, once the owner agrees to go live: https://martin.verbotenmedia.se/

`sitemap.xml` and `robots.txt` name that intended address. Open Graph tags point at the preview URL. The Open Graph image is the forest photograph. There is no CNAME file yet. GitHub Pages should deploy from the `main` branch, folder `/`.

## Photographs

Each picture is its own set of files in `assets/`. To swap one, replace that set and keep the filenames, or change the `src` and `srcset` on that picture only.

- Hero and Open Graph: `forest-800.jpg`, `forest-1163.jpg`
- Introduction: `martin-800`, `martin-900` (`.webp` and `.jpg`)
- Before Experience: `goldfish-800`, `goldfish-1600`, `goldfish-2000`
- Before Verboten Media: `arch-800`, `arch-1260`

The number is the width. WebP is used where it is smaller; JPEG is the fallback. The forest hero stays JPEG, because WebP at the same quality was larger. Generated files are about quality 78, and none are wider than the source.
