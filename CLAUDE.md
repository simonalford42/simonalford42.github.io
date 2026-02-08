# Local Development

## Editing content

Page content lives in `content/*.md` files. After editing, run the build script to regenerate HTML:

```bash
python3 build.py
```

This builds all `*.html` pages from `content/*.md` using a shared template in `build.py`.

## Preview site locally

Start a local server:

```bash
python3 -m http.server 8000
```

Then visit http://localhost:8000

## Verify changes with Playwright

After making changes, use Playwright to screenshot and verify the site looks correct:

```bash
playwright-cli open http://localhost:8000
playwright-cli screenshot
playwright-cli session-stop
```
