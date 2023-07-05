<p align="center">
  <a href="https://modernfontstacks.com/">
    <img src="img/logo-mfs.svg" width="128" height="128" alt="Modern Font Stacks">
  </a>
  <br>for<br>
  <a href="https://tailwindcss.com" target="_blank">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/tailwindlabs/tailwindcss/HEAD/.github/logo-dark.svg">
      <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/tailwindlabs/tailwindcss/HEAD/.github/logo-light.svg">
      <img alt="Tailwind CSS" src="https://raw.githubusercontent.com/tailwindlabs/tailwindcss/HEAD/.github/logo-light.svg" width="350" height="70" style="max-width: 100%;">
    </picture>
  </a>
</p>

<h1 align="center">mfs-tailwind</h1>
<h2>The "<a href="https://github.com/system-fonts/modern-font-stacks">Modern Font Stacks</a>" as `theme:{fontFamily}` directives for TailwindCSS config</h2>

---

## Installation

Add any or all of the following to the `theme` section of your `tailwind.config.js` file:

```js
  theme: {
    fontFamily: { // https://github.com/system-fonts/modern-font-stacks
      systemui:     ['system-ui', 'sans-serif'],
      transitional: ['Charter', 'Bitstream Charter', 'Sitka Text', 'Cambria', 'serif'],
      oldstyle:     ['Iowan Old Style', 'Palatino Linotype', 'URW Palladio L', 'P052', 'serif'],
      humanist:     ['Seravek', 'Gill Sans Nova', 'Ubuntu', 'Calibri', 'DejaVu Sans', 'source-sans-pro', 'sans-serif'],
      geohumanist:  ['Avenir', 'Montserrat', 'Corbel', 'URW Gothic', 'source-sans-pro', 'sans-serif'],
      classhuman:   ['Optima', 'Candara', 'Noto Sans', 'source-sans-pro', 'sans-serif'],
      neogrote:     ['Inter', 'Roboto', 'Helvetica Neue', 'Arial Nova', 'Nimbus Sans', 'Arial', 'sans-serif'],
      monoslab:     ['Nimbus Mono PS', 'Courier New', 'monospace'],
      monocode:     ['ui-monospace', 'Cascadia Code', 'Source Code Pro', 'Menlo', 'Consolas', 'DejaVu Sans Mono', 'monospace'],
      industrial:   ['ui-rounded', 'Hiragino Maru Gothic ProN', 'Quicksand', 'Comfortaa', 'Manjari', 'Arial Rounded MT', 'Arial Rounded MT Bold', 'Calibri', 'source-sans-pro', 'sans-serif'],
      roundsans:    ['ui-rounded', 'Hiragino Maru Gothic ProN', 'Quicksand', 'Comfortaa', 'Manjari', 'Arial Rounded MT', 'Arial Rounded MT Bold', 'Calibri', 'source-sans-pro', 'sans-serif'],
      slabserif:    ['Rockwell', 'Rockwell Nova', 'Roboto Slab', 'DejaVu Serif', 'Sitka Small', 'serif'],
      antique:      ['Superclarendon', 'Bookman Old Style', 'URW Bookman', 'URW Bookman L', 'Georgia Pro', 'Georgia', 'serif'],
      didone:       ['Didot', 'Bodoni MT', 'Noto Serif Display', 'URW Palladio L', 'P052', 'Sylfaen', 'serif'],
      handwritten:  ['Segoe Print', 'Bradley Hand', 'Chilanka', 'TSCu_Comic', 'casual', 'cursive'],
    },
    extend: {},
  },
```

## Usage

```html
<div class="font-oldstyle"></div>
<div class="font-neogrote"></div>
…
```
---