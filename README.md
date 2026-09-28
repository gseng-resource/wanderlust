# Wanderlust

Personal travel guides and tools, published with GitHub Pages at
**https://gseng-resource.github.io/wanderlust/**

## Layout

```
index.html        Home page linking to everything below
japan/            Tokyo shopping guide, Osaka navigator
china/            Shanghai hotel selections
singapore/        Singapore family guide
tools/            Itinerary prompt generator
assets/           Images used for link previews and the home page
```

The HTML files left at the top level (e.g. `OsakaInteractive.html`) are
redirects, so links shared before the reorganisation still work.

## Adding a new trip

1. Put the page in a folder named after the country, e.g. `korea/seoul.html`.
2. Put its preview image in `assets/` and point the page's `og:image` at
   `https://gseng-resource.github.io/wanderlust/assets/<image>`.
3. Add a card for it in `index.html`.
