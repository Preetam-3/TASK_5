# World Map

A static world map built with plain HTML and CSS. All countries are drawn as an inline SVG, and no JavaScript is used.

## Files

- `index.html` – the page, containing the SVG map with one `<path>` per country
- `style.css` – colours, borders, background and the slight zoom

## Run locally

Open `index.html` in any browser. No build step or dependencies are needed.

## Customize

Edit `style.css`:

- `.stage` – page background
- `.map` – size and zoom (`transform: scale(...)`)
- `.map path` – country fill and border colours
- `.map path:hover` – hover colour

## Hosting

Because it is fully static, the folder can be served by any static host, including GitHub Pages (use the `main` branch and the root folder).
