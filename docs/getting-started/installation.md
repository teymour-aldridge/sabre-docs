# Installation
### Loading Sabre from a CDN.
**Production URL**

Use this for production environments.
```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/teymour-aldridge/sabre@a06cc50fb35ae0669fd9ea4cf66777ae3e74fff8/styles.min.css" integrity="sha384-1xUVGuTCq1IfLyym2iY9LjKQopkxmKtQVMMVYwsygfxN67um/2zgRxL3C7Plx0bc" crossorigin="anonymous">
```
**Development URL (not suited for production environments).**

This link automatically gives you the latest version of Sabre – which may contain bugs.
The file is also not automatically minified so it is slower to load.
```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/teymour-aldridge/sabre/styles.css">
```
### Hosting Sabre yourself.
You can <a href="https://cdn.jsdelivr.net/gh/teymour-aldridge/sabre/sass/styles.min.css">download sabre.min.css</a> and host it yourself.
### Customising
Sabre is written in SCSS, making it easily customisable using variable overrides. For more details see [the documentation page](/getting-started/customisation.md).