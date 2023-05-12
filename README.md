# Typeset

Typeset is an up-to-date and open-source CSS typeset for article-type content which aims to improve upon the default browser renderings of common HTML elements. It was written specifically to easily integrate into a codebase without much configuration needed beyond theming (e.g. colors or font).

## Usage

Get a copy of `typeset.css` via your preferred method and integrate the file or even just it's contents into your codebase while overwriting defaults to suit your usage.

Also; open `example.html` or visit [my website](https://kikoi.site) for a live example of the typeset properly used.

### I Just Need A Typeset

Include the code below as CSS or HTML according to your use case.

```css
@import url(https://cdn.jsdelivr.net/gh/k12978/Typeset@main/typeset.css);
```

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@xz/fonts@1/serve/inter.css" type="text/css" />
```

Using this method is the fastest and easiest way to implement Typeset but you cannot edit the typeset directly but you can still overwrite it using classed CSS or `!important` keyword.

## Specification

Typeset utilizes classless CSS and is formatted per the recommendations of [CSS Guidelines v2.2.5](https://cssguidelin.es/). Typeset's styles are written while referencing [MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/a) and [W3](https://www.w3schools.com/tags/default.asp) with the actual *usage* of the element in mind. Beyond referencing documentation, I seek actual usage of the elements in the web to reference.
