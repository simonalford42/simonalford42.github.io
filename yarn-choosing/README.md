# Six Little Stars

Standalone static build of the yarn palette designer. GitHub Pages serves this
directory directly at `/yarn-choosing/`. All scripts, styles, fonts and 184 yarn
photos are included; there is no backend or external API dependency.

The designer source is in `~/code/projects/baby-blanket/web`. To update:

1. Run `npm run build:static` in that project.
2. Copy the contents of its `dist-static/` folder into this directory.
3. Publish the personal website through its usual GitHub Pages workflow.

The Misc link is maintained in `content/misc.md`; run `python3 build.py` at the
website root when changing that content.

Yarn names and photos: Wool & Company, catalog snapshot September 9, 2026.
Preview shades are photo-derived approximations. Palettes save on the current
browser/device and can be downloaded as a yarn list or SVG preview.
