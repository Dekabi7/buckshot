# BUCKSHOT® — Castro PG14

Buckshot Promotion website.

Album site for **BUCKSHOT®** by Castro PG14 (SCARYGENERATIONS MEDIA, LLC.).
Static site: `index.html` + `assets/`. No build step. Hosted on GitHub Pages.

## When the album drops
- **Streaming links:** in `index.html`, find `plat soon` and replace each `<span class="plat soon">NAME</span>` with `<a class="plat" href="LINK">NAME</a>`.
- **Release date:** set `const RELEASE = new Date('YYYY-MM-DDT00:00:00-05:00')` to show a live countdown, then "OUT NOW".
- **Email signup:** remove `hidden` from `<div class="signup">` and wire the form submit to a mailing-list service.
