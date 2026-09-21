# PXL Sprite Inspector

A standalone static gallery of 3,400 animated and still sprites.

Website: https://edlud.github.io/pxSpriteWebsite/

## Run locally

From this directory, run:

```sh
python3 -m http.server 8000
```

Open http://localhost:8000/.

## Publish

GitHub Pages publishes the root of the `main` branch. Push changes to `main` to update the website. No build step or dependencies are required.

`index.html` contains the viewer, styles, scripts, and sprite metadata; `pxl_gifs/` contains the images. `.nojekyll` disables Jekyll processing.

The source archive did not contain the original `pxl_extracted/` sprite sheets, so requests for those optional previews have been removed. Animated GIF previews and sprite metadata are retained. Typography uses Google Fonts with local font fallbacks.
