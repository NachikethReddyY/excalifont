# Excalifont web font

The official [Excalifont](https://plus.excalidraw.com/excalifont) font, packaged for self-hosting in web projects. Font copyright belongs to Excalidraw. This package is an independent distribution and is not endorsed by Excalidraw.

```sh
npm i excalifont
```

```css
@import "excalifont/style.css";

body { font-family: "Excalifont", system-ui, sans-serif; }
```

Or import the stylesheet in JavaScript:

```js
import "excalifont/style.css";
```

WOFF2, WOFF, and TTF are included for broad browser support. The CSS uses `font-display: swap` and the file URLs are resolved by your bundler. For older setups without CSS package import support, copy `style.css` and `fonts/` together into your public assets.

## License

The font is licensed under the SIL Open Font License 1.1. The copyright and complete license text are in [OFL.txt](./OFL.txt) and embedded in the font. This package does not modify the font artwork.
