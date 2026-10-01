# Karen Lin Portfolio — local remake

A dependency-free, locally runnable recreation of the public portfolio at https://karenlin.site/.

## Run locally

Open `index.html` in a browser, or from this directory run:

```sh
python3 -m http.server 8000
```

Then visit http://localhost:8000.

The home, project, About, and Play pages are implemented with plain HTML, CSS, and JavaScript. Typography uses Google Fonts when online; system fonts provide a fallback.

## Asset note

The original site’s project imagery and photography were not included in the provided ZIP, so the local version currently uses neutral gray placeholders for project imagery and photography. Replace the `.cover` and `.tile` treatments with original screenshots and photography for a closer visual match.

## Case-study layout

All six project pages use a shared editorial format inspired by the MaizeBus draft: a wide hero image area, project summary and metadata, then consistent problem, opportunity, solution, learning, and impact sections. Image areas remain gray placeholders until the original assets are available.
