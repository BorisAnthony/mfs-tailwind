<p align="center">
  <a href="https://modernfontstacks.com/">
    <img src="https://raw.githubusercontent.com/system-fonts/modern-font-stacks/main/img/logo-mfs.svg" width="128" height="128" alt="Modern Font Stacks">
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
The "<a href="https://github.com/system-fonts/modern-font-stacks">Modern Font Stacks</a>" as `theme:{fontFamily}` directives for TailwindCSS config.

The stacks originate from the [Modern Font Stacks](https://modernfontstacks.com), a passion project of [Dan Klammer](https://danklammer.com).
See the [repository of the project](https://github.com/system-fonts/modern-font-stacks) to preview the stacks.

**Wordpress users**
See [LittleBigThing for a Wordpress plugin](https://github.com/LittleBigThing/Modern-Font-Stacks-for-WP).

---

## Installation

### TailwindCSS ^4.0

As of TailwindCS 4.0, the `tailwind.config.js` file is no longer needed ( _though it will still work that way too_ ).
Simply add any of these we need to your base CSS file.

```css
@theme {
  --font-systemui:     system-ui, sans-serif;
  --font-transitional: Charter, 'Bitstream Charter', 'Sitka Text', Cambria, serif;
  --font-oldstyle:     'Iowan Old Style', 'Palatino Linotype', 'URW Palladio L', P052, serif;
  --font-humanist:     Seravek, 'Gill Sans Nova', Ubuntu, Calibri, 'DejaVu Sans', source-sans-pro, sans-serif;
  --font-geohumanist:  Avenir, Montserrat, Corbel, 'URW Gothic', source-sans-pro, sans-serif;
  --font-classhuman:   Optima, Candara, 'Noto Sans', source-sans-pro, sans-serif;
  --font-neogrote:     Inter, Roboto, 'Helvetica Neue', 'Arial Nova', 'Nimbus Sans', Arial, sans-serif;
  --font-monoslab:     'Nimbus Mono PS', 'Courier New', monospace;
  --font-monocode:     ui-monospace, 'Cascadia Code', 'Source Code Pro', Menlo, Consolas, 'DejaVu Sans Mono', monospace;
  --font-industrial:   Bahnschrift, 'DIN Alternate', 'Franklin Gothic Medium', 'Nimbus Sans Narrow', sans-serif-condensed, sans-serif;
  --font-roundsans:    ui-rounded, 'Hiragino Maru Gothic ProN', Quicksand, Comfortaa, Manjari, 'Arial Rounded MT', 'Arial Rounded MT Bold', Calibri, source-sans-pro, sans-serif;
  --font-slabserif:    Rockwell, 'Rockwell Nova', 'Roboto Slab', 'DejaVu Serif', 'Sitka Small', serif;
  --font-antique:      Superclarendon, 'Bookman Old Style', 'URW Bookman', 'URW Bookman L', 'Georgia Pro', Georgia, serif;
  --font-didone:       Didot, 'Bodoni MT', 'Noto Serif Display', 'URW Palladio L', P052, Sylfaen, serif;
  --font-handwritten:  'Segoe Print', 'Bradley Hand', Chilanka, TSCu_Comic, casual, cursive;
}
```

### TailwindCSS ^3.0

Add any or all of the following to the `theme` section of your `tailwind.config.js` file:

```js
module.exports = {
  corePlugins: {},
  content: [],
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
      industrial:   ['Bahnschrift', 'DIN Alternate', 'Franklin Gothic Medium', 'Nimbus Sans Narrow', 'sans-serif-condensed', 'sans-serif'],
      roundsans:    ['ui-rounded', 'Hiragino Maru Gothic ProN', 'Quicksand', 'Comfortaa', 'Manjari', 'Arial Rounded MT', 'Arial Rounded MT Bold', 'Calibri', 'source-sans-pro', 'sans-serif'],
      slabserif:    ['Rockwell', 'Rockwell Nova', 'Roboto Slab', 'DejaVu Serif', 'Sitka Small', 'serif'],
      antique:      ['Superclarendon', 'Bookman Old Style', 'URW Bookman', 'URW Bookman L', 'Georgia Pro', 'Georgia', 'serif'],
      didone:       ['Didot', 'Bodoni MT', 'Noto Serif Display', 'URW Palladio L', 'P052', 'Sylfaen', 'serif'],
      handwritten:  ['Segoe Print', 'Bradley Hand', 'Chilanka', 'TSCu_Comic', 'casual', 'cursive'],
    },
    extend: {},
  }
}
```

---

## Usage

```html
<div class="font-systemui"></div>
<div class="font-transitional"></div>
<div class="font-oldstyle"></div>
<div class="font-neogrote"></div>
etc…
```

