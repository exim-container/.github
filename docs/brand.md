# Brand

The PNG files are rendered from the SVG sources with `rsvg-convert` (package `librsvg2-bin`):

```sh
rsvg-convert -w 512 -h 512 brand/logo.svg -o brand/logo.png
rsvg-convert -w 1280 -h 640 brand/banner.svg -o brand/banner.png
```
