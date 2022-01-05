This repository contains some icon extending Font Awesome to add some Fable related icons.

- `faf faf-fable`: Fable logo
- `faf faf-fsharp-org`: F# logo

It also extends Bulma icons to support these new icons.

In order, to use the library you need to import it in your SCSS file.

```scss
@import "./node_modules/fable-icons/scss/fable-font.scss";
```

By default, we are using https://unpkg.com/ to serve the fonts files.

If you prefer to serve them from your own server, you can set `$fable-font-base-url` to the URL of your server.
