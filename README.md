## Description

[Eric Meyer's CSS Reset](https://meyerweb.com/eric/tools/css/reset/) is great but outdated, we need a more modern CSS Reset, and this is my solution!

## Code

```css
*, *::before, *::after {
    box-sizing: border-box;
}

* {
    margin: 0;
}

html, body {
    height: 100%;
}

html:focus-within {
    scroll-behavior: smooth;
}

body {
    line-height: 1.5;
    text-rendering: optimizeSpeed;       /* it needs more testing */
    -webkit-font-smoothing: antialiased; /* it needs more testing */
}

img, picture, video, canvas, svg {
    display: block;
    max-width: 100%;
}

input, button, textarea, select {
    font: inherit;
}

p, h1, h2, h3, h4, h5, h6 {
    overflow-wrap: break-word;
}

p {
    hyphens: auto;
}

a:not([class]) {
    text-decoration-skip-ink: auto;
}

#root {
    isolation: isolate;
}
```

## Thanks

- [Eric Meyer's CSS Reset](https://meyerweb.com/eric/tools/css/reset/)
- [CSS for JavaScript developers](https://courses.joshwcomeau.com/css-for-js/treasure-trove/010-global-styles)
- [A Modern CSS Reset](https://andy-bell.co.uk/a-modern-css-reset/)

## License
[MIT](https://github.com/jynxio/modern-css-reset/blob/main/LICENSE)
