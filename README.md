# wiremark-www

The marketing site for [wiremark](https://github.com/Blackburn-Labs/wiremark),
served at [www.wiremark.dev](https://www.wiremark.dev). A static
[Astro](https://astro.build) site: today a single introduction page; more to
come.

The theme intentionally mirrors the docs site
([docs.wiremark.dev](https://docs.wiremark.dev/), Docusaurus): same primary
palette, font stacks, surfaces, and dark footer. The docs repo's
`site/src/css/custom.css` is the other side of that seam — keep the two in
sync as the brand evolves.

The hand-drawn hero image (`src/assets/login-sketch.svg`) is a static asset in
the style of `@wiremark/core`'s renderer. Once the engine fully renders the
canonical login example, regenerate it with the real thing
(`npx @wiremark/cli`).

## Commands

| Command           | Action                                      |
| :---------------- | :------------------------------------------ |
| `npm install`     | Install dependencies                        |
| `npm run dev`     | Start local dev server at `localhost:4321`  |
| `npm run build`   | Build the production site to `./dist/`      |
| `npm run preview` | Preview the build locally before deploying  |
