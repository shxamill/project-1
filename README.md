# Packaging Showcase — HTML/CSS Practice

A static front-end practice project built with HTML and CSS. The page presents packaging mockup, dieline, and 3D-design showcase sections using local image assets.

## Run locally

Open index.html directly in a browser, or start a local server from the project root:

~~~bash
python -m http.server 8000
~~~

Then visit http://localhost:8000.

## Validate local assets

Run `python scripts/check_assets.py` to check local HTML/CSS references. The same check runs automatically in GitHub Actions on pushes and pull requests.

## Project structure

| Path | Purpose |
| --- | --- |
| index.html | Page structure and showcase content |
| style.css | Layout, typography, and visual styling |
| images/ | Images and SVG assets used by the page |

## Project status and attribution

This is a learning/reference recreation, not an official product or service. It is not affiliated with or endorsed by Pacdora or any brands referenced in the page. Some names, marks, copy, and image assets may belong to their respective owners; check permissions before reusing or redistributing them.

## Contributing

See CONTRIBUTING.md. Keep changes focused and verify that local image paths still resolve.

## License

No repository-level open-source license is currently provided. Do not assume that public availability grants permission to reuse or redistribute the code or included assets.
