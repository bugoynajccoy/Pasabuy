# Instagram UI Icons (Bootstrap Icons 1.13.2, offline)

174 curated icons from Bootstrap Icons for building Instagram-style interfaces.
No CDN or internet needed.

## Contents
- `svg/`         individual SVG files (use as <img>, or inline)
- `sprite.svg`   all icons as <symbol>s (`#bi-<name>`)
- `icons.css`    helper classes (.bi, .bi-sm/md/lg/xl, .bi-like)
- `preview.html` searchable gallery (click to copy snippet)
- `icons.json`   list of icon names

## Usage
Inline sprite (best for color + sizing):
```html
<link rel="stylesheet" href="icons.css">
<svg class="bi bi-lg"><use href="sprite.svg#bi-heart"/></svg>
<svg class="bi bi-lg bi-like"><use href="sprite.svg#bi-heart-fill"/></svg>
```
Note: external `<use href="sprite.svg#...">` needs to be served over http(s)
(not file://). For file:// pages, paste the sprite contents into the page body.

Plain image: `<img src="svg/house.svg" width="24">`

Icons inherit `currentColor`, so style with CSS `color`.
Typical states: outline = inactive, `-fill` = active/liked/selected.

## License
Bootstrap Icons is MIT licensed (see LICENSE).
Instagram is a trademark of Meta; the `instagram` glyph is subject to brand guidelines.
